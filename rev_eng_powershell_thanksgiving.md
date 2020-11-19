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

AST

```
Set-Variable -Name xi -Value ("HAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYHAPPYJOYHAPPYJOYJOYJOYJOYJOY");Set-Variable -Name sigma -Value ("HAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOY");Set-Variable -Name pi -Value ("HAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOY");Set-Variable -Name omega -Value ("HAPPYJOYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYJOYJOYJOYHAPPYJOY");Set-Variable -Name eta -Value ("HAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOY");Set-Variable -Name alpha -Value ("HAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPY"); remove-variable alpha,eta,omega,pi,sigma,xi
```

Token

```
&("{0}{1}{3}{2}"-f'Set-Var','ia','le','b') -Name ('xi') -Value (("{26}{39}{42}{38}{0}{44}{2}{40}{14}{28}{18}{6}{1}{3}{8}{37}{5}{34}{35}{17}{24}{9}{15}{41}{45}{13}{12}{19}{4}{33}{7}{23}{20}{27}{21}{16}{43}{32}{31}{22}{29}{36}{30}{25}{10}{11}"-f'J','PYJOY','YH','H','JOYJOYH','HAPPYJ','APPYHAPPYJOYHAP','YJ','APP','OYHA','YJOYJ','OY','YJ','HAPP','YHA','PPYJ','PPYJ','O','YJOYH','OYHAPPYHAPPYJOYHAPPY','YJO','YHA','APP','O','YJOYJ','O','HAPPYJOYJOY','YHAPP','PPYJO','Y','YJ','H','Y','APPYJO','OY','JOYJ','JOYJO','YJOY','Y','H','APPYJO','OYJO','APP','O','OYJO','Y'));&("{2}{0}{3}{1}" -f 'V','le','Set-','ariab') -Name ("{1}{0}" -f'gma','si') -Value (("{18}{30}{19}{14}{15}{17}{6}{36}{25}{7}{20}{23}{21}{9}{12}{29}{10}{2}{13}{1}{16}{22}{24}{34}{3}{32}{0}{11}{31}{5}{33}{35}{28}{38}{8}{4}{26}{27}{37}" -f'Y','Y','PYJOYJOYJO','PYJOYHAPPYHAPPY','YHAPPYJOYHA','JOYHAPPYJOY','Y','YHAPPYJO','YHAPP','APPYHAPP','YHAP','JOYJ','YHAP','YHAPPYJOYHAPP','APP','YJ','JOY','O','HAP','JOYH','YJ','YH','HAPP','O','YJO','O','PP','YJ','HAPPY','PYJOYHAPP','PY','OY','HAPP','HAPPYHA','YJOYJOYHAP','PPY','JOYJOYJOYJ','OY','JOYJO'));.("{1}{2}{0}{3}" -f'ar','S','et-V','iable') -Name ('pi') -Value (("{25}{23}{47}{0}{14}{34}{9}{2}{21}{42}{1}{8}{32}{45}{35}{6}{15}{5}{7}{19}{37}{41}{36}{40}{3}{30}{16}{22}{18}{26}{17}{4}{43}{28}{49}{11}{24}{27}{29}{20}{33}{48}{38}{10}{46}{39}{31}{13}{12}{44}"-f 'JO','YJOYHAP','HAPPYHAP','YJOYH','OYHA','AP','HAPP','PYJ','PYH','Y','JOYH','PYJOY','PPYHAPP','A','YJOYHAPPYJO','YJOYH','AP','YJ','HA','OYJOY','JOY','PYJOYJOYH','PYJOY','AP','J','H','PP','OYJO','JOY','Y','APPYH','YHAPPYH','APPYJOYHAPPY','JO','YJOYHAPP','OYJOY','PP','H','OY','P','YJO','A','APP','PPY','YJOY','J','AP','PY','YHAPPYJ','HAP'));&("{0}{1}{2}{3}"-f 'Set-Var','i','a','ble') -Name ("{1}{0}"-f'ega','om') -Value (("{19}{36}{39}{34}{17}{22}{29}{26}{33}{2}{37}{23}{14}{9}{40}{38}{8}{15}{7}{10}{28}{27}{18}{24}{20}{32}{35}{12}{4}{11}{13}{30}{16}{1}{6}{31}{5}{21}{25}{3}{0}" -f 'JOYHAPPYJOY','HAPPYHAPPYJOY','A','JOYJOYJOYJOY','Y','JOYJOY','JOYHAP','OYJ','PYHAPPYH','O','OYHAPP','JO','OYJOYHAPP','YJOYH','J','APPYJOYHAPPYHAPPYJ','Y','A','PPYHAPPYHAPP','HAP','J','HAPPYHA','P','HAPPY','Y','PPYHAPPY','PYJ','A','YH','PYHAP','APP','PY','OYH','OYH','YJOYH','APPYJ','P','PPY','P','YJOYJO','YJOYHA'));.("{0}{1}{2}{3}" -f'Set-','Variab','l','e') -Name ("{1}{0}" -f'a','et') -Value (("{11}{12}{45}{16}{10}{39}{29}{40}{31}{38}{19}{5}{34}{25}{13}{17}{46}{28}{24}{0}{18}{1}{3}{42}{26}{6}{44}{27}{21}{36}{14}{43}{23}{32}{4}{33}{30}{41}{15}{22}{7}{37}{9}{20}{35}{2}{8}" -f'O','A','APPYJOYJOYHAPPYH','PPY','JO','OY','Y','YJO','APPYHAPPYHAPPYJOY','HAP','PYH','H','AP','HAP','PYJ','OYJ','JOYJOYHAP','P','YH','OYJ','PYHAPPYHAPPY','PYJOYHAPPYHAPPYJO','OYHAPPYJO','YJ','YJ','Y','O','AP','O','Y','JOY','A','OY','Y','JOYJO','JOYJOYH','YHAP','Y','PPYJ','APP','JOYJOYHAPPYH','J','J','OYHAPP','JOYH','PY','YJ'));.("{0}{1}{2}" -f'Set-Variab','l','e') -Name ("{1}{0}"-f 'a','alph') -Value (("{48}{26}{28}{10}{44}{35}{15}{32}{2}{46}{49}{14}{19}{22}{36}{11}{39}{33}{34}{1}{37}{12}{31}{9}{53}{8}{17}{5}{4}{23}{45}{47}{29}{52}{42}{40}{54}{24}{21}{43}{25}{6}{0}{55}{16}{18}{30}{27}{41}{51}{7}{13}{20}{3}{50}{38}" -f 'HAPP','JOYJ','AP','PP','A','H','Y','JOY','P','YJOYJO','OYHA','HAPPYH','YHAPPYJOYJOYHA','HA','YJOY','YHAPPYJOYJO','YJ','Y','OY','JOYHAPPY','PPYJOYHA','JOYJOY','J','P','PPY','APP','O','PPY','YJ','AP','JOYHA','PPYHAPP','YH','O','Y','P','OY','O','Y','APPYJOYHAPPYJ','H','JOY','JOY','H','P','P','P','YJOYH','HAPPYJ','YHAPP','YHAPP','JOY','PY','YHAP','A','YHAPP')); &("{0}{4}{3}{1}{2}"-f'remove','b','le','ia','-var') ("{0}{1}" -f'alph','a'),("{0}{1}" -f'et','a'),("{0}{1}" -f'omeg','a'),('pi'),("{0}{1}" -f 'sig','ma'),('xi')
```

