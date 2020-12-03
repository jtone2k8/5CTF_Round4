All of these were created with Invoke-obfuscation

***********************************
Easy - 1 item only
***********************************
1.

Flag: `fivectf{turkeys_go_gobble_gobble}`

Question:

Encoding:

```
  inVOKe-ExPRessION ( ('xiz'+'turkey=3UN'+'f'+'ivect'+'f{tur'+'keys_'+'g'+'o_gob'+'b'+'le_'+'gobble}3UN').REpLACE(([ChAr]120+[ChAr]105+[ChAr]122),[StRiNG][ChAr]36).REpLACE(([ChAr]51+[ChAr]85+[ChAr]78),[StRiNG][ChAr]34)) 
```

Endcoded Message:

`$turkey="fivectf{turkeys_go_gobble_gobble}"`

Obfuscation Technique:

String Concatenate x1

***********************************
2.

Flag: `fivectf{lets_get_basted}`

Question:

Encoding:

```
(("{7}{8}{5}{0}{6}{2}{3}{10}{1}{4}{11}{9}"-f'6nf','_g','v','ectf{l','et_ba','te=5','i','h5Gb','as','ted}56n','ets','s')).rePLAce('h5G','$').rePLAce(([ChAR]53+[ChAR]54+[ChAR]110),[STrING][ChAR]34)| &((geT-VARiAbLe '*mDR*').naME[3,11,2]-JOIn'')
```

Endcoded Message:

`$baste="fivectf{lets_get_basted}"`

Obfuscation Technique:

Reorder x1

***********************************

3. 

Flag: `fivectf{i_yam_what_i_yam}`

Question:

Encoding:

```
&( $env:cOMSpec[4,24,25]-JOiN'') ( ([RuNtimE.InTeropsERvICEs.MArsHaL]::PTrtostRiNGauto([rUNtimE.INtEROPSERViCes.marShaL]::SeCUrEstRiNGTOBSTr( $('76492d1116743f0423413b16050a5345MgB8AFcAZgArAGkATgBMAGYAdAB2AFUAdQBWAFQANAAxAEwANgByAFoARwB6AHcAPQA9AHwAYgBiAGMAMgBlADYAYwAyADIAYgA0ADYAYwA4ADcAMQAzADUANQA5ADkAMAA4ADgAZQA3ADgAOAAxAGEAYQA1ADYAMABiADEAMwAwAGIAYwAyAGQAYQAxADQAZQA4ADMAMQAxADUAYwA1ADUAOQA1AGEAOQBmADgANwA1AGMAZgA5ADYAMwA5ADAAOQA3ADEAZABlAGMAZAAyADMAYwAxADEAYQBhAGUAMAA3ADIAOABmAGMAZABkAGIAMABiAGEANgA4ADEANwBhADQANABiAGEAMQAwAGYAMgBiAGUAZQA0AGQANwBlADQAYQAxADQAMgBiADEANQAxAGQAOQA2ADMAMQA1ADgANgBkAGIAZAA5AGQANQAyADUAZgA1ADAANgAyADMANQA1AGEAYgBmADUAMAA1ADEAOAA0AGQAMwBkAGIAMABkADQAOQA0ADUAMwA0AGMAZQBlAGUAMAAzAGIANgBiAGIAYQBjADcANwAwADkAMQBlADQAZQBkAGQANgBjADAANgBjAGEANAA2ADUAYQA0ADIAZAA5ADcAZQA2ADcAYwAxADkANwA5ADkANABmAGUAYgAwADUANgAyADAAMgA3ADAANgBmADIAYgAxADgAYgBmADMAZAA0ADMAYgBiADEAZgBiADgAOQA3AGEAZQBjAGMAYwA2ADAAYQA=' | ConVerttO-secUReStRIng -K 105,96,78,5,118,178,158,144,131,126,145,80,44,50,161,3)) )) )
```

Endcoded Message:

`$yammy="fivectf{i_yam_what_i_yam}";remove-variable yammy`

Obfuscation Technique:

encoding secure-string x1

***********************************

4.

Flag: `fivectf{im_stuffed}`

Question:

Encoding:

```
${+ }=  +  $(  );${=$%}  =${+ };${!=%}=++  ${+ }  ;  ${-}  =(  ${+ }=  ${+ }  +  ${!=%}  );  ${!}  =(${+ }  =${+ }+  ${!=%}  );${/@+}=  (${+ }  =  ${+ }+  ${!=%})  ;${;.(}=  (  ${+ }=${+ }+${!=%}  )  ;  ${;}  =(${+ }  =${+ }  +${!=%}  );${=*}=(  ${+ }  =  ${+ }  +${!=%}  )  ;  ${$}  =(${+ }=  ${+ }+  ${!=%});${[%-}=(  ${+ }  =  ${+ }  +  ${!=%})  ;${([!}  =  "["  +"$(  @{}  )"[${=*}  ]  +  "$(@{})"["${!=%}${[%-}"  ]  +  "$(  @{  })"[  "${-}${=$%}"]  +  "$?"[${!=%}]  +"]"  ;  ${+ }=  "".("$(@{  }  )"["${!=%}${/@+}"]+  "$(  @{  })  "[  "${!=%}${;}"  ]  +"$(@{}  )"[${=$%}  ]  +"$(@{})"[  ${/@+}]  +  "$?  "[  ${!=%}  ]  +"$(@{  })"[${!}  ])  ;  ${+ }="$(  @{  }  )"["${!=%}"  +  "${/@+}"  ]+  "$(  @{}  )"[${/@+}]+  "${+ }"["${-}"+  "${=*}"  ]  ;"${([!}${!}${;}+  ${([!}${!=%}${!=%}${;.(}+${([!}${!=%}${!=%}${;}+  ${([!}${!=%}${!=%}${=*}  +${([!}${!=%}${=$%}${-}+${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}+${([!}${!=%}${=$%}${=$%}  +  ${([!}${;}${!=%}+${([!}${!}${/@+}  +${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${=$%}${;.(}  +  ${([!}${!=%}${!=%}${$}+${([!}${!=%}${=$%}${!=%}+  ${([!}${[%-}${[%-}+${([!}${!=%}${!=%}${;}+${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${-}${!}+${([!}${!=%}${=$%}${;.(}  +${([!}${!=%}${=$%}${[%-}+${([!}${[%-}${;.(}  +${([!}${!=%}${!=%}${;.(}  +${([!}${!=%}${!=%}${;}  +${([!}${!=%}${!=%}${=*}  +${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}  +${([!}${!=%}${=$%}${=$%}+  ${([!}${!=%}${-}${;.(}  +  ${([!}${!}${/@+}  +${([!}${;.(}${[%-}  +  ${([!}${!=%}${!=%}${/@+}+${([!}${!=%}${=$%}${!=%}  +  ${([!}${!=%}${=$%}${[%-}  +  ${([!}${!=%}${!=%}${!=%}+${([!}${!=%}${!=%}${$}  +${([!}${!=%}${=$%}${!=%}  +${([!}${/@+}${;.(}+${([!}${!=%}${!=%}${$}+  ${([!}${[%-}${=*}+${([!}${!=%}${!=%}${/@+}  +${([!}${!=%}${=$%}${;.(}+${([!}${[%-}${=*}+  ${([!}${[%-}${$}+  ${([!}${!=%}${=$%}${$}  +  ${([!}${!=%}${=$%}${!=%}  +${([!}${!}${-}  +${([!}${!=%}${!=%}${;.(}+  ${([!}${!=%}${!=%}${;}+${([!}${!=%}${!=%}${=*}  +  ${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}  +${([!}${!=%}${=$%}${=$%}  |${+ }"  |.${+ }  
```

Endcoded Message:

`$stuffed="fivectf{im_stuffed}";remove-variable stuffed`

Obfuscation Technique:

encoding special characters x1

***********************************
Medium 2x items
***********************************

5.

Flag: `fivectf{your_the_apple_of_my_pie}`

Decoded Message Step by Step:

reverse x1

```
$UpX8B3=" )''NIOj-]52,51,4[cepsmOc:VNe$ ( &|)43]raHC[]gNIrts[,)15]raHC[+48]raHC[+57]raHC[((ecalPEr.)63]raHC[]gNIrts[,'vnc'(ecalPEr.)'elppa e'+'l'+'ba'+'irav-evomer;'+'3T'+'K}'+'eip_ym_fo_'+'elppa_eh'+'t_r'+'uoy'+'{ftce'+'v'+'if3TK=e'+'lp'+'pavnc'( "; iEx(" $(seT-ItEm 'vARiaBLe:ofS' '')" + [STRiNg] ( $UPX8b3[ - 1.. - ( $UPX8b3.LEnGTH) ])+" $( seT-iTEm 'VAriable:ofS'  ' ' ) " )
```

reorder x1

```
((("{106}{71}{112}{109}{60}{39}{38}{15}{7}{30}{75}{27}{3}{63}{20}{58}{104}{107}{25}{35}{16}{11}{24}{92}{45}{31}{108}{14}{64}{115}{94}{65}{37}{116}{55}{66}{59}{69}{56}{88}{96}{89}{46}{50}{42}{98}{102}{51}{8}{110}{57}{74}{103}{47}{44}{99}{68}{34}{21}{114}{91}{19}{85}{33}{72}{113}{28}{32}{70}{48}{17}{2}{95}{101}{26}{22}{29}{10}{84}{90}{9}{0}{62}{49}{81}{105}{73}{53}{52}{100}{1}{4}{41}{61}{78}{54}{83}{43}{86}{80}{77}{5}{6}{111}{76}{97}{13}{82}{87}{36}{79}{12}{18}{40}{93}{67}{23}"-f'eT-It','9','vncY','[]gNI','E)o0L + ',' ( ','8x','2,51,4[cepsmOc:VNe8xG ','9E','(s','0','cal','Ariabl',')','s[,','9ENIOj-]5','e','a','e:of','+Y9E{ftceY9','[','9E','x',' Y9E ) o0L ) ','PEr.','aHC[+57]raH','E','C','9','(o','( &DkT)4',']','E+Y9E','Ev','_rY9E+Y','C[((','9E','.)','Y',')Y9E','SY','[','v-evomer;Y','UPX8b3[ ','E+Y9Eelp','raHC[','EbaY9','_Y9','Ep','v','E+Y9Eira','Y','9E Y','Y','] ( 8','Eel','9ElY','+Y9Eei',',)15]','Y9E','o0L ','STRiN','Em Y9E','rts','Y9EvncY9E(','r','ppa e','E  Y9E','+Y9Et','+Y','lpY9E+Y9','G','Y9E+Y9Eif3','S','p_ym_','3]raH','PX8b3.','-','g','V','.. ','ARiaBLe',' ])+o0L 8xG( seT','xG','L ','E+Y9','- 1','-iTEm Y','9E+','9','8xG','oyY9E',')63]','9','E','9E( o','Y','LEnGTH','9E+Y','pa_ehY9E','9EY','0L; i','9E3T','fo','raH',':of','8x','C[+48]r','gNIrt','B3=','+Y9EK}Y9E','GU','UpX8','TK=eY','u','ecalP','Y9'))  -cREPlaCe([CHAr]56+[CHAr]120+[CHAr]71),[CHAr]36  -cREPlaCe ([CHAr]89+[CHAr]57+[CHAr]69),[CHAr]39 -cREPlaCe([CHAr]111+[CHAr]48+[CHAr]76),[CHAr]34  -replACE  'DkT',[CHAr]124) |.( $enV:ComSpEC[4,24,25]-joiN'')
```

Launch CMD

Encoding:

```
c:\wInDOws\sYsTeM32\cMD.exe  /c pOwErShelL -nOniNTErAct   "(((\"{106}{71}{112}{109}{60}{39}{38}{15}{7}{30}{75}{27}{3}{63}{20}{58}{104}{107}{25}{35}{16}{11}{24}{92}{45}{31}{108}{14}{64}{115}{94}{65}{37}{116}{55}{66}{59}{69}{56}{88}{96}{89}{46}{50}{42}{98}{102}{51}{8}{110}{57}{74}{103}{47}{44}{99}{68}{34}{21}{114}{91}{19}{85}{33}{72}{113}{28}{32}{70}{48}{17}{2}{95}{101}{26}{22}{29}{10}{84}{90}{9}{0}{62}{49}{81}{105}{73}{53}{52}{100}{1}{4}{41}{61}{78}{54}{83}{43}{86}{80}{77}{5}{6}{111}{76}{97}{13}{82}{87}{36}{79}{12}{18}{40}{93}{67}{23}\"-f'eT-It','9','vncY','[]gNI','E)o0L + ',' ( ','8x','2,51,4[cepsmOc:VNe8xG ','9E','(s','0','cal','Ariabl',')','s[,','9ENIOj-]5','e','a','e:of','+Y9E{ftceY9','[','9E','x',' Y9E ) o0L ) ','PEr.','aHC[+57]raH','E','C','9','(o','( &DkT)4',']','E+Y9E','Ev','_rY9E+Y','C[((','9E','.)','Y',')Y9E','SY','[','v-evomer;Y','UPX8b3[ ','E+Y9Eelp','raHC[','EbaY9','_Y9','Ep','v','E+Y9Eira','Y','9E Y','Y','] ( 8','Eel','9ElY','+Y9Eei',',)15]','Y9E','o0L ','STRiN','Em Y9E','rts','Y9EvncY9E(','r','ppa e','E  Y9E','+Y9Et','+Y','lpY9E+Y9','G','Y9E+Y9Eif3','S','p_ym_','3]raH','PX8b3.','-','g','V','.. ','ARiaBLe',' ])+o0L 8xG( seT','xG','L ','E+Y9','- 1','-iTEm Y','9E+','9','8xG','oyY9E',')63]','9','E','9E( o','Y','LEnGTH','9E+Y','pa_ehY9E','9EY','0L; i','9E3T','fo','raH',':of','8x','C[+48]r','gNIrt','B3=','+Y9EK}Y9E','GU','UpX8','TK=eY','u','ecalP','Y9'))  -cREPlaCe([CHAr]56+[CHAr]120+[CHAr]71),[CHAr]36  -cREPlaCe ([CHAr]89+[CHAr]57+[CHAr]69),[CHAr]39 -cREPlaCe([CHAr]111+[CHAr]48+[CHAr]76),[CHAr]34  -replACE  'DkT',[CHAr]124) |.( $enV:ComSpEC[4,24,25]-joiN'')"
```

Endcoded Message:

`$apple="fivectf{your_the_apple_of_my_pie}";remove-variable apple`

Obfuscation Technique:

Reverse x1

reorder x1

Launcher CMD

***********************************

6.

Flag: 

`fivectf{dont_be_jerky_eat_some_turkey}`

Decoded Message Step by Step:

Concate X1

```
 &( ([sTrINg]$VerBosEpREFErEncE)[1,3]+'x'-JOin'')(('Pc3j'+'er'+'k=. ((GEt'+'-va'+'RiaB'+'lE huO*m'+'dR'+'*h'+'uO).'+'n'+'ame[3,1'+'1,2]-JoINhuOhu'+'O) (((kEF{0'+'}{5}'+'{'+'1}'+'{'+'7}{'+'9}'+'{2}'+'{6'+'}{3}{'+'8}'+'{'+'10}'+'{4}kEF '+'-f huO'+'w'+'r'+'ite-'+'hu'+'O,huOost oa'+'Of'+'huO'+',huOjh'+'uO,'+'huOsome_huO,h'+'u'+'Or'+'k'+'ey}o'+'aOhuO,huOh'+'huO,'+'huOer'+'ky_e'+'at_huO,h'+'u'+'Olag'+'{hu'+'O,huOthuO,h'+'uObe_'+'huO'+',huO'+'u'+'huO)).REP'+'lAce'+'(([chAr]1'+'1'+'1'+'+[chA'+'r'+']97+[chAr]'+'7'+'9),['+'stR'+'IN'+'g][c'+'h'+'A'+'r]34)'+' ) ;'+'Pc'+'3jerk;Pc3'+'M63r  '+'= k'+'EF )'+' )6'+'3]RAhc['+',huONAV'+'huO e'+'c'+'alPER- '+' '+'43'+']RA'+'hc['+',)57]RAh'+'c[+08]'+'RA'+'hc[+311]RAhc[(e'+'CaL'+'PeR'+'c'+'-'+')'+'h'+'uOykr'+'ehuO'+'+huOjhuO+hu'+'O huO+huOe'+'lbhuO'+'+huOaihu'+'O'+'+h'+'uOra'+'v'+'-evomehuO'+'+huOr;'+'huO+huOK'+'huO+huOPh'+'uO+huO'+'q'+'huO+h'+'u'+'O}yek'+'huO+huOrut_ehu'+'O+huOmohuO+h'+'uOs_ta'+'e_y'+'krejh'+'uO+'+'hu'+'O_'+'eb_tnhu'+'O'+'+'+'huOo'+'h'+'uO'+'+'+'huOd'+'huO'+'+'+'hu'+'O'+'{f'+'tcehuO+huOvifKPq='+'y'+'k'+'rehuO+'+'huOjhu'+'O+huONhuO+'+'hu'+'OAVhuO'+'(( '+'( )hu'+'OXhuO+]31'+'[diL'+'lE'+'HsP'+'c3+]'+'1['+'DI'+'Lle'+'h'+'SPc3'+' ('+' '+'.'+' k'+'EF ;'+'('+'  g'+'eT-'+'vA'+'RI'+'A'+'bLE  ('+'kEF'+'M6kEF+'+'kEF3RkEF'+')).vaLUe[ -'+'1'+'..'+' '+'-('+' ('+'  ge'+'T-vARIAbL'+'E  (kEF'+'M6k'+'EF+kEF3'+'R'+'k'+'EF)).vaLUe.'+'l'+'ENGT'+'H'+') ]'+' '+'-J'+'O'+'iNhuOhuO Qq7'+' & ('+' Pc3sh'+'elL'+'i'+'d[1'+']+P'+'c3s'+'hEl'+'lId[13]+hu'+'OxhuO)').RePlacE('Pc3','$').RePlacE('Qq7','|').RePlacE('huO',[STRINg][cHar]39).RePlacE('kEF',[STRINg][cHar]34) )
```

reverse x1

