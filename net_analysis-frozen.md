>>>
Question 1:
	What OS,Web Browser,Browser Version Number was used in the pcap? (os,browser,version.x)

flag:
	linux,Firefox,68.0

![image](uploads/44763a790e9b47372746fbfd63670284/image.png)
>>>

>>>
question 2:
	This pcap was taken from a proxy server, what is the name and version of the proxy?
	format: name,version

flag:
	squid,4.13

![image](uploads/73f42e7b640ebe58ac21d7e82a203154/image.png)
>>>

>>>
question 3:
	What is the squid server's hostname?

flag:
	Arendale's_Gates

![image](uploads/77cc1e1ace36ebcf3140a724b6e8e9d4/image.png)
>>>
>>>
question 4:
	What is the IP address of the Squid Server?

flag:
	192.168.56.101
![image](uploads/ba17b5c1551d1d972b3a5582c8975b11/image.png)
>>>
>>>
question 5: 
	How many CONNECTs are there is this pcap that went through the proxy?

flag:
	157

http.request.method == "CONNECT"
>>>
>>>
question 6:
	Where was the user at when they were redirected to a compromised webpage?
	www.somepage.tld/subpage/subpage

flag:
	www.reddit.com/r/frozen

![image](uploads/9a70e0bf6c7b3ee02e56722fd24aebe5/image.png)
>>>
>>>

question 7: 
	what web address did the user get tricked into going to that was a compromised web page?

flag:
	www.frozone.com

http.request.full_uri

![image](uploads/29dbda60fc8585bdc2d5c1d05594c431/image.png)

>>>
>>>

question 8:
	what item was dropped on the compromised site that the user was force to download?

flag:
	QR code

![image](uploads/fb80bfd9a097e3cb764005587c62c37b/image.png)

>>>
>>>

question 9:
	what website was spoofed?

flag: 
	frozen.disney.com	

![image](uploads/3ee6718c469e691e0dcaafa6f0b67278/image.png)

![image](uploads/c2487614654b0fdfc8e10f42fb1b308f/image.png)
>>>
>>>

question 10: 
	What is the flag that is created when the QR code pieces are put back in order?

flag:  
	frozen_multipack

![image](uploads/09b79eccde54135fa4a5bfc909df6260/image.png)

![image](uploads/d21e35a2b9a50c02f57bcae55f8eb0c8/image.png)

![image](uploads/4006fda5a3671708dd26fab9e0500e16/image.png)

>>>
>>>

question 11: 
	What is the flag that you see when you open the QR code up?

hint: 
	Kristoff was a Guy that zipped up to help Anna find her sister

https://webqr.com/index.html

![image](uploads/4719d14c6c4d4320e13be5667feabb3e/image.png)

![image](uploads/b7355cd761a9dde1e3375cd51eb3c984/image.png)

- H4sIABj5aF8A/21SPW/bOhSdy19xtywZ6sZKxqIfS4C2U4COhCxREiuK1xEpK45hoECHtxQPHrrmecoP8JjlPaAwXqD8ge79JbmXsh0FqGBeXh6ec+4l6UzPVOKzxUTn0jVVpWo5MdhKbPwShLgoFDiLLeQEOmgL7RWgBU94hY31saYFWp0X/gXwRzEk/Up8Qg8xZIh+WmvriQsTslTKHjg0cdIPjuINlNrmKVaAGWiHJvaaih7sdzrOer5NQXswiKUDo0sF50dV6PGyoUp8iFYzx0GBrSHvnuULQlyr6wA5j3UF2jqdKvEOG5PaIw+lUlM21/YYChXPqPGSLsTBOfhaq/Q9MssoOlqhWH4M6XOIDivecjEFOWIKOdWDOTYQmzaeU0tkuruX/RF3JzxEascmKjZ770ypQ36ow20NZMNJfFaGBEwg6jxQP5COzpXjcbAI6eDlnmKoH3OpAk246EmclBDbeYV13/PTgwy6H6Yg/lRuRxuoD38fUlw0tYWYrohKpeBM3D9pilg/a24fn5Wj3+Lnfw9/davL31//7VYU7m8e/tlufq15fUs7d93q/ibgvGR03a2R5v+/NdsNhW7V3Yb9Bh/+7u5I/z0I3HZDkaDbj8tuTU4/eGu76dZC5EWbpi5fJFN5NfXy6hqdbKxM/JdSyWvpq+nMXuPrpRCZ1D5bzqxyKlZ5ktCtSGkyXcnFXIjR+BRG0QhGpzSPIxonlI9ppvUZ5zSiMxq8R+OE8tOXfc445xHzd3tj9no14LKWZ8LYNyI+43s/1gacdBH3QHvBh/va6c4i8Qj8br+KQAQAAA==

