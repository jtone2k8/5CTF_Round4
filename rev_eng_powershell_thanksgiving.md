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
(New-OBjEct io.compRession.dEflATESTrEAm( [SySTeM.iO.memoRYSTrEam][coNVeRT]::FRoMbase64sTrING( 'bVdrc9rIEv0r82E3SBFySQi9krofiCMbXDa2wQW5q1Jtyax4JGC8Aru8Yfnvt8/MtIa4bpXl6enpx5me1ujwwRK/Pe/6202Wdwvnt7txf3tT5QHJrbeWbQnLallW5+fw4B8PLaflp8dDHB8PHfojjU+j7x0P3eR4CGke0BPTk0bHQ9KlNZ8E+ZBPSE8Kg0SGSkKKERwPUQo7/JMz6UVL3RihSd1Nj2R9iChVgAgxzSg6gioIlD8N4YVVAKMQKYUKEKoDN7KNySKSVoBHKwFNAix6amPw6mI7PvZCT0whYsQmDBFFSLFP0oVIQakSGhNaC0nXBRCPnNIEEeBJHiHyeT7wYge+F2COvORJGpghCAULsH9AJDkGbqyRjnKGFCmiqSwTmaNs2BA50mqQyHL45INCJMjv4YBI6AIxgnn0T9aLlBGUOB6CHAE26egvwC5kfWi9I+sgywc3DyhkekxIQyuhXJUbJOOIInTIQioIEOoTetg1tY5w5z8uHvC06dno0R3ssxsh5vfTV625n2phft9ohJZ2lRb2t9cVh7LF5mKi5YuJaGtxVT5eV5+2F7smzvDSsrVYN6GrOcGDBQ3QPOiVybwBMlwUOftllw26KVCLJnGwmlt68n2oBYrZ0+JIj59uoNyf97OxRbgZ0Ki31BJnbVP0enDZZ0BTxyA6mhJRNCVnozPbYDuBtr7TAuFi3XCgha7nF5R7lltWNSs5td3p4GXQ04qrpbxlRoCp2d4WJjEWxCPZCD3hI5vaP/1lyoZ6dKgEItCTD1w/PrDF06p+GN++K4w5O/sUF6XEOTSn7S8tUb2sy4krEdPDRzJ9m5uykeCcdNqYkTHszUwLs+psT8bb8b7m4lHfnrYop8guTPj7qbVRyDB7M0fIYblzCYSxGzydnGSTAtXsfNNlDbn23O5qEyrG8xV7Td09GctNmh4vTLetGZFEPM6424qm67SAMIKTTbfzHWfo6JGbwRGWyHfc7Xrcfqmr18Ak4ir8rsdvP7XQ/4s1egwYySwvLhsRG+JWZlDmFrjLOP9UlXVa6qoZBBOt6ZT/cKBf+wynOXWvuPsemyah91yY8FrK/XZQMCRxEHQb/MlWm8Z1f1bNnrizYDOpzKHnTto9ORm8P2ccfugKdvtyO87u+B1wiqDt5za/OA+j5r3+8eu1cz99Gmy1/L3ZiLA+8IGP9ju+5K7c+f+5hPVYXWR1xoucFn1on42y53U5yyzVt1jLd/vRYHhZ5LNlWRdBamws2rfS0tfdUVLsaSGJ7Peu3V/CU+V06nH/BclNXB2hiw7hBBEnSGz49K5QY1vQKMjsAzWsJdM9XdK0oJCTrEaZn0fZRVVXw1llN+eLvnSvtit0C6K0bPd8VN1dI3l+3u9R7sBRQtzRAnES2pAUg0g09i0C0NJ6Ih5GT19L1gdGLdAojT61hS0+S15mvcx68gsPXoKvveRgniIIHcWbQlAtRXUSzc4kDVAsylN0DGwqCRT9oAViINI1VLwlVNwCDAyEyFe8BN98UDowA3ChWNGUJFREAfyqo4gJeBeoW1fxHVAH0A2QBZBESc26iu+AeRDhk5QN/A1MBUwQTCXU3A5kE1SF+aOneahimqBLgaZv4HOJYqVgmaCLkqlhi4rHgryFniJ44GAgLqkiRSBCYHGgYsGRKk08RkRv5Ltz6miRRm+7Nj0/9FjrsXqjf7huabjRukiPudOJzao3rKN3zreDoRi/Tq71lHNM/1ACcruVifAVG1lxkoUWhE3w7BuOuX0dGo/r+xetBvl5adIv3iGtq0kT1tHS4n2iaGFpKShqhQ4T97vWLs+1UOqxK0eyI9V/i09a27bj2NSBo8CME3V4Z7yn9eYPVk1Xlyaq4EKfL8tRLsy+q3pXWVRZ9srLkRZfJ+u/X9JM/Id9x3pckWtNJGJfcVanQbkoRbXhXaEbHuWEPPTyxOVMeixEQUiFbes5XetrjmtLP954U+8Zx1iZfTw2pc215J2gGNNDt8LwdjVGtGz0/K1SmGAx5HOEaX+9e6PBqRvlu1N2TFN85j3U5VKLvmnITwZdtJiWJ0fIBeqvm0YXnxmPPK/z3MrOSSqv7wCUz4StK3HPb0IlTIGXJxCbIhK4RtLC/om7JHcSz2cI1QsbmC2iU23bndHXhG7cij4LM8q17I2KJMY3hAT65aal2KdLXUpBV4jGSW1cN5lej0xIbOD+a6wX8VtghMu/CUAaxGBQOgBpU/vhOqZvlXU5QYyPN3+NPgLu2bDc0E/1tu+3O4X7fTsgW5yx7Ch8nBD1PBMCNWvJgPh8uHV2t5ZfFbrTGjVwnHhQRl4ijPa/Mn21dye90aD35boSrY+br/XHln321NtkBsTtathq2Z/rarN9rdzXsqYfY+tKlO3H/wE=' ) ,[SysteM.IO.comPreSSIOn.comPResSioNMoDe]::DecOMPRESS)|fOReaCh-objECT {New-OBjEct iO.stREAMreAdeR($_ ,[sYStem.text.eNcODinG]::AsCIi)} ).ReadtOEND( )|&((gV '*mdr*').nAME[3,11,2]-joiN'')
```

cmd -> rundll ->32bit powershell

```
c:\WiNDOws\SYsTEm32\CMD   /c "sET   fzS=(New-OBjEct io.compRession.dEflATESTrEAm( [SySTeM.iO.memoRYSTrEam][coNVeRT]::FRoMbase64sTrING( 'bVdrc9rIEv0r82E3SBFySQi9krofiCMbXDa2wQW5q1Jtyax4JGC8Aru8Yfnvt8/MtIa4bpXl6enpx5me1ujwwRK/Pe/6202Wdwvnt7txf3tT5QHJrbeWbQnLallW5+fw4B8PLaflp8dDHB8PHfojjU+j7x0P3eR4CGke0BPTk0bHQ9KlNZ8E+ZBPSE8Kg0SGSkKKERwPUQo7/JMz6UVL3RihSd1Nj2R9iChVgAgxzSg6gioIlD8N4YVVAKMQKYUKEKoDN7KNySKSVoBHKwFNAix6amPw6mI7PvZCT0whYsQmDBFFSLFP0oVIQakSGhNaC0nXBRCPnNIEEeBJHiHyeT7wYge+F2COvORJGpghCAULsH9AJDkGbqyRjnKGFCmiqSwTmaNs2BA50mqQyHL45INCJMjv4YBI6AIxgnn0T9aLlBGUOB6CHAE26egvwC5kfWi9I+sgywc3DyhkekxIQyuhXJUbJOOIInTIQioIEOoTetg1tY5w5z8uHvC06dno0R3ssxsh5vfTV625n2phft9ohJZ2lRb2t9cVh7LF5mKi5YuJaGtxVT5eV5+2F7smzvDSsrVYN6GrOcGDBQ3QPOiVybwBMlwUOftllw26KVCLJnGwmlt68n2oBYrZ0+JIj59uoNyf97OxRbgZ0Ki31BJnbVP0enDZZ0BTxyA6mhJRNCVnozPbYDuBtr7TAuFi3XCgha7nF5R7lltWNSs5td3p4GXQ04qrpbxlRoCp2d4WJjEWxCPZCD3hI5vaP/1lyoZ6dKgEItCTD1w/PrDF06p+GN++K4w5O/sUF6XEOTSn7S8tUb2sy4krEdPDRzJ9m5uykeCcdNqYkTHszUwLs+psT8bb8b7m4lHfnrYop8guTPj7qbVRyDB7M0fIYblzCYSxGzydnGSTAtXsfNNlDbn23O5qEyrG8xV7Td09GctNmh4vTLetGZFEPM6424qm67SAMIKTTbfzHWfo6JGbwRGWyHfc7Xrcfqmr18Ak4ir8rsdvP7XQ/4s1egwYySwvLhsRG+JWZlDmFrjLOP9UlXVa6qoZBBOt6ZT/cKBf+wynOXWvuPsemyah91yY8FrK/XZQMCRxEHQb/MlWm8Z1f1bNnrizYDOpzKHnTto9ORm8P2ccfugKdvtyO87u+B1wiqDt5za/OA+j5r3+8eu1cz99Gmy1/L3ZiLA+8IGP9ju+5K7c+f+5hPVYXWR1xoucFn1on42y53U5yyzVt1jLd/vRYHhZ5LNlWRdBamws2rfS0tfdUVLsaSGJ7Peu3V/CU+V06nH/BclNXB2hiw7hBBEnSGz49K5QY1vQKMjsAzWsJdM9XdK0oJCTrEaZn0fZRVVXw1llN+eLvnSvtit0C6K0bPd8VN1dI3l+3u9R7sBRQtzRAnES2pAUg0g09i0C0NJ6Ih5GT19L1gdGLdAojT61hS0+S15mvcx68gsPXoKvveRgniIIHcWbQlAtRXUSzc4kDVAsylN0DGwqCRT9oAViINI1VLwlVNwCDAyEyFe8BN98UDowA3ChWNGUJFREAfyqo4gJeBeoW1fxHVAH0A2QBZBESc26iu+AeRDhk5QN/A1MBUwQTCXU3A5kE1SF+aOneahimqBLgaZv4HOJYqVgmaCLkqlhi4rHgryFniJ44GAgLqkiRSBCYHGgYsGRKk08RkRv5Ltz6miRRm+7Nj0/9FjrsXqjf7huabjRukiPudOJzao3rKN3zreDoRi/Tq71lHNM/1ACcruVifAVG1lxkoUWhE3w7BuOuX0dGo/r+xetBvl5adIv3iGtq0kT1tHS4n2iaGFpKShqhQ4T97vWLs+1UOqxK0eyI9V/i09a27bj2NSBo8CME3V4Z7yn9eYPVk1Xlyaq4EKfL8tRLsy+q3pXWVRZ9srLkRZfJ+u/X9JM/Id9x3pckWtNJGJfcVanQbkoRbXhXaEbHuWEPPTyxOVMeixEQUiFbes5XetrjmtLP954U+8Zx1iZfTw2pc215J2gGNNDt8LwdjVGtGz0/K1SmGAx5HOEaX+9e6PBqRvlu1N2TFN85j3U5VKLvmnITwZdtJiWJ0fIBeqvm0YXnxmPPK/z3MrOSSqv7wCUz4StK3HPb0IlTIGXJxCbIhK4RtLC/om7JHcSz2cI1QsbmC2iU23bndHXhG7cij4LM8q17I2KJMY3hAT65aal2KdLXUpBV4jGSW1cN5lej0xIbOD+a6wX8VtghMu/CUAaxGBQOgBpU/vhOqZvlXU5QYyPN3+NPgLu2bDc0E/1tu+3O4X7fTsgW5yx7Ch8nBD1PBMCNWvJgPh8uHV2t5ZfFbrTGjVwnHhQRl4ijPa/Mn21dye90aD35boSrY+br/XHln321NtkBsTtathq2Z/rarN9rdzXsqYfY+tKlO3H/wE=' ) ,[SysteM.IO.comPreSSIOn.comPResSioNMoDe]::DecOMPRESS)^|fOReaCh-objECT {New-OBjEct iO.stREAMreAdeR($_ ,[sYStem.text.eNcODinG]::AsCIi)} ).ReadtOEND( )^|^&((gV '*mdr*').nAME[3,11,2]-joiN'')&&C:\wIndOwS\SysTEm32\rUndlL32  SHELL32.DLL ShellExec_RunDLL   "C:\wInDoWs\sySWow64\WIndowSPowershELL\v1.0\POwersheLL.eXe"   "-nOpRo  "   "-WI HiDdeN"     "${eXECUTIoncONTeXt}.'inVokecOMManD'.(  '{2}{1}{0}{3}' -f 'ScR','VOke','iN','Ipt' ).Invoke(  (^&  (  'Gi') ('{1}{0}'-f'Zs','enV:f'  ) ).'vaLuE'    )"
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