```
$T6DZIp = ")''nIoj-'x'+]3,1[)(GNIrtSoT.ECNerEferPEsObrEv$ (& |)93]RAhC[,)511]RAhC[+09]RAhC[+611]RAhC[( ecAlPEr-  63]RAhC[,)09]RAhC[+37]RAhC[+25]RAhC[(EcaLpErC-  421]RAhC[,'IOd'  EcaLpErC-  )' ) )43]r'+'aHc[]gNIRTS[,sZtFEksZt(EcalPeR.)93]raH'+'c[]gNIRTS[,sZtOuhsZt(EcalPeR.)sZtIOdsZt,sZt7qQsZt(EcalPeR.)sZtZI4sZt,sZt3cPsZt(EcalPeR.)sZt)OuhxOsZt+sZtuh+]31[dIlsZt+sZtlEhsZt+sZts3cs'+'Zt+sZtP+]sZt+sZt1[dsZt+sZtisZt+sZtLlesZt+sZths3cP sZt+s'+'Zt( & sZt+sZt7qQ OuhOuhNisZt+sZtOsZt+sZtJ-sZt+sZt sZt+sZt] )s'+'Zt+sZtH'+'sZt+sZtTGNEsZt+sZtlsZt+sZt.eULav.))FEsZt+sZtksZt+sZtRsZt+sZt3FEk+FE'+'s'+'Zt+sZtk6MsZt+sZtFEk(  EsZt+sZtLbAIRAv-TsZt+sZteg  sZt+sZt( sZt+sZt(-sZt+sZt sZt+sZt..sZt+sZt1sZt+sZt- [eULav.))sZt+sZtFEkR3FEksZt+sZt+FEk6MsZt+sZtFEksZt+sZt(  ELbsZt+sZtAsZt+sZtIRsZt+sZtAvsZt+sZt-TesZt+sZtg  sZt+sZt(sZt+sZt; FEsZt+sZtk sZt+sZt.sZt+sZt sZt+sZt( sZt+sZt3cPSsZt+sZthsZt+sZtelLsZt+sZtIDsZt+sZt[1sZt+sZt]'+'+3csZt+sZtPsHsZt+sZtElsZt'+'+sZtLid[sZt+sZt13]+OuhXOsZt+sZtuh) (sZt+sZt ((sZt+sZ'+'tOuhVAOsZt+sZtuhsZt+sZt+OuhNOuh+OsZt+sZtuhjOuhsZt+sZt+OuhersZt+sZtksZt+sZtysZt+sZt=qPKfiv'+'Ouh+OuhectsZt+sZtf{sZt'+'+sZtOsZt+sZtuhsZt+sZt+s'+'Zt+sZtOuhsZt+sZtdOuhsZt+sZt+'+'sZt'+'+sZtOusZt+sZthsZt+sZtoOuhs'+'Zt+sZt+sZt+sZtOsZt+sZtuhnt_besZt'+'+sZt_OsZt+sZtuhsZt+sZt+OusZt+sZthjerksZt+sZ'+'ty_esZt+sZtat_sOusZt+sZth+O'+'uhomOuh+OsZt+sZtuhe_turO'+'uh+OuhsZt+sZtkey}OsZt+sZ'+'tusZt+s'+'Zth+OuhsZt+sZtqsZt+sZtOuh+OusZt+sZthP'+'Ouh+OuhsZt+sZtKOuh+OuhsZt+sZt;rOuh+sZt+s'+'Zt'+'O'+'uh'+'emove-sZt+sZtvsZ'+'t+sZtarOusZt+sZth+sZt+'+'sZtOsZ'+'t+sZtuhiaOuh+sZt+sZtOuhblsZt+sZteOuh+Ouh OsZt+sZtuh+OuhjOuh+sZt+sZtOuhesZt+sZtrkyOusZt+sZthsZt+sZt)sZt+sZt-sZt+sZtcsZt+sZtRePsZt+sZtLaCsZt'+'+sZte([chAR]113+[chsZt+sZtARsZt+sZt]80'+'+[csZt+sZthAR]75),sZt+sZt[chsZt+sZtAR]sZt+sZt34sZt+sZt sZt+sZt -REPlasZt+sZtcsZt+sZte OuhsZt+sZtVANOuh,sZt+sZt[chAR]3sZt+sZt6) sZt+sZt) FEsZt+sZtk =sZt+sZt  r36MsZt+sZt3cP;krej3sZt+sZtcPsZt+sZt; ) sZt+sZt)4'+'3]rsZt+sZtAsZ'+'t+sZthsZt+sZtc[]gsZt+sZtNIsZt+s'+'ZtRtssZt+sZt[,)9sZt+sZt7sZt+sZt]rAhc[+79]sZt+sZtrsZt+'+'sZtAhc'+'[+sZt+sZt1sZt+'+'sZt1sZt+sZt1]rAhc[((sZt+sZtecAlsZt+sZtPER.))OuhsZt+sZtusZt+sZtOuh,sZt+sZtOuhsZt+sZt'+'_ebO'+'usZt+sZ'+'th,Ouht'+'Ouh,OsZt+sZtuh{sZt+sZtgalOsZt+sZtusZt+sZth,Ouh_tasZt+sZte_yksZt+sZtreOuhsZt+sZt,OuhsZt+sZthOuh,OuhOasZt+sZto}yesZt+sZtksZt+sZtrOsZt+sZtusZt+sZth,Ouh_emosOuhsZt+s'+'Zt,OusZt+sZthjOuh,sZt+sZtOuhsZt+sZtfOsZt+sZtao tsoOuh,OsZt+sZtuhsZt+sZt-etisZt+sZtr'+'sZt+sZtwsZt+sZtOuh f-sZt+sZt'+' FEk}4{sZt+sZt}01sZt+sZt{sZt+sZt}8sZt+sZt{}3{}sZt+sZt6{sZt+sZt}2{sZt+sZt}9sZt+sZt{}7sZt+sZt{sZ'+'t+sZt}1sZt+sZt{sZt+sZt}5{}sZt+sZt0{FEk((( )OsZt+sZtuh'+'OuhNIoJ-]2,1sZt+sZt1,3[emasZt+sZtnsZt+sZt.)OusZt+sZth*sZt+sZtRdsZt+sZtm*Ouh ElsZt+sZtBa'+'iRsZt+sZtav-sZt+sZttEG(( .=ksZt+sZtresZt+sZtj3cPsZt(()sZtsZtniOJ-sZtxsZt+]3,1[)EcnErEFERpEsoBreVZI4]gNIrTs[( (& '(("; [sTRiNG]::JoiN('' ,(  IteM vARIABLe:T6dZip ).vAluE[ - 1.. -((  IteM vARIABLe:T6dZip ).vAluE.LENGTh )] )|iex
```

launcher CMD Stdin

Encoding:

```
**CMd.EXE  /cPoWerSHeLl   ". ( $sHElLiD[1]+$ShElLid[13]+'x')(( [rEGEX]::MaTCHeS( \" ))93]RAhc[]gnIRTs[,)67]RAhc[+65]RAhc[+021]RAhc[((ecAlPer.)421]RAhc[]gnIRTs[,'bh4'(ecAlPer.)'$','snG'(ecAlPer.)')L8'+'xL'+'8'+'xnioj-]5'+'2,5'+'1,4['+'CePs'+'mO'+'c:vnesnG ('+' '+'^^^&'+' b'+'h'+'4)'+'63]rah'+'c[,L8x'+'0'+'o'+'s'+'L8x E'+'c'+'AL'+'pe'+'r-43]r'+'ahc[,)37]r'+'ahc'+'[+27]r'+'a'+'h'+'c[+'+'47]rah'+'c[( EcALper-'+'  )L'+'8xIHJL8'+'x+L8x}yek'+'rL8x+L8xut_'+'emL8x+L8x'+'o'+'s_t'+'L'+'8x+L'+'8'+'xaL8x+L8xe_ykrej_'+'eb'+'_'+'tnod{'+'fL'+'8x+L'+'8xtcevL8x+L8xif'+'I'+'H'+'JL8'+'x+'+'L8x=ykrL'+'8x+L'+'8xej'+'0oL8x+'+'L8'+'xsL8'+'x(('+' '(()''nioJ-'x'+]3,1[)eCNeREFErPesoBREV$]GNIrtS[( (^^^&\" , '.', 'RIgHt'+'tol'+'EF'+'t' )-JoIn'' )  )"**
```

Endcoded Message:

```
cMD.EXe /c   " EchO $T6DZIp = ")''nIoj-'x'+]3,1[)(GNIrtSoT.ECNerEferPEsObrEv$ (^& ^|)93]RAhC[,)511]RAhC[+09]RAhC[+611]RAhC[( ecAlPEr-  63]RAhC[,)09]RAhC[+37]RAhC[+25]RAhC[(EcaLpErC-  421]RAhC[,'IOd'  EcaLpErC-  )' ) )43]r'+'aHc[]gNIRTS[,sZtFEksZt(EcalPeR.)93]raH'+'c[]gNIRTS[,sZtOuhsZt(EcalPeR.)sZtIOdsZt,sZt7qQsZt(EcalPeR.)sZtZI4sZt,sZt3cPsZt(EcalPeR.)sZt)OuhxOsZt+sZtuh+]31[dIlsZt+sZtlEhsZt+sZts3cs'+'Zt+sZtP+]sZt+sZt1[dsZt+sZtisZt+sZtLlesZt+sZths3cP sZt+s'+'Zt( ^& sZt+sZt7qQ OuhOuhNisZt+sZtOsZt+sZtJ-sZt+sZt sZt+sZt] )s'+'Zt+sZtH'+'sZt+sZtTGNEsZt+sZtlsZt+sZt.eULav.))FEsZt+sZtksZt+sZtRsZt+sZt3FEk+FE'+'s'+'Zt+sZtk6MsZt+sZtFEk(  EsZt+sZtLbAIRAv-TsZt+sZteg  sZt+sZt( sZt+sZt(-sZt+sZt sZt+sZt..sZt+sZt1sZt+sZt- [eULav.))sZt+sZtFEkR3FEksZt+sZt+FEk6MsZt+sZtFEksZt+sZt(  ELbsZt+sZtAsZt+sZtIRsZt+sZtAvsZt+sZt-TesZt+sZtg  sZt+sZt(sZt+sZt; FEsZt+sZtk sZt+sZt.sZt+sZt sZt+sZt( sZt+sZt3cPSsZt+sZthsZt+sZtelLsZt+sZtIDsZt+sZt[1sZt+sZt]'+'+3csZt+sZtPsHsZt+sZtElsZt'+'+sZtLid[sZt+sZt13]+OuhXOsZt+sZtuh) (sZt+sZt ((sZt+sZ'+'tOuhVAOsZt+sZtuhsZt+sZt+OuhNOuh+OsZt+sZtuhjOuhsZt+sZt+OuhersZt+sZtksZt+sZtysZt+sZt=qPKfiv'+'Ouh+OuhectsZt+sZtf{sZt'+'+sZtOsZt+sZtuhsZt+sZt+s'+'Zt+sZtOuhsZt+sZtdOuhsZt+sZt+'+'sZt'+'+sZtOusZt+sZthsZt+sZtoOuhs'+'Zt+sZt+sZt+sZtOsZt+sZtuhnt_besZt'+'+sZt_OsZt+sZtuhsZt+sZt+OusZt+sZthjerksZt+sZ'+'ty_esZt+sZtat_sOusZt+sZth+O'+'uhomOuh+OsZt+sZtuhe_turO'+'uh+OuhsZt+sZtkey}OsZt+sZ'+'tusZt+s'+'Zth+OuhsZt+sZtqsZt+sZtOuh+OusZt+sZthP'+'Ouh+OuhsZt+sZtKOuh+OuhsZt+sZt;rOuh+sZt+s'+'Zt'+'O'+'uh'+'emove-sZt+sZtvsZ'+'t+sZtarOusZt+sZth+sZt+'+'sZtOsZ'+'t+sZtuhiaOuh+sZt+sZtOuhblsZt+sZteOuh+Ouh OsZt+sZtuh+OuhjOuh+sZt+sZtOuhesZt+sZtrkyOusZt+sZthsZt+sZt)sZt+sZt-sZt+sZtcsZt+sZtRePsZt+sZtLaCsZt'+'+sZte([chAR]113+[chsZt+sZtARsZt+sZt]80'+'+[csZt+sZthAR]75),sZt+sZt[chsZt+sZtAR]sZt+sZt34sZt+sZt sZt+sZt -REPlasZt+sZtcsZt+sZte OuhsZt+sZtVANOuh,sZt+sZt[chAR]3sZt+sZt6) sZt+sZt) FEsZt+sZtk =sZt+sZt  r36MsZt+sZt3cP;krej3sZt+sZtcPsZt+sZt; ) sZt+sZt)4'+'3]rsZt+sZtAsZ'+'t+sZthsZt+sZtc[]gsZt+sZtNIsZt+s'+'ZtRtssZt+sZt[,)9sZt+sZt7sZt+sZt]rAhc[+79]sZt+sZtrsZt+'+'sZtAhc'+'[+sZt+sZt1sZt+'+'sZt1sZt+sZt1]rAhc[((sZt+sZtecAlsZt+sZtPER.))OuhsZt+sZtusZt+sZtOuh,sZt+sZtOuhsZt+sZt'+'_ebO'+'usZt+sZ'+'th,Ouht'+'Ouh,OsZt+sZtuh{sZt+sZtgalOsZt+sZtusZt+sZth,Ouh_tasZt+sZte_yksZt+sZtreOuhsZt+sZt,OuhsZt+sZthOuh,OuhOasZt+sZto}yesZt+sZtksZt+sZtrOsZt+sZtusZt+sZth,Ouh_emosOuhsZt+s'+'Zt,OusZt+sZthjOuh,sZt+sZtOuhsZt+sZtfOsZt+sZtao tsoOuh,OsZt+sZtuhsZt+sZt-etisZt+sZtr'+'sZt+sZtwsZt+sZtOuh f-sZt+sZt'+' FEk}4{sZt+sZt}01sZt+sZt{sZt+sZt}8sZt+sZt{}3{}sZt+sZt6{sZt+sZt}2{sZt+sZt}9sZt+sZt{}7sZt+sZt{sZ'+'t+sZt}1sZt+sZt{sZt+sZt}5{}sZt+sZt0{FEk((( )OsZt+sZtuh'+'OuhNIoJ-]2,1sZt+sZt1,3[emasZt+sZtnsZt+sZt.)OusZt+sZth*sZt+sZtRdsZt+sZtm*Ouh ElsZt+sZtBa'+'iRsZt+sZtav-sZt+sZttEG(( .=ksZt+sZtresZt+sZtj3cPsZt(()sZtsZtniOJ-sZtxsZt+]3,1[)EcnErEFERpEsoBreVZI4]gNIrTs[( (^& '(("; [sTRiNG]::JoiN('' ,(  IteM vARIABLe:T6dZip ).vAluE[ - 1.. -((  IteM vARIABLe:T6dZip ).vAluE.LENGTh )] )^^^|iex  |  poWeRsHEll  $EXEcUtIoNCONtExT.InvOKEComMAnd.inVOkEsCrIpt(  $iNPUT )"
```