![image](uploads/772229d1e53a605619597d3cc6b05976/image.png)
	
flag:
	fivectf{big_summer_blow_out} 
location: 
	- (putting qr back together)
encoded flag:
	-

>>>
>>>

Question 12: 
	Find the flag with a bunch of random numbers?

Hint: 
	Fun fact Chromium has a melting point 8 times that of water?

flag:
	fivectf{some_people_are_worth_melting_for}

location:
	https://gchq.github.io/CyberChef/#recipe=To_Octal('Space')&input=Zml2ZWN0Zntzb21lX3Blb3BsZV9hcmVfd29ydGhfbWVsdGluZ19mb3J9

encoded flag:
	146 151 166 145 143 164 146 173 163 157 155 145 137 160 145 157 160 154 145 137 141 162 145 137 167 157 162 164 150 137 155 145 154 164 151 156 147 137 146 157 162 175

![image](uploads/c24a2f9d83fc9e0f9ce7c065593223d7/image.png)

>>>
>>>
Question 13:
	Find the flag with legs.

Hint: 
	What was Kristoff touching when he said flawless while walking up the ice palace stairs?
Hint 2: 
	How many legs to spiders have? 

flag: 
	fivectf{i_cant_feel_my_legs}
location: 
	Rails (8) http://rumkin.com/tools/cipher/railfence.php
