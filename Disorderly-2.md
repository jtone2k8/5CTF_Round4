```
# STEP 1a
# Identify the endbits

from re import findall as fa
from re import sub as sub

encoded_message='ctlvoxqzgiaumcpuokwxuzbgmdxqaixdxgwufeojwqarvwckomvzgiaywhqtjcdplmdmowgajhpcwerfqgdxabpdvjzjvfqewreapqdjcdvlrowtcyzjczgljdicmzoarwcepmzmpambodcrduscerncphdojcdvkmwapxpcswyeuazjpdiareczonjdjslzmzjvszarioaugwxawtqkxigczmpzfydrwhfjtoawrwxkhozaxbwgusfjtdifjlctuwrfsgdytzaxvpbzjdmzrasuyozcvngxiagdvrvwapsyawkvjcqwxedgamtokazydgifxzcoxkwtcmdconxnpwvfoyatwuijqflzvywoyzrzxansmhtzsmbtofzjzmuzamcwsmczkhsjdanoyhcozjzfomazbpyadbtrnlaodrzyiawvygoadkrdqualyftezywjdotevcrehawmciqwxlwapjswbampfihzjozcghjwxqgczhnjgoadlrzlgcrzmswfrwychwjzestcmfwigvxuaozywciyzxiqagvdxfpvzxwxazquglyqndvgcxuzkfydgfmdflvqxdrkzsfuyqzuciprwridaokjipdquajqlcgzydxndcrqzarvplwcxgcwomwycpdiojofiugdyuzfejsgfzjwycpzmwqcrldapjazsjdjkpadxsfidugmzmvloadpxnuogwcrhldfrqczuijwmugdaskxqadbjtwalrifdxphwbrzywygauobmgeczycwnjawgorlwhcxvpqldamowanmqeavdjzcogjdmnawsxwgckxdmqtcvlzjcwpuqnyqzgfkxgnzargczjwxcwvygqczxdmbfdtoxotiwvarewvcrdpsajdxgcdywasnragzvxzpcujcsdbyhdfsmopedfmbzparpaedjpiwvydxdrocjgzcvbrzclqbxowkgaujszaxblfwqxbgzjdmqznaejtihswcxdcstexdalvjdywghcmtbwfjzqcjczqgujzxbszaycezuqrwmtzauyfizgyqdfrswatvyocvbezypkzcjnzcysazgjilfguoyzfuktqrhanzpqrehadmatndjgwcjqickthjsfziyldohayophcblrdvatmqfdnrhztnfmfowxcbwtjgdbcxlbqwcynaqlvgrawobmbwavgjqnkcphyangzqumvkzaxtfzrtfsdykdchxfbgkvsjewpamfzbjecwhrgnhoazrkotwfyhcwtsjcnzjqlghbaxzsfpjdncvprlczgyeavzywihqgfxlczrdnceqjtikwcsm'
poss_endbits = [i for i in 'abcdefghijklmnopqrstuvwxyz']

y = fa('(.)m(.?)', encoded_message)
for a,b in y:
	try:
		poss_endbits.remove(a)
	except: pass
	try:
		poss_endbits.remove(b)	
	except: pass

print(sorted(poss_endbits))

# STEP 1b
# validate the endbits

# we can only have 5 endbits, so we'll brute from these 6 + m
# we use comb instead of perm because the order isn't important

from itertools import combinations as comb
poss_endbits = ['e', 'i', 'j', 'r', 'x', 'y']

def check_letters(enc):
	for let in enc:
		if len(let) > 7: return False
	return True

for ends in comb(poss_endbits, 4):
	temp = encoded_message
	temp = sub('[m' + ''.join(ends) + ']', ' ', temp)
	if check_letters(encoded_message):
		print(ends)


# STEP 2
# locate the space
# a space is the only printable with a single bit turned on
# spaced is changing every endbit to a space

spaced = 'ctlvo qzgiau cpuokw uzbg d qai d gwufeo wqa vwcko vzgia whqt cdpl d owga hpcwe fqgd abpdv z vfqew eapqd cdvl owtc z czgl dic zoa wcep z pa bodc dusce ncphdo cdvk wap pcsw euaz pdia eczon d slz z vsza ioaugw awtqk igcz pzf d whf toaw w khoza bwgusf tdif lctuw fsgd tza vpbz d z asu ozcvng iagdv vwaps awkv cqw edga tokaz dgif zco kwtc dcon npwvfo atwui qflzv wo z z ans htzs btofz z uza cws czkhs dano hcoz zfo azbp adbt nlaod z iawv goadk dqual ftez w dotevc ehaw ciqw lwap swba pfihz ozcgh w qgczhn goadl zlgc z swf w chw zestc fwigv uaoz wci z iqagvd fpvz w azqugl qndvgc uzkf dgf dflvq d kzsfu qzucip w idaok ipdqua qlcgz d ndc qza vplwc gcwo w cpdio ofiugd uzfe sgfz w cpz wqc ldap azs d kpad sfidug z vloadp nuogwc hldf qczui w ugdask qadb twal ifd phwb z w gauob gecz cwn awgo lwhc vpqlda owan qeavd zcog d naws wgck d qtcvlz cwpuqn qzgfk gnza gcz w cwv gqcz d bfdto otiwva ewvc dpsa d gcd wasn agzv zpcu csdb hdfs opedf bzpa paed piwv d d oc gzcvb zclqb owkgau sza blfwq bgz d qznae tihswc dcste dalv d wghc tbwf zqc czqgu z bsza cezuq w tzau fizg qdf swatv ocvbez pkzc nzc sazg ilfguo zfuktq hanzpq ehad atnd gwc qickth sfzi ldoha ophcbl dvat qfdn hztnf fow cbwt gdbc lbqwc naqlvg awob bwavg qnkcph angzqu vkza tfz tfsd kdch fbgkvs ewpa fzb ecwh gnhoaz kotwf hcwts cnz qlghba zsfp dncvp lczg eavz wihqgf lcz dnceq tikwcs'.split()

# only 3 letters are by themselves
# therefore {32: 'dwz'}

# STEP 3
# figure out the other brackets

# We know that no two brackets will be used twice in the same letter
# so we can remove all letters from eachothers' brackets
# first, let's shrink the possibilities by removing the endbits we 
# know from the alphabet before we start (leave d, w, and z because 
# they're in other letters

letter_dict = {
    'a': 'abcdefghiklnopqstuvwz',
    'b': 'abcdefghiklnopqstuvwz',
    'c': 'abcdefghiklnopqstuvwz',
    'd': 'abcdefghiklnopqstuvwz',
    'e': 'abcdefghiklnopqstuvwz',
    'f': 'abcdefghiklnopqstuvwz',
    'g': 'abcdefghiklnopqstuvwz',
    'h': 'abcdefghiklnopqstuvwz',
    'i': 'abcdefghiklnopqstuvwz',
    'k': 'abcdefghiklnopqstuvwz',
    'l': 'abcdefghiklnopqstuvwz',
    'n': 'abcdefghiklnopqstuvwz',
    'o': 'abcdefghiklnopqstuvwz',
    'p': 'abcdefghiklnopqstuvwz',
    'q': 'abcdefghiklnopqstuvwz',
    's': 'abcdefghiklnopqstuvwz',
    't': 'abcdefghiklnopqstuvwz',
    'u': 'abcdefghiklnopqstuvwz',
    'v': 'abcdefghiklnopqstuvwz',
    'w': 'abcdefghiklnopqstuvwz',
    'z': 'abcdefghiklnopqstuvwz',
}

for letters in spaced:
	for l in letters:
		letter_dict[l] = l + sub('['+ letters + ']', '', letter_dict[l])

from pprint import pprint
pprint(letter_dict)

# except for "e" and "i" everthing is in nice 3s. But e and i are in other good ones
{'a': 'acf',
 'b': 'bin',
 'c': 'caf',
 'd': 'dwz',
 'e': 'eikl',
 'f': 'fac',
 'g': 'gpt',
 'h': 'huv',
 'i': 'iben',
 'k': 'kel',
 'l': 'lek',
 'n': 'nbi',
 'o': 'oqs',
 'p': 'pgt',
 'q': 'qos',
 's': 'soq',
 't': 'tgp',
 'u': 'uhv',
 'v': 'vhu',
 'w': 'wdz',
 'z': 'zdw'}

# now we can remove the duplicates and dwz
# (remove i from eikl because i is used in bin)
triads = {'a': 'acf',
         'b': 'bin',
         'e': 'ekl',
         'g': 'gpt',
         'h': 'huv',
         'o': 'oqs'
}

# STEP 4
# trying all the combos to solve it


encoded_message='ctlvoxqzgiaumcpuokwxuzbgmdxqaixdxgwufeojwqarvwckomvzgiaywhqtjcdplmdmowgajhpcwerfqgdxabpdvjzjvfqewreapqdjcdvlrowtcyzjczgljdicmzoarwcepmzmpambodcrduscerncphdojcdvkmwapxpcswyeuazjpdiareczonjdjslzmzjvszarioaugwxawtqkxigczmpzfydrwhfjtoawrwxkhozaxbwgusfjtdifjlctuwrfsgdytzaxvpbzjdmzrasuyozcvngxiagdvrvwapsyawkvjcqwxedgamtokazydgifxzcoxkwtcmdconxnpwvfoyatwuijqflzvywoyzrzxansmhtzsmbtofzjzmuzamcwsmczkhsjdanoyhcozjzfomazbpyadbtrnlaodrzyiawvygoadkrdqualyftezywjdotevcrehawmciqwxlwapjswbampfihzjozcghjwxqgczhnjgoadlrzlgcrzmswfrwychwjzestcmfwigvxuaozywciyzxiqagvdxfpvzxwxazquglyqndvgcxuzkfydgfmdflvqxdrkzsfuyqzuciprwridaokjipdquajqlcgzydxndcrqzarvplwcxgcwomwycpdiojofiugdyuzfejsgfzjwycpzmwqcrldapjazsjdjkpadxsfidugmzmvloadpxnuogwcrhldfrqczuijwmugdaskxqadbjtwalrifdxphwbrzywygauobmgeczycwnjawgorlwhcxvpqldamowanmqeavdjzcogjdmnawsxwgckxdmqtcvlzjcwpuqnyqzgfkxgnzargczjwxcwvygqczxdmbfdtoxotiwvarewvcrdpsajdxgcdywasnragzvxzpcujcsdbyhdfsmopedfmbzparpaedjpiwvydxdrocjgzcvbrzclqbxowkgaujszaxblfwqxbgzjdmqznaejtihswcxdcstexdalvjdywghcmtbwfjzqcjczqgujzxbszaycezuqrwmtzauyfizgyqdfrswatvyocvbezypkzcjnzcysazgjilfguoyzfuktqrhanzpqrehadmatndjgwcjqickthjsfziyldohayophcblrdvatmqfdnrhztnfmfowxcbwtjgdbcxlbqwcynaqlvgrawobmbwavgjqnkcphyangzqumvkzaxtfzrtfsdykdchxfbgkvsjewpamfzbjecwhrgnhoazrkotwfyhcwtsjcnzjqlghbaxzsfpjdncvprlczgyeavzywihqgfxlczrdnceqjtikwcsm'

triads = {'a': 'acf',
         'b': 'bin',
         'e': 'ekl',
         'g': 'gpt',
         'h': 'huv',
         'o': 'oqs'
}

# we know that 'dwz' is 32, so we can skip it, and we know the endbits are
# we use perm instead of comb because the order of the groups IS important
from itertools import permutations as perm
endbits = 'jmrxy'
for alph in perm(triads.values(), 6):
	possible_alphabet = alph[0] + 'dwz' + ''.join(alph[1:]) + endbits
	out = decrypt(encoded_message, possible_alphabet )
	if "flag" in out:
		print(out, possible_alphabet)


("Wow. I wasn't even sure that Disorderly 1 could be solved.  Congratulations!  I'm basically just writing out a bunch of words so you have more data to work with.  Otherwise it would be more difficult.  Anyway, your flag is flag{the_world_is_finally_in_order_through_entropy}", 'acfdwzeklbingpthuvoqsjmrxy')
```