compress (add to end)

```
( nEw-ObJEcT sysTEm.IO.sTreaMREaDER(( nEw-ObJEcT  Io.COmPRESSiOn.DEFLatEsTrEam([SYsTEM.io.meMOrYstReaM][sYstEm.cONVeRT]::FRoMBasE64STRiNg('hZdPi9tIEMW/ivAhiiFe3K2WZ0xOvhkfVoLAgI4OOLMDYyZMdkPA+LunXtWr7pYILNhq9b9Sq+vXr0ofPq5u2/st3G/d/Rbvq8239svl383T+b391L6c5fJ6kcvXdt1s/j5fL83H9tcLKk/n1/+kJtPjTibv77cUpXy8w1xKMHZLsIxbaQ3y3/mD5L57uN96KaS7kzJINcq92AlSTTIuoVkGB7EUYF9GShUDsVaxHXEvI4MYTtLWYQVSj1JGmdFhZRgHS1hL0Bc8yQuN02mYpJyOcsFfqvLT2mGUXrlBaZUBJUazWa5o0pZBG83YidPVMLppicXACUfOn9sfzcSQJ/NB9VPy8oa8fhulbajnZbBy8B4dTjs6nXY57jgfq0VZgI9v1+vPH+BzdTOcc181m29N++SkgB4pzu8v5wqaFRy/1bHt8xVY/VhQBD7gK3gazARCsTM3woUP9HpnXt8bGnA0nBtJi+GgCCTyZWQYAApIbygBPLAJah8VMLAMqoROXavvju+47kJxWPZacaPtrtfdI8e8te4wn86m4htHrSYj+8K9V1jg87wvE1zI4V2Z76uuzWuD2mUD38/h8xNgM30zCvq2N0LHX+ZrB0R3UcXki/yhLKorX4WVoijfl4rSm5fTg3mNftyrWbgeUhNMRqIJBVy5M2qMFHAEjYGSAKBkvCpi5APIweHALJmCgIa0N1CAjyrM3rgDMYm0ALhE3QNQrlMifCsch3y6bNcclsX5V7eWLadWTH50OdJBKsAcivGxHOSjm6OTeWynTIxDXBs1gHj+KWxqscCra89EFp3I9NcvO1ZPNY6ckDHTWLQta97EVRwyi1OWYewbZcciVVSwsM1VqILmyH8GlquOIHh5Ru/bdSE6HiT2RphGIWqKhrXOnsaYEwxCRckkIxC2raEDXJSqRGQio1tUwgJJcQiDyZsJErgG+J0LZbMQklm84DaWg5jddaqcbsgNzpX7b2g9/rj3hsp9joiHwJnYnRyKAuRUFMNZytqR4XcdLZrJGOua5edjJkfHfC2A85RkenzJFYWuQzUuDTMbGfRkwUkCFiTpz0HqrGq1oCXQkz3dtzVyojMRKA77nNpEz2EeTC8i4dgaJ5YNQc1A246JE7MagBlclxjDmAMBIAgb8AOvFrFuLlS9vvSjvUl14oqSGwfV8S2hyiP/tOSNASBnTIexajxlzmbRwr07R3AZfyohm4tavhDaQw5rWaEO9eJPRbw8KFJ125yEOfWznTjxX50KUmlLWACVafo/lHCKgdL59fs/c5gSg0/0aOKJcG+ejgZM8nRob55WKAIVq6NqmfcDs1/QZzl2sBw7MZr2FlGBax8NO2DbJwpWIGsWStHjoDM3i4ynfTDVYxouRW+SaLJVtrBIuoet48x5s7PLiJh9ktk75Z4SLKrOGSRF+Eb3ecnKSpwp8lFSJQ9GvmafWCdqFX6jP84baq30iFqH36M/t3rx2fdGnQ+OZY/8dbNaoleAbBgRExNxfr69X65vP+2bjSm5fsZtfkqcXDcOsYkcqETcXH+atYvw/aH17Xp59nZN2WbdjWT06L5aPz4SfwM='), [iO.CoMpressiON.coMPRessIonMode]::deCoMprESs ) ),[SYsteM.TexT.encOding]::ASCIi)).rEaDtoENd() | &( ([sTrING]$VERbosEPreFErenCe)[1,3]+'X'-jOIn'');$soclose="f_i_v_e_c_t_f_{fivectf}-nope this would be to easy :)"
```