Question:

Encoding:

```
$s="abb108afa30d03";$m="abb1a1aab10ca9";$a="050da8a4aba2ad";$y="aaa80aabad0caa"
```

AST

```
Set-Variable -Name s -Value ("abb108afa30d03");Set-Variable -Name m -Value ("abb1a1aab10ca9");Set-Variable -Name a -Value ("050da8a4aba2ad");Set-Variable -Name y -Value ("aaa80aabad0caa")
```

token
```
.("{1}{0}{2}"-f 'l','Set-Variab','e') -Name ('s') -Value (("{2}{0}{1}"-f'b1','08afa30d03','ab'));.("{1}{0}{2}{3}"-f'e','S','t-V','ariable') -Name ('m') -Value (("{2}{0}{1}" -f'c','a9','abb1a1aab10'));.("{2}{0}{1}{3}"-f 'et-Va','ria','S','ble') -Name ('a') -Value (("{1}{0}{3}{2}{4}" -f '0d','05','a4aba2a','a8','d'));.("{2}{1}{0}"-f 'iable','Var','Set-') -Name ('y') -Value (("{0}{3}{1}{2}" -f 'aaa80','ad','0caa','aab')); remove-variable s,m,a,y
```

compress
```
( nEW-ObjEct  System.IO.STReAmREadER( (nEW-ObjEct  iO.cOmpreSSiOn.DeflatEstrEAm( [iO.meMoRYStReAm] [sYsTeM.COnveRT]::frOMBASe64sTRIng( 'ddDBCsIwDAbgVyle4qCTdlOY+A5eBO9/twrChuBUkLF3N0k32A4eVhbI36/JbrsZ/Di4cSjGTX4z1JKlS3zlVzzvCFxEykx+RhfNlnr5v6J9c8HBQoNeghQ897oKN5SucSUXnM6y024BDKW2RiH4Y0TaxGmXSvdHMZytJXHU24OHB4J3MzM3JsaQTsGtDEzi2sHaSa8s9aF71Qy5RqY6iLdHQCEXoeKjWaAaVDFNYomXN61xwX3XXLK8Ll4tAJWT+9WsoVZa4jN2j0/MP9OuTG87C/v9AQ==') , [sYSTeM.IO.ComPREssiOn.coMpresSIOnMODe]::DEcomPreSS ) ) ,[tEXT.eNcoDINg]::ascii) ).READToend() |inVOkE-eXprESSIoN
```