f             _             
 i           t f           }
  v         n   e         s 
   e       a     e       g  
    c     c       l     e   
     t   _         _   l    
      f i           m _     
       {             y
Encoded flag:	
	f_itf}vneseaegcclet__lfim_{y

![image](uploads/98a86c42ff2ef567784b19a6e2a4d092/image.png)

>>>
>>>

Question 14: 
	Find the shifty looking snowman.

hint: 
	A Snowman would look weird if you shifted his body around

flag:
	fivectf{do_you_want_to_build_a_snowman?}
location:
	https://www.dcode.fr/shift-cipher
	Alt Shit 1 every Character
encoded flag:
	ghwddsg{cp_xpt_xzos_un_ctjke_z_tmpvnzo?}

![image](uploads/bd85158bbcd78c73daa259ca62c86779/image.png)

>>>
>>>

question 15: 	
	find the bat like flag.

hint: 
	How do bats sleep?

flag:
	fivectf{Why_is_everyone_hanging_off_the_earth_like_a_bat?}
location: 
	upside down https://www.dcode.fr/upside-down-writing
encoded flag:
	{¿ʇɐq‾ɐ‾ǝʞıן‾ɥʇɹɐǝ‾ǝɥʇ‾ɟɟo‾ƃuıƃuɐɥ‾ǝuoʎɹǝʌǝ‾sı‾ʎɥM}ɟʇɔǝʌıɟ

![image](uploads/5e301dc9e2aa46d7c1aa7b1528c8d602/image.png)

>>>
>>>

question 16: 
	olaf is a true friend dont you think?

hint: 
	sometime you have to melt snow to see what is underneath.

flag:
	fivectf{olaf, you're melting}
location:
	http://www.darkside.com.au/snow/
encoded flag:
The snow glows white on the mountain tonight	     	  	    	     
Not a footprint to be seen   	      	 	   	   	 	   
A kingdom of isolation     	  	 	       	 		   
And it looks like I'm the queenThe wind is howling like this swirling storm inside
Couldn't keep it in, heaven knows I triedDon't let them in, don't let them see
Be the good girl you always have to be      	   	     	     	  
Conceal, don't feel, don't let them know     	      	      	   
Well, now they knowLet it go, let it go	    	     	     	   	  
Can't hold it back anymore     	       	  	   	      	   	       
Let it go, let it go      		       	   	  	      
Turn away and slam the door	     	   	     	    	   	       

![image](uploads/c20943661cb0a9e8874ec299f36c2a9d/image.png)  

![image](uploads/3ad2a8a905dbbc693fdcb40b981fe1da/image.png)

Install Snow - 

Decode 

snow -C snowme.txt

![image](uploads/5dc1c2661b1ab5a85f0bad7790b216b7/image.png)

>>>
>>>

fivectf{big_summer_blow_out} 

The snow glows white on the mountain tonight	     	  	    	     
Not a footprint to be seen   	      	 	   	   	 	   
A kingdom of isolation     	  	 	       	 		   
And it looks like I'm the queenThe wind is howling like this swirling storm inside
Couldn't keep it in, heaven knows I triedDon't let them in, don't let them see
Be the good girl you always have to be      	   	     	     	  
Conceal, don't feel, don't let them know     	      	      	   
Well, now they knowLet it go, let it go	    	     	     	   	  
Can't hold it back anymore     	       	  	   	      	   	       
Let it go, let it go      		       	   	  	      
Turn away and slam the door	     	   	     	    	   	       
  
{¿ʇɐq‾ɐ‾ǝʞıן‾ɥʇɹɐǝ‾ǝɥʇ‾ɟɟo‾ƃuıƃuɐɥ‾ǝuoʎɹǝʌǝ‾sı‾ʎɥM}ɟʇɔǝʌıɟ

ghwddsg{cp_xpt_xzos_un_ctjke_z_tmpvnzo?}

f_itf}vneseaegcclet__lfim_{y

146 151 166 145 143 164 146 173 163 157 155 145 137 160 145 157 160 154 145 137 141 162 145 137 167 157 162 164 150 137 155 145 154 164 151 156 147 137 146 157 162 175

>>>
>>>

gzipped

.....ùh_.ÿmR=oÛ:..Ë_q·,.êÆJÆ¢.K.¶S...,Q.+.×.)+.a @.·...ºæyÊ.ð.å= 0^ ü.îý%¹.²..¨`^^..sî%éLÏTâ³ÅDçÒ5U¥j91ØJlü..¸(.8.-ä.:h.í. .Ox..õ±¦.Z..þ.ðG1$ýJ|B.1d.~Zkë...²TÊ.84qÒ..â
.Úæ)V..h.&ö...ìw:Îz¾MA{0.¥.£K.çGUèñ²¡J|.V3ÇA..!ï.å.B\«ë.9.u.Ú:.*ñ...Ú#.¥RS6×ö.
.Ï¨ñ..ÄÁ9øZ«ô=2Ë(:Z¡X~.és..+Þr1.9b
9Õ.96..6.SKdº».ý.w'<DjÇ&*6{ïL©C~¨Ãm
dÃI|V..L ê<P?..Î.ãq°.éàå.b¨.s©.M¸èI...Ûy.ußóÓ..º.¦ þTnG.¨...R\4µ..®.J¥àLÜ?i.X?kn...£ßâç...u«Ëß_ÿíV.îo.þÙn~.y}K;wÝêþ&à¼dtÝ..æÿ¿5Û
.nÕÝ.ý..þîîHÿ=.ÜvC. Û.ËnMN?xk»éÖBäE.¦._$Sy5õòê..l¬Lü.RÉké«éÌ^ãë¥..Ô>[Î¬r*Vy.Ð.Hi2]ÉÅ\.Ñø.FÑ.F§4.#.'..i¦õ.ç4¢3.¼Gã.òÓ.}Î8ç.ów{cöz5à².gÂØ7">ã{?Ö..t.÷@{Á.ûÚéÎ"ñ.ün¿.@...
	
b64 encoded

H4sIABj5aF8A/21SPW/bOhSdy19xtywZ6sZKxqIfS4C2U4COhCxREiuK1xEpK45hoECHtxQPHrrmecoP8JjlPaAwXqD8ge79JbmXsh0FqGBeXh6ec+4l6UzPVOKzxUTn0jVVpWo5MdhKbPwShLgoFDiLLeQEOmgL7RWgBU94hY31saYFWp0X/gXwRzEk/Up8Qg8xZIh+WmvriQsTslTKHjg0cdIPjuINlNrmKVaAGWiHJvaaih7sdzrOer5NQXswiKUDo0sF50dV6PGyoUp8iFYzx0GBrSHvnuULQlyr6wA5j3UF2jqdKvEOG5PaIw+lUlM21/YYChXPqPGSLsTBOfhaq/Q9MssoOlqhWH4M6XOIDivecjEFOWIKOdWDOTYQmzaeU0tkuruX/RF3JzxEascmKjZ770ypQ36ow20NZMNJfFaGBEwg6jxQP5COzpXjcbAI6eDlnmKoH3OpAk246EmclBDbeYV13/PTgwy6H6Yg/lRuRxuoD38fUlw0tYWYrohKpeBM3D9pilg/a24fn5Wj3+Lnfw9/davL31//7VYU7m8e/tlufq15fUs7d93q/ibgvGR03a2R5v+/NdsNhW7V3Yb9Bh/+7u5I/z0I3HZDkaDbj8tuTU4/eGu76dZC5EWbpi5fJFN5NfXy6hqdbKxM/JdSyWvpq+nMXuPrpRCZ1D5bzqxyKlZ5ktCtSGkyXcnFXIjR+BRG0QhGpzSPIxonlI9ppvUZ5zSiMxq8R+OE8tOXfc445xHzd3tj9no14LKWZ8LYNyI+43s/1gacdBH3QHvBh/va6c4i8Qj8br+KQAQAAA==

QR Code
>>>