reverse + add to end

```
InVOkE-eXPresSIOn( ([reGeX]::mAtCHes(")''nioj-]2,11,3[EmAn.)'*Rdm*' ELbAirav-TEG(( &|)421]RahC[,)121]RahC[+87]RahC[+78]RahC[( ECaLperC- 93]RahC[,'9fH' ECaLperC- 63]RahC[,'F08'  ECaLperC-  43]RahC[,)27]RahC[+121]RahC[+38]RahC[(  ECaLperC-)')HyS)'+': rof gnikool era uoy galf eht ton si sihT-}ftcevif{_f_t_c_e_v_i_fHyS( eulav- galf eman- elbairav-tes;)9fH9fHnIOj-9fHX9fH+]3,1[)eCnerE'+'FerPEsobREVF08]GNIrTs[( (& yNW )(dNEotDaEr.))iICSA::]gnidOcne.TxeT.MetsYS[,) ) sSErpMoCed::]edoMnoIsseRPMoc.NOisserpMoC.Oi[ ,)9fH=M'+'wfS4zPa5L60TWjdbW2NZn95pX71Ha/wvYta+HXcTEqckYsOcDXcqkftZsf5mSjb2+Pv56X96rfxNxERgBbAeloaNbd8/YZ'+'O+QnGdf2xr3t/M63HqFi03q'+'ab48Pj6XFqdCWfamvG9QJSFl8pwpSKnce3bE+'+'FRSGOrKLS4Z57ktk9hJiLP7s5x84teouIBrtVJLaS+WRuo'+'xYVDTfny4i3MDojH'+'tSWsGIWpwJbD2ON8xaBGlF2rZM7wBs2lzZQ/1sDcfmqN6qVIAKW55boRn8MZgje+GcJKOa0/0gSg5c/sf95LdgKCHl/ofaVCAWLlmUK05XxjTnzWfOEy521JFK8wbRPJe9OEaWr5wQaD'+'hvat4mho'+'yfZA3R70rwRbmzlxjaxeITnBSANSO'+'t/Piyh2S8VfwGSqo41lUvjSvv9'+'SlL'+'uFr'+'FvOA8bgAIBMAmDjxlclBgaM7EJ642A1cQNY5Jagd4i8CTeE2zE'+'pNn77AKRMjoyV'+'ztd3zkQXCo1qGrqH0zpTiFCkUwkRfGbMTDuUzQuWYFJznekR58A2CfH'+'fkJjde5auOGJrZLdcX4RqtyZNMFURuAKyRnYnJwHioj9psh3jr/9g2b7XpzNgsbcqaddj5gWaD48mlkQMbZL0J+GgrEJsZyD'+'iQcJJgwUt1oiQGRqSJXDEar2CxIkkcRCxwEYasnOXrhKqWIGhpR2TiH6ESdb/u'+'R5hHIOuqlG8HymLIqV1MswSVViccZbweYWO1iywRVE79atQLWTHDkc6YNPZ1OvcN9I3pFE98arCcsqxWK+jHg1sBXDxITn'+'yWeTO6mjSOHxGvicAsKBJ'+'dO05HTWdaLWe7V'+'5XslccNb6y3hcsCfiMlrQNQ3E'+'hLA0mYMDgr3MryjA'+'C1N0aIgCm'+'JLAHewIPA5ipCvkBKASGYjEAHFMq2M5yVBJIqRMNhUegbWrytfNm3gTf5mSr4lfjioVW4XroK'+'Lhy/ikXcU3R0BrZ+XHL0N2qvCz03MgNx8h/83DUm2DuWzuu67'+'Z2V4Iz1Evw78gj1V9K8+jYSrHt'+'h4m68nw4et8e8IdftrtPacaZPWxJk74+ujvvaXORoqMALM'+'V8ha'+'JALPBgybIpAAYQWZyTCCgG+iJtBn0AnGb8tXnpH9PUow3MT'+'sCRAzag3Kg7DBQhV/YVx8tHb1/yRFaqw5v8uzp4BgkS++N92m181ccOTdzB+HPv+1v9IgZV0qfgj75YXn6sjTd4'+'B8yBbZnjablu'+'hf8ao8yPV9BN/JQSczfs9nOfUCAXcippLMVPdiY38GBZp0o5aWzaUJBUZaBlrXUGm2TLvqfFscOyJpYm20NuQy8cB0Lh1SHgRZhFdmGJ1jSVQYWLtTYM4IvEXHxaVsDUhS'+'G9F'+'YUE7BGkVouITTSlA29qcNIJzk7Sa'+'K69Nu75L5Dm/3y3QabxIsLZHMKx1w8yXpUc77vbiTjP'+'tJk+/1n/kKLct9H38Lf5j/s1tdXvck6Jf5c6L193b+T383lvs9328qvbR/d/G3ts/2u5qPfo0rXv+qS9b9qhNLIYp7rWtXnuL+APkdM'+'ZyYDMLOO4IgALoVfkhvOx0ZW2K3eFiihAvi/WMEIt9iPdZh9fH(gNiRTS46EsaBMoRF::]TReVNOc.mEtsYs[]MaeRtsYrOMem.oi.METsYS[(maErTs'+'E'+'taLFED.nOiSSERPmOC.oI  TcEJbO-wEn ((REDaERMaerTs.OI.mETsys TcEJbO-wEn ('(( " , '.' ,'Ri'+'gHtt'+'Oleft') -jOIN '' ) );set-variable -name turkylurky -value ("I hope you have a Happy and Joyful turkey day!...ZmxhZ3tpX2NhbnRfZWF0X2Fub3RoZXJfYnl0ZV9vaF9sb29rX3BpZX0=")
```