ascii
```
&( $veRbOseprEFEREnce.tOSTrING()[1,3]+'X'-JoIN'') ( " $( seT 'OfS' '' ) "+ [StrInG]('40~32E110%69q87%45f79E98!106t69E99t116q32d32f83q121>115q116!101t109>46!73f79X46X83>84q82t101X65f109d82t69t97~100%69!82q40q32X40>110%69!87t45!79t98d106!69t99t116d32d32~105f79%46%99t79X109E112>114E101t83d83d105E79%110d46t68f101f102t108%97>116>69d115%116%114!69~65d109!40!32q91E105~79>46f109d101f77>111>82~89%83%116t82%101!65~109E93E32t91f115E89q115q84q101t77X46!67t79f110d118t101q82%84d93~58f58!102d114E79>77d66t65t83E101~54t52!115~84t82%73~110q103t40!32~39%100t100>68t66d67>115t73!119~68!65~98E103E86X121t108f101>52E113%67%84t100f108t79q89%43E65!53X101t66f79d57t47q116>119!114q67f104X117f66~85E107d76f70d51d78~48t107d51q50t65%52>101~86~104t98E73d51d54f47X74q98~114f115q90E47f68>105~52X99%83~106>71d84t88!52%122>49!74%75X108>83!51~122%108f86E122~122>118f67d70X120%69!121t107>120t43t82E104d102E78q108!110f114>53~118E54E74X57E99~56E72f66f81f111t78>101t103!104t81%56~57E55>111t75E78t53q83~117>99~83E85X88t110t77!54E121t48f50~52E66~68X75>87E50t82E105>72d52X89t48%84t97!120E71X109d88f83E118>100X72t77q90>121!116~74!88q72t85~50>52>79q72>66>52f74%51!77!122t77q51%74X115>97t81q84E115%71>116~68!69%122f105X50>115%72d97d83>97X56E115X57!97!70d55t49E81>121~53t82~113!89t54E105d76%100f72~81f67~69>88d111q101f75q106~87%97%65E97t86d68%70d78q89d111d109~88%78E54q49d120f119q88q51f88q88>76%75!56>76E108%52!116!65d74>87d84f43!57~87d115>111~86~90d97!52d106%78X50!106!48~47%77>80~57X79X117!84E71f56>55>67d47q118>57q65d81t61t61d39E41X32d44f32t91%115t89q83t84>101d77d46q73>79q46d67q111!109!80t82f69>115t115d105f79f110>46t99!111t77t112>114~101!115X83>73q79d110E77~79~68f101X93f58!58d68>69>99~111f109X80E114f101d83~83~32>41d32d41%32d44d91t116>69E88t84q46~101~78!99f111d68f73~78!103~93d58q58f97>115X99E105%105d41>32%41q46~82d69!65E68~84E111X101d110d100d40%41d32~124q105d110X86q79~107!69f45d101t88%112d114t69E83!83>73E111>78'.spLIt( 'XfE>tqd~!%')| FoREaCH-obJEcT {([chAr][InT] $_) } ) +" $( set-vaRiABlE 'ofS'  ' ') ") 
```

