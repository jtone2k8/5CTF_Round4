`

#Z  m  l  2  Z  W  N  0  Z  n  t  p  b  n  Z  v  a  2  V  f  d  G  h  l  X  2  V  2  b  2  t  l  c  n  N  9

#23 31 18 2  5  7  26 36 28 19 29 35 27 1  23 24 32 20 30 11 16 13 14 3  34 10 8  33 17 9  4  15 25 22 6  21

#n 2 l t Z N W V 2 2 f Z G h l d b l n 2 9 n Z v c N b Z t V m a 2 X p 0

#1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 

#x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x x  
  
#fivectf{invoke_the_evokers}

#Zml2ZWN0ZntpbnZva2VfdGhlX2V2b2tlcnN9

#n2ltZNWV22fZGhldbln29nZvcNbZtVma2Xp0

<#

echo ('{23}{31}{18}{2}' -f $f) #Zml2

echo ('{5}{7}{26}{36}' -f $f)  #ZWN0

echo ('{28}{19}{29}{35}' -f $f)#Zntp

echo ('{27}{1}{23}{24}' -f $f) #bnZv

echo ('{32}{20}{30}{11}' -f $f)#a2Vf

echo ('{16}{13}{14}{3}' -f $f) #dGhl

echo ('{34}{10}{8}' -f $f)     #X2V

echo ('{33}{17}{9}' -f $f)     #2b2

echo ('{4}{15}{25}' -f $f)     #tlc

echo ('{22}{6}{21}' -f $f)     #nN9

#>

$answer =""

$answer= ('{23}{31}{18}{2}' -f $f) #Zml2

$answer+= ('{5}{7}{26}{36}' -f $f)  #ZWN0

$answer+= ('{28}{19}{29}{35}' -f $f)#Zntp

$answer+= ('{27}{1}{23}{24}' -f $f) #bnZv

$answer+= ('{32}{20}{30}{11}' -f $f)#a2Vf

$answer+= ('{16}{13}{14}{3}' -f $f) #dGhl

$answer+= ('{34}{10}{8}' -f $f)     #X2V

$answer+= ('{33}{17}{9}' -f $f)     #2b2

$answer+= ('{4}{15}{25}' -f $f)     #tlc

$answer+= ('{22}{6}{21}' -f $f)     #nN9 

[System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String($answer))

`