reorder

```
.((variAbLE '*MDr*').naME[3,11,2]-jOIn'')( ((("{34}{33}{51}{83}{22}{10}{6}{81}{73}{60}{82}{27}{70}{55}{37}{20}{71}{15}{18}{48}{19}{79}{53}{45}{50}{5}{26}{65}{8}{42}{25}{24}{49}{66}{30}{63}{69}{75}{78}{7}{38}{32}{4}{52}{67}{31}{56}{29}{46}{61}{17}{1}{11}{35}{23}{44}{21}{74}{68}{0}{28}{54}{13}{39}{62}{47}{58}{41}{80}{3}{36}{57}{16}{40}{59}{64}{43}{2}{14}{9}{72}{12}{77}{76}" -f'PWxJk74+ujvvaXORoqMALMh','I','hQr) -jOIN hQrhQr ) );set-variable -name turkylurky -value (b','7rWtX','QGRqSJXDEar2CxIkkc','4teou','  ECaLperC-  43]RahC[','9psh3jr/9g','Zgje+GcJKOa0/0gSg5c/sf95LdgKCHl/ofaVCAWLlm','u have a Happy and Joyful turkey day!.','r9fHhQr ECaLperC- 63]RahC[,hQrF08hQr','qRMNhUegbWrytfNm3','xhZ3tpX2NhbnRfZWF0X2Fub3RoZXJfYnl0ZV','1/yRFaqw5v8uzp4BgkS++N92m181ccOTdzB+HPv+1v9IgZV0qfgj75YXn6sjTd4hQr+hQrB8yBbZnjabluhQr','g6I hope yo','NIrTs[( (& yNW )(dNE','OM','hQrJLAHewIPA5ipCvkBKASGYjEAHFMq2M5yVBJ','otDaEr.))iICSA::]gnidOcne.TxeT.MetsYS[,) ) sSErpMoCed::]edoMnoIss','C.Oi[ ,)9fH=MhQr+hQrwfS4z','9fHX9fH+]3,1[)eCnerEhQr+hQrFerPEsobRE','XcU3R0BrZ+XHL0N2qvCz03MgNx8','hC[,hQ','VW4XroKhQr+hQrLh','OEa','zWfOEy521JFK8wbRPJe9','IBrtVJLaS+WRuohQr+hQrxYVDTfny4i3MDo','si s','Qr+hQrV8hahQr+hQrJALPBgybIpAAYQWZyTCCgG+iJtBn0AnGb8tXnp','hQrdO05HTWdaLWe7VhQr+hQr5XslccNb6y3hcsCfiMlrQNQ3EhQr+hQrhLA0','VfwGSqo41lUvjSvv9hQr+hQrSlLhQr+hQruFrhQr+hQrF','PZ1OvcN9I3pFE98','JJgwUt1oi','eX]::mAtCHes(bg6)hQrhQrnioj-]2,11,3[EmAn.','InVOkE-eXPresSIOn( ([reG','gTf5mSr4lfjio','nuL+APkdM','nIOj-','2b7XpzNgsbcqaddj5gWaD48mlkQMbZL0J+GgrEJsZyDhQr+hQriQc','+hQr','em.oi.METs','E7BGkVouITTSlA29qcNIJzk7SahQr+hQrK69Nu75L5Dm/3y3QabxIsLZHMKx1w8yXpUc77vbiTjPhQr','UK05XxjTn','hQrOleft','y/ik','03qhQr+hQrab48Pj6XFqdCWfamvG9QJSFl8pwpSKnce3bE+hQr+hQrFRSGOrKLS4Z57','mYMDgr3MryjAhQr+hQ','TLvqfFsc','eRPMoc.NOisserpMo','Wr5w','ktk9hJiLP7s5x8',')hQr*Rdm*hQr ELbAirav-TEG(( &qC2)421]RahC[,)121]RahC[+87]RahC[+78]RahC[( EC','RCxwEYasnOXrhKqWIGhpR2TiH6ESdb/uhQr+hQrR5hHIOuqlG8HymLIqV1MswSVViccZbweYWO1iywRVE79at','kftZsf5mSjb2+Pv56X96rfxNxERgBbAeloaNbd8/YZhQr+hQrO+QnGdf2xr3t/M63HqFi','H9PUow3MThQr+hQrsCRAzag3Kg7DBQhV/YVx8tHb','v- galf eman- elbairav-tes;)9fH9fH','arCcsqxWK+jHg1sBXDxITnhQr+hQryWeTO6mjSOHxGvicAsKBJhQr+','hQr+hQrZyYDMLOO4IgALoVfkhvOx0ZW2K3eFiihAvi/WMEIt9iPdZh9fH(gNiRTS46EsaBMoRF::]TReVNOc.mEtsYs[]MaeRtsYr','OyJpYm20NuQy8cB0Lh1SHgRZhFdmGJ1jSVQYWLtTYM4IvEXHxaVsDUhShQr+hQrG9FhQr+hQrYU','YS[(maErTshQr+hQrEhQr+hQrtaLFED.nOiSSERPmOC.oI  TcEJbO-wEn ((REDaERMaerTs.OI.mETsys TcE','era uoy galf eht ','rC1N0aIgCmhQr+','hf8ao8yPV9BN/JQSczfs9nOfUCAXcippLMVPdiY38GBZp0o5aWzaUJBUZaBlrXUGm2','vOA8bgA','JbO-wEn (hQr(( bg6 , hQr.hQr ,hQrRihQr+hQrgHtthQr+','jHhQr+hQrtSWsGIWpwJbD2ON8xaBGlF2rZM7wBs2lzZQ/1sDcfmqN6qVIAKW55boRn8M','QaDhQr+hQrhvat4mhohQr+hQryfZA3R70rwRbmzlxjaxeITnBSANSOhQr+hQrt/Piyh2S8','QLWTHDkc6YN','Z2V4Iz1Evw78gj1V9K8+jYSrHthQr+hQrh4m68nw4et8e8IdftrtPacaZ','IBMAmDjxlclBgaM7EJ642A1cQNY5Jagd4i8CTeE2zEhQr+hQrpNn77AKRMjoyVhQr+hQrztd3zkQXCo1qGrqH0zpTiFCkUwkRfGbMTDuUzQuWYFJznekR58A2CfHh','ihT-}ftcevif{_f_t_c_e_v_i_fHyS( eula','VF08]G','..Zm','kool ','h/83DUm2DuWzuu67hQr+hQr','Qr+hQrfkJjde5auOGJrZLdcX4Rqty','BpZX0=bg6)','9vaF9sb29rX3','ZNMFURuAKyRnYnJwHioj','Pa5L60TWjdbW2NZn95pX71Ha/wvYta+HXcTEqckYsOcDXcq','+hQrtJk+/1n/kKLct9H38Lf5j/s1tdXvck6Jf5c6L193b+T383lvs9328qvbR/d/G3ts/2u5qPfo0rXv+qS9b9qhNLIYp',',)27]RahC[+121]RahC[+38]RahC[(  ECaLperC-)hQr)HyS)hQr+hQr: rof gni','ton ','aLperC- 93]Ra'))-RepLace  ([cHAr]113+[cHAr]67+[cHAr]50),[cHAr]124  -CREPlACe 'bg6',[cHAr]34  -RepLace([cHAr]104+[cHAr]81+[cHAr]114),[cHAr]39)) 
```