octal
```
&( $VerBOseprEFereNce.TOsTrINg()[1,3]+'x'-jOin'') ("$( Set-Item  'vaRiAblE:OFs'  '' )"+ [striNg]('46P50r40P44r166r145z122;142P117r163z145h160r162;105h106z105;122W105!156s143P145!56h164o117h123!124W162;111z116W107;50!51a133a61!54a63z135;53o47r130o47o55!112o157r111;116s47!47P51!40o50a40a42h40o44r50P40o163a145s124a40o47a117;146!123W47a40r47z47s40;51s40s42!53;40a133h123a164r162;111r156P107P135h50z47o64P60o176s63z62z105s61r61W60;45a66W71a161h70s67;45P64P65P146W67r71P105r71h70;41h61;60o66!164P66P71W105!71P71;164;61s61o66r161!63r62s144;63!62W146!70s63o161r61h62a61h76r61P61r65W161a61P61s66;41h61o60P61r164o61W60a71s76W64W66z41P67!63s146r67P71P130W64a66o130;70a63!76r70s64h161!70o62z164W61r60s61s130s66;65a146o61!60r71z144;70;62P164z66!71o164z71s67o176r61s60a60a45W66z71z41r70z62P161h64W60;161!63o62a130z64P60P76!61o61;60!45W66z71!41a70W67r164W64s65z41!67P71a164!71s70h144P61W60P66h41o66h71W164s71s71o164W61W61s66a144r63W62z144r63W62W176z61W60r65;146h67;71s45W64z66o45s71W71z164W67r71r130!61z60r71s105P61h61;62;76!61o61o64!105o61a60P61z164o70r63o144;70W63;144z61r60P65s105!67z71a45!61P61W60h144s64h66s164h66P70P146r61W60W61;146r61a60s62;164h61P60a70h45o71h67o76s61s61s66z76o66P71o144r61r61h65W45s61r61h66h45h61P61s64s41o66!71!176!66!65!144W61z60o71P41s64;60h41;63h62o161h71r61P105;61r60o65;176W67s71o76!64z66P146;61;60z71;144s61!60z61W146r67;67r76;61r61P61a76h70r62h176!70;71!45!70s63W45P61a61z66h164W70s62r45W61r60W61a41P66!65a176r61r60P71s105o71s63o105h63W62r164h71P61h146!61;61;65r105s70o71o161!61!61o65z161r70!64W161W61z60s61s164;67h67a130W64P66W41h66s67r164!67!71z146!61s61a60h144s61W61P70o164P61;60h61;161P70o62s45W70h64o144;71W63a176r65r70a146z65o70!41a61h60a62r144h61s61h64o105z67a71h76W67s67z144z66r66!164s66P65o164r70z63z105s61W60s61s176s65a64r164!65r62o41W61z61o65r176z70h64s164o70!62!45r67h63o176!61z61z60a161;61!60W63h164P64;60P41s63a62h176;63s71s45s61s60P60a164!61P60a60z76o66s70z164W66P66W144o66a67s76o61h61h65z164;67r63r41o61o61P71z176;66W70s41h66!65;176!71o70P105W61;60W63;105o70o66s130W61r62W61o164s61a60P70r146s61o60h61r76P65W62s105o61W61a63P45!66s67z45h70h64r164a61r60;60;146o61W60a70r164r67P71s161;70h71o45W64;63r105s66h65!41!65a63s130z61s60!61P164h66!66r146s67s71P144z65;67a164P64a67h161h61!61!66o76r61h61o71o41P61!61a64a161P66s67!146o61a60h64r130P61;61r67o146a66a66a176z70h65W105a61r60;67a144!67r66W146s67s60s144a65o61r144W67W70a176;64h70!164o61o60a67o144P65;61!161P65o60a164W66P65a45!65a62s76r61s60h61P176o70s66a176W61h60s64;164;71!70z105W67z63s144o65r61o144r65h64W146o64o67P130o67z64;161s71o70r176!61W61W64s146o61!61h65s161W71;60s105o64o67r146s66W70s76s61!60z65z176h65a62a130a71!71!45o70z63h176s61W60z66o76z67a61P144o70h64a164z70r70P41;65h62P45a61W62P62!76;64o71a41z67P64z45W67P65P130!61!60o70z76a70;63h41!65P61P176s61z62h62a45a61z60o70!146;70z66P105a61r62P62s176r61s62o62;76W61P61!70!146o66W67s144W67;60h130h61;62h60r45W66!71z41!61P62a61P164a61P60r67P76s61P62;60!164o64o63!164o70a62h105h61o60s64W144a61;60W62h105h67!70a161P61r60r70;41h61!61r60z146s61o61r64a76s65o63o176r61a61r70P105a65a64s105o67z64s130;65P67!105a71o71r176W65z66W105P67o62W146W66!66s146;70s61r146r61h61;61a164P67o70!76!61P60z61P164W61a60W63W41;61a60W64a164r70P61r45h65h66r176z65;67o105;65s65a76a61h61s61h164o67a65P105r67!70W164W65a63;161o70P63s176!61o61h67z76r71a71;176h70!63;105W70h65;130;70a70z164s61P61r60a164P67r67h41h65h64W105s61!62;61o164!64o70P146P65;60s176W65o62s105s66P66P176;66z70o130a67s65r76z70r67!105h65s60P164r70s62h105a61r60h65s76W67z62W144r65z62h130W70;71P164a64!70s45h70;64h164r71z67r41r61z62;60h105!67r61z130r61s60h71r144o70a70z146a70z63!105s61h61o70z76W61a60;60r130o67W62z164a67P67;161z71W60r76z61a62P61r41o61r61P66h176s67P64o41s70P70o161W67!62a164;70P65P176z65z60z76;65!62z76s67P71z161P67a62P76a66P66s76;65s62r146h67r64s45!65z61o41o67o67P41r61r62P62r164a67;67s161!65W61s45r67a64h130W61h61W65o76a71;67W164;70a61;161!70!64r105o61P61a65P45W67;61z76;61W61r66!176r66z70W41h66a71!45P61;62o62h146s61P60P65W130P65o60h76h61W61o65P45P67s62h144a71r67r144r70P63!76h71s67r130;65z66s105r61s61h65o130r65;67!41z71h67W41s67s60!144W65h65h164;64h71W105o70r61P76;61P62P61r176!65;63a164r70W62r176o61z61z63P41z70h71o164r65h64h105!61P60r65s144P67z66s45P61a60o60r146r67;62!176!70r61W146P66W67a176a66o71W76W70!70h144r61s61r61h161P61h60z61a146P67W65o161h61o60s66;176a70o67z45z71z67!45o66o65W105h71!67o164P70P66s144W66a70o45W67W60P144P67o70a161W70s71W144W61s61s61W144r61h60!71W176a70r70!45r67h70!105;65o64P161a64o71;144a61h62s60W146s61!61r71W161;70;70h161!65P61W146!70a70!161o70h70z76o67z66a45h67!65z41s65a66!76h67s66P105o61o60s70s45r65!62o41a61s61o66P41a66r65!144P67r64;76P70r67;144a70r64W146z64;63;41r65a67;176h70s67h144a61s61W65!76z61!61o61s176h70s66z176W71!60!144s71a67W41z65W62!144P61W60o66a45!67a70a130;65P60W41s61;60W66r41;64s70W176h64r67h45o67s67z76s70z60a176P65W67!130z67!71;130z61P61;67h41z70W64r105a67;61r146z65s66!76a65z65;76o66r67r144a64W67s161;61h61;70W76a65r67o161;66r65s144o70a61r164W66z61s164z66a61r144h63h71!105W64P61r130W63o62!144!64o64W146z63W62;164r71r61o45a61P61P65!164z70;71h161a70P63a164s70z64z76!61P60;61z144s67o67;144P64P66o161z67W63a76z67s71o161;64P66P144P66W67P161z61W61a61P41r61h60o71s41a70P60P164;70o62h146W66r71z76W61r61a65a164;61W61;65!144;61o60P65s146z67s71z146r61z61o60z76h64s66r164a71s71z41;61s61s61!164r67;67W164a61o61P62a76P61z61z64o176h61a60W61o41;61s61a65!130r70a63r76h67z63h161h67P71W144h61o61s60W105r67h67!176W67P71s176z66o70a146h61W60;61W130o71;63h146r65P70h41z65o70W144z66;70;76h66s71a76r71r71s176h61h61o61W146!61o60r71r130z70z60P105!61a61P64P146P61o60!61r144z70s63o176P70h63a176s63!62r76;64a61r144!63W62!144a64!61P45h63h62o144z64P64h144!71P61s164s61P61s66s76a66a71W105W70s70o164P70h64!161;64a66h176W61r60W61s176h67o70z41a71P71s146h61r61o61s144r66h70!146P67r63z176!67h70o41r61;60z63;176h71h63a144!65h70W161h65W70s146r71P67a76!61P61a65;130z71s71z105W61;60a65P45P61o60z65o144o64z61h76P63;62W45!64r61o161z64o66s176a70a62h144!66a71;41s66P65;105z66r70a176P70W64z105W61!61r61W130r61r60a61a144s61r61z60!144;61!60h60W144!64!60;45a64s61h144o63P62o176W61h62P64;161o61z60!65r144a61W61r60o130s70o66W161!67o71h176P61a60W67s41W66h71s146;64a65W144z61h60z61;164a70W70r45P61s61a62s144h61s61;64P164a66z71s105h70o63r41a70o63!76;67s63r105W61h61;61a76!67s70W47a56o163;160;114a111o164z50s40s47a130;146!105s76;164;161r144z176r41o45r47;51W174s40P106s157s122z105a141;103r110z55z157z142P112s105o143h124W40W173s50W133o143h150W101o162s135h133r111;156o124z135o40o44!137a51P40P175z40W51;40z53s42s40z44z50P40h163;145!164h55a166o141z122;151h101r102s154a105z40h47z157;146z123h47s40o40!47;40o47o51s40o42r51;40'-split';'-SpLIT'a' -SpLiT'r'-Split'W' -spLiT 'z' -SPlit 'P'-sPlit'o'-SPlIt 'h'-SplIt '!' -sPlIT 's'|FoREACh{ ( [ChaR] ([CONvert]::TOiNT16(($_.ToSTriNG() ),8 ) ))}) +" $( SET-ITem  'VarIAble:OFS' ' ')" ) 
```

