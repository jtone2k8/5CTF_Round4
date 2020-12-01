```
#==================================================================
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

#==================================================================
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
	ends = list(ends)
	ends.append('m')
	ends = ''.join(sorted(ends))
	temp = encoded_message
	temp = sub('[' + ends + ']', ' ', temp)
	if check_letters(temp.split()):
		print(ends)

# This returns only 1 possilbe result of endbits
# jmrxy

#==================================================================
# STEP 2
# locate the space
# a space is the only printable with a single bit turned on
# spaced is changing every endbit to a space

spaced = set(sub('[jmrxy]', ' ', encoded_message).split())
for let in spaced:
	if len(let)==1:
		print(let)

# only 3 letters are by themselves
# therefore {32: 'dwz'}

#==================================================================
# STEP 3
# figure out the other brackets

# We know that no two brackets will be used twice in the same letter
# so we can remove all letters from eachothers' brackets
# first, let's shrink the possibilities by removing the endbits we 
# know from the alphabet before we start (leave d, w, and z because 
# they're in other letters

alphabet = list('abcdefghijklmnopqrstuvwxyz')
[alphabet.remove(letter) for letter in list('jmrxy')]
    

letter_dict = {}
for letter in alphabet:
    letter_dict[letter] = ''.join(alphabet)

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

#==================================================================
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
from disordery import decrypt
endbits = 'jmrxy'
for alph in perm(triads.values(), 6):
	possible_alphabet = alph[0] + 'dwz' + ''.join(alph[1:]) + endbits
	out = decrypt(encoded_message, possible_alphabet )
	if "flag" in out:
		print(out, possible_alphabet)


("Wow. I wasn't even sure that Disorderly 1 could be solved.  Congratulations!  I'm basically just writing out a bunch of words so you have more data to work with.  Otherwise it would be more difficult.  Anyway, your flag is flag{the_world_is_finally_in_order_through_entropy}", 'acfdwzeklbingpthuvoqsjmrxy')
```