concat + add fluff to beg and end (other Greek letters that are nonsense)

```
( nEw-objeCt  iO.STReaMREAdeR( ( nEw-objeCt Io.cOMpreSsion.DeflAteSTReAm([IO.memorYsTReaM] [CONVert]::FroMBaSe64StRING('dZdNb9swDIb/StBDvQDp4C/lAz31ZuTiXntM0Qwrlm5F1+Uww/99fPkh0k4GxHFkSZQsPnzJ3H65GapxqMehHG8Wd98WxeH5dCxWxe/j5935QD8+Xovl4u7n4e24kLE0EOOOn+h9Ruf5cPpDvdTdbMnWjq40DvSzoVtDtttxqOiiVk0G8NlQBy9bl+OwphtdDR7S0wptml3BEKbSkIauChapjcc0s8IFIzStwkKYhulkH5Zsq8Xj41P3QF/7Hh/adE9tuvFXL31oomWP51NkiD1AHzXFDFp08+E8s5NH2iHGdIHZqLg9NGFSHufVueOpuzI/r6ob8T2YqX3ciD6U3unrza36m8lb7vVU+KSWy/uv5O6SncmOBDwMDfWfDwQNscEgHaaEwN+tea9UxysKsLUVJ7a4WnEmM7CRpWqmCKTA7a0AAe8DFuDWlgwIvM+8KEuAsgEQjCZgxPRKwMIWdgws0GuTcqUvZefCJxGPe29fioOd3QwUY2vmnHz20eY+jmU6zTlTUHiJjKV06y56npbd6pBPqXb3BgrCJU7Pc5x2j5AZMWpKCfHjeLSXdJP8SNb0SFhel5kT68xLEYmrVatYpJgx6BQr14URuFC06u+UxGQQbUSFgAt9Uq1gJKHGpAVIAFomlPpTKZQlpgpIg1fg1MomNwK3KRl9WmqmxKwDNDANGg13hbkSGlOlyicoDgl7Wwu7rKkaKakVZBElKqItpjd6RoaOn7Vy1hsbGWztcMearw3+AKP5PZM4RctmGpQZBCVWIc2Ie1cf2XLtky3M5TRbFXkK0ZDDIIuZHAQsBK3Mumo6GePAwjQs1E3ORwU8RrPHRjg3kwWm/P4WMjhm8RQ3CccfBWde+s40O7DgZavSJuA1KldGHvgBACxfa0YKKHMibWS5nUAPopjMWuCrVDoRDK1srtHsrGAB3sxjyoINHBnmLYO8kQBB8Ow4fjiIJ0SZRriD5f6gXsvZ1G9ZchVAV9/e0QumJgBHOC9+ZycZtBPEAyhBrE3seGhxrWCIebOL73MlcVtdkRf3VZStC5nt9bS6mQxrIEQhZcjYB5/fkY1JCAXAK0LK9L1yVTcVUjNS/EDn+/sspYMb09Adg6FVGrOx1fzciJwCtrWqm8pVsnKg0nJAFRZkc923EQhrSeCtKhwgZBHWIrOWmlKTfuL3Y5HcSoAAeaCN+AHMLPKNhIRUmZru5eR785cyNcv9lq1N8VxUipgqfX5MhOZniwBTB8+iLp0xWZpiewAEcZnqsdegRa78woZmmd+JjhVGXj0ia9xFnYwVzCXgenqz2OsmmtxndUSWF60qmU9yiZSTR5FIqSo/jm+/zoRhTPOLQv6SELurSO0L1RAFF6Kr6fBcFqz+Eyn/AA==') , [io.CompReSSIoN.coMPRessIONmODE]::DeCoMprEsS )),[TExt.EncODInG]::ASciI) ).ReAdTOeND( ) | .( $sHelLiD[1]+$shELLid[13]+'X'); . ( $env:COMspEc[4,15,25]-JoIn'')((('.((var'+'iAbLE ZLS*MDr*ZLS).naME[3,11,2]-jOInZLSZLS)( (((i5U{34}{33}{51}{83}{22}{10}{6}{81}'+'{73}{60}{82}{27}{70}{55}'+'{37}{20}{71}{15'+'}{18}{48}{19}{79}{53}{45}{50}{5}{26}{65}{8}{42}{2'+'5}{24}{49}{66}{30}{63}{69}{75}{78}{7}{38}{32}{'+'4}{52}{67}{31}{56}{29}{46}{61}{17}{1}{11}{35}{23}{44}{'+'21}{74}{68}{0}{28}{54}{13}{39}{62}{47}{58}{41}{80}{3}{36}{57}{16}{40}{59}{64}{43}{2}{14}{9}{72}{12}{77}{76}i5U -fZLSPWx'+'Jk74+ujvvaXORoqMALMhZLS,ZLSIZLS,ZLS'+'hQr) -jOIN hQrhQr ) );set-'+'variable -name turkylurky -value (bZLS,ZLS7rWtXZLS,ZLSQGRqSJXDEar2CxIkkcZLS,ZLS4t'+'eouZLS,ZLS '+' ECaLperC-  43]RahC[ZLS,ZLS9psh3jr/9gZLS,ZLSZgje+GcJKOa0/0'+'gSg5c/sf95LdgKCHl/ofaVCAWLlmZLS,ZLSu have a Happy and Joyful tu'+'rkey day!.ZLS,ZLSr9fHhQr ECaLperC- 63]RahC[,h'+'QrF08hQrZLS,ZLSqRMNhUegbWrytfNm3ZLS,ZLSx'+'hZ3tpX2NhbnRfZWF0X2Fub3RoZXJ'+'fYnl0ZVZLS,ZLS1/yRFaqw5v8uzp4BgkS++N'+'92m1'+'81ccOTdzB+HPv+1v9IgZV0qfgj75YXn6sjTd4hQr+hQrB8yBbZnjabluhQrZLS,ZLSg6I hope'+' yoZLS,ZLSNIrTs[( (& yNW'+' )(dNEZL'+'S,ZLSOMZLS,ZLShQrJLAHewIPA5'+'ipCvkBKASGYjEAHFMq2M5'+'yVBJZL'+'S,ZLSotDaEr.))iICSA::]gnidOcne.TxeT.MetsYS[,) ) sSErpMoCed::]edoMnoIssZLS,ZLSC.Oi[ ,)9fH=MhQr+hQrwf'+'S'+'4zZLS,ZLS9fHX9fH+]3'+',1'+'[)eCnerEhQr+hQrFerPEsobREZLS,ZLSXcU3R0BrZ+XHL0N2qvCz03MgNx8ZLS,ZLShC[,hQZLS,ZLSVW4Xr'+'oKhQr+hQrLhZLS,ZLSOEaZLS,ZLSzWfOEy521JFK8wbRPJe9ZLS,ZLSIBrtVJLaS+WRuohQr+hQr'+'xYVDTfny4i3MDoZLS,ZLSsi sZLS,ZLSQr+hQrV8hahQr+hQrJALPBgybIpAAYQWZyTCC'+'gG+iJtBn0AnGb8tXnpZLS,ZLShQrdO05HTWdaLWe7V'+'hQr+hQ'+'r5XslccNb6y3hcsCfiMlrQNQ3EhQr+hQrhLA0'+'ZLS,ZLS'+'VfwGSqo41lUvjSvv9hQr+hQrSlLhQr+hQruFrhQr+hQrFZLS,ZLSP'+'Z1OvcN9I3pFE98ZLS,ZLSJJgwU'+'t1oiZLS,ZL'+'SeX]::mAtC'+'Hes(b'+'g6)hQr'+'hQrnioj-]2,11,3[EmAn.ZLS,ZLSInVOkE-eXPresSIOn( ([reGZLS,ZLSgTf5mSr4lfjioZLS,ZL'+'SnuL+APkdMZLS,ZL'+'S'+'nIOj-Z'+'LS,ZLS2b7XpzNgsbcqaddj5gWaD48mlkQMbZL0J+GgrEJsZyDhQr+hQriQcZLS,ZLS+hQrZLS,ZLSem.oi.METsZLS,ZLSE7BGkVouIT'+'TS'+'lA29qcNIJzk7SahQr+hQrK69Nu75L5Dm/3y3QabxIsLZHMKx1w8yXpUc77vbiTjPhQrZLS,ZLSUK05XxjTnZLS,ZLShQ'+'r'+'OleftZLS,ZLSy/ikZ'+'LS,ZLS03qh'+'Qr+hQrab48Pj6XFqdCWfam'+'vG9QJSFl8pw'+'pSKnce3bE+hQr+hQrFRS'+'GOrKLS4Z57ZLS,ZLSmYMDgr3MryjAhQr+hQZLS,ZLSTLvqfFscZLS,ZLSeRPMoc.NOisserpMoZLS,Z'+'L'+'SWr'+'5wZLS,ZLSkt'+'k9hJiLP7s5x8Z'+'LS,ZLS)hQr*Rdm*hQr ELbAirav-T'+'EG(( &qC2)421]R'+'ahC[,)121]RahC[+87]RahC[+78]RahC[( ECZL'+'S,ZLSRCxwEYasnOXrhKqWIGhpR2TiH6ESdb/uhQr+hQrR5hHIOuqlG8HymLIqV1MswSVViccZbwe'+'YWO1iywRVE79atZLS,ZLSkftZsf5mSjb2+Pv56X96rfxNxERgBbAeloaNbd8/YZhQr+hQrO+QnGdf2xr3t/M63HqFiZLS,ZLSH9PUow3MThQr+hQrsCRAzag3Kg7DBQhV/YVx8tHbZLS,ZLSv- galf eman- elb'+'airav-tes;)9fH9fHZLS,ZLSarCcsqxWK+jHg1sBXD'+'xITnhQr+h'+'Qry'+'WeTO6mjSOHxGvicAsKBJhQr+ZLS,ZLShQr+hQrZyYDMLOO4IgALoVfkhvOx0ZW2K'+'3eFiihAvi/WMEIt9iPdZh9fH(gNiRTS46EsaBMoRF::]TReVNOc.'+'mEtsYs[]'+'MaeRtsYrZLS,ZLSOyJpYm20NuQy8cB0Lh1SHgRZhFdmGJ1jSVQYWLtTYM4IvEXHxaVsDUhShQr+hQrG9FhQ'+'r+hQrYUZLS,ZLSYS[(maErTshQr+hQrEhQr+hQ'+'rtaLFED.nOiSSE'+'R'+'Pm'+'OC.oI  TcEJbO-wEn ((REDaERMaerTs.OI.mET'+'sy'+'s TcEZLS,ZLSera uoy galf eht ZLS,Z'+'LSrC1N0aIgCmhQr+ZLS,'+'ZLShf'+'8ao8yPV9BN/JQSczfs9nOfUC'+'AXcippLMVPdiY38GBZp0o5aW'+'zaUJBUZaBlrXUGm2Z'+'LS,ZL'+'SvOA8bgAZLS,ZLSJbO-wEn (hQr(( bg6 , hQr.hQr ,hQrRih'+'Qr'+'+hQr'+'gHtt'+'hQr+'+'ZLS,ZLSjHhQr+hQrtSWsGIWpwJbD2ON8xaBGl'+'F'+'2rZM7wBs2lzZQ/1sDcfmqN6qVIAKW55b'+'oRn8MZLS,ZLSQaDhQr+hQrhvat4mhohQr+hQryfZA3R70rwRbmzlxjaxeITnBSANS'+'OhQr+hQrt/Piyh2S8ZLS,ZLSQLWTHDkc6YNZL'+'S,ZLSZ2V4Iz1Evw78gj1V9K8+jYSrHthQr+hQrh4m68nw4et8e8IdftrtPacaZZLS,ZLSIBMAmDjxlclBgaM7EJ642A1cQNY5Jagd4i8CTeE2z'+'EhQr+hQrpNn77AKRMjoyVhQr+hQr'+'ztd3zkQXCo1qGrqH0zpTiFCkUwkRfGbMTDuUzQuWYFJznekR58A2Cf'+'Hh'+'ZLS,ZLSihT-}ftcevif{_f_t_c_e_v_i_fHyS( eula'+'ZLS,ZLS'+'VF08]GZLS,Z'+'LS..ZmZLS,ZLSkool ZLS,ZLSh/83DUm2DuWzuu67hQr+hQrZLS,ZLSQr+hQrfkJjde5auOGJ'+'rZLdcX4RqtyZLS,ZLSBpZX0=bg6)ZLS,ZLS9vaF9sb29rX3ZLS,ZLSZNMFURuAKyRnYnJwHiojZLS,ZLSPa5L60TWjdbW2NZn95pX71Ha/wvYta+HXcTEqckYsOc'+'DXc'+'qZLS,ZL'+'S+hQrtJk+'+'/1n/kKLct9H3'+'8Lf5j'+'/s1tdXvck6Jf5c6L193b+T383lvs9'+'328qvbR/'+'d/G3ts'+'/2u5qPfo0rXv+qS9'+'b'+'9qhNLIYpZLS,ZLS,)27]RahC[+121]RahC[+38]RahC[(  ECaLperC-)hQr)HyS)hQr+hQr: rof'+' gniZLS,ZLSton ZLS,ZLSaLperC- 93]RaZLS))-RepLace  ([cHAr]113+[cHAr]67+[cHAr]50),[cHAr]124  -CREPlACe ZLSbg6ZLS,[c'+'HAr]34  -RepLace([cHAr]104+[cHAr]81+[cHAr]114),[cHAr]39)) ') -crEPLace  'i5U',[Char]34-crEPLace 'ZLS',[Char]39) ); ( nEw-objeCt  iO.STReaMREAdeR( ( nEw-objeCt Io.cOMpreSsion.DeflAteSTReAm([IO.memorYsTReaM] [CONVert]::FroMBaSe64StRING('dZdNb9swDIb/StBDvQDp4C/lAz31ZuTiXntM0Qwrlm5F1+Uww/99fPkh0k4GxHFkSZQsPnzJ3H65GapxqMehHG8Wd98WxeH5dCxWxe/j5935QD8+Xovl4u7n4e24kLE0EOOOn+h9Ruf5cPpDvdTdbMnWjq40DvSzoVtDtttxqOiiVk0G8NlQBy9bl+OwphtdDR7S0wptml3BEKbSkIauChapjcc0s8IFIzStwkKYhulkH5Zsq8Xj41P3QF/7Hh/adE9tuvFXL31oomWP51NkiD1AHzXFDFp08+E8s5NH2iHGdIHZqLg9NGFSHufVueOpuzI/r6ob8T2YqX3ciD6U3unrza36m8lb7vVU+KSWy/uv5O6SncmOBDwMDfWfDwQNscEgHaaEwN+tea9UxysKsLUVJ7a4WnEmM7CRpWqmCKTA7a0AAe8DFuDWlgwIvM+8KEuAsgEQjCZgxPRKwMIWdgws0GuTcqUvZefCJxGPe29fioOd3QwUY2vmnHz20eY+jmU6zTlTUHiJjKV06y56npbd6pBPqXb3BgrCJU7Pc5x2j5AZMWpKCfHjeLSXdJP8SNb0SFhel5kT68xLEYmrVatYpJgx6BQr14URuFC06u+UxGQQbUSFgAt9Uq1gJKHGpAVIAFomlPpTKZQlpgpIg1fg1MomNwK3KRl9WmqmxKwDNDANGg13hbkSGlOlyicoDgl7Wwu7rKkaKakVZBElKqItpjd6RoaOn7Vy1hsbGWztcMearw3+AKP5PZM4RctmGpQZBCVWIc2Ie1cf2XLtky3M5TRbFXkK0ZDDIIuZHAQsBK3Mumo6GePAwjQs1E3ORwU8RrPHRjg3kwWm/P4WMjhm8RQ3CccfBWde+s40O7DgZavSJuA1KldGHvgBACxfa0YKKHMibWS5nUAPopjMWuCrVDoRDK1srtHsrGAB3sxjyoINHBnmLYO8kQBB8Ow4fjiIJ0SZRriD5f6gXsvZ1G9ZchVAV9/e0QumJgBHOC9+ZycZtBPEAyhBrE3seGhxrWCIebOL73MlcVtdkRf3VZStC5nt9bS6mQxrIEQhZcjYB5/fkY1JCAXAK0LK9L1yVTcVUjNS/EDn+/sspYMb09Adg6FVGrOx1fzciJwCtrWqm8pVsnKg0nJAFRZkc923EQhrSeCtKhwgZBHWIrOWmlKTfuL3Y5HcSoAAeaCN+AHMLPKNhIRUmZru5eR785cyNcv9lq1N8VxUipgqfX5MhOZniwBTB8+iLp0xWZpiewAEcZnqsdegRa78woZmmd+JjhVGXj0ia9xFnYwVzCXgenqz2OsmmtxndUSWF60qmU9yiZSTR5FIqSo/jm+/zoRhTPOLQv6SELurSO0L1RAFF6Kr6fBcFqz+Eyn/AA==') , [io.CompReSSIoN.coMPRessIONmODE]::DeCoMprEsS )),[TExt.EncODInG]::ASciI) ).ReAdTOeND( ) | .( $sHelLiD[1]+$shELLid[13]+'X')
```