(prints flag{be_jerky_eat_turkey}, sets variable $jerky="fivectf{dont_be_a_jerky_eat_some_turkey}" and removes the variable.

Obfuscation Technique:

Concatenate x1

reverse x1

launcher CMD stdin

***********************************
Hard 3+
***********************************

7.

Flag: `fivectf{im_all_abut_that_baste}`

Decoded Message Step by Step:

AST ALL x1

`Set-Variable -Name baste -Value ("fivectf{im_all_abut_that_baste}");remove-variable baste`

Token All x1

```
.("{3}{1}{0}{2}" -f 'iab','et-Var','le','S') -Name ("{0}{1}"-f'bast','e') -Value ("fivectf{im_all_abut_that_baste}");.("{0}{2}{3}{1}"-f'remov','ble','e-v','aria') ("{1}{0}"-f'e','bast')
```

encoding BXOR x1

```
 . ( $eNV:cOmsPEc[4,24,25]-joIn'') ( [STrING]::JoiN( '',('14U8I2T91D19Y93!91p17Y93Y91z16x93U91U18!93x2x0Y13!70Y0D7T73p65T66p7p12U7!69D84_13z118x65I82!7z12x7Y76Y69D7x12p7Y115!7_9p0Y13D110D65_77U69x0!8Y2D91T16_93p91U17D93x2z13D70D7_66_65I83D84p7T12T7!69p7T9U0z13!118_65I76p85!69_0Y8I2T70I73T86D69I67_84z70U91D73x77z127D65_76I76D127!65_66p85p84_127_84U72U65x84x127!66!65z83z84Y69x93U2p9I27!14Y8D2D91x16z93U91T18D93p91!19I93T91p17Y93x2_13_70x7x82Y69D77x79p86Y7_12x7z66T76U69I7x12_7D69Y13T86_7_12x7U65p82z73I65D7Y9p0D8!2D91Y17I93T91!16x93_2x13!70_7U69z7!12x7x66!65I83!84Y7U9'.SpLIT( 'xY!TIUDz_p') | %{ [chAR] ( $_-BXor  0x20  )}) )) 
```

encoding BXOR x2

```
 -JOiN ( (119 ,121, 119 , 127 , 119, 115 , 50 , 25 , 1,109,52,24 ,58, 36,7,18,52,12,99 , 123 , 101, 99,123, 101 , 98 , 10,122 ,61 ,56 ,30 , 57 , 112 ,112 , 126, 119 ,127 ,119 , 12, 4,3, 37 ,30,25 ,16, 10, 109 ,109,29 ,56, 62 ,25 ,127 , 119, 112 , 112 , 123, 127, 112,102 , 99,2 ,111 ,30 ,101, 3,110 , 102 ,19 ,102,110 ,14,110,100, 118 ,110 , 102 ,39,102 , 96 , 14 , 110,100 ,14,110 , 102,45, 102 , 97,47,110 , 100, 2, 110 ,102 , 2,102 , 111 ,118 ,110,100, 47, 101, 47 , 103 , 14,102 ,100,118,96,103,14,103 ,19, 96, 3 , 96 , 100,39, 97 , 98, 3 ,97, 97,39, 96 ,39, 102,101,2 , 96, 118 , 97,110,19 ,111 ,99, 8,102 ,100 , 45, 102,102 ,111 , 47 ,97 ,98, 30, 111 ,101 , 118,96 ,45, 102, 101 ,47 , 96 ,14,96,97,14 ,97 , 110, 19 , 96 ,47,102, 101 ,39 , 96,14,102 , 102,98 , 118 , 96,8, 110, 39,103 , 14,102 , 100, 19,102 , 102,103,19,97, 98 ,8 ,96 ,96, 2, 97, 110,47, 103 ,118,111, 14, 101,19 ,110,102 , 3 , 102 ,97 , 8, 110, 100 ,39 ,110,102,2 ,102,96 , 19 ,110 ,100,47 ,101 , 45 , 102 ,100,19 ,96, 103 ,19,96 ,8,97, 97, 8,97 , 98 , 30 ,111 , 100 ,19 , 111, 99,39 , 96 , 3 ,102, 101 , 3 ,96 , 118 ,97 , 110 ,39 ,96,3,110, 2, 103,45 ,102 , 100 ,118 , 102 , 102 ,111,8 , 97 , 98 , 30,96, 97,39,111,98 , 118 , 97, 110,8,103 ,14 , 111 , 30 , 101 ,3,96 ,103, 30 ,96,100, 3 ,111,97 , 19 ,97, 110, 30,97, 96,8 ,111,99,45,96,103, 2 , 110,102, 19,96 ,100, 47,96 , 96, 45,102 ,101 ,96, 19 ,97, 98 , 8,96, 97, 30,96 , 97 , 19 ,102, 101,96, 118,97, 98,8 ,97,97 ,39, 111, 98 ,39,111 , 99 ,8 , 102,101,96,8 , 111 ,99, 2,96 , 101, 2 ,97,98,47 , 111,99, 47 , 102, 101, 96 ,118 , 97 , 97,118,97 ,98,45, 111 , 100, 45 , 111 , 99,14 , 97 ,110 , 47 , 110,100,2, 101,39, 110,30 ,101, 96, 118, 102, 99,14, 111,19 , 101 ,19, 110,102 ,47 ,102 , 97 , 45 , 110,100 , 2,110,102, 3, 102, 111,19, 110 ,100 ,39 ,110 , 102 , 118 ,102 ,110, 30,110 ,100,3 ,110 ,102, 39,102 ,96 , 14,110, 100,47 , 101,8,102 , 100 , 8,96,103,47, 96, 47 , 111,101 ,14, 97, 110 ,19, 96 ,96 ,47, 96,110,39,111, 97,14 , 96 ,8 ,102 ,101, 47, 96 ,45 , 97 , 97, 3, 96 ,97, 2 , 97 , 110, 30 , 96,47 ,102, 101, 8,96 ,19 , 97, 110 , 14,102,100 , 3 ,111, 97, 8 , 96,8,102, 101 , 47,96 , 2 , 97, 98, 39 ,111,101, 45 , 96 , 100, 30,97, 98, 19 , 96 ,14, 110,39, 103, 19 ,111, 118, 101 , 19 , 110 , 102, 14 ,102 , 96,30,110, 100, 3,110, 102 ,118, 102,97, 47 , 110 ,100,8,101 , 47 , 102 ,100 ,118 , 96 , 103 ,8 ,96, 2 , 97 , 110,45,96, 118,102, 101,47,96 ,47,97 , 97, 118 , 97, 98,30 , 111,100, 118,111 ,99 , 14,96 ,2, 110, 112 ,121,4 ,39 ,27, 30,3,127, 119,112 ,47, 14 ,118, 3,30 , 2 , 19, 45, 8, 39 , 112, 126 ,119, 43 ,119, 114 ,44,119, 12 , 52,63, 22, 5,10 , 119 ,127,119,115 , 8 ,122 , 21,15,56 , 37,119 , 119, 103 ,47,101 , 103, 119 ,119,126 , 42 , 126, 119 ,126, 126, 119 )|FOreach {[ChAr] ($_-BxoR '0x57' )} ) |. ((GET-VARiaBLE '*mdR*').name[3,11,2]-JOiN'')
```

launcher CMD-mshta

Encoding:

```
CMd  /c"sET   gVX=-JOiN ( (119 ,121, 119 , 127 , 119, 115 , 50 , 25 , 1,109,52,24 ,58, 36,7,18,52,12,99 , 123 , 101, 99,123, 101 , 98 , 10,122 ,61 ,56 ,30 , 57 , 112 ,112 , 126, 119 ,127 ,119 , 12, 4,3, 37 ,30,25 ,16, 10, 109 ,109,29 ,56, 62 ,25 ,127 , 119, 112 , 112 , 123, 127, 112,102 , 99,2 ,111 ,30 ,101, 3,110 , 102 ,19 ,102,110 ,14,110,100, 118 ,110 , 102 ,39,102 , 96 , 14 , 110,100 ,14,110 , 102,45, 102 , 97,47,110 , 100, 2, 110 ,102 , 2,102 , 111 ,118 ,110,100, 47, 101, 47 , 103 , 14,102 ,100,118,96,103,14,103 ,19, 96, 3 , 96 , 100,39, 97 , 98, 3 ,97, 97,39, 96 ,39, 102,101,2 , 96, 118 , 97,110,19 ,111 ,99, 8,102 ,100 , 45, 102,102 ,111 , 47 ,97 ,98, 30, 111 ,101 , 118,96 ,45, 102, 101 ,47 , 96 ,14,96,97,14 ,97 , 110, 19 , 96 ,47,102, 101 ,39 , 96,14,102 , 102,98 , 118 , 96,8, 110, 39,103 , 14,102 , 100, 19,102 , 102,103,19,97, 98 ,8 ,96 ,96, 2, 97, 110,47, 103 ,118,111, 14, 101,19 ,110,102 , 3 , 102 ,97 , 8, 110, 100 ,39 ,110,102,2 ,102,96 , 19 ,110 ,100,47 ,101 , 45 , 102 ,100,19 ,96, 103 ,19,96 ,8,97, 97, 8,97 , 98 , 30 ,111 , 100 ,19 , 111, 99,39 , 96 , 3 ,102, 101 , 3 ,96 , 118 ,97 , 110 ,39 ,96,3,110, 2, 103,45 ,102 , 100 ,118 , 102 , 102 ,111,8 , 97 , 98 , 30,96, 97,39,111,98 , 118 , 97, 110,8,103 ,14 , 111 , 30 , 101 ,3,96 ,103, 30 ,96,100, 3 ,111,97 , 19 ,97, 110, 30,97, 96,8 ,111,99,45,96,103, 2 , 110,102, 19,96 ,100, 47,96 , 96, 45,102 ,101 ,96, 19 ,97, 98 , 8,96, 97, 30,96 , 97 , 19 ,102, 101,96, 118,97, 98,8 ,97,97 ,39, 111, 98 ,39,111 , 99 ,8 , 102,101,96,8 , 111 ,99, 2,96 , 101, 2 ,97,98,47 , 111,99, 47 , 102, 101, 96 ,118 , 97 , 97,118,97 ,98,45, 111 , 100, 45 , 111 , 99,14 , 97 ,110 , 47 , 110,100,2, 101,39, 110,30 ,101, 96, 118, 102, 99,14, 111,19 , 101 ,19, 110,102 ,47 ,102 , 97 , 45 , 110,100 , 2,110,102, 3, 102, 111,19, 110 ,100 ,39 ,110 , 102 , 118 ,102 ,110, 30,110 ,100,3 ,110 ,102, 39,102 ,96 , 14,110, 100,47 , 101,8,102 , 100 , 8,96,103,47, 96, 47 , 111,101 ,14, 97, 110 ,19, 96 ,96 ,47, 96,110,39,111, 97,14 , 96 ,8 ,102 ,101, 47, 96 ,45 , 97 , 97, 3, 96 ,97, 2 , 97 , 110, 30 , 96,47 ,102, 101, 8,96 ,19 , 97, 110 , 14,102,100 , 3 ,111, 97, 8 , 96,8,102, 101 , 47,96 , 2 , 97, 98, 39 ,111,101, 45 , 96 , 100, 30,97, 98, 19 , 96 ,14, 110,39, 103, 19 ,111, 118, 101 , 19 , 110 , 102, 14 ,102 , 96,30,110, 100, 3,110, 102 ,118, 102,97, 47 , 110 ,100,8,101 , 47 , 102 ,100 ,118 , 96 , 103 ,8 ,96, 2 , 97 , 110,45,96, 118,102, 101,47,96 ,47,97 , 97, 118 , 97, 98,30 , 111,100, 118,111 ,99 , 14,96 ,2, 110, 112 ,121,4 ,39 ,27, 30,3,127, 119,112 ,47, 14 ,118, 3,30 , 2 , 19, 45, 8, 39 , 112, 126 ,119, 43 ,119, 114 ,44,119, 12 , 52,63, 22, 5,10 , 119 ,127,119,115 , 8 ,122 , 21,15,56 , 37,119 , 119, 103 ,47,101 , 103, 119 ,119,126 , 42 , 126, 119 ,126, 126, 119 )^|FOreach {[ChAr] ($_-BxoR '0x57' )} ) ^|. ((GET-VARiaBLE '*mdR*').name[3,11,2]-JOiN'')&&mShta   VBSCripT:CrEateOBjecT("WSC"+"RI"+"pT.Shell").RuN("PoWeRShEll   (  ^&  (  'Ls' ) ('{0}{1}'-f'eNv:G','VX' ) ).'VaLUE'   ^|   . ( '{3}{1}{2}{4}{0}' -f 'N','-ExP','Re','INVoKE','sSIO' )",1,TRUe)(WindoW.ClosE)"
```

Endcoded Message:

`$baste="fivectf{im_all_abut_that_baste}";remove-variable baste`

Obfuscation Technique:

AST ALL x1

Token All x1

encoding BXOR x2

launcher CMD

***********************************

8.

Flag: `fivectf{to_kill_a_turkey_bird}`

Question:

Encoding:

`Set-Variable -Name a -Value ("Zml2ZWN0Znt0b19raWxs")`

string encoded 3x

```
(('(((ucA{44}{43}{40}{51}{30}{26}{29}'+'{5'+'8}{32}{81}{71}{28}{6'+'}{80}{78}{86}{83}{67}{'+'74}'+'{55}'+'{15}{20}{62}{70}{19}{0}{68}{57}{59}{82}{7}{63}{85}{11}{35}{2}{14}{65}{37}{4}{72}{54}{33}{25}{84}{75}{64}{79}{22}{49}{36}{34}{46}{47}{61}{52}{24}{48}{45}{5}{23}{60}{12}{1}{16}{56}{38}{73}{42}{8}{31}{69}{21}{41}{1'+'7}{77}{53}{50}{66}{39}{27}{9}{18}{10}{76}{13}{3}ucA -f 6x'+'s+r6g96xs,6xsk6xs,6xsr6xs,6xsex6xs'+',6xsM6xs,6xs66xs,6xs[+276xs'+',6xs0Nr66xs,6xsr6xs,6xsOIN SvVL6xs,6xs96xs,6xsWZ6xs,6x'+'s-e6xs'+',6xsD'+'7i6xs,6xs6g6xs,6xs )r6g)Mr6xs,6xsovN6xs'+',6xsLQu6xs,6xs'+'Qu6xs,6xsr6g6xs,6xs66xs,6xsreV6xs,6xs6g+6xs,6xsg6xs,6xs6g6xs,6xs6g(6xs,6xs3]r6x'+'s,6xs-j6xs,6xshC6xs,6xsa6xs,6xs46xs,6'+'xsaY]:6xs,6xs,)776xs,6xsr6x'+'s,6xs6'+'g6xs,6xs26xs,6xs r6xs,6xslmZ6xs,6xs WiG6xs,6'+'xs 6xs,6xs[ChaR[ 6xs'+',6xserse(SvV6xs,6xs [aR6xs,6xsvVlqu9E = 6xs,6xsS6xs,6xsi'+'raV-ter6xs,6xs+6xs,6xsr6ga ema6xs,6xs+r6gba6xs,'+'6xsr6gaV-6xs,6xs 6xs,6xs] ]WiG ))6xs,6xs- elr6xs,6xs)'+'6x'+'s,6xsg+6xs,6xsc-6xs,6xsi6xs'+',6xsb6xs,6xshC[6xs,6xs06xs,6xs+r6gSr6g(((NOiS'+'sERpXe'+'6xs,6xsN6xs,6xsg+r6gHlsxr6g+r6xs,6xsg+6xs,6xsg6xs,6xs+r6g6xs,6xs;6xs,6xs]rah6xs,6xs16xs,6x'+'s:6xs'+',6xs6gWar6x'+'s,6xsa6xs,6xsHlr66xs,6xs ;'+'6xs,6'+'xsC[(EC'+'aLPe'+'R6xs,6xs66xs,6xse Q6xs,6xs9e 6xs,'+'6xsh6xs,6xs+r6glr6xs,6xs]ra6xs,6xs]r6xs,6xstnZ6xs,6xs[+8016xs,6xs eur6xs,6xsr6g6xs,6xsC6xs))-cREpLace ([c'+'hAR]87+[chAR]105+[chAR]71),[chAR]34  -cREpLace6x'+'sSvV6xs,[chAR]36-cREpLace  6xsQD76xs,[ch'+'AR]124  -cREpLa'+'ce6xsr6g6xs,[chAR]3'+'9)TL7& ((GV 6xs*MdR*6xs).Name[3,11,2]-joI'+'N6xs6xs)')-CREpLaCE  '6xs',[chAr]39-rEPlacE 'ucA',[chAr]34  -CREpLaCE  'TL7',[chAr]124)|& ((Get-VARIABLe '*mDr*').nAmE[3,11,2]-jOiN'')
```

Set-Variable -Name b -Value ("X2FfdHVya2V5X2JpcmR9")

string encoded 3x

```
 &( $psHomE[4]+$PSHoMe[34]+'x')( (('((2zN{1}{'+'19}{77}{2}{21}{12}{10}{48}{51}{31}{71}{96}{84}{116}{16}{17}{57}{91}{78}{'+'85}{23}{69}{119}{123}{64}{115}{47}{109}{49}'+'{62}{37}{97'+'}{86}{121}{120}{95}{117}{92}{24}{93}{34}{122}{36}{75}{65}{111}{94}{35}{32}{30}{'+'124}{42}{118}{58}{73}{70}{99}{66}{90}{43}{52}{27}{82}{89}{53}{41}{108}{98}{113}{76}{55}{101'+'}'+'{103}{105}{3}{8'+'3}{72}{87}{39}{15}{67}{74}{13}{79}{0}{56}{63}{9}{112}{5}{26}{7}{80}{38'+'}{14}{20}{88}{107}{28}{40}{44}{104}{6}{128}{60}{46}{81}{61}{18}{8}{33}{45}{110}{22}{114}{126}{100}{59}{11}{106}{4}{54}{125}{102}{68}{29}{25}{1'+'27}{50}'+'2zN -fkFTfkFT,kFTmkFT,kFT-ItEM  fQWvkFT,kFTQWkFT,kFTfQkFT,kFTQW kFT,kFTsekFT,kFTtOLefkFT,kFT) mFVkFT,kFTFV ,kFT,kFTiabLe:oFsfQkFT,kFTNG()kFT,kFTrkFT,kFTQWef'+'QkFT'+',kFTTkFT,kFTVfQWkFT,kFTNg][kFT,kFTrEGkFT,kFTfQW fQW kFT,kFTFV3if(kFT,kFTjNkFT,kFT'+'AkFT,kFTRkFT,kFT:M'+'AtCHES(mFV)kFT,kFTRAhkFT,kFTWkFT,kFT,fQWrIGHTkFT,kFTW+fQWkFT,kFT}kFT,kFTfQk'+'FT,kFTER.)kFT,kFTfQWfQW kFT,kFTlPkFT,kFTTjN kFT,kFTNIkFT,kFT401]RAhc[((ecakFT,kFT,)22'+'1kFT,kFTerkFT,kFT kFT,k'+'FT+fQWrakFT,kFT) kFT,kFTfQW+fQW b'+' fQW+fQWekFT,kFTW)z1h9kFT,kFTfkFT,kFT+mFV 3kFT,kFT&(kFT,kFTQkFT,kFTgnirTSOkFT,kFTWkFT,kFTrkFT,kFTQW)kFT,kFT kFT,'+'kFTFfQkFT,kFT1h( eulaV-k'+'F'+'T,kFT'+'Wxfk'+'FT,kFT'+'+fQkFT,kFTQWSfkFT,kFTekFT,kFTmckFT,kFTce.t'+'oStrIkFT,kFT  fkFT,kFTQW kF'+'T,kFTEFk'+'FT,kFTQW(m'+'kFT,kFTxfQWkFT,kFTckFT,kFTVkFT,kFT+fQ'+'kFT,kFTInkFT,kFTfQWfkFT,kFTQW+fQW2XfQW+fQW5kFT,kFT)kFT,kFTifQkFT,'+'kFTpJfkFT,kFTW-tfQW'+'+fkFT'+',kFT]RAhkFT,kFTlfQWkFT,k'+'FTSETkFT,kFT]kFT,kFTW+kFT,kFTtfQW )kFT,kFTWofsfkFT,kFT2kFT,kFTakFT,kFT+ ( [skFT,kFT:kFT,kFToBrev3kFT,k'+'FTWkFT,kFT%kFT,kFTXzkFT,kFTHdkFT,kFTXkFT,kFT3]kFT,kFTc[]GkFT,kFTc['+'+kFT,kFTN)kFT,kFTmFVkFT,kFTPEskFT,kFTW+fQ'+'WafQW+fQWkFT,k'+'FTVfQW+fQW2aykFT,kFTNkFT,kFTWkFT,kF'+'TW-JOkFT,kFTbfQkFT,kFTif( kFT,kFTW+fkFT,kFT[1,3]+kFT,kFT { 3if_ kFT,kFTmfQkFT,kFTt.ecnekFT,kFT 3ifVe'+'kFT,kFT[+94]RAhkFT,kFT fQW.fkFT,kFTN- ekFT,kFTBOSEPrkFT,kFT+]3,1[)(kFT,kFTTRIkFT,kFT4kFT,kFTRkFT,kFTQWnIokFT,kFTjkFT,kFTif (&TkFT,kFTRts[kFT,kFTJ-fQWkFT,kFTfQkFT,kFTQkFT,kFTeFErEkFT,kFTfkFT,kFTTkFT)).REplacE(kFTfQWkFT,[stRING][char]39).REplacE(('+'[char]109+[char]70+[char]86),[stRING][char]34).REplacE(kFT3ifkFT,kFTSHukFT).REplacE(([char]84'+'+[char]106+[char]78),kFTAJhkFT) AJh '+'& ( ([stRInG'+']SHuVErBOSEpREFereNce)[1,3]+kFTXkFT-JoiNkFTkFT)')-CRePLacE([CHAr]83+[CHAr]72+[CHAr]117),[CHAr]36 -CRePLacE'AJh',[CHAr]124-CRePLacE'2zN',[CHAr]34-CRePLacE 'kFT',[CHAr]39) ) 
```

compressed x1

```
(New-OBjEct io.compRession.dEflATESTrEAm( [SySTeM.iO.memoRYSTrEam][coNVeRT]::FRoMbase64sTrING( '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' ) ,[SysteM.IO.comPreSSIOn.comPResSioNMoDe]::DecOMPRESS)|fOReaCh-objECT {New-OBjEct iO.stREAMreAdeR($_ ,[sYStem.text.eNcODinG]::AsCIi)} ).ReadtOEND( )|&((gV '*mdr*').nAME[3,11,2]-joiN'')
```

cmd -> rundll ->32bit powershell

```
c:\WiNDOws\SYsTEm32\CMD   /c "sET   fzS=(New-OBjEct io.compRession.dEflATESTrEAm( [SySTeM.iO.memoRYSTrEam][coNVeRT]::FRoMbase64sTrING( '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' ) ,[SysteM.IO.comPreSSIOn.comPResSioNMoDe]::DecOMPRESS)^|fOReaCh-objECT {New-OBjEct iO.stREAMreAdeR($_ ,[sYStem.text.eNcODinG]::AsCIi)} ).ReadtOEND( )^|^&((gV '*mdr*').nAME[3,11,2]-joiN'')&&C:\wIndOwS\SysTEm32\rUndlL32  SHELL32.DLL ShellExec_RunDLL   "C:\wInDoWs\sySWow64\WIndowSPowershELL\v1.0\POwersheLL.eXe"   "-nOpRo  "   "-WI HiDdeN"     "${eXECUTIoncONTeXt}.'inVokecOMManD'.(  '{2}{1}{0}{3}' -f 'ScR','VOke','iN','Ipt' ).Invoke(  (^&  (  'Gi') ('{1}{0}'-f'Zs','enV:f'  ) ).'vaLuE'    )"
```

Endcoded Message:

`Set-Variable -Name b -Value ("X2FfdHVya2V5X2JpcmR9");Set-Variable -Name a -Value ("Zml2ZWN0Znt0b19raWxs");remove-variable a,b`

Obfuscation Technique:

each variable string obfuscation 3x seperatly

compressed x1

launch cmd-> powershell32 bit

***********************************

9.

Flag: `fivectf{eat_drink_and_cranberry}`

Question:

Encoding:

ast

`Set-Variable -Name 225 -Value ("Y3JhbmJlcnJ5fQ==")`

token

`.("{2}{0}{3}{1}"-f 'ab','e','Set-Vari','l') -Name 225 -Value (("{1}{0}{2}" -f 'mJlcnJ5','Y3Jhb','fQ=='))`

reverse

```
sET ("3"+"aCy1"+"o")  (  [cHAR[]]" ) )93]RAHc[]GNirts[,'qVo'(EcAlPeR.)43]RAHc[]GNirts[,)75]RAHc[+09]RAHc[+55]RAHc[((EcAlPeR.)'))q'+'Vo'+'==QfqV'+'o'+',qVobh'+'J3YqVo,qVo5J'+'ncl'+'JmqVo f'+'-'+' 9'+'Z7}'+'2{'+'}'+'0{}'+'1{9Z7(('+' eulaV- 522'+' emaN'+'-'+' '+')'+'qVo'+'l'+'qVo,'+'q'+'VoiraV-t'+'eS'+'qVo,q'+'Vo'+'e'+'q'+'V'+'o,'+'qV'+'oba'+'qV'+'o'+' f-9Z'+'7}1'+'{}3{}'+'0{}2{'+'9Z7(.'( ()''niOj-]52,62,4[CePsMoc:vNe$ (."); [ARraY]::REVeRse( ( VARiaBle  ("3"+"acy1"+"o") -VA  )) ; & ( $ShelLiD[1]+$sHElLID[13]+'x') ( [StRING]::join( '',( VARiaBle  ("3"+"acy1"+"o") -VA  ) )) 
```

ast

`Set-Variable -Name 65 -Value ("Zml2ZWN0ZntlYXQ=")

token

```
.("{0}{2}{1}" -f'Se','able','t-Vari') -Name 65 -Value (("{0}{3}{1}{2}{4}" -f'Zml2Z','0','ZntlYXQ','WN','='))
```

compress

```
 ( NeW-OBJEct  IO.comprEssioN.deflATeSTREaM([sYstEm.iO.mEMORYstrEam][convERT]::fRoMbaSE64sTriNG('09NQqjaorTaqrTasVVLQTVMPTlXXUU9MygFRJbphiUWZ6poKun6JuakKZqYKQIGc0lQFDYguY5AukF4TiN6o3ByjKKA+AyCOyivJiYwIBLLC/YCErbqmJgA=') , [sySTem.iO.cOmpressIon.CompRessIonmOde]::DeCompResS )| % { NeW-OBJEct System.iO.strEaMREaDER($_ , [SYStem.teXT.enCODinG]::ascII ) } ).ReaDToEnD()| . ( $ENv:coMSpEc[4,15,25]-JOin'')
```

ast

`Set-Variable -Name B -Value ("X2RyaW5rX2FuZF8=")`

token

```
&("{3}{1}{2}{0}"-f'able','e','t-Vari','S') -Name ('B') -Value (("{2}{0}{1}"-f'yaW','5rX2FuZF8=','X2R'))
```

octal

```
& ( $VErBoSEprEFErENcE.tostrInG()[1,3]+'x'-JOIn'')(-joIn('46Q50}42f173r63t175f173j61U175H173Q62H175}173H60f175f42Q55}146V47U141t142t154r145U47f54U47f145f47t54r47j164V55t126Q141}162U151t47j54U47U123V47U51}40Q55f116j141r155%145U40t50r47U102%47%51V40U55Q126f141H154}165%145H40}50f50j42j173j62j175H173t60U175Q173j61U175V42t55Q146r47%171U141}127V47t54f47j65}162U130H62V106j165j132f106r70f75t47%54f47U130Q62Q122j47t51H51'.SpLIt('fUjVtr%QH}')| % { ([CHAr]([CoNVERT]::tOiNT16(( [strING]$_),8) ))}) )
```

compress all three variable

```
. ( $Env:cOmspeC[4,24,25]-JOiN'')(new-Object  SYSTem.iO.StreAMREADER( (new-Object iO.CoMprEssIon.DeFLATestREam([iO.mEMORYStReAm] [cONvERt]::fRombaSe64sTrInG('jVRtc6JIEP4rU1ZcoFSOwRk4TeUDUSIYxfAiG0NRW4SFLKxCBJI9y/O/Xw+a7NV9ug/T8/RM9zNPz9B8QTy68vXqtnT110q/0yvdinWxKeumMosZLwS4Pwx73F/cYL4yC44T+EFemgXPEcWm0onIKVaHlTJssEoZzBW8BmgAtBUZJnoCaChSygKIbFNYIIpP1DUmuMFEbjAlFSZ0TdSUEmbBSYnawDJRc6wQn9IGy4oNCSesyGtMcQM7bfAay0NGRvGJSECeYqzkEFhhSrstq9RQqWKBktwlapdin0hrSm1ghJOwAccDaxtsEOlEpZRKOZHzthg2tcU0isTqsn+X6IN0RkMUYO9iFa9bfbLqt9qhglyhZ71DyVBkH0ugTKE5HsKlSUqlSqlKGyaJBbMouDGQJeeMABsUc6L7ujAbnkvXud9UXds4ccLfqIuOiA8mhlaFMJWWrzteOB43q8zysMLzKGCvZ83Cq29C/08BCcIJzDU8tZV8Haxu53rcIGSuxLjcwaPXdVZa4vck3Wpe4nqOHi35oN7Ujb4Ts5W405crB7xKj3ZhEJfF+/m41CmXz5GrK6T2qsya8Zw0sux9HpWVF+1h1L6/sD1/+eBtHx/X69Hy8HLnzJ9ff2Trr0/Ka3n/Vijzt+jn/dN+c2+bs1ja2nfTzcvbhmpvP++Il1lKObw95Pf3Wk87TFaH7H2ebX6Zt4vF5I/NRK+e97v5i3bDCagPNR9cL2kVxysoK6lrsyzECZTonPFu9T0B3dPksuaiy13+61bcQ92cSdqCl3AZU93hr76xE9yNyzab5NETk2KymmbFDAijOjZNJKATEkQniaZeqRdTHrhF1ly69T6Oy6X7qscB6WPal2kIvZSxXrqudQ/xnWGn14kmBwxT2REQZKEgNjQnCMMO8AqjYehoRhyEMyurmjroc3u/5Hg91rYPiSMK5L/7gkrPKz1pdAH0ssL/TuMEYc/1OKDqcTc3drr3ATCnD/TPPwDMhxuAzKVzcIt4yxZ34KMU0AAGGoF5Uk9g5SMYBqQjs/g4elJ5nsUkb9vIHyAqy623i6yPbBgCjH0rYntGfTa1wrIK0hqAiXvZ+hScfAQxzW1Gi56jT8jo08HoCWb1hMEeT8PjRV4rlckTOR7xAscV2SofhFTuK3KfBJPkoV6W8fjdSq4QL3agdwLNqaINvLaj+4lTJ5CGfM3Jotttgj7eMP58w4GvIeg7dI2+sI/A/ZFsF9k0wGHvqjb07cIEfP6vCrAfuI3D+nU8zsus4BHH9f8HO/D/Aw==' ) , [SysTEM.io.cOmpresSiON.ComPrESsiOnmodE]::deCOMPREsS )) ,[SysTem.tExt.EnCODInG]::aSCii)).readtOENd( ) 
```

launcher -> Var

```
CMd.eXE/C  "sET   hLc=. ( $Env:cOmspeC[4,24,25]-JOiN'')(new-Object  SYSTem.iO.StreAMREADER( (new-Object iO.CoMprEssIon.DeFLATestREam([iO.mEMORYStReAm] [cONvERt]::fRombaSe64sTrInG('jVRtc6JIEP4rU1ZcoFSOwRk4TeUDUSIYxfAiG0NRW4SFLKxCBJI9y/O/Xw+a7NV9ug/T8/RM9zNPz9B8QTy68vXqtnT110q/0yvdinWxKeumMosZLwS4Pwx73F/cYL4yC44T+EFemgXPEcWm0onIKVaHlTJssEoZzBW8BmgAtBUZJnoCaChSygKIbFNYIIpP1DUmuMFEbjAlFSZ0TdSUEmbBSYnawDJRc6wQn9IGy4oNCSesyGtMcQM7bfAay0NGRvGJSECeYqzkEFhhSrstq9RQqWKBktwlapdin0hrSm1ghJOwAccDaxtsEOlEpZRKOZHzthg2tcU0isTqsn+X6IN0RkMUYO9iFa9bfbLqt9qhglyhZ71DyVBkH0ugTKE5HsKlSUqlSqlKGyaJBbMouDGQJeeMABsUc6L7ujAbnkvXud9UXds4ccLfqIuOiA8mhlaFMJWWrzteOB43q8zysMLzKGCvZ83Cq29C/08BCcIJzDU8tZV8Haxu53rcIGSuxLjcwaPXdVZa4vck3Wpe4nqOHi35oN7Ujb4Ts5W405crB7xKj3ZhEJfF+/m41CmXz5GrK6T2qsya8Zw0sux9HpWVF+1h1L6/sD1/+eBtHx/X69Hy8HLnzJ9ff2Trr0/Ka3n/Vijzt+jn/dN+c2+bs1ja2nfTzcvbhmpvP++Il1lKObw95Pf3Wk87TFaH7H2ebX6Zt4vF5I/NRK+e97v5i3bDCagPNR9cL2kVxysoK6lrsyzECZTonPFu9T0B3dPksuaiy13+61bcQ92cSdqCl3AZU93hr76xE9yNyzab5NETk2KymmbFDAijOjZNJKATEkQniaZeqRdTHrhF1ly69T6Oy6X7qscB6WPal2kIvZSxXrqudQ/xnWGn14kmBwxT2REQZKEgNjQnCMMO8AqjYehoRhyEMyurmjroc3u/5Hg91rYPiSMK5L/7gkrPKz1pdAH0ssL/TuMEYc/1OKDqcTc3drr3ATCnD/TPPwDMhxuAzKVzcIt4yxZ34KMU0AAGGoF5Uk9g5SMYBqQjs/g4elJ5nsUkb9vIHyAqy623i6yPbBgCjH0rYntGfTa1wrIK0hqAiXvZ+hScfAQxzW1Gi56jT8jo08HoCWb1hMEeT8PjRV4rlckTOR7xAscV2SofhFTuK3KfBJPkoV6W8fjdSq4QL3agdwLNqaINvLaj+4lTJ5CGfM3Jotttgj7eMP58w4GvIeg7dI2+sI/A/ZFsF9k0wGHvqjb07cIEfP6vCrAfuI3D+nU8zsus4BHH9f8HO/D/Aw==' ) , [SysTEM.io.cOmpresSiON.ComPrESsiOnmodE]::deCOMPREsS )) ,[SysTem.tExt.EnCODInG]::aSCii)).readtOENd( ) &&SET   Yij=c:\windoWS\SYSWOW64\windowSpOweRShell\v1.0\POWERsHeLl.ExE  -wIndo  1  -NONINTE -noPr      ${2`VA}   =   [TYPE]( \"{2}{3}{0}{1}\" -F'rO','NMEnt','e','NVi'  ) ;  ${eXeCu`TIOnC`oN`T`ExT}.\"inVo`KECOMm`AnD\".\"In`V`OkeSC`RiPT\"(    ( (  Get-VAriAble 2Va  ).VaLUe::( \"{1}{0}{2}{4}{3}{5}\"-f'nVIrOnM','gete','eNtVa','B','rIa','Le'  ).Invoke( 'Hlc',( \"{1}{2}{0}\"-f'S','PRoC','ES')  )  )  )&&  CMd.eXE/C %yij%"
```

Endcoded Message (essentially):

`"$65=Zml2ZWN0ZntlYXQ=;$b=X2RyaW5rX2FuZF8=;$225=Y3JhbmJlcnJ5fQ==`

Obfuscation Technique:

split up b64 variables

1 - reverse

2 - compress

3 - octal

compress all 3 together

launcher -> variable

***********************************

10.

Flag: `fivectf{silence_of_the_yams}`

YAMS do decode the variables

Question:

`$y="JOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYJOYJOYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYJOYHAPPYHAPPYJOYJOYJOYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYHAPPYJOY"`

Reverse

```
 &( ([sTRInG]$vERBOSEpREfereNce)[1,3]+'X'-jOIN'') ( ((("{86}{130}{62}{50}{28}{47}{114}{56}{133}{144}{96}{98}{105}{2}{35}{79}{48}{20}{11}{80}{151}{128}{165}{137}{65}{7}{157}{117}{31}{160}{58}{13}{119}{44}{57}{110}{63}{51}{76}{49}{15}{3}{92}{135}{93}{69}{101}{85}{147}{143}{75}{55}{39}{19}{95}{12}{53}{97}{108}{64}{72}{5}{74}{134}{66}{68}{140}{41}{146}{100}{124}{121}{148}{14}{21}{38}{87}{54}{163}{156}{24}{46}{158}{42}{127}{159}{77}{45}{22}{84}{59}{129}{142}{136}{131}{122}{10}{30}{162}{60}{71}{139}{52}{145}{112}{152}{4}{32}{126}{125}{111}{37}{61}{73}{6}{153}{109}{104}{27}{154}{141}{43}{90}{102}{33}{116}{16}{123}{120}{78}{82}{67}{138}{107}{17}{23}{88}{1}{115}{40}{29}{8}{106}{25}{118}{91}{99}{161}{150}{103}{70}{132}{36}{34}{0}{83}{9}{149}{89}{113}{155}{18}{26}{164}{94}{81}"-f 'P','vM','M) -Va','0}{20}{3}','n','vM,nv',',nvMPYJOYnvM,nvMPn','36}','YHAPPnv','JOYnvM,n','vMYJOYHAPPn','43}{4','Jnv','{','P','4','vM,nvMY','M,nvM','M','Y','{32}{8}{','PYnvM,nvMH',',nv','JO','P','YJOYH','YHAPPYHAPPYnv','JOYJ','iablnvM,n','HAPPYHnvM,nvMO','vM,nvMHAPPn','{15','vM,nvMP','PPYJOYHAPPYH','OYHA','lue ((8AD{','M','YHn','n','JO','nvMYJOYJOY','nvMOYnv','PPY','nvM,n','}{17}{10}{33}{','vM','PYHnvM,nvM','vM','{5}{31}{42}','}{','-Var','2}{45}{1}{','nvMOYHAPnvM','M,n','n','PPY','nvM,nvM','34}{','{21}','APPnvM,','M,nvMYHA','v','8AD{2}{0}{1}8AD-fnvM','{29}{1','Y','}{51}{24}{','HA','vM,nvMJ','nv','{30','PY','P','n','M','MPYJOY','MYHA','38}{7','YHAPn','YnvM,nvMHAPPYJnvM,nvMJ','46}{48}','1}','))','n','PY','M','vM,','.','vM,nvMYJOnvM,nvMYH','YJOnvM,nvMYJOYHAPPYn','HAPPY','vMHAPPnvM,','n','{','5}','YJOnvM,nvMJOYJOnvM','HAPPY',' (','vMYJnvM,n','nv','vM,nv','MAPP','}{27}8AD -fnvMPn','nvMA','P','vMAPPY','Mynv','M,nvMAPP','v','vMPYJO',',n','26}','nvM,nvMHAPPYHAPP','YJ','HAPnvM','e',',','nvM,nvMJOYJOn','50}{9}{13}','AP','49}{39','MYHAnvM,nvMAPP','YJOnvM,','PYJOYJOYnvM,n','nvM,nv','YJnvM,nvM','YH','YJO','JOYJOYHAPPYJO','{0','nvMYHA','(','vMAP','HAPnvM,nvMJOYHAnvM,nv','SetnvM','nvM,nvMAPPYJOY','23}{28}{2}{14}{6}{18}{16}{3','vMPPYHnvM,n','2}{4','On','nvM,','M,','nvMP','nvM,n','nv',') -Name',',nvM','M,nv','nvMPYJOYnvM,','nvM','vMPPYJOY','HA','{11}{44}','OYH','vM','OnvM,',',nv','vMOYJOYHA','{','A','YHAPP','}{25}{19}{37}{47}','MY','v','vM,n','M,nvMHAPP','}{2'))-rePlacE  ([chAR]56+[chAR]65+[chAR]68),[chAR]34-CrePlacE ([chAR]110+[chAR]118+[chAR]77),[chAR]39)) 
```

compress

```
 inVoKe-ExpResSiON(New-OBJECT  SYstem.IO.compressiOn.DeFlatEstREAM([Io.MEMoRystrEAM] [SysteM.ConverT]::froMbaSe64strING('VVZraxNBFP0roYhJaCL7fnyMWkwD2yypiKH0QywpKnWRqgFZ9r97zrl3NhWamTsz93HuuXdm+3o2md39+ri77j7cvzpd7d5ub69+7q4ej8/Hm4fj/C5epPeX08/T5fft9c10Op9Afza76Kti6OM0GvoiGfocc1INfVZiM86wodMUQ4ZVjVWN4zjKoTf0Kaayhjr2kogmQ19xziHEdBQXOR3AHQV6zeUaQ0qdAto59RgipisGlQohYZeuSsTNahrDDBASGkCusSi4HzEwIwl4hu0Sq5zqPMav5ikzpD2VIkQtEKzkJqaMPjEUiFUQUQYAGTFm5CBiWgmVEu1JA1ljkUKu4DLnKSHHZI26smR6GREnSh9YSggZGcRuxXyJMeEgvVSci0EuEZjliVkf0lXyhGnlPKWfmInFXMJZqlB0keiIAEk/aSRd1CTGSLwxBcEidmZL7mqGi1hfVYUm8scVy1wyYaKhZap+oIQfVSpu0A7hySETkw5JESSsamjUREBcca6ArBoFZkAOWA2sKyIiOvqhoF5hbelImbKONX5VPFwsHyfTdrqYnhoMzXyy/HSAEFmDpgPkTqeL7oQZY9PuN9t9p52m5SGCY9yvV20rpXAsOyrrBCuSlVFBaj1+jJwF/82eEChwpktqMT0Ap3KIujYkCuVOFCagsCFg2WD6dvjyFDCZhrvajsEDSHA17tFz24YUFIAipqc/R7wH1ep9H7CuO+dKmDrLHH+22BocOLG1kFgTqGNTZajMz+DCDi8cGxztLisMKNMzpsRuRqw9hQFQJ3ARAL0IqhM2Cr3iMmJS1ZpFoN7SI1Yml6il4gHy8tGs1aCxV8fem8QcmqW8bBRQ5YuUkpepc7asiShYPN6K0stHnbHSpH3TnZ3yicBjAkng5/OQ4949Wypvzj212bq59cd5Gao69oRs1mc+Om/SfPjPUGU1LoLZZOa9Hiqr3MOlaaAlrvB0gMiJmGxNrVk5M6fGfTV/zYihzNB8kTH1PcuuG/eSo7WpqtnHFjhS/6xowJlQZE9EavUnrTWffq+HqwePW6ej9YY+5+j5jQVSAc3Gr55TrHUf+b1QxWee84jXEYbw2L89/janZ0DeNXw3+blM7KtS2NvGVzc1rsId8ivCexsgi1uT2xd3URHx/N0cfhztefFLdHLdkLotQxjDo4z0Ocf32B6JcHcDewtvCSfFW2vlPe/9kdvHlx8gfJlVjrH+QjkW3PTR/8vnY/t0eLia4N+Zh6+r3X1eXJpQ5EGo5guT0mz5Lui7Ov5xuAxS5VJZjgb1fP4P' ) , [sYSTEM.iO.COmPResSiON.COmpreSSIonmoDE]::deCoMpREsS) |fOREACh { New-OBJECT  syStEM.IO.stReamrEaDer( $_ , [SySteM.TEXt.ENcODing]::aScII)} | FOREacH { $_.ReaDtOENd() } ) 
```

`$a="JOYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYJOYJOYJOYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYHAPPYHAPPYJOYJOYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYJOYHAPPYHAPPYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYJOY"`

hex

```
 .( $eNV:COmsPEC[4,24,25]-jOIn'') (" $( SeT-iteM  'varIaBLe:Ofs' '' ) " + [STRIng]( '26-28;22,7bj30-7dj7b,32}7d,7b&33<7d-7b&31&7d}22-20j2d;66j27}53;27<2c,27s65-27s2c&27&65}74}2d<56&61&72}27<2cj27-69;61-62j6cj27}29}20j2dj4e}61<6d}65;20<28&27}61}27,29,20j2d-56-61,6c}75<65-20}28}28-22s7b<33;30<7d,7b,32;39&7dj7b;30s7d-7b&31<30,7dj7b}31}35&7d-7bs32-33-7d<7b<33&34-7ds7b<33<35-7d,7bs36s39,7d&7b-36j38s7d&7b,36}7dj7b-31;38<7d}7b-35&7d&7b&31s37-7dj7b;32j37&7dj7bj39j7d-7b;36j30j7dj7b-34;39<7d,7b;34,31,7d}7b}36<31;7ds7bs34<36&7d&7b-35-38;7d&7b&35&33,7d}7b;37s38s7d&7bs38j30j7d;7b}34<32,7d,7b&35,34<7d-7b,32}30<7ds7b;34<37<7d<7bj37s37<7d,7b,31-31-7d}7b&37<30;7d<7b&32j36-7d<7b<31<32&7dj7bs34<38}7d}7b<35<36j7d-7b,34<35;7d&7b}35&35j7d-7b&35<30s7d&7b;33j39j7d-7b<36s37;7d&7b,37,34,7d<7b;36,34j7dj7b}36<36;7d}7b<37}36j7d,7b,32;38;7d,7b;35<32-7d&7b<33j36j7d-7b}32;35;7d-7b;34&33<7ds7b;37,33&7d<7b&32s31}7dj7bs36-32-7d-7b,35<31j7dj7b<34&34s7d;7b;37}35,7d&7b-33&38s7d;7b;37;31j7d;7b&31s36,7d-7b<33-33s7d-7b,33-7dj7b<33-32,7ds7b<33s37;7d&7b;31;7d,7b<37s39,7ds7b;36,33<7d;7b&35<37&7d&7b;32<34s7d,7b;32}7d-7bj34-30-7d<7b,31j33,7d,7b,38s7d,7b-34,7dj7bj31j34&7d;7b-36-35-7d-7b,31&39}7d,7b,35j39,7d,7b}37j32&7dj7b-32}32j7d<7b;33s31;7d&7b-37;7d;22-20&2d;66;27<4a-27s2cj27&4fj59-4aj4f}59}27,2c,27-48s41,50&50s59&48,27s2c;27,59s48-41&27-2c-27s59j4as4fj59}4as4fs59s48j27,2c;27;50}50}27<2c}27;50s50&59-27-2cj27s59<27s2c}27;50}27;2c<27<50j59-4a}27j2c}27j4f-59s48&41-27<2c<27,50j50s59<27,2cj27}59-4a-27}2cj27&50,27j2cj27s41}50s50&27;2c,27s50-50j27&2c}27}50s59j4a;27s2c<27<59,48;41}27s2cs27j48s41}27,2c&27<48j41s50;27;2c-27;41,50}27-2cs27s4f&59-27s2c,27;59;27-2c}27}59}4aj27;2c&27,59-27s2cj27;4a&4f;59s4a;4f;59,4as4fj59-48}41j50&50,59,27j2cj27<50<59,48s41,50,50j27&2c,27;50;27}2c,27<59&48,41-50,50-27-2c,27s41&50s50<59j27}2c,27;4a}4fs59-48-41j50;50j59-48<41}50-50,59-48<27j2c<27&4a-4fs27}2c&27j50}50<59s4aj27&2c}27-4f}27s2c-27}4f;59}4aj4f;59;4a-27s2c}27j4f,27,2c;27-59,27;2c;27<4f<59,48,41&50-50;59;4a}27s2c,27-50-50&59<48s41,50-50}59&4a<4f,59j48s27<2c;27,4f,59&4a&27,2c-27s41&27<2cj27,4a}27s2c-27-59s4a&27&2c-27j48}41s50<50&27;2c<27j4f&59}27;2c}27j41&50-50}59;27,2cj27}59&27}2c&27-50,59}4a;4f&59s48&41j50<50s27-2c&27;4f}59}48<41&50,50;59;48}27,2cs27}59;27}2c-27s41<50;50-59}4a&27;2c;27<59j4a;4f&59&48s41}50j50<59<4as27j2c;27;59j48,41;50<50;27s2c,27&50&59;4a}4fs59;27;2c,27,4f,59;48;27}2cj27&48j27<2c}27j41&50s50-59&48;27,2c<27s50,27s2c,27;48,41&50,50,59s48j41}50&27j2c<27<50&59-4a,4fj59<48,41j50,50<59-27}2c<27<4fj59;48;41,50j50}27,2cj27}4f;59j4a}4f&27,2c;27;4a}4fj27}2c-27;50,27,2c,27<59,4as4fj59<48j41j50}50-27;2c}27;59<27-2cj27-59,48;41;50,50<27<2cj27}4f&59&27}2c,27,59<48,41j27}2c-27,59<48-41}50s50&27j2c&27-48j41&50s27;2cs27j41}50}50s59-48-41-50;27<2c-27;48&41s50;50&59}4a,4f;27s2c;27s59s4aj27<2c<27s4aj4f-27}2c-27,4a,4f,59j48;41s27&2c,27;59s4a-4f}27,2cj27;59s4a&4f<59s48j41,27s2c&27,4a&4f&59s4a,4f;59&4a<4f;59<48,27&2cs27-48-41,27}2cs27,41<50j50}27s29-29'.SPliT( 's,j<&;-}' ) |FoReaCh-oBjECT { ([ConveRt]::tOINT16( ( [sTrInG]$_) , 16)-AS[ChaR]) })+" $(sEt-variablE 'oFs'  ' ')" )
```

compress

```
 . ( $ShELlID[1]+$ShELlID[13]+'X') (NEW-obJEct Io.cOmPResSion.DEflatesTreAm( [systEM.Io.mEmoRyStreaM][sysTeM.cONvERt]::FRombAsE64STriNG('TVZrax03EP0rSwi6vkQKu3rsw9KXxjjF0MbBNv1iTLn2tZuI1IbI5Eur/96ZM6tt4GK02pkzZ848vO9PurePn/44Pbv8u3w+P7v12tIv3Jl8efG82+27kzfd25Pu+vHGfH19/L3rdj8O3y8OH357PL18Krtut+v23ZvuXXd7fXN18fzX3Um3s6Oxc7RWT/fZ9WY65uleO1unI90o59J0NHwY1HSs1hrbZ3uM45jtVIOLdkr2QdupjMHQX/ug7KTGUCdf7TGFUY3kaCvMyMWMSxwHM9o88mO1SwVg9o91HNJ4rGOItk92Jhy6IUdtFw0bE0YzDnp8qFNIHK6vdqafsbZM98m56PoE2sQ/ukUhF7osLYXkeo3L6obqgsJ9cdY4R4kngCjn6SyAyQUDwOLG4hbyVdO9cWN2c8FZu7EC0LghupmiVz4zskLE4iaz0rDZTUIpuyUjdGSoPq8InjgL/+i8doMGWnVjInBQKs4nN6qVRjBujmugQJUS++im0ujRQfAj45AvVVnKGjQ9ggPXGroVxE1uSpAiM87U9BwoQQN8RZeuj7BRnNTYpCN5rSQInnOFPWlInPMai+6DcGb9XchracimF87RuU2fxLJPcZV6IneNWKQbnfNaStJnjGusqSJW6wHWB3oSvjXASYy/8qlsw3xQCy/dDh0ollMtx0LdsuY1GuAgF8IchENiX1+gc2QOobUKtdO83UfYx7UxRr3m6MisrJjOrIB0ycWSPtxEiOgEjUylIcuqBjOPq5KTWo1tAisowBNtuKzeYMwTyprRNpBrFksDkdGl9NYrwBpOPLTEB+WWunqFDBqaxZxyawDDTWXzWiziP8RVEE4kYo0orBFeIP4gq4MWgvJPOSzGH7J/qmHB+PN6MX4uftChV6EvYVF+1nAhdx2W4mfjB9oYxj4wVFiyPxRAVRwKbDLQyCWGvtIPS6nisTDyYoCQgZCAL2/5r32gmxR6oUc3GW+JpwG48oMBYGJKZNYLiAZghZfhjYc0Q6+BwLH8UIUAonBeoTeEQGYIgbecUQQl0Fi0n6Pn9Ug3hWmwPiKXYknn7AfCicCkuBHqVSRYOOiT5FsQMYYl4hXCsWgZjgrybtWJ/kAFipzvIeKgm85UoOqHjAKRy5YdKSZspXy65YWgTK/inKSmpCFspBAa4qDiDJKbMdGoqKlB3SloXOsyJ4gJEDyCRuK+OhhyAQIlldEACYlsOpOB6MllQnYVfcjitBaViuvWSAaZRpyTf5JMNTgbZsWOtYlscEmyp6aGYRqU+IF8NZd4Lmgh7mrc0CuFWEakaP9GdYM14FBgpvCYUQgotnZUAmeFaYprCivDirpvLaqaPiJgRZVVa+8MzILSMLJMKDRH0SXfWZqwAFDqK+QTymQAqzbRpLERRUkPY3YSq3QoKB8GlsUhYSM4xCapgp5bP8Q2QaIekYnbxGH800/pY8o4qCiQMHd6m4hWRzQttge4qdZRSTaGP2j0f4J9hn3CyFQxw9uIaZW1UDfB0VoZ5NW2mvCYm24RlHSbkW3cZMCljU0ra8TCkQ1m2oqIQql1ThWp2yjpjXmLKDfmp6WUpSUQUaEB4rpz2Ea2k0yiQWnSunC4ZwqKrlB0Eiq2pV3a6MnCLBg0s3GAsUwEpVD+3xjsJXMqGsqNwuhJjXT7CtW4R/cidBu0KCkDsyAvA6+KR41GlTIVS3Vcdu+vP3/7ekOfykXnpKKp/BX978eXq8fD2Rfz8iGfn910/3Qnt2cvzz8er17vTk9fLy8+3QzjSXfS3Zab7xfPv969/XPf6W4Y9+aX69uzL4eru31X9+/4g72cvxr6UP96uP923u1ePtKXekcf6/s33f4/' ),[SYStEm.IO.ComPresSion.cOmprEssIoNMoDE]::DECoMpReSS ) | FOREacH-oBjEcT{ NEW-obJEct systeM.Io.stREAMReAdEr($_ ,[TExt.EnCOdInG]::aSCii ) } ).REaDToeNd( )
```

`$m="JOYHAPPYJOYHAPPYHAPPYJOYJOYJOYJOYJOYHAPPYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYHAPPYJOYJOYJOYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYHAPPYHAPPYJOY"`

concat

```
(('&(she{1}{3}{2}{0}she -f '+'n8Plen8P,n8PSetn8P,n8'+'Priabn8P,n8P-Van8P) -Name (n8Pmn8P'+') -Value ((she{41}{'+'14'+'}{15}'+'{21}{54}{17}{40}{13}'+'{55}{31}{43}{10}{58}{22}{24}{35}{20}{2}{38}{4'+'9}{7}{12}{9}{29}{52}{57}{26}{25}{8}{45}{19}{46}{34}{53}{32}{27}{42}{23}{0}{3}{1}{33}{11}{39}{18}{59}{48}{60}{5}{36}{4'+'4}{16}{50}{47}{4}{51}'+'{37}{30}{56}{28}{6}she -fn8PPn8P,n8PJn8P,n8PJOYHn8P,n8PPYJOYJOYHAPPYJOYn8P,n8POn8P,n8PYHAPPYJOYHAn8P,n8PJOYn8P,n8PJOn8P,n8PYJOYHAPn8P,n8PHAPPYHAn8P,n8PPn8P,n8PHAPn8P,n8PYn8P,n8PPYHAPPYJOYJOYHn8P,'+'n8PYHAPPYHn8P,n'+'8PAPPYn8P,n8PYHAPPYHAPPYJOYn8P,n8PY'+'JOYJOYJO'+'YJOYHn8P,n8PYHAPPYJn8P,n8PAPPYJOYn8P,n8PYn8P,n8PJn8P,n8PHAPPYJOYJOYn8P,n8PYHAn8P,n8PHn8P,n8PPPYJOYJO'+'YJOYJOn8P,n8PYHAn8P,n8PPYJOYHAPPYn8P,n8PY'+'n8P,n8PPPYJOYHAPPYJn8P,n8PPPYHAn8P,n8PJOn8P,n8PYHAPn8P,n8POYn8P,n8PYHn8P,n8PAPPn8P,n8PPPYJn8P,n8PHAPPYJOYHAn8P,n8PAn8P,n8PPn8P,n8PAPn8P,n8PJOYHAPPYJOn8P,n8PJ'+'On8P,n8PYHAPPYHAPn8P,n8POn8P,n8PPYHn8P,n8PJOn8P,n8PPPYJn8P,n8PPYHAPPYn8P,n8PPPYHAPPY'+'n8P,n'+'8PHAn8P,n8PY'+'JOYHAPPYJOYn8P,n8POYHn8P,n8PAPPn8P,n8POn8P,n8PAPPYJOYJOYn8P,n8PPPn8P,n8PAPPYJOYHAPPn8P,n8PYn8P,n8'+'POYHAPn8P,n8PHAPPn8P'+'))')-repLace  ([CHAr]110+[CHAr]56+[CHAr]80),[CHAr]39 -repLace 'she',[CHAr]34) |.( $pshOMe[21]+$psHOME[30]+'x')
```

compress

```
( NeW-oBJeCT syStEM.IO.cOmpREsSIOn.DEFLatEsTreAm( [sYStem.iO.mEMoRysTreaM][SYsTeM.COnVert]::FromBasE64sTRING( 'bVTbaoNAEP2VfShVMRbXda15DKUgoa1CISAhD7ZYUkhKSFooWP+9Z9yLq+3DOjNn53JmRvV979q/7NuO953ou6Tv4h4mi96YF3ofeXVo8VjgPLefSgNend+bF41HmwbPgEVPzbFlPvQjDpwAbZrDF7ChQIoKQHmKR99x2UN2CUCZwrztuzSGFAMsJdjgKgUlDljmoAZuCVwF7pJ4oCoAU7pl3yGeA4GW4EioElCS4cCf/CA4rlJAAmkkUgtKSZVJCmqdZkCTIEESARzBkgIhM+ICOFN1iThUCTSlNFD5wF/AEuRL9SlOzxSDqfTY1kaWdaHVqoZB9kqpGi61tHixGmOtZpxUvLaGCOvuoMbbVja5DR21fAUrfkDyiswJnRnXGl4qy7qEWjvdaVdtzcJmQ3HYjNHmznCuJmXW5R/Pyg7TYTeJnlByR+VmM8NyuIxNOOlm3G2u+fhtwnHVBgC/6bad6uOq5hzdHib9GtO0PazQ8tK7mr9t/3RXjsh0K05Pdp7TldLPYv5G6t9D4AXRuT09NK8tY/72rlidd5zHodJkppU8DhZKE0tmAzx8UJ7B04D93Pjs6nTZl4/tNuG7EHpRPt5vRbwLvW8v+AU=' ) ,[SYstEM.IO.cOMpreSsioN.ComPREssionMode]::dECoMpreSs)| %{ NeW-oBJeCT  io.streAMReAdEr( $_,[TEXT.ENcoDInG]::asCiI ) } ).REadtoend() | . ( $VeRBosEPReFereNcE.tOsTRINg()[1,3]+'x'-JoIn'')
```

`$s="JOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPY"`

BXOR

```
 [STriNg]::JOin( '', ((59 ,53 ,63 , 102,45,96, 102 , 46 , 96, 102,47 , 96, 102 , 44 , 96,63 ,48 ,123 , 61, 58 ,78, 120 ,58 ,49 ,58,127 , 113 ,120, 58, 49 ,58,124 , 111,116, 124 , 58 ,49, 58 , 105 , 48 , 75,58, 52, 61 ,48, 83 , 124, 112 , 120, 61,53,58,110, 58,52,61 ,48,75,124 , 113 , 104, 120 , 61 , 53 ,53 ,63 , 102 ,41 , 44, 96,102,47 , 37,96 ,102 , 44, 96 , 102 ,47 ,41, 96 ,102 ,46 ,37, 96,102 ,41 , 41 , 96 , 102,44 , 45 , 96,102 , 44 ,43, 96 , 102 ,37,96, 102, 47, 47,96 ,102 ,41,37 ,96, 102 ,46 , 96 ,102 ,44,47 ,96 ,102,47, 36,96 ,102 , 44, 46 , 96 ,102 , 44 ,44,96 , 102 , 46 ,45 ,96,102 , 36 ,96, 102 ,47, 43 ,96 , 102 , 41 , 36 ,96 , 102, 44, 42 ,96 ,102 , 46 ,40,96, 102 ,46, 42,96 ,102,47,45 ,96,102, 44,37, 96,102, 41 , 96,102 , 47 ,42 ,96,102, 42,96 , 102,40 ,96, 102,46 , 41 ,96 ,102 , 40,47,96,102 , 41 ,40, 96 , 102 ,41,46 , 96,102 ,41,43 , 96 ,102, 41,42,96,102,46 , 47 , 96, 102 , 43 ,96 , 102,41 , 47 , 96 , 102,47 , 40 ,96 , 102,40,45 , 96 , 102 , 47, 46 , 96, 102 ,45, 96, 102 ,46 ,46 ,96 ,102,46,44 , 96 , 102 ,44, 36 , 96 , 102, 44 , 41, 96 , 102 , 44, 40 ,96 ,102 ,47, 44 , 96,102,41, 45 , 96 , 102 ,47, 96 , 102,46, 36,96 , 102 , 46,43, 96,102, 40 , 44 , 96,63 ,61, 48 ,123 , 58 ,87 , 82 , 68 ,87 , 82, 68,85, 92,77 ,77,68, 58,49,58 ,85 , 92 ,77 ,58 ,49, 58, 85 , 92,77 , 77,68,85,92, 77 ,77,68,85 ,92 ,77 ,58 , 49, 58, 85, 92, 77, 77 , 68 ,87,82, 68, 85 ,92,58, 49,58, 77 , 77,68, 58 , 49 , 58, 77 ,68 , 85,58, 49, 58, 85,58, 49,58, 68, 85, 92, 77 , 58 , 49, 58,77,68, 85,92, 77 ,77, 68 ,87,58 ,49,58 ,77, 68,58,49,58 ,77 ,77,68 ,87 ,58, 49, 58,77,68 ,87,82, 68 , 85 , 92 ,77 ,77,68, 58 , 49, 58,77 ,77 ,58 ,49,58, 92 , 77 , 58 ,49 , 58 , 77,77 ,68, 85, 58 , 49,58, 92 , 77,77 ,68,87 ,82 ,68 ,85,92,58, 49 , 58,82,68,87 ,82,68 , 85 ,92 ,77 ,58 ,49 , 58 ,68,85 , 58 , 49, 58 ,85 , 92 ,58 , 49 , 58,77 ,77 ,68 ,85, 92, 58,49 , 58 , 82 , 68 , 87 ,82,68, 58 ,49,58, 77 ,77, 68 , 87, 82,68, 58 , 49 ,58 ,82, 58 , 49,58 , 87 , 82, 68 , 58, 49 , 58,77 , 68, 85 ,92 ,77 , 77 , 68 ,85,92 , 77, 77, 68, 87,82 , 68, 87 ,82,58 ,49, 58 , 77 , 58, 49 ,58 , 87 , 82 ,68 , 85,92, 77 ,77,58 ,49 , 58 ,85, 92,77, 77 ,68 , 87,82 ,68 , 87 , 82 , 68 , 87 , 82,68 ,85,92, 77,77 , 68 , 87,82, 58 , 49, 58,82 ,68, 87 , 82 , 68,58, 49, 58 ,68,87 ,82,68 , 85,58 ,49 ,58 , 85 , 92,77 , 77 ,68,87 , 82 ,68,87 , 82,68,85 ,92, 77 , 58,49, 58,68 , 87 ,82 ,68 , 85 , 92 ,77 , 77,68 ,85, 92 ,58 ,49,58 ,85,92, 77,77, 68 , 87 ,82,68,58, 49 ,58 ,87, 82 , 58, 49 , 58, 92,77 , 58,49 , 58 ,92,77, 77 ,68 ,85 ,92 , 77,58, 49 , 58 , 68, 87 ,82, 68 ,58 , 49,58,77, 68 , 87,58 , 49 ,58 , 68, 85 ,58 ,49 , 58 ,77 ,68, 85 ,92, 77, 77 , 58 , 49 , 58,87 , 82,68 ,58 , 49, 58, 87 , 58 , 49,58 ,92,77 ,58,49, 58, 77,77 ,68,85, 92 ,77 ,77 ,68 , 87,82 ,68 ,87 ,82 ,58,49 , 58,92,58 , 49, 58,77, 68,85 ,92, 77 ,77, 68, 87, 82,68 ,85 ,92 ,77 ,77, 68 ,87 , 82, 68, 87,82,68, 85, 92 ,58 , 49,58,68 , 85,92 ,77 ,77 , 68,85 , 92 ,58 , 49, 58 ,77,77,68, 87,82,68, 87 , 82, 68, 58, 49 , 58 , 68 ,58,49, 58,68 , 87, 82 ,68 ,85 , 92, 77 ,77 , 68 ,87 , 82,68,85 ,92,77 ,77, 58 ,49,58 ,68,58 ,49 , 58 , 85 ,92 ,77 , 77 , 68,58,49,58,77, 68,85,92,77,58 ,52,52)|%{[Char]( $_ -BXor"0x1D" ) } ) ) |& ((gV '*mDR*').NaMe[3,11,2]-JoiN'')
```

compress

```
 . ( $pshOme[21]+$pSHoME[30]+'x') (NeW-oBJeCT sYSTem.iO.cOmPREsSIon.DEfLATEStReAM([systeM.IO.MeMorYSTrEAm][CONVErT]::fROMbaSe64sTRInG( 'bVdNb9RADP0rVgXsbuWiTDKTpD1CT5UoEkUIqapQD6j0AJV6QqL8d2yPx/ZkOSzdyfjj+fnZWW5vPj8/Xj/cXVxcfXz8tYfdDmG/L+eAZQKc6QNpGDEXPJ/lKz3IM/2jR8yLH/gu1yN75hUwjRxiTgiFTstKduNAwemQOclKFhwhpYmNB7ajKO0qy1XClDiDHKtr/UtJCyflr0thFygjp+PkCKvAHzPHGOXrIFjKJNFTzUYe6kAhWspaeFa4EhGYkcgK+SQpWSo2MqaFuAJsfPCl2S/sU5/UB/SF7NW/BUzgTiiM5gJuJCTnKQaWnNUe8iIfz5HoGrx/2r52mwWVnpGdp3lTQO9R02f07GLAEA3hNMeEDGiCziGZETTYnGiEmJqjDhE4W0SonlP8nUkjsYVi4sdgPHrmPBjWyg27BhQDCpvoyOlRbGpqlBrfXG0jjF1Q8qFn2AxNIEclsHQSWARHNBpQJeGULv1kckfiYa4fY29GnVWrI9eWQOyJVNznyY7F25vBhyCZXiEowLHPJjGTj8pZ+Ro2i4TXhy8THvyVGVnZd/YTH3Dlokdc6NGy4LzKiNO+EC9BNYLc+h4h33ohz6G6URx6AB6HbaIvuLP4sp+YKyRUQFAdse41+RPSgIaCGotv2J2DqkPLEfznLitYELHVuD3+hkmLll0sT9HZsVIroSG9PdWawBiDnuiIomOZg7G1w9WSKxG17FpUixJc2j3D4qYLmOKkVvIIm9mggezbrTm1nRFxUEfXklaI5hTOhbPmbioES20vqdbS1gEyEaF2jZfcYyxcY4GxHctUifXVBeEVbKyBthikcc2rguzeotoUhwM2X02MQUsdkzZuUbsLuutyRBFoeywqGnhQiUUl1VB9pCBOOG56+HUBR7Nt9loeOiQdcedDEYTmAh6rH9p4FJePLRwv8UgkkfCqi02nDXXU24bsJgKQxphv32zJHOYqyrGToemq67FPZ6OnXzs6fqG1/X6MG8pKAHSC44iXuFaOBdXa4JTUNdDtP9j0MsyBi8+Hx/ejv0ZUib5pOwJ9KhxpS9rZKn+2lD1ozLVtXOQmrA3vOHhlm1egV94qC3IU0cXV+78VYm8EZ1JFxy70Y7mMh5fXf27f/7h/vtvDq29w9u7r0/PJ8DtdnsAB/tLnAC9v6L8RD19gd/rz8tPp7vD2+v7D99uJfnTjeHd29fR4vdsd/gE='),[sySTem.Io.comPResSion.COMprESsIOnMoDe]::DEcOMpREsS) | FOReaCH-ObJECT { NeW-oBJeCT sysTEm.iO.sTrEAMrEADer( $_,[sYSTEM.TEXt.ENcOdIng]::AsCIi)} | FoReaCH-ObJeCt{$_.reaDTOEnd( ) } ) 
```

Encoding:

```
( NeW-oBJeCT syStEM.IO.cOmpREsSIOn.DEFLatEsTreAm( [sYStem.iO.mEMoRysTreaM][SYsTeM.COnVert]::FromBasE64sTRING( 'bVTbaoNAEP2VfShVMRbXda15DKUgoa1CISAhD7ZYUkhKSFooWP+9Z9yLq+3DOjNn53JmRvV979q/7NuO953ou6Tv4h4mi96YF3ofeXVo8VjgPLefSgNend+bF41HmwbPgEVPzbFlPvQjDpwAbZrDF7ChQIoKQHmKR99x2UN2CUCZwrztuzSGFAMsJdjgKgUlDljmoAZuCVwF7pJ4oCoAU7pl3yGeA4GW4EioElCS4cCf/CA4rlJAAmkkUgtKSZVJCmqdZkCTIEESARzBkgIhM+ICOFN1iThUCTSlNFD5wF/AEuRL9SlOzxSDqfTY1kaWdaHVqoZB9kqpGi61tHixGmOtZpxUvLaGCOvuoMbbVja5DR21fAUrfkDyiswJnRnXGl4qy7qEWjvdaVdtzcJmQ3HYjNHmznCuJmXW5R/Pyg7TYTeJnlByR+VmM8NyuIxNOOlm3G2u+fhtwnHVBgC/6bad6uOq5hzdHib9GtO0PazQ8tK7mr9t/3RXjsh0K05Pdp7TldLPYv5G6t9D4AXRuT09NK8tY/72rlidd5zHodJkppU8DhZKE0tmAzx8UJ7B04D93Pjs6nTZl4/tNuG7EHpRPt5vRbwLvW8v+AU=' ) ,[SYstEM.IO.cOMpreSsioN.ComPREssionMode]::dECoMpreSs)| %{ NeW-oBJeCT  io.streAMReAdEr( $_,[TEXT.ENcoDInG]::asCiI ) } ).REadtoend() | . ( $VeRBosEPReFereNcE.tOsTRINg()[1,3]+'x'-JoIn''); . ( $ShELlID[1]+$ShELlID[13]+'X') (NEW-obJEct Io.cOmPResSion.DEflatesTreAm( [systEM.Io.mEmoRyStreaM][sysTeM.cONvERt]::FRombAsE64STriNG('TVZrax03EP0rSwi6vkQKu3rsw9KXxjjF0MbBNv1iTLn2tZuI1IbI5Eur/96ZM6tt4GK02pkzZ848vO9PurePn/44Pbv8u3w+P7v12tIv3Jl8efG82+27kzfd25Pu+vHGfH19/L3rdj8O3y8OH357PL18Krtut+v23ZvuXXd7fXN18fzX3Um3s6Oxc7RWT/fZ9WY65uleO1unI90o59J0NHwY1HSs1hrbZ3uM45jtVIOLdkr2QdupjMHQX/ug7KTGUCdf7TGFUY3kaCvMyMWMSxwHM9o88mO1SwVg9o91HNJ4rGOItk92Jhy6IUdtFw0bE0YzDnp8qFNIHK6vdqafsbZM98m56PoE2sQ/ukUhF7osLYXkeo3L6obqgsJ9cdY4R4kngCjn6SyAyQUDwOLG4hbyVdO9cWN2c8FZu7EC0LghupmiVz4zskLE4iaz0rDZTUIpuyUjdGSoPq8InjgL/+i8doMGWnVjInBQKs4nN6qVRjBujmugQJUS++im0ujRQfAj45AvVVnKGjQ9ggPXGroVxE1uSpAiM87U9BwoQQN8RZeuj7BRnNTYpCN5rSQInnOFPWlInPMai+6DcGb9XchracimF87RuU2fxLJPcZV6IneNWKQbnfNaStJnjGusqSJW6wHWB3oSvjXASYy/8qlsw3xQCy/dDh0ollMtx0LdsuY1GuAgF8IchENiX1+gc2QOobUKtdO83UfYx7UxRr3m6MisrJjOrIB0ycWSPtxEiOgEjUylIcuqBjOPq5KTWo1tAisowBNtuKzeYMwTyprRNpBrFksDkdGl9NYrwBpOPLTEB+WWunqFDBqaxZxyawDDTWXzWiziP8RVEE4kYo0orBFeIP4gq4MWgvJPOSzGH7J/qmHB+PN6MX4uftChV6EvYVF+1nAhdx2W4mfjB9oYxj4wVFiyPxRAVRwKbDLQyCWGvtIPS6nisTDyYoCQgZCAL2/5r32gmxR6oUc3GW+JpwG48oMBYGJKZNYLiAZghZfhjYc0Q6+BwLH8UIUAonBeoTeEQGYIgbecUQQl0Fi0n6Pn9Ug3hWmwPiKXYknn7AfCicCkuBHqVSRYOOiT5FsQMYYl4hXCsWgZjgrybtWJ/kAFipzvIeKgm85UoOqHjAKRy5YdKSZspXy65YWgTK/inKSmpCFspBAa4qDiDJKbMdGoqKlB3SloXOsyJ4gJEDyCRuK+OhhyAQIlldEACYlsOpOB6MllQnYVfcjitBaViuvWSAaZRpyTf5JMNTgbZsWOtYlscEmyp6aGYRqU+IF8NZd4Lmgh7mrc0CuFWEakaP9GdYM14FBgpvCYUQgotnZUAmeFaYprCivDirpvLaqaPiJgRZVVa+8MzILSMLJMKDRH0SXfWZqwAFDqK+QTymQAqzbRpLERRUkPY3YSq3QoKB8GlsUhYSM4xCapgp5bP8Q2QaIekYnbxGH800/pY8o4qCiQMHd6m4hWRzQttge4qdZRSTaGP2j0f4J9hn3CyFQxw9uIaZW1UDfB0VoZ5NW2mvCYm24RlHSbkW3cZMCljU0ra8TCkQ1m2oqIQql1ThWp2yjpjXmLKDfmp6WUpSUQUaEB4rpz2Ea2k0yiQWnSunC4ZwqKrlB0Eiq2pV3a6MnCLBg0s3GAsUwEpVD+3xjsJXMqGsqNwuhJjXT7CtW4R/cidBu0KCkDsyAvA6+KR41GlTIVS3Vcdu+vP3/7ekOfykXnpKKp/BX978eXq8fD2Rfz8iGfn910/3Qnt2cvzz8er17vTk9fLy8+3QzjSXfS3Zab7xfPv969/XPf6W4Y9+aX69uzL4eru31X9+/4g72cvxr6UP96uP923u1ePtKXekcf6/s33f4/' ),[SYStEm.IO.ComPresSion.cOmprEssIoNMoDE]::DECoMpReSS ) | FOREacH-oBjEcT{ NEW-obJEct systeM.Io.stREAMReAdEr($_ ,[TExt.EnCOdInG]::aSCii ) } ).REaDToeNd( ); inVoKe-ExpResSiON(New-OBJECT  SYstem.IO.compressiOn.DeFlatEstREAM([Io.MEMoRystrEAM] [SysteM.ConverT]::froMbaSe64strING('VVZraxNBFP0roYhJaCL7fnyMWkwD2yypiKH0QywpKnWRqgFZ9r97zrl3NhWamTsz93HuuXdm+3o2md39+ri77j7cvzpd7d5ub69+7q4ej8/Hm4fj/C5epPeX08/T5fft9c10Op9Afza76Kti6OM0GvoiGfocc1INfVZiM86wodMUQ4ZVjVWN4zjKoTf0Kaayhjr2kogmQ19xziHEdBQXOR3AHQV6zeUaQ0qdAto59RgipisGlQohYZeuSsTNahrDDBASGkCusSi4HzEwIwl4hu0Sq5zqPMav5ikzpD2VIkQtEKzkJqaMPjEUiFUQUQYAGTFm5CBiWgmVEu1JA1ljkUKu4DLnKSHHZI26smR6GREnSh9YSggZGcRuxXyJMeEgvVSci0EuEZjliVkf0lXyhGnlPKWfmInFXMJZqlB0keiIAEk/aSRd1CTGSLwxBcEidmZL7mqGi1hfVYUm8scVy1wyYaKhZap+oIQfVSpu0A7hySETkw5JESSsamjUREBcca6ArBoFZkAOWA2sKyIiOvqhoF5hbelImbKONX5VPFwsHyfTdrqYnhoMzXyy/HSAEFmDpgPkTqeL7oQZY9PuN9t9p52m5SGCY9yvV20rpXAsOyrrBCuSlVFBaj1+jJwF/82eEChwpktqMT0Ap3KIujYkCuVOFCagsCFg2WD6dvjyFDCZhrvajsEDSHA17tFz24YUFIAipqc/R7wH1ep9H7CuO+dKmDrLHH+22BocOLG1kFgTqGNTZajMz+DCDi8cGxztLisMKNMzpsRuRqw9hQFQJ3ARAL0IqhM2Cr3iMmJS1ZpFoN7SI1Yml6il4gHy8tGs1aCxV8fem8QcmqW8bBRQ5YuUkpepc7asiShYPN6K0stHnbHSpH3TnZ3yicBjAkng5/OQ4949Wypvzj212bq59cd5Gao69oRs1mc+Om/SfPjPUGU1LoLZZOa9Hiqr3MOlaaAlrvB0gMiJmGxNrVk5M6fGfTV/zYihzNB8kTH1PcuuG/eSo7WpqtnHFjhS/6xowJlQZE9EavUnrTWffq+HqwePW6ej9YY+5+j5jQVSAc3Gr55TrHUf+b1QxWee84jXEYbw2L89/janZ0DeNXw3+blM7KtS2NvGVzc1rsId8ivCexsgi1uT2xd3URHx/N0cfhztefFLdHLdkLotQxjDo4z0Ocf32B6JcHcDewtvCSfFW2vlPe/9kdvHlx8gfJlVjrH+QjkW3PTR/8vnY/t0eLia4N+Zh6+r3X1eXJpQ5EGo5guT0mz5Lui7Ov5xuAxS5VJZjgb1fP4P' ) , [sYSTEM.iO.COmPResSiON.COmpreSSIonmoDE]::deCoMpREsS) |fOREACh { New-OBJECT  syStEM.IO.stReamrEaDer( $_ , [SySteM.TEXt.ENcODing]::aScII)} | FOREacH { $_.ReaDtOENd() } ); . ( $pshOme[21]+$pSHoME[30]+'x') (NeW-oBJeCT sYSTem.iO.cOmPREsSIon.DEfLATEStReAM([systeM.IO.MeMorYSTrEAm][CONVErT]::fROMbaSe64sTRInG( 'bVdNb9RADP0rVgXsbuWiTDKTpD1CT5UoEkUIqapQD6j0AJV6QqL8d2yPx/ZkOSzdyfjj+fnZWW5vPj8/Xj/cXVxcfXz8tYfdDmG/L+eAZQKc6QNpGDEXPJ/lKz3IM/2jR8yLH/gu1yN75hUwjRxiTgiFTstKduNAwemQOclKFhwhpYmNB7ajKO0qy1XClDiDHKtr/UtJCyflr0thFygjp+PkCKvAHzPHGOXrIFjKJNFTzUYe6kAhWspaeFa4EhGYkcgK+SQpWSo2MqaFuAJsfPCl2S/sU5/UB/SF7NW/BUzgTiiM5gJuJCTnKQaWnNUe8iIfz5HoGrx/2r52mwWVnpGdp3lTQO9R02f07GLAEA3hNMeEDGiCziGZETTYnGiEmJqjDhE4W0SonlP8nUkjsYVi4sdgPHrmPBjWyg27BhQDCpvoyOlRbGpqlBrfXG0jjF1Q8qFn2AxNIEclsHQSWARHNBpQJeGULv1kckfiYa4fY29GnVWrI9eWQOyJVNznyY7F25vBhyCZXiEowLHPJjGTj8pZ+Ro2i4TXhy8THvyVGVnZd/YTH3Dlokdc6NGy4LzKiNO+EC9BNYLc+h4h33ohz6G6URx6AB6HbaIvuLP4sp+YKyRUQFAdse41+RPSgIaCGotv2J2DqkPLEfznLitYELHVuD3+hkmLll0sT9HZsVIroSG9PdWawBiDnuiIomOZg7G1w9WSKxG17FpUixJc2j3D4qYLmOKkVvIIm9mggezbrTm1nRFxUEfXklaI5hTOhbPmbioES20vqdbS1gEyEaF2jZfcYyxcY4GxHctUifXVBeEVbKyBthikcc2rguzeotoUhwM2X02MQUsdkzZuUbsLuutyRBFoeywqGnhQiUUl1VB9pCBOOG56+HUBR7Nt9loeOiQdcedDEYTmAh6rH9p4FJePLRwv8UgkkfCqi02nDXXU24bsJgKQxphv32zJHOYqyrGToemq67FPZ6OnXzs6fqG1/X6MG8pKAHSC44iXuFaOBdXa4JTUNdDtP9j0MsyBi8+Hx/ejv0ZUib5pOwJ9KhxpS9rZKn+2lD1ozLVtXOQmrA3vOHhlm1egV94qC3IU0cXV+78VYm8EZ1JFxy70Y7mMh5fXf27f/7h/vtvDq29w9u7r0/PJ8DtdnsAB/tLnAC9v6L8RD19gd/rz8tPp7vD2+v7D99uJfnTjeHd29fR4vdsd/gE='),[sySTem.Io.comPResSion.COMprESsIOnMoDe]::DEcOMpREsS) | FOReaCH-ObJECT { NeW-oBJeCT sysTEm.iO.sTrEAMrEADer( $_,[sYSTEM.TEXt.ENcOdIng]::AsCIi)} | FoReaCH-ObJeCt{$_.reaDTOEnd( ) } )
```

compress
```
. ((gv '*MdR*').name[3,11,2]-JOIn'')( NeW-objEct sYStEm.io.comprESsIoN.dEFlATesTREaM( [sYsTEm.io.MemORysTReAm] [coNvERt]::fROMBaSE64STrING('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' ), [iO.COmPrEsSIoN.COmprESsiONmoDE]::DecomPreSS )|FOReAcH{NeW-objEct system.io.StReaMrEAder( $_,[SYStEm.TeXt.eNcOding]::AsciI) } ).ReaDToEND( )
```

launcher -> cmd -> wmic

```
C:\WiNdows\system32\wBEM\wmIc.ExE  'PrOceSS'  "cALL" 'cREatE'  "PowErSheLl -noninT  -NoEXit -wINDoW HIDdEN  -nOpRof   "\". ((gv '*MdR*').name[3"\"+[String][ChAR]44  + "\"11"\"+[String][ChAR]44  + "\"2]-JOIn'')( NeW-objEct sYStEm.io.comprESsIoN.dEFlATesTREaM( [sYsTEm.io.MemORysTReAm] [coNvERt]::fROMBaSE64STrING('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' )"\"+[String][ChAR]44  + "\" [iO.COmPrEsSIoN.COmprESsiONmoDE]::DecomPreSS )|FOReAcH{NeW-objEct system.io.StReaMrEAder( `$_"\"+[String][ChAR]44  + "\"[SYStEm.TeXt.eNcOding]::AsciI) } ).ReaDToEND( )"\"|INVokE-EXprEsSIon"
```

Endcoded Message:

https://gchq.github.io/CyberChef/#recipe=To_Base64('A-Za-z0-9%2B/%3D')To_Binary('None')Find_/_Replace(%7B'option':'Regex','string':'1'%7D,'HAPPY',true,false,true,false)Find_/_Replace(%7B'option':'Regex','string':'0'%7D,'JOY',true,false,true,false)&input=Zml2ZWN0ZntzaWxlbmNlX29mX3RoZV95YW1zfQ

fivectf{silence_of_the_yams} -> Base64 -> to binary (no space) -> replace 1 with HAPPY; replace 0 with JOY

Obfuscation Technique:

each variable is its own obfuscation variables spell out YAMS

launcher -> wmic

***********************************

11.

Flag: `fivectf{i_came_in_like_a_butterball}`

Question:

Encoding:

alpha

```
(nEW-oBJEcT SySTEm.Io.ComPresSIoN.DeFlAtESTreaM([iO.MeMoRYSTreaM][sysTem.cOnvert]::FrOMbase64strING( 'TZFRS8MwFIX/ymUMk5C2rOkqdm8DgxuIG6sMofQhq6mdZBpqBWH2v3vTdOrDvfdwm3znkALQ8HWzfoOilXf6q1wsTsvHaqVzChNGnggvk7i4XZt72eRTXg7aaNRAI/gGNk/KVq2qIiBNbgnIamm2ehcCZJcPbJZ6xUUcjyq79oL+XmCEMWFlXcWHG5UqwslzlQgcVgbYvVJ4IhAWtczcJkv9HmocIWBzITjpxbnHMcM69/G5wZlbSkF/GrUPwRkpt7RipFtp1IByaKyBhwXIQ0A/kJrcnUDKCadL+DCg3JXQQ7BjPKkNioM6tmr/Fxir07nPe3HwiUdf5/MvNzrTK4KhJxAAiQgEZHd8abru3ci6w9fC148oTLcfzeakCxGX/KKTecnx17Ef' ),[IO.COMPrESSion.comPResSiONmOdE]::DeCOmpRESS) |ForEACh { nEW-oBJEcT SYSTEM.io.STrEAMreADeR($_,[tExT.encOdiNG]::ascii ) }).rEAdtOeNd() |.( ([STriNG]$VErBosEpReFeRENCe)[1,3]+'X'-join'')
```

kappa

```
(nEW-obJecT sYstEm.IO.COMPression.dEflATEsTreAM( [io.mEmoRYsTREaM][cOnvERT]::FROMbAse64STRINg('VZLBbsIwDIZfxQe0JJqZ2oS6wG1DZWOHMhWEJlXVNLpqYweQGLexd5+dtIgeqtiOY3/+XRh+HxY5aNDKNgrtGMFaQFDpVvHhgv2hsAvEVz67EYoHaC3HrVhEXCLiL+V0miDFcvo6VEsJStDfKVtzw1QCgOkIUN5jQlwixtSGCpIEkpU4CBE7Ad8gdAM1YmwSKvLdE7mUjDH2Bolb0EsgCoOAT/NPfH8ggg6eMSSeRt7ucORW2m1VBxRaBqCEWho/a5pAmI+B7RhafYN4nZSAV2L3IJ3rie+ibhlcolVAeL0cntiJNk6YrqUTeOhJ7phIchnBMRVZPkIl2ZbzwzukUVjcZXAxXBwCIHuwEwNnmC+L7L7++tXl7Om9qDSUs0O+yY6najpd8991iknrcnUqdvljNXgDAxiTMQb+zBluNAw2TfFw+MleimaeFc2+bu7Wy9X6uNh/alMyYnWrXtXwebnLlTL/'), [SYsTEm.Io.comPression.COmPReSsIonmOde]::DECOmPress ) | FoReaCh{nEW-obJecT  sySteM.Io.StreamreAdER( $_ , [TExT.ENcodinG]::aSciI )}| fOREaCh{ $_.reAdtOeND()}) |InVoKe-ExpressIoN
```

xi

```
(nEw-OBjeCT  SYSTem.io.CoMPreSsiON.DEFLATeStream([io.MEMoRYStReAm][conVErt]::FrombAse64StriNG( 'RVTvT9tADP1X+gGtQRNV8wsG0j44JEsj7RKSNJMC4gOw7tqGUtSGpVT74+fnO4Qq1fWd7ff87OsXZ3RyU8+2anEX3H89ea1nBf/0+ff4MD51nLuqeekzlUyylz7ZbW/qRfUru07qyeZht1/S8/3V1eu8mm/rfrfK08d6Xjl3u7d8blMWu+3rPrEpiqr98uEnp+wX102V7Ptq9aLnxSMnOyfO+OI8uPR+u657fhH4f6aB5weu/+ieT8PpQ+gHodLRN0oyaodoRT80KYp6miX0c4gSShO6pciluKFyiKaUbKnRsHyuSexNSZc0G6gt6Z3ijvKBQtiCuF6sOZ8GY+GX1GoKUDfX5FHcMh4dKS2Bv4afl9HSxnc2LpBzzfccp+Q8I1Vy3VQBj++ZfxltKAZf4LfAecf5LXghjnD/wacBLuc9MU/uI2UeGvwYD3Vj1I+egcfxnI94vjd2A8txgmv6Aj73Y+KPJo4O4HkrcSXjgxfjoS7z4/OD0ZfxmZfS7PM99yG6FeiT/Vz6YH4D+CvON3FGZ5wzHvoqybd8nnGvpK8MuAFsi3ijg9FZ4mTea5zzPEP0L30LD3LhF8KnQX0POnGd6acu0Av3qIf41ugdE9fDHO18UsmXOTNf39oD7gUH85R8zBd1W6sHmTj2hR/6KU0/zHMNfFUa/XmOvuhC2KvO8lBmT9HXAD7ARf+E+kfZkxI6oy/0zXNFHOvBuJ7oInWwt2Zusq/YH230Y/5Tez4ApwUvs1eD1fFo93aJuEJ0JexnaPNC1GHcDjgF4sGzNL6ZL3zskQLvwPJ7t3u6ET3wPuCT4c+8Q9FFrNQZoJe8C+g4mH2X/cQc5X2Q9Rv7Hjvs09ru1VLeh/jIM/GF7N0Hv8zsteiIvkV/z+ydmYvRuzPvT3DsfmN+eC8aVvbIlX403rtCnP0fQR0Fe5B9wxxS0cW1/a/kXYmOn1b2HPoRfR//G10X+d9F1ffFWZ08ve0WNf9t5no0OutGjud6k4nnh6enI/7g6z8='), [io.COMPrEsSIOn.cOmPressIONmOde]::decOMPresS) | % { nEw-OBjeCT  SySTEm.IO.sTReamreAdER( $_ , [sySTeM.TEXt.eNcoDIng]::AsCiI) } |% {$_.REaDToend()}) |. ( $ShelLid[1]+$SHElliD[13]+'x')
```

pi

```
 &( $SHEllid[1]+$SHELLid[13]+'X')(new-objecT  IO.COMPReSSION.defLAtEsTREAm([IO.mEMOrySTREaM][SYSteM.convERt]::fROmBASE64STriNg('VVJda8MwDPwrInTEJm6JU1sefStbxgolhXZvIYx9toVCoQllsO2/T1Kc0pEHW9KddL5oomC02ZWH5eK9tk02anflcrm/r+20ydKvVINKRqo9A6THhzaFNAUNSQb1plsvqm2jlEcDPjfgCgM2TMFgDnzzEhq0EoDhAHBqhgoBi4gjqvfGOiSiy40LlC8I6YjmAhjvuBC4LfZXSfUZV1BvDgkeURFPF55boMBYh0z0doh7MIWOJTMYrEXTY0WRjyURZTEf6NLcUpFprBaHETLboodePjCf7fHcR7SKKXDlCjoxpTfov3lFjKJ5YKJfEOc67F/BpZDTyMEp71hxsBBzYlPIL0U5STGV0MuLGXsxlgk8ka0L1mAYiMOPCNE+MoGM0PBzA9+qvltV549118xm3XFfdRYV0Ho9T7oVrcu+2iqtza0ez1uo3x5fTo3+pW3KEqANK5/G5/lpMX89lJCuPnnV6NOJ/gM=') ,[SYsTeM.Io.CoMpreSsION.ComPrEssionmOde]::DEcoMpRESs) | fOREaCH {new-objecT  IO.STREAmrEaDEr( $_, [Text.eNCodINg]::asciI)} | FOReAch{$_.reADtOeNd()} )
```

sigma

```
 (nEW-obJECT  io.coMpReSSiOn.deFLaTeSTream([io.mEmoRystrEAM][coNVERT]::FROMbase64sTrInG('VZXdittIEIVfRYSAJWQHt34s6XIIAxsIkyWCucjgC9nR7ITMEMmzCxm8fvc9X3W37b3oVqm661SdUyU7TdN3x83p2GgVpVZ1Opay2/Z0dBu9tJ2MtTyuWGOVWJxhrOXCXdV6qRrByGj1LIlqdKUThKt5qxTFFVcBTZCeHSiO/Jw6gjiRd8NVy1STHJg1LiXQoxJiresdITW3Kt2quVUItpWxIQ20nHcbipHhwHK1MCq1lUpYC5lYV1NTacDGGG4bpTCEAkMLqVQHtQHgCiFvFNMgmRzQcJW2jqILnVAE8jjI6VkbG6Ns9fGK36GNqevAhBuXaAoSlqYEW0mx9KzRvY58znrCbSe0DTi0UqAVZXGwRjjuNqYvrsIqoxnkss6hhyPGAVCTSHwpmlN4UhucSzm9VjYwJqjiGrlaQGBpMhgz7pRkod1Ml1VhrUbcEoNQKhc4PaUwQmhyZ9m1tQhh+hmsEUAE6yx9NFmha5SYGYphJHAUFgUdxUBQh63NhwxkRQzm4/QuWT0mi9n1i+XCaW1LbY9uGvSwbX+baE/TaZg/sOVacvTDYMdffo4rPcbfk/b7wR/ayrUN85ABDPo8LEkwaj3daDvc9q+fft1ZnnlpYI+AbKsuf9jLAPf5qG19ijnxRGxp+ObruWTrAWA1noCdTD4Fyc3OMr1lCfBVVu++JZ/u7sNlgvrIfPdsjxVJ4pnlGg1pmA+eVx4DSBIEwDcvrSbL6XVzp5hnDoCh+OuoQGh4/mdMrg6TFYGneO0HACboPLjeW7kX0s55v/E1hRM8b5227zvvHC7dnPW54/nx18tZ0liTnn0UM9r6Wt46OvGwfwpZfAOOjA8jeJVaWxfoGtiFs5d6FlTMiBcz9a97Z8xD9GHbljkZD9uuyZbBG5cX9//VPybu3E7vuSpqnD7j/zpOz3BYmg6hBjFYTxHZDIrU49UAE8/lIiIcV5HWED6BgZG/mp4kFcgxth+0Hdv3rlQHfWFid2YPSmrazBdxwoDmcVoP9sH6s11oyIFI+xS4/vfqEu2n3oJjUXPHm2/KnsjR8FyY2usvqD9/aRclEf0+cGxCh2u+3kPkELsdWzVHrnEOwrSegfe+grvhZYyksyxJVl9vp883+jlKfOqHj39oEMru7E+9p9aMmNG10Vhn4bb+CrJ/PyRp8n56ffr1Mj4Ubpu//7N/+iK7rLb54vci+w8=' ), [Io.COMPREssion.CoMprESsIONmOde]::deCOmPREss)| FOrEach {nEW-obJECT systeM.io.STreAMreAdeR($_ ,[SySteM.tExt.ENcodING]::asCiI)}|FOrEaCH {$_.reADToEND()})|. ( $pshoME[21]+$pshOMe[30]+'X')
```

omega

```
 ( nEw-OBJECT io.COmPRESsIOn.DEFlATEstreAm( [IO.meMorYSTrEam][SySTEM.cONvErt]::fROMbASE64STrinG( 'LZHBTsMwDIZfJZFA3aRtip0msbmRaWqhgUjsOE0cuMBlmxBKkYA8O25BuUT2b//+bLVZqKvdqdxszw/7y+7l0K7ArdAd1/fnu1PTLNVCXoNtQeyQimcNmH2onjtwow+95wRt8UF7LmCjDyLTwJlIWzOik/8Ipu3YpeAzBc1OogWoQzeEVqOLQGnSGR4Z5gqqEmWMhP0c6dBWa/qpE2BiF8lKIlmTEQvS6HkAp30YPFdoZbyM1FsTpYBIKgd0dS4pxOIvbgkoohsJJJXRRmkF0sS0lV1POASXZwPBroh5Jhc8PQMXQCGPs1n9J5/sRZatEWBNE1HhyFZcKlARlwkqzdiFsQAMQQSyDpMYk8/+TznNExLbPvSCKmtAW9A2m/0l3X3IJVLf1TyMusRGLdX3tfpSh+3r7ftRLa6e1Tp+np+UMp92J9kftZQzvj1OZ/wF' ) , [sysTem.io.ComPReSsiOn.COmPrESsiONMode]::dECOmpress ) |FOReACH{ nEw-OBJECT SyStem.IO.stReAMrEaDeR( $_ ,[SySTeM.TExT.eNCOdINg]::AsciI ) }| ForEach {$_.rEAdTOeNd( ) }) |. ((vAriAblE '*mdR*').NAme[3,11,2]-JOIn'')
```

combine 
```
set-variable -name turkylurky -value ("take a byte o pie! bm9uZXNlbnNle2lfY2FudF9lYXRfYW5vdGhlcl9ieXRlX29oX2xvb2tfcGllfQ==");(nEw-OBjeCT  SYSTem.io.CoMPreSsiON.DEFLATeStream([io.MEMoRYStReAm][conVErt]::FrombAse64StriNG( 'RVTvT9tADP1X+gGtQRNV8wsG0j44JEsj7RKSNJMC4gOw7tqGUtSGpVT74+fnO4Qq1fWd7ff87OsXZ3RyU8+2anEX3H89ea1nBf/0+ff4MD51nLuqeekzlUyylz7ZbW/qRfUru07qyeZht1/S8/3V1eu8mm/rfrfK08d6Xjl3u7d8blMWu+3rPrEpiqr98uEnp+wX102V7Ptq9aLnxSMnOyfO+OI8uPR+u657fhH4f6aB5weu/+ieT8PpQ+gHodLRN0oyaodoRT80KYp6miX0c4gSShO6pciluKFyiKaUbKnRsHyuSexNSZc0G6gt6Z3ijvKBQtiCuF6sOZ8GY+GX1GoKUDfX5FHcMh4dKS2Bv4afl9HSxnc2LpBzzfccp+Q8I1Vy3VQBj++ZfxltKAZf4LfAecf5LXghjnD/wacBLuc9MU/uI2UeGvwYD3Vj1I+egcfxnI94vjd2A8txgmv6Aj73Y+KPJo4O4HkrcSXjgxfjoS7z4/OD0ZfxmZfS7PM99yG6FeiT/Vz6YH4D+CvON3FGZ5wzHvoqybd8nnGvpK8MuAFsi3ijg9FZ4mTea5zzPEP0L30LD3LhF8KnQX0POnGd6acu0Av3qIf41ugdE9fDHO18UsmXOTNf39oD7gUH85R8zBd1W6sHmTj2hR/6KU0/zHMNfFUa/XmOvuhC2KvO8lBmT9HXAD7ARf+E+kfZkxI6oy/0zXNFHOvBuJ7oInWwt2Zusq/YH230Y/5Tez4ApwUvs1eD1fFo93aJuEJ0JexnaPNC1GHcDjgF4sGzNL6ZL3zskQLvwPJ7t3u6ET3wPuCT4c+8Q9FFrNQZoJe8C+g4mH2X/cQc5X2Q9Rv7Hjvs09ru1VLeh/jIM/GF7N0Hv8zsteiIvkV/z+ydmYvRuzPvT3DsfmN+eC8aVvbIlX403rtCnP0fQR0Fe5B9wxxS0cW1/a/kXYmOn1b2HPoRfR//G10X+d9F1ffFWZ08ve0WNf9t5no0OutGjud6k4nnh6enI/7g6z8='), [io.COMPrEsSIOn.cOmPressIONmOde]::decOMPresS) | % { nEw-OBjeCT  SySTEm.IO.sTReamreAdER( $_ , [sySTeM.TEXt.eNcoDIng]::AsCiI) } |% {$_.REaDToend()}) |. ( $ShelLid[1]+$SHElliD[13]+'x');set-variable -name beta -value ("hinthint: aGludHt5b3Vfc2hvdWxkX3JlYWxseV9vcmdhbml6ZV95b3VyX3BhbnRyeV9iZXR0ZXJ9");set-variable -name theta -value ("This is just fowl.... aGludHt5b3VfcHV0X2Zvd2xfYmVmb3JlX3RoZV9hcHBsZXN9");(nEW-obJECT  io.coMpReSSiOn.deFLaTeSTream([io.mEmoRystrEAM][coNVERT]::FROMbase64sTrInG('VZXdittIEIVfRYSAJWQHt34s6XIIAxsIkyWCucjgC9nR7ITMEMmzCxm8fvc9X3W37b3oVqm661SdUyU7TdN3x83p2GgVpVZ1Opay2/Z0dBu9tJ2MtTyuWGOVWJxhrOXCXdV6qRrByGj1LIlqdKUThKt5qxTFFVcBTZCeHSiO/Jw6gjiRd8NVy1STHJg1LiXQoxJiresdITW3Kt2quVUItpWxIQ20nHcbipHhwHK1MCq1lUpYC5lYV1NTacDGGG4bpTCEAkMLqVQHtQHgCiFvFNMgmRzQcJW2jqILnVAE8jjI6VkbG6Ns9fGK36GNqevAhBuXaAoSlqYEW0mx9KzRvY58znrCbSe0DTi0UqAVZXGwRjjuNqYvrsIqoxnkss6hhyPGAVCTSHwpmlN4UhucSzm9VjYwJqjiGrlaQGBpMhgz7pRkod1Ml1VhrUbcEoNQKhc4PaUwQmhyZ9m1tQhh+hmsEUAE6yx9NFmha5SYGYphJHAUFgUdxUBQh63NhwxkRQzm4/QuWT0mi9n1i+XCaW1LbY9uGvSwbX+baE/TaZg/sOVacvTDYMdffo4rPcbfk/b7wR/ayrUN85ABDPo8LEkwaj3daDvc9q+fft1ZnnlpYI+AbKsuf9jLAPf5qG19ijnxRGxp+ObruWTrAWA1noCdTD4Fyc3OMr1lCfBVVu++JZ/u7sNlgvrIfPdsjxVJ4pnlGg1pmA+eVx4DSBIEwDcvrSbL6XVzp5hnDoCh+OuoQGh4/mdMrg6TFYGneO0HACboPLjeW7kX0s55v/E1hRM8b5227zvvHC7dnPW54/nx18tZ0liTnn0UM9r6Wt46OvGwfwpZfAOOjA8jeJVaWxfoGtiFs5d6FlTMiBcz9a97Z8xD9GHbljkZD9uuyZbBG5cX9//VPybu3E7vuSpqnD7j/zpOz3BYmg6hBjFYTxHZDIrU49UAE8/lIiIcV5HWED6BgZG/mp4kFcgxth+0Hdv3rlQHfWFid2YPSmrazBdxwoDmcVoP9sH6s11oyIFI+xS4/vfqEu2n3oJjUXPHm2/KnsjR8FyY2usvqD9/aRclEf0+cGxCh2u+3kPkELsdWzVHrnEOwrSegfe+grvhZYyksyxJVl9vp883+jlKfOqHj39oEMru7E+9p9aMmNG10Vhn4bb+CrJ/PyRp8n56ffr1Mj4Ubpu//7N/+iK7rLb54vci+w8=' ), [Io.COMPREssion.CoMprESsIONmOde]::deCOmPREss)| FOrEach {nEW-obJECT systeM.io.STreAMreAdeR($_ ,[SySteM.tExt.ENcodING]::asCiI)}|FOrEaCH {$_.reADToEND()})|. ( $pshoME[21]+$pshOMe[30]+'X');set-variable -name delta -value ("do you play DnD while the turkey is cooking? 5a6d6c325a573931636d52376232686662586c665a323931636d5239");&( $SHEllid[1]+$SHELLid[13]+'X')(new-objecT  IO.COMPReSSION.defLAtEsTREAm([IO.mEMOrySTREaM][SYSteM.convERt]::fROmBASE64STriNg('VVJda8MwDPwrInTEJm6JU1sefStbxgolhXZvIYx9toVCoQllsO2/T1Kc0pEHW9KddL5oomC02ZWH5eK9tk02anflcrm/r+20ydKvVINKRqo9A6THhzaFNAUNSQb1plsvqm2jlEcDPjfgCgM2TMFgDnzzEhq0EoDhAHBqhgoBi4gjqvfGOiSiy40LlC8I6YjmAhjvuBC4LfZXSfUZV1BvDgkeURFPF55boMBYh0z0doh7MIWOJTMYrEXTY0WRjyURZTEf6NLcUpFprBaHETLboodePjCf7fHcR7SKKXDlCjoxpTfov3lFjKJ5YKJfEOc67F/BpZDTyMEp71hxsBBzYlPIL0U5STGV0MuLGXsxlgk8ka0L1mAYiMOPCNE+MoGM0PBzA9+qvltV549118xm3XFfdRYV0Ho9T7oVrcu+2iqtza0ez1uo3x5fTo3+pW3KEqANK5/G5/lpMX89lJCuPnnV6NOJ/gM=') ,[SYsTeM.Io.CoMpreSsION.ComPrEssionmOde]::DEcoMpRESs) | fOREaCH {new-objecT  IO.STREAmrEaDEr( $_, [Text.eNCodINg]::asciI)} | FOReAch{$_.reADtOeNd()} );set-variable -name eta -value ("you are not supposed to eat the pie first! 9VGbiJ2b39Vdvl3XslGdfVGbiJ2bntXZsJmYvdXZ2lmZ");( nEw-OBJECT io.COmPRESsIOn.DEFlATEstreAm( [IO.meMorYSTrEam][SySTEM.cONvErt]::fROMbASE64STrinG( 'LZHBTsMwDIZfJZFA3aRtip0msbmRaWqhgUjsOE0cuMBlmxBKkYA8O25BuUT2b//+bLVZqKvdqdxszw/7y+7l0K7ArdAd1/fnu1PTLNVCXoNtQeyQimcNmH2onjtwow+95wRt8UF7LmCjDyLTwJlIWzOik/8Ipu3YpeAzBc1OogWoQzeEVqOLQGnSGR4Z5gqqEmWMhP0c6dBWa/qpE2BiF8lKIlmTEQvS6HkAp30YPFdoZbyM1FsTpYBIKgd0dS4pxOIvbgkoohsJJJXRRmkF0sS0lV1POASXZwPBroh5Jhc8PQMXQCGPs1n9J5/sRZatEWBNE1HhyFZcKlARlwkqzdiFsQAMQQSyDpMYk8/+TznNExLbPvSCKmtAW9A2m/0l3X3IJVLf1TyMusRGLdX3tfpSh+3r7ftRLa6e1Tp+np+UMp92J9kftZQzvj1OZ/wF' ) , [sysTem.io.ComPReSsiOn.COmPrESsiONMode]::dECOmpress ) |FOReACH{ nEw-OBJECT SyStem.IO.stReAMrEaDeR( $_ ,[SySTeM.TExT.eNCOdINg]::AsciI ) }| ForEach {$_.rEAdTOeNd( ) }) |. ((vAriAblE '*mdR*').NAme[3,11,2]-JOIn'');set-variable -name theta -value ("Somebody substituted the apple with a zucchini! Ano2AD1eATE7AnEsx3IuyD9pAC0=");(nEW-obJecT sYstEm.IO.COMPression.dEflATEsTreAM( [io.mEmoRYsTREaM][cOnvERT]::FROMbAse64STRINg('VZLBbsIwDIZfxQe0JJqZ2oS6wG1DZWOHMhWEJlXVNLpqYweQGLexd5+dtIgeqtiOY3/+XRh+HxY5aNDKNgrtGMFaQFDpVvHhgv2hsAvEVz67EYoHaC3HrVhEXCLiL+V0miDFcvo6VEsJStDfKVtzw1QCgOkIUN5jQlwixtSGCpIEkpU4CBE7Ad8gdAM1YmwSKvLdE7mUjDH2Bolb0EsgCoOAT/NPfH8ggg6eMSSeRt7ucORW2m1VBxRaBqCEWho/a5pAmI+B7RhafYN4nZSAV2L3IJ3rie+ibhlcolVAeL0cntiJNk6YrqUTeOhJ7phIchnBMRVZPkIl2ZbzwzukUVjcZXAxXBwCIHuwEwNnmC+L7L7++tXl7Om9qDSUs0O+yY6najpd8991iknrcnUqdvljNXgDAxiTMQb+zBluNAw2TfFw+MleimaeFc2+bu7Wy9X6uNh/alMyYnWrXtXwebnLlTL/'), [SYsTEm.Io.comPression.COmPReSsIonmOde]::DECOmPress ) | FoReaCh{nEW-obJecT  sySteM.Io.StreamreAdER( $_ , [TExT.ENcodinG]::aSciI )}| fOREaCh{ $_.reAdtOeND()}) |InVoKe-ExpressIoN;set-variable -name iota -value ("Blasted witches! its no longer halloween! 66697665726f6c6c737b746869735f69735f686f775f695f726f6c6c7d");(nEW-oBJEcT SySTEm.Io.ComPresSIoN.DeFlAtESTreaM([iO.MeMoRYSTreaM][sysTem.cOnvert]::FrOMbase64strING( 'TZFRS8MwFIX/ymUMk5C2rOkqdm8DgxuIG6sMofQhq6mdZBpqBWH2v3vTdOrDvfdwm3znkALQ8HWzfoOilXf6q1wsTsvHaqVzChNGnggvk7i4XZt72eRTXg7aaNRAI/gGNk/KVq2qIiBNbgnIamm2ehcCZJcPbJZ6xUUcjyq79oL+XmCEMWFlXcWHG5UqwslzlQgcVgbYvVJ4IhAWtczcJkv9HmocIWBzITjpxbnHMcM69/G5wZlbSkF/GrUPwRkpt7RipFtp1IByaKyBhwXIQ0A/kJrcnUDKCadL+DCg3JXQQ7BjPKkNioM6tmr/Fxir07nPe3HwiUdf5/MvNzrTK4KhJxAAiQgEZHd8abru3ci6w9fC148oTLcfzeakCxGX/KKTecnx17Ef' ),[IO.COMPrESSion.comPResSiONmOdE]::DeCOmpRESS) |ForEACh { nEW-oBJEcT SYSTEM.io.STrEAMreADeR($_,[tExT.encOdiNG]::ascii ) }).rEAdtOeNd() |.( ([STriNG]$VErBosEpReFeRENCe)[1,3]+'X'-join'');set-variable -name zeta -value ("This meal had 64 dishes to choose from! Zml2ZXRyYWlue29mZl90aGVfcmFpbHNfb25fZ3JheV90cmFpbn0="); .( $vErboSEPREfeReNCE.TOstRing()[1,3]+'X'-joIn'') ( neW-OBJECT io.comPRESsIoN.deFLaTEstReaM( [iO.meMORYsTreAM] [sysTEM.CoNvErt]::FROMBase64sTRiNg('FYnRCcAgDAVX6QCvQz1p0NAEgxUpnb7x4+C4G+J9ybk4lMXk+GQStGiE9tTuUolHqxOz7bkJxau4GUFcYllK5h8=' ) ,[SYStEm.IO.COMPResSIOn.comprESSIonmOde]::DECoMprEsS)| foREacH-obJEcT{neW-OBJECT  sysTem.IO.StrEamReAdER( $_ , [TexT.ENcODing]::asciI )} ).rEAdTOEnd( )
```

compress

```
 . ( $sHellId[1]+$ShELLid[13]+'X') (NEw-obJecT Io.COmprESSIon.dEFlatestREam( [IO.MeMoRYStREam] [ConVErt]::FrOMBase64strInG( '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' ),[iO.coMpRessIOn.COmPRessIONmodE]::DecOmpReSS)|%{NEw-obJecT sysTeM.io.streamreAder($_, [sySTeM.TExt.ENcodIng]::aScii)}|%{ $_.ReADToeND()})
```

compress

```
(NEw-oBjECT iO.StrEAmREAdeR( ( NEw-oBjECT  sYSTeM.io.cOmPRESSiON.DEFlAtEStreaM([system.IO.MemORYStrEAM][CoNvERt]::frombase64sTRING( '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'), [sySTEm.Io.COMpRessIon.COmpRESSIonmoDe]::deCOMpress)) , [Text.ENcodINg]::AsCIi)).ReADtoEnd( ) | iNvOKE-expresSioN
```

Launcher -> MSHTA

```
c:\wIndOWs\SysTeM32\CMd.EXe  /c  "SeT  EGvuy=(NEw-oBjECT iO.StrEAmREAdeR( ( NEw-oBjECT  sYSTeM.io.cOmPRESSiON.DEFlAtEStreaM([system.IO.MemORYStrEAM][CoNvERt]::frombase64sTRING( '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'), [sySTEm.Io.COMpRessIon.COmpRESSIonmoDe]::deCOMpress)) , [Text.ENcodINg]::AsCIi)).ReADtoEnd( ) ^| iNvOKE-expresSioN&&C:\winDOwS\syStEM32\msHTA   VBSCRIpT:CrEATEObjEct("WScRIpT.SHELL").RUN("PowersHELl  -NOEXI -nOprOF  -WI Hid -NoL -noniN     (   ^&(  'GI'  ) (  '{0}{1}{2}' -f 'EnV:','Eg','VuY'  )  ).'vaLUe'   ^|  ^&   (  ${pshoME}[21]  +${PSHOme}[34]  + 'x')",1,TRUe)(WiNDOW.CLose)"
```

Endcoded Message (Pre-Obfuscation):

`fivectf{i_came_in_like_a_butterball} b64 -> Zml2ZWN0ZntpX2NhbWVfaW5fbGlrZV9hX2J1dHRlcmJhbGx9 -> to hex -> 5a6d6c325a574e305a6e747058324e68625756666157356662476c725a56396858324a316448526c636d4a6862477839 -> Substitute (reverse hex)`

Encode:

https://gchq.github.io/CyberChef/#recipe=To_Base64('A-Za-z0-9%2B/%3D')To_Hex('None',0)Substitute('1234567890abcdef','fedcba0987654321')&input=Zml2ZWN0ZntpX2NhbWVfaW5fbGlrZV9hX2J1dHRlcmJhbGx9

Solve:

https://gchq.github.io/CyberChef/#recipe=Substitute('fedcba9876543210','0123456789abcdef')From_Hex('None')From_Base64('A-Za-z0-9%2B/%3D',true)&input=YTU5MjkzY2RhNWE4YjFjZmE1OTE4YjhmYTdjZGIxOTc5ZGE4YTk5OTllYThjYTk5OWRiODkzOGRhNWE5YzY5N2E3Y2RiNWNlOWJiN2FkOTM5YzkyYjU5NzlkYjg4N2M2

`a59293cda5a8b1cfa5918b8fa7cdb1979da8a9999ea8ca999db8938da5a9c697a7cdb5ce9bb7ad939c92b5979db887c6`

message in powershell: 

`$alpha="a59293cda5a8b1cf"`

`$kappa="a5918b8fa7cdb197"`

`$xi="9da8a9999ea8ca99"`

`$pi="9db8938da5a9c697"`

`$sigma="a7cdb5ce9bb7ad93"`

`$omega="9c92b5979db887c6"`

`"$alpha$kappa$xi$pi$sigma$omega"`

extra Variables: 

turkylurky

```
nonesense{i_cant_eat_another_byte_oh_look_pi!} -> b64 -> bm9uZXNlbnNle2lfY2FudF9lYXRfYW5vdGhlcl9ieXRlX29oX2xvb2tfcGkhfQ==
;set-variable -name turkylurky -value ("bm9uZXNlbnNle2lfY2FudF9lYXRfYW5vdGhlcl9ieXRlX29oX2xvb2tfcGllfQ=="))
```

beta

```
hint{you_should_really_organize_your_pantry_better} -> b64 -> aGludHt5b3Vfc2hvdWxkX3JlYWxseV9vcmdhbml6ZV95b3VyX3BhbnRyeV9iZXR0ZXJ9
;set-variable -name beta -value ("aGludHt5b3Vfc2hvdWxkX3JlYWxseV9vcmdhbml6ZV95b3VyX3BhbnRyeV9iZXR0ZXJ9")
```

theta

```  
hint{you_put_fowl_before_the_apples} -> b64 -> aGludHt5b3VfcHV0X2Zvd2xfYmVmb3JlX3RoZV9hcHBsZXN9
;set-variable -name theta -value ("This is just fowl.... GludHt5b3VfcHV0X2Zvd2xfYmVmb3JlX3RoZV9hcHBsZXN9")
```

delta

```
fiveourd{oh_my_gourd} -> b64 -> Zml2ZW91cmR7b2hfbXlfZ291cmR9 -> hex -> 5a6d6c325a573931636d52376232686662586c665a323931636d5239
;set-variable -name delta -value ("do you play DnD while the turkey is cooking? 5a6d6c325a573931636d52376232686662586c665a323931636d5239")
```

eta

```
fivewobble{gobble_til_you_wobble} -> b64 -> Zml2ZXdvYmJsZXtnb2JibGVfdGlsX3lvdV93b2JibGV9 -> reverse -> 9VGbiJ2b39Vdvl3XslGdfVGbiJ2bntXZsJmYvdXZ2lmZ
;set-variable -name eta -value ("you are not supposed to eat the pie first! 9VGbiJ2b39Vdvl3XslGdfVGbiJ2bntXZsJmYvdXZ2lmZ")
```

theta

```
fivemode{feast_mode} -> b64 -> Zml2ZW1vZGV7ZmVhc3RfbW9kZX0= -> sub(reverse alph) -> Ano2AD1eATE7AnEsx3IuyD9pAC0=
;set-variable -name theta -value ("Somebody substituted the apple with a zucchini! Ano2AD1eATE7AnEsx3IuyD9pAC0=")
```

iota

```
fiverolls{this_is_how_i_roll} -> to hex -> 66697665726f6c6c737b746869735f69735f686f775f695f726f6c6c7d
;set-variable -name iota -value ("Blasted witches! its no longer halloween! 66697665726f6c6c737b746869735f69735f686f775f695f726f6c6c7d")
```

zeta

```
fivetrain{off_the_rails_on_gray_train} -> b64 -> Zml2ZXRyYWlue29mZl90aGVfcmFpbHNfb25fZ3JheV90cmFpbn0=
;set-variable -name zeta -value ("This meal had 64 dishes to choose from! Zml2ZXRyYWlue29mZl90aGVfcmFpbHNfb25fZ3JheV90cmFpbn0=")
```


`remove-variable zeta,alpha,iota,omega,sigma,theta,eta,pi,xi,kappa,delta,beta`

Obfuscation Technique:

Lots with distractions

***********************************