launcher -> cmd -> wmic

```
wMiC.eXE  PRoCesS   cALL     crEaTE   "pOWersHELl  -noNINTEraCtiVe -wiNdo  h  "\"&( `$VerBOseprEFereNce.TOsTrINg()[1"\"  +  [STRINg][CHar]44+ "\"3]+'x'-jOin'') ("\"+  ([CHar]34).ToStRING()  +  "\"`$( Set-Item  'vaRiAblE:OFs'  '' )"\"+  ([CHar]34).ToStRING()  +  "\"+ [striNg]('46P50r40P44r166r145z122;142P117r163z145h160r162;105h106z105;122W105!156s143P145!56h164o117h123!124W162;111z116W107;50!51a133a61!54a63z135;53o47r130o47o55!112o157r111;116s47!47P51!40o50a40a42h40o44r50P40o163a145s124a40o47a117;146!123W47a40r47z47s40;51s40s42!53;40a133h123a164r162;111r156P107P135h50z47o64P60o176s63z62z105s61r61W60;45a66W71a161h70s67;45P64P65P146W67r71P105r71h70;41h61;60o66!164P66P71W105!71P71;164;61s61o66r161!63r62s144;63!62W146!70s63o161r61h62a61h76r61P61r65W161a61P61s66;41h61o60P61r164o61W60a71s76W64W66z41P67!63s146r67P71P130W64a66o130;70a63!76r70s64h161!70o62z164W61r60s61s130s66;65a146o61!60r71z144;70;62P164z66!71o164z71s67o176r61s60a60a45W66z71z41r70z62P161h64W60;161!63o62a130z64P60P76!61o61;60!45W66z71!41a70W67r164W64s65z41!67P71a164!71s70h144P61W60P66h41o66h71W164s71s71o164W61W61s66a144r63W62z144r63W62W176z61W60r65;146h67;71s45W64z66o45s71W71z164W67r71r130!61z60r71s105P61h61;62;76!61o61o64!105o61a60P61z164o70r63o144;70W63;144z61r60P65s105!67z71a45!61P61W60h144s64h66s164h66P70P146r61W60W61;146r61a60s62;164h61P60a70h45o71h67o76s61s61s66z76o66P71o144r61r61h65W45s61r61h66h45h61P61s64s41o66!71!176!66!65!144W61z60o71P41s64;60h41;63h62o161h71r61P105;61r60o65;176W67s71o76!64z66P146;61;60z71;144s61!60z61W146r67;67r76;61r61P61a76h70r62h176!70;71!45!70s63W45P61a61z66h164W70s62r45W61r60W61a41P66!65a176r61r60P71s105o71s63o105h63W62r164h71P61h146!61;61;65r105s70o71o161!61!61o65z161r70!64W161W61z60s61s164;67h67a130W64P66W41h66s67r164!67!71z146!61s61a60h144s61W61P70o164P61;60h61;161P70o62s45W70h64o144;71W63a176r65r70a146z65o70!41a61h60a62r144h61s61h64o105z67a71h76W67s67z144z66r66!164s66P65o164r70z63z105s61W60s61s176s65a64r164!65r62o41W61z61o65r176z70h64s164o70!62!45r67h63o176!61z61z60a161;61!60W63h164P64;60P41s63a62h176;63s71s45s61s60P60a164!61P60a60z76o66s70z164W66P66W144o66a67s76o61h61h65z164;67r63r41o61o61P71z176;66W70s41h66!65;176!71o70P105W61;60W63;105o70o66s130W61r62W61o164s61a60P70r146s61o60h61r76P65W62s105o61W61a63P45!66s67z45h70h64r164a61r60;60;146o61W60a70r164r67P71s161;70h71o45W64;63r105s66h65!41!65a63s130z61s60!61P164h66!66r146s67s71P144z65;67a164P64a67h161h61!61!66o76r61h61o71o41P61!61a64a161P66s67!146o61a60h64r130P61;61r67o146a66a66a176z70h65W105a61r60;67a144!67r66W146s67s60s144a65o61r144W67W70a176;64h70!164o61o60a67o144P65;61!161P65o60a164W66P65a45!65a62s76r61s60h61P176o70s66a176W61h60s64;164;71!70z105W67z63s144o65r61o144r65h64W146o64o67P130o67z64;161s71o70r176!61W61W64s146o61!61h65s161W71;60s105o64o67r146s66W70s76s61!60z65z176h65a62a130a71!71!45o70z63h176s61W60z66o76z67a61P144o70h64a164z70r70P41;65h62P45a61W62P62!76;64o71a41z67P64z45W67P65P130!61!60o70z76a70;63h41!65P61P176s61z62h62a45a61z60o70!146;70z66P105a61r62P62s176r61s62o62;76W61P61!70!146o66W67s144W67;60h130h61;62h60r45W66!71z41!61P62a61P164a61P60r67P76s61P62;60!164o64o63!164o70a62h105h61o60s64W144a61;60W62h105h67!70a161P61r60r70;41h61!61r60z146s61o61r64a76s65o63o176r61a61r70P105a65a64s105o67z64s130;65P67!105a71o71r176W65z66W105P67o62W146W66!66s146;70s61r146r61h61;61a164P67o70!76!61P60z61P164W61a60W63W41;61a60W64a164r70P61r45h65h66r176z65;67o105;65s65a76a61h61s61h164o67a65P105r67!70W164W65a63;161o70P63s176!61o61h67z76r71a71;176h70!63;105W70h65;130;70a70z164s61P61r60a164P67r67h41h65h64W105s61!62;61o164!64o70P146P65;60s176W65o62s105s66P66P176;66z70o130a67s65r76z70r67!105h65s60P164r70s62h105a61r60h65s76W67z62W144r65z62h130W70;71P164a64!70s45h70;64h164r71z67r41r61z62;60h105!67r61z130r61s60h71r144o70a70z146a70z63!105s61h61o70z76W61a60;60r130o67W62z164a67P67;161z71W60r76z61a62P61r41o61r61P66h176s67P64o41s70P70o161W67!62a164;70P65P176z65z60z76;65!62z76s67P71z161P67a62P76a66P66s76;65s62r146h67r64s45!65z61o41o67o67P41r61r62P62r164a67;67s161!65W61s45r67a64h130W61h61W65o76a71;67W164;70a61;161!70!64r105o61P61a65P45W67;61z76;61W61r66!176r66z70W41h66a71!45P61;62o62h146s61P60P65W130P65o60h76h61W61o65P45P67s62h144a71r67r144r70P63!76h71s67r130;65z66s105r61s61h65o130r65;67!41z71h67W41s67s60!144W65h65h164;64h71W105o70r61P76;61P62P61r176!65;63a164r70W62r176o61z61z63P41z70h71o164r65h64h105!61P60r65s144P67z66s45P61a60o60r146r67;62!176!70r61W146P66W67a176a66o71W76W70!70h144r61s61r61h161P61h60z61a146P67W65o161h61o60s66;176a70o67z45z71z67!45o66o65W105h71!67o164P70P66s144W66a70o45W67W60P144P67o70a161W70s71W144W61s61s61W144r61h60!71W176a70r70!45r67h70!105;65o64P161a64o71;144a61h62s60W146s61!61r71W161;70;70h161!65P61W146!70a70!161o70h70z76o67z66a45h67!65z41s65a66!76h67s66P105o61o60s70s45r65!62o41a61s61o66P41a66r65!144P67r64;76P70r67;144a70r64W146z64;63;41r65a67;176h70s67h144a61s61W65!76z61!61o61s176h70s66z176W71!60!144s71a67W41z65W62!144P61W60o66a45!67a70a130;65P60W41s61;60W66r41;64s70W176h64r67h45o67s67z76s70z60a176P65W67!130z67!71;130z61P61;67h41z70W64r105a67;61r146z65s66!76a65z65;76o66r67r144a64W67s161;61h61;70W76a65r67o161;66r65s144o70a61r164W66z61s164z66a61r144h63h71!105W64P61r130W63o62!144!64o64W146z63W62;164r71r61o45a61P61P65!164z70;71h161a70P63a164s70z64z76!61P60;61z144s67o67;144P64P66o161z67W63a76z67s71o161;64P66P144P66W67P161z61W61a61P41r61h60o71s41a70P60P164;70o62h146W66r71z76W61r61a65a164;61W61;65!144;61o60P65s146z67s71z146r61z61o60z76h64s66r164a71s71z41;61s61s61!164r67;67W164a61o61P62a76P61z61z64o176h61a60W61o41;61s61a65!130r70a63r76h67z63h161h67P71W144h61o61s60W105r67h67!176W67P71s176z66o70a146h61W60;61W130o71;63h146r65P70h41z65o70W144z66;70;76h66s71a76r71r71s176h61h61o61W146!61o60r71r130z70z60P105!61a61P64P146P61o60!61r144z70s63o176P70h63a176s63!62r76;64a61r144!63W62!144a64!61P45h63h62o144z64P64h144!71P61s164s61P61s66s76a66a71W105W70s70o164P70h64!161;64a66h176W61r60W61s176h67o70z41a71P71s146h61r61o61s144r66h70!146P67r63z176!67h70o41r61;60z63;176h71h63a144!65h70W161h65W70s146r71P67a76!61P61a65;130z71s71z105W61;60a65P45P61o60z65o144o64z61h76P63;62W45!64r61o161z64o66s176a70a62h144!66a71;41s66P65;105z66r70a176P70W64z105W61!61r61W130r61r60a61a144s61r61z60!144;61!60h60W144!64!60;45a64s61h144o63P62o176W61h62P64;161o61z60!65r144a61W61r60o130s70o66W161!67o71h176P61a60W67s41W66h71s146;64a65W144z61h60z61;164a70W70r45P61s61a62s144h61s61;64P164a66z71s105h70o63r41a70o63!76;67s63r105W61h61;61a76!67s70W47a56o163;160;114a111o164z50s40s47a130;146!105s76;164;161r144z176r41o45r47;51W174s40P106s157s122z105a141;103r110z55z157z142P112s105o143h124W40W173s50W133o143h150W101o162s135h133r111;156o124z135o40o44!137a51P40P175z40W51;40z53s42s40z44z50P40h163;145!164h55a166o141z122;151h101r102s154a105z40h47z157;146z123h47s40o40!47;40o47o51s40o42r51;40'-split';'-SpLIT'a' -SpLiT'r'-Split'W' -spLiT 'z' -SPlit 'P'-sPlit'o'-SPlIt 'h'-SplIt '!' -sPlIT 's'|FoREACh{ ( [ChaR] ([CONvert]::TOiNT16((`$_.ToSTriNG() )"\"  +  [STRINg][CHar]44+ "\"8 ) ))}) +"\"+  ([CHar]34).ToStRING()  +  "\" `$( SET-ITem  'VarIAble:OFS' ' ')"\"+  ([CHar]34).ToStRING()  +  "\" ) "\"|&( $shEllId[1]+$ShELlID[13]+'X')"
```

Endcoded Message:

hex:
666976656374667b73696c656e63655f6f665f7468655f79616d737d

substitue -> 0-f f-0
https://gchq.github.io/CyberChef/#recipe=To_Hex('None',0)Substitute('1234567890abcdef','fedcba0987654321')&input=Zml2ZWN0ZntzaWxlbmNlX29mX3RoZV95YW1zfQ

aaa80aabad0caa050da8a4aba2adabb1a1aab10ca9abb108afa30d03

'$s="abb108afa30d03";$m="abb1a1aab10ca9";$a="050da8a4aba2ad";$y="aaa80aabad0caa"'

Obfuscation Technique:

S

***********************************

11.

Flag: `fivectf{silence_of_the_yams}`

Question:

Encoding:

```

```

Endcoded Message:


`$`

Obfuscation Technique:

S

***********************************