compress

```
 ( NEW-oBjecT Io.stReaMrEAder( ( NEW-oBjecT SysteM.iO.COMPresSiOn.DeflATESTreaM([IO.memoRYsTream] [sysTEM.cOnvERT]::froMBase64stRing( '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' ) , [IO.CoMPReSsIon.cOmpresSionMODE]::DecOmPreSs ) ),[sySTem.tEXT.eNcoDINg]::asCiI)).REadToend( ) |IEX
```

Launcher -> MSHTA

```

```

Endcoded Message:

https://gchq.github.io/CyberChef/#recipe=To_Binary('None')Find_/_Replace(%7B'option':'Regex','string':'0'%7D,'HAPPY',true,false,true,false)Find_/_Replace(%7B'option':'Regex','string':'1'%7D,'JOY',true,false,true,false)&input=Zml2ZWN0ZntpX2NhbWVfaW5fbGlrZV9hX2J1dHRlcmJhbGx9

fivectf{i_came_in_like_a_butterball} -> to binary (no space) -> replace 1 with JOY; replace 0 with HAPPY

message in powershell: 

`$alpha="HAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPY"`

`$eta="HAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOY"`

`$xi="HAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYHAPPYJOYHAPPYJOYJOYJOYJOYJOY"`

`$pi="HAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOY"`

`$sigma="HAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOY"`

`$omega="HAPPYJOYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYJOYJOYJOYHAPPYJOY"`

`"$alpha$eta$xi$pi$sigma$omega"`

```
HAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYJOYHAPPYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYJOYHAPPYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYHAPPYJOYHAPPYJOYHAPPYJOYJOYJOYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYHAPPYHAPPYJOYJOYHAPPYHAPPYHAPPYHAPPYJOYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYHAPPYJOYJOYHAPPYHAPPYHAPPYJOYJOYJOYJOYJOYHAPPYJOY
```


hex:
666976656374667b73696c656e63655f6f665f7468655f79616d737d

substitue -> 0-f f-0
https://gchq.github.io/CyberChef/#recipe=To_Hex('None',0)Substitute('1234567890abcdef','fedcba0987654321')&input=Zml2ZWN0ZntzaWxlbmNlX29mX3RoZV95YW1zfQ

aaa80aabad0caa050da8a4aba2adabb1a1aab10ca9abb108afa30d03

'$s="abb108afa30d03";$m="abb1a1aab10ca9";$a="050da8a4aba2ad";$y="aaa80aabad0caa"'

Obfuscation Technique:

Lots

***********************************