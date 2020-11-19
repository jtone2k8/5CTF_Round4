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
 &( $verboSEprEFeReNCE.tOsTRiNg()[1,3]+'x'-jOiN'') ( NEw-oBject  io.COMprESsIoN.deflATEStrEAM( [SyStem.Io.memORYstrEaM][sysTEm.COnVErT]::froMbase64STRiNg('U9NQqjaorTasrTaqVdJNUw9OLdFV11EPSyzKTEwCMnJS1TUVdP0Sc1MVYCqVFIDqEkFyBRmJINmwxJxSoDRQ3gRkDNQ8Y7B5SWZJBkClyUZAwiQlFUimmAOJJLNEY6BeTQA='), [SYsTem.IO.compResSion.cOmprEssIONMODE]::DECoMpReSs) | fOREach {NEw-oBject iO.sTrEaMReAder($_ , [sYStEm.tExt.ENcODinG]::AScIi )}|FoREAcH { $_.READtOeND()}) 
```

kappa

```
 ( NEw-OBJEct sYstem.Io.CompReSsIOn.DEflatEsTREaM([Io.meMORYsTReam] [systEM.CONVERt]::fRoMbase64STriNg( 'U9NQqjaqrTaorTaurTasVVLQTVNQT1TXUc9MTMpJBdLBqSW6YUC6SF1TQdcvMTdVAajDEKQDoragAKQ6OxEkHZaYUwqUByowAZtnCjYYqNgIrFjdINkAqNY8yTIlNRnIMEq0BJJmIP1JIK66piYA' ) ,[iO.COMpReSSion.cOmPrEsSionmodE]::DeCOMPrEss )| FoREAch-OBJEcT {NEw-OBJEct SYStEM.IO.StrEAMReaDEr( $_, [SYstEm.TExT.ENCoDiNg]::aSciI)} |FOreACH-objeCT {$_.REAdtOEnd( )} ) | &( $eNV:comspeC[4,26,25]-Join'')
```

xi

```
 .( ([STRInG]$VERbOSepREfErEnce)[1,3]+'x'-join'')(NEW-oBjEcT SYSTem.io.coMPrESsiON.dEFlATEsTReaM([iO.memOrYsTrEAm][coNVerT]::FROMBAsE64strInG('U9NQqjaorTasrTaqVVLQTVNQD04t0Q1T11FPLMpMBFJJOanqmgq6fom5qQoa6hWZIE5YYk4pkAfUalyL0K2bpg7SkJZkkALSlwjiJKYmGQBZieqamgA='), [sySTem.iO.cOMPRessioN.COMpreSSioNmODe]::DECOMPrEsS ) |fOreACH-OBJECt{ NEW-oBjEcT sYSTEM.iO.STReAMrEADER( $_, [SySTEM.TExt.EncODINg]::ASCIi )}).reADtoENd( ) 
```

pi

```
(NEW-ObJeCT sySTEm.iO.coMpResSIoN.DEFlATestREAM([Io.MeMoRySTreaM] [SYsteM.CoNVErT]::FROMbasE64StrIng('09NQqjasrTaorTaqrTauVVLQTVMPS1TXUQ9OLdEFUkWZQCIxKSdVXVNB1y8xN1VBQ70gE8QJS8wpBfKA+k3AmoFGGMKNMEhNAuozAxHJBokmIDNSLBItQTTQJE0A' ) ,[IO.cOmPReSSioN.coMpRESSioNmOde]::DecomPrESs) | forEACh { NEW-ObJeCT  Io.sTReamReaDer( $_,[sySTem.tEXT.eNcoDINg]::ASCII ) } |FOreacH { $_.REaDTOeND( )}) |IeX
```

sigma

```
.( $PSHOme[4]+$Pshome[30]+'X')(NEW-objeCt  Io.COMPRESSIoN.DeFLatEsTReAm( [iO.MeMoRYStreaM][conVeRt]::fRoMbAse64sTRIng('JYxLCoQwEAWvEty0ATPED+gp3Axk/6KZQdCNn1XTd7dDNsWDKt6nrrgT9sKtVMb9DCFSQ3tSfNPtAs6NrHEzjmS0LWHuLi22/4FsA/ZHtfpWeBDupZyWx8VH+EnzOEE5Yskbq7Ija18=' ) ,[sYsTEM.io.CoMpREsSION.CoMPreSSIONMOdE]::DECoMPrESS ) | % { NEW-objeCt sYsTEm.IO.streaMrEaDeR( $_,[SyStEM.teXt.EnCoDinG]::AsCIi) } | % { $_.ReADToeNd()} ) 
```

omega

```
 . ( $ENV:cOMspEc[4,15,25]-jOiN'')(new-oBjeCt IO.coMpREsSION.DEFLatEstReAM([IO.MeMORySTReAM][COnVERt]::FromBaSe64stRiNg('09NQqjaqrTaorTaurTasVdJNUw9LLMpU11FPykkFksGpJbpAKlFdU0HXLzE3VQGo3gCmMh8ok5uaDpYMS8wpBcpCjDMEG2cCMldJAajQGGwE0EwLIAHiJCcapCSmJlummKeoa2oCAA=='),[Io.CompREsSIoN.cOmPRESsIONMOdE]::deCOmPRESs) |% {new-oBjeCt Io.STrEAMreaDeR($_ , [sYStEM.texT.ENcODinG]::AscIi)}).REaDTOeND()
```

combine 
```
set-variable -name theta -value ("Somebody substituted the apple with a zucchini! Ano2AD1eATE7AnEsx3IuyD9pAC0="); .( ([STRInG]$VERbOSepREfErEnce)[1,3]+'x'-join'')(NEW-oBjEcT SYSTem.io.coMPrESsiON.dEFlATEsTReaM([iO.memOrYsTrEAm][coNVerT]::FROMBAsE64strInG('U9NQqjaorTasrTaqVVLQTVNQD04t0Q1T11FPLMpMBFJJOanqmgq6fom5qQoa6hWZIE5YYk4pkAfUalyL0K2bpg7SkJZkkALSlwjiJKYmGQBZieqamgA='), [sySTem.iO.cOMPRessioN.COMpreSSioNmODe]::DECOMPrEsS ) |fOreACH-OBJECt{ NEW-oBjEcT sYSTEM.iO.STReAMrEADER( $_, [SySTEM.TExt.EncODINg]::ASCIi )}).reADtoENd( );set-variable -name turkylurky -value ("take a byte o pie! bm9uZXNlbnNle2lfY2FudF9lYXRfYW5vdGhlcl9ieXRlX29oX2xvb2tfcGllfQ==");.( $PSHOme[4]+$Pshome[30]+'X')(NEW-objeCt  Io.COMPRESSIoN.DeFLatEsTReAm( [iO.MeMoRYStreaM][conVeRt]::fRoMbAse64sTRIng('JYxLCoQwEAWvEty0ATPED+gp3Axk/6KZQdCNn1XTd7dDNsWDKt6nrrgT9sKtVMb9DCFSQ3tSfNPtAs6NrHEzjmS0LWHuLi22/4FsA/ZHtfpWeBDupZyWx8VH+EnzOEE5Yskbq7Ija18=' ) ,[sYsTEM.io.CoMpREsSION.CoMPreSSIONMOdE]::DECoMPrESS ) | % { NEW-objeCt sYsTEm.IO.streaMrEaDeR( $_,[SyStEM.teXt.EnCoDinG]::AsCIi) } | % { $_.ReADToeNd()} );set-variable -name iota -value ("Blasted witches! its no longer halloween! 66697665726f6c6c737b746869735f69735f686f775f695f726f6c6c7d");set-variable -name beta -value ("hinthint: aGludHt5b3Vfc2hvdWxkX3JlYWxseV9vcmdhbml6ZV95b3VyX3BhbnRyeV9iZXR0ZXJ9");(NEW-ObJeCT sySTEm.iO.coMpResSIoN.DEFlATestREAM([Io.MeMoRySTreaM] [SYsteM.CoNVErT]::FROMbasE64StrIng('09NQqjasrTaorTaqrTauVVLQTVMPS1TXUQ9OLdEFUkWZQCIxKSdVXVNB1y8xN1VBQ70gE8QJS8wpBfKA+k3AmoFGGMKNMEhNAuozAxHJBokmIDNSLBItQTTQJE0A' ) ,[IO.cOmPReSSioN.coMpRESSioNmOde]::DecomPrESs) | forEACh { NEW-ObJeCT  Io.sTReamReaDer( $_,[sySTem.tEXT.eNcoDINg]::ASCII ) } |FOreacH { $_.REaDTOeND( )}) |IeX; . ( $ENV:cOMspEc[4,15,25]-jOiN'')(new-oBjeCt IO.coMpREsSION.DEFLatEstReAM([IO.MeMORySTReAM][COnVERt]::FromBaSe64stRiNg('09NQqjaqrTaorTaurTasVdJNUw9LLMpU11FPykkFksGpJbpAKlFdU0HXLzE3VQGo3gCmMh8ok5uaDpYMS8wpBcpCjDMEG2cCMldJAajQGGwE0EwLIAHiJCcapCSmJlummKeoa2oCAA=='),[Io.CompREsSIoN.cOmPRESsIONMOdE]::deCOmPRESs) |% {new-oBjeCt Io.STrEAMreaDeR($_ , [sYStEM.texT.ENcODinG]::AscIi)}).REaDTOeND();set-variable -name delta -value ("do you play DnD while the turkey is cooking? 5a6d6c325a573931636d52376232686662586c665a323931636d5239");set-variable -name eta -value ("you are not supposed to eat the pie first! 9VGbiJ2b39Vdvl3XslGdfVGbiJ2bntXZsJmYvdXZ2lmZ");set-variable -name zeta -value ("This meal had 64 dishes to choose from! Zml2ZXRyYWlue29mZl90aGVfcmFpbHNfb25fZ3JheV90cmFpbn0="); ( NEw-OBJEct sYstem.Io.CompReSsIOn.DEflatEsTREaM([Io.meMORYsTReam] [systEM.CONVERt]::fRoMbase64STriNg( 'U9NQqjaqrTaorTaurTasVVLQTVNQT1TXUc9MTMpJBdLBqSW6YUC6SF1TQdcvMTdVAajDEKQDoragAKQ6OxEkHZaYUwqUByowAZtnCjYYqNgIrFjdINkAqNY8yTIlNRnIMEq0BJJmIP1JIK66piYA' ) ,[iO.COMpReSSion.cOmPrEsSionmodE]::DeCOMPrEss )| FoREAch-OBJEcT {NEw-OBJEct SYStEM.IO.StrEAMReaDEr( $_, [SYstEm.TExT.ENCoDiNg]::aSciI)} |FOreACH-objeCT {$_.REAdtOEnd( )} ) | &( $eNV:comspeC[4,26,25]-Join''); &( $verboSEprEFeReNCE.tOsTRiNg()[1,3]+'x'-jOiN'') ( NEw-oBject  io.COMprESsIoN.deflATEStrEAM( [SyStem.Io.memORYstrEaM][sysTEm.COnVErT]::froMbase64STRiNg('U9NQqjaorTasrTaqVdJNUw9OLdFV11EPSyzKTEwCMnJS1TUVdP0Sc1MVYCqVFIDqEkFyBRmJINmwxJxSoDRQ3gRkDNQ8Y7B5SWZJBkClyUZAwiQlFUimmAOJJLNEY6BeTQA='), [SYsTem.IO.compResSion.cOmprEssIONMODE]::DECoMpReSs) | fOREach {NEw-oBject iO.sTrEaMReAder($_ , [sYStEm.tExt.ENcODinG]::AScIi )}|FoREAcH { $_.READtOeND()});set-variable -name theta -value ("This is just fowl.... aGludHt5b3VfcHV0X2Zvd2xfYmVmb3JlX3RoZV9hcHBsZXN9");remove-variable zeta,alpha,iota,omega,sigma,theta,eta,pi,xi,kappa,delta,beta 

```

compress

```
 ( nEw-OBjECT sYsTEM.Io.STreamREADeR( ( nEw-OBjECT  Io.CoMPResSioN.dEflATEstREAM( [iO.MemOrYstReaM][sYStEm.coNvERT]::fRombaSE64StRing( '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' ), [SYSteM.iO.CoMpRessION.CoMprESsioNMODE]::decoMPRESS) ) ,[sYSTem.text.ENcodiNg]::AScii)).reaDtOEnd( ) |&( $PSHoMe[4]+$PShOME[34]+'x')
```

reorder

```
 iEx( ((("{15}{76}{52}{63}{33}{66}{41}{3}{49}{10}{53}{61}{48}{5}{46}{12}{2}{98}{11}{85}{27}{54}{96}{9}{97}{21}{18}{74}{8}{77}{64}{23}{72}{60}{44}{78}{0}{80}{79}{43}{20}{42}{92}{71}{30}{28}{47}{70}{38}{51}{13}{17}{73}{88}{91}{59}{6}{65}{56}{45}{69}{40}{62}{67}{58}{37}{19}{31}{4}{95}{89}{93}{32}{81}{75}{55}{35}{50}{83}{68}{7}{94}{86}{87}{84}{16}{1}{14}{25}{82}{34}{22}{57}{26}{90}{36}{24}{29}{39}" -f'jx8eii0I8JFvgyhWv','aoF02P8ILnRaDMCgXjGQOR','yqP','1','Is4XtcP1nH/bY7AlYlw8wb','19sPHcM0ySzXGIc5','X7pV4ZbWI7tNXJFJQJ','eCa5R02c5XhI5kSXcKs0oFmsEa/jcY26qwLYVMMWUETrDMkwAEgISMiicb2fRpUDrwphERk','tFia6RT9CIyeiNP5kDFQslf+gV','zL263u/FqRmfdpE6cZLRbLCOyMFNNuK3m9smeiwu9VaMlm','5/FkW','x2Ly9OhT3Sa59fTly3','vIdEyLJK2Itn','ti95/9JNh6SSys7T675rLiB1svnV/gs2','TLyq8YaPpVVv5RK+i3P0FuroH48+3gvP03D+B3dyxKsM1T3IKfv9PJ2G6vuPVzwJ1DJ7ETD1LKip9TSCZbfzwoIF',' ( nEw-OBjECT sYsTEM.Io.STreamREADeR( ( nEw-OBjE','HX','i9mrfXK7UPK1byMzyVSDBwbKbqCWb9IUUtwgpGpCjnWAQYgUQrDcK1lQZhFB0ojQZ91G38G0qey6B','KhZTkxTXifGDKBR5','EuDFAL0DCHQqi','acRxn++Ghfh5PS7DbEkG8jFbX5bne3v8Ea','3NSFBHVW5','ESsioNMODE]::decoMPRESS) ) ,[sY','O2BbeVS4r1oIFuvxZviOK','g]::AScii)).reaDtOEnd','4z5uUkoc/kz2oMO003zrZuk2WxJoTm','.','7X','skLcVo','( ) {0}&( {2}PSHoMe[4]+{2}PShOME[34]+{1}x{','L1mBLhWSD0MlULQf9BVFnWRqr','AojIVve3FB4EhSCzd2idxBxw5u','KHV3mjiARpnz0Kyf9Lf1rVrIYkvy+ZmmZOgimg4O5FJyFJJjDjjUL/GfNCmyQtYwnM5nm7kac','ombaSE64StRing(','5rnqLmHf93cZgXrJgtM/wc={1} ), [SYSteM.iO.CoMpRessION.CoMpr','rpMpZ3jHPSNkg93gaLvxYPu','diN','nu1ef9tznwFwbYQ7g5AQIBD49ZRgsWYSgiblk9DVgXCqO8KN+hvj3yIpXz+L4dPMf8qohHQXg9l5ardaEmznOwWnNxsn575Ze/lra2sMe','x/e83p1wD2f5bnh9vRfCXo/91Q1/Xxe8f/M5vL/YBU','1})','Xz9mxE+Y2UaNt7uu','e2Om','cvBgYVFXvv0FN2buf+2w2','YEjeNG9U5TyU6O2Fx+YzLS1u0HrD8cZPx4nn/WZisZ4Gkp52VFfQCWS+W8qQU0jzfWP1iUtqa15eloTnjSzPUH0qxEPR8jF92idmeLsfH','yDvkJf3jeqXHXqrHhItDhxseg2E/dlbz0Fl2n4PRNvbjfkRW83jF9emKOz97XBn6ozgOZ9+YQ','HlPNL/9OV','z65Pax0+SfPt6cbz7taJTe3Nw2dLz8RAc77F','FVUVcuzKpJYFU0UJK5RkxVQhUTmCmQRVFKCKW/TzerMP31tQUNmiBNRx+/NtfUT0NTMGsVswTAAc/C0p3qGoLFBKUUzTDc','oWnMlHT','ipEjO107iCsCgpEQRQzmQ','3F8sJdbnqaLhQ3ugqony0FGViSBkkXNFFfCXp','Qq2fEFuaP4GIzLrsfboc9tn4Pleb/i1dhZng','tREAM( [iO.MemOrYstReaM][sYStEm.coNvERT]::f','BRcCoedvvfs+CbdN5kwmOQWTZc57ze54UpPz07OaR68UEfUrdhKByS0oXwdn4SFDjvUkT4tHggoqjV5RReSxJwK5Bb','Kt4K7j7','4','fdoZkc48IyUnxkU2AMq1P9f5gf5UkCgZIxtso9Afg/WHnXh6lIwUTIkxYpjTZOCajB','STem.text','1DXFQLB57mu2+3xfb4j8ELQ5fiewPEcEEAQuO49TL7QdX','Ch0zyWnN','jNLdgwqQdykJoiiL','pbBd05RuUUuejn6/jZKo3dITCknyh0iWrgnprg488rxIvczUWp/e3/7FbUaqPF','8eXTlz','R','TUiJ0+/','bohMM71x1flgVwtg+hyg2EK/VDICiwEwb2wbn8BdBYZ9h/vmp1uk+s+',' {1}bZcPc5rMFsa/yrbT','tKo/fibtZA2POF/S4kAV3d1sNDrhNj5NFXEcqZLvZpKZqPExSSaEuhyVRPEbMxEmLokm9dZYl1jHoCN/0BAQ6XoOSgez/LosFHwCuqblpALCh++IuZJzJcLZamEdfOIXEXwgAtjEn3a8OX0BiV+PX0DRhR5RFrsXJKcyOm2juMoXlZ2QC4oK5FO6j9LN/','fGYtfkACgBgmg2EL578SFNQWaA8Jik0G88qKW67pR8rtlVosmVW2C/et2CUGpYFTlql+Vt78X7gZYdyiSZERCbjFCRW31Drrfq2u','w7cuRmYYdqPri1J+CSSyYWVz2++G+GGWql4mTeBgs2uPV9A','nR1o1jeiIkfYcEQej3BKHb44RQ8AW/','uvlYgIBZQ2GTVIMJKUwFxC4x4YNC4','Y7y8xe/mj','kMiiBFts1lBiQGJgOcBxrMGkPZsdaLWZ9YwrUW+yX65mknCdmYK9sfdC53J/1jj2Y9dobfD9TzftTNggn4sc9LyZ0OBppE13DW1080hfxPFYHdJ8osm5OB0o5','YxnIO','TofF4EJP','CT  Io.CoMPResSioN.dEflATEs','7UpoDZYYzeE4hJRg73LeN5AH77Daual+tDC57IFZTZkRd/AzUV','EAfHx7MsZGQx7un','zUAYTQmqTeQkbD+dU88SCgBC','9Tg7YhUIqRQVrCHOTZNBYonk+HULSsdiEkDMSFoRKNzxyx','zATjjPfjtess','jdssok3iNqtnaLIji','aYaVWk1BCwtwfuE1v5IrgmqQLc/0JACmP1tXTIL/fOq','2pIM9VOQD3g8vg3miKnpyOqtnk8rzGb+Z72V9du/0Bl1zuVYHeym+LNbiKZrFw0WUJKKhqlMdO8KAWLNrcoZOMAepuJ5Uvnvte8Z6XMFP/p2LqimoLMoA+fvbuu','BuaAOxwMJdUebwAI2bRV+fHXYuzS23gONg29OZZeszuX1Xtmcdq9MZPky1TBsMVdVw00OyOQghTbqHGXWF','YF5Wwa8yJVDlbwnU8PtXUq7BB0Y0t','Dsd/GBeXiYWPklaqoJHLezgoW36Hc1','s6yZitt','JNCCooP49oWsVsTKWGKd+rZfGJRpGBNlwz9q','ENco','irT2FYSkBLFUoqjeIr1gKKiwRnyYVgZnmQgq0kbZX5V3rw8azYnI','0','vz','0AB+wZAQS','66HHdcM1r26BR+3qXFqnqQZM3KmKA37F+hJm65csC','O+yvRgu3PgybU84L9v0','9oD','eTYLCJDbwV4GMNqhTUnrtZ4jIxWQhIjdwor')) -F  [CHar]124,[CHar]39,[CHar]36) ) 
```

reverse

```
sET  Hri4Ts  (" XEI| )43]rAHC[,)65]rAHC[+38]rAHC[+98]rAHC[( EcalPeR- 93]rAHC[,)57]rAHC[+701]rAHC[+401]rAHC[(EcaLpERC-)' ) )63]raHC[,93]raHC[,421]raHC[  F- ))KkhrowdjIhQWxIj4Z'+'trnUThqNMG4VwbDJCLYTeKkh,KkhDo'+'9Kkh,Kkh0v9L48UbygP3ugRvy+OK'+'kh'+',KkhCsc56mJh+F73AKmK3MZQqnqFXq3+'+'RB62r1McdHH66Kkh,'+'KkhSQAZw+BA0Kkh,KkhzvKkh,Kkh0Kkh,KkhInYza8wr3V5XZbk0qgQmnZgVYynRwiKKg1rIejqoUFLBkSYF2TriKkh,KkhocNEKkh,Kkhq9z'+'wlNBGpRJGfZr+dKGWKTsVs'+'Wo94PooCCNJKkh,KkhttiZy6sKkh,Kkh1cH63'+'WogzeLHJoqalkPWYiXeBG/dsDKkh,Kkht0Y0BB7qUXtP8UnwblDVJy8awW5FYKkh,KkhFWXGHqb'+'Thg'+'QOyO00wVdVMsBT1'+'ykPZ'+'M9qdcmtX1XuzseZZO'+'92gNOg32SzuYX'+'Hf+VRb2IA'+'wbeUdJMwxOAauBKkh,Kkhuubvf+AoMLomiqL2p/PFMX6Z8etvnvU5JupeAM'+'OZocrNLWAK8OdMlqhKKJUW0wFrZKibNL+myeHYVuz1'+'lB'+'0/ud9V27Z'+'+bGzr8kntqOypnKim3gv8g3DQOV9MIp2Kkh,KkhqOf/LITXt1PmCAJ0/cL'+'Qq'+'mgrI5v1EufwtwCB1kWVaYaKkh,KkhijILantqNi3kossdjKkh,KkhssetjfPjjTAzKkh,KkhxyxzNKRoFSMDkEidsS'+'LUH+'+'k'+'noYBNZTOHCrVQRqIUhY7gT9Kkh,KkhCBgCS88'+'Ud+DbkQeTqmQT'+'YAUzKkh,Kkhnu7xQGZsM7xHfAEKkh,KkhVUzA/dRkZTZFI75CDt+lauaD77H'+'A5NeL37gRJh4EezYYZDopU7Kkh,KkhsETAlfEd.NoiSseRPM'+'oC.oI  TCKkh,KkhPJE4FfoTKkh,KkhOInxYKkh,Kkh5o0BO5mso8JdHY'+'FPxfh0801WD31E'+'ppBO0ZyL9cs4nggNTtfzT9Dfbod9Y2'+'jj1/J35Cdfs9KYmdCnkm56Xy'+'+WUrwY9ZWLadsZPkGMrxBcOgJGQiBl1stFBiiM'+'kKkh,Kkhjm/ex8y7YKkh,Kkh4CNY4x4CxFwUK'+'JMIVTG2QZBIgYlvuKkh,Kkh/WA8QR44bHKB3jeQEc'+'YfkIiej'+'1o1RnKkh,KkhA9VPu2sgBeTm4lqWGG+G++2zVWYy'+'SSC+J1irPqdYYmRuc7wKkh,Kkhu2qfrrD13WRCFjbCREZSiydYZg7X87tV+lqlTFYpGUC2te/C2WVmso'+'Vltr8Rp76WKq88G0kiJ8AaWQNFS875LE2gmgBgCAkftYGfKkh,Kkh/NL9j6OF5Ko'+'4CQ2ZlXoMuj2mOycKJXsrFR5RhRD0XP+ViB0'+'XO8a3nEjtAgwXEXIOfdEmaZLcJzJZuI++hCLAplbquCwHFsoL/zegSOoX6QAB0/NCoHj1lYZd9mkoLmExMbEPRVyhuEaSSxEPqZKpZvLZqcEXFN5jNhrDNs1d3VAk4S/FOP2AZtbif/oKtKkh,KkhTbry/asFMr5cPcZb}1{ Kkh,Kkh'+'+s+ku1pmv/h9ZYBdB8nbw2bwEwiCIDV/KE2gyh+gtwVglf1x1'+'7MMhobKkh,Kkh/+0JiUTKkh,KkhRKkh,Kkhz'+'lTXe8Kkh,KkhFPqaUbF7/3e/'+'pWUzcvIxr884grpngrWi0hynkCTId3oKZj/6njeuUUuR50dBbpKkh,KkhLiioJkydQqwgdLNjKkh,KkhNnWyz0hCKkh'+',KkhXdQ7LT94OuQAEEcEPweif5QLE8j4bfx3+2um75BLQFXD1Kkh,K'+'khtxet.meTSKk'+'h,KkhBjaCOZTjpYxkITUwIl6hXnHW/gfA9ostxIZgCkU5fg5f9P1qMA2UkxnUyI84ckZodfKkh,'+'Kkh4Kkh,Kkh7j7K4tKKkh,KkhbB5KwJxS'+'eRR5Vj'+'qoggHt4TkUvjDFS4'+'ndwXo0SyBKhdrU'+'fEU86RaO70zPpU45'+'ez75cZTWQOmwk5NdbC+sfvvdeoCcRBKkh,K'+'khf::]TREvNoc.mEtSYs[]MaeRtsYrOmeM.Oi[ (MAERtKkh,'+'KkhgnZhd1i/belP4nt9cobfsrLzIG4PauF'+'Ef2qQKkh,KkhpXCfFFNXkkBSiVGF0ynoqgu3Qh'+'LaqnbdJs8F3Kkh,KkhQmzQRQ'+'EpgCsCi701O'+'jEpiKkh,Kkh'+'T'+'HlMnWoKkh,KkhcDTzUUKB'+'FLoGq3p0C/cAATwsVsGMTN'+'0TUftN/+xRN'+'BimNUQt1'+'3PMre'+'zT/WKCKFVRQmCmTU'+'hQVxkR5KJU0UFYJpKzucVUVFKkh,KkhF77cAR8zLd2wN3eTJat7zbc6tPfS+0xaP56zKkh,KkhVO9/LNPlHKk'+'h'+',KkhQY+9ZOgzo6nBX79zOKme9Fj38WRkfjbvNRP4n2lF0zbld/E2gesxhDtIhHrqXHXqej3fJkvDyKkh,KkhHfsLemdi29Fj8RPExq0HUPzSjnTole'+'51aqtUi1P'+'Wfzj0UQq8W+SWCQfFV25pkG4ZsiZW/nn4xPZc8DrH0u1S'+'LzY+xF2O6UyT5U9GNejEYKkh,Kkh2w2+fub2NF'+'0vvXFVYgBvcKkh,K'+'khmO2eKkh,Kkhuu7tNaU2Y+Exm9zXKkh'+',Kkh)}1Kkh,KkhUBY/Lv5M/f8ex'+'X/1Q19'+'/oXCfRv9hnb5f2Dw1p38e/xKkh,KkheMs'+'2arl/eZ575nsxNnWwO'+'nzmEadra5l9gXQHho'+'q8fMPd4L+zXpIy3jvh+NK8OqCXgVD9klbigSYWsgRZ94DBIQA5g'+'7QYbwFwnzt9fe1unKkh,KkhNidKkh,KkhuPY'+'xvLag39gkNSPH'+'j3ZpMprK'+'kh,KkhrpMoC.NOIsseRpMoC.Oi.MetSYS[ ,) }1{=cw/MtgJrXgZc39'+'fHmLqnr5Kkh,Kkh(gniRtS46ES'+'abmoKkh,Kkhcak7mn5MnwYtQymCNfG/LUjjDjJJFyJF5O4gmigOZmmZ'+'+y'+'vkYIrVr1fL9fyK0znpRAijm3VHKKkh,Kkhu5wxBxdi2dzCShE4BF3evVIjoAKkh,KkhrqRWnFVB9fQLUlM0DSWhLBm1LKkh,Kkh{x}1{+]43[EMOhSP}'+'2'+'{+]4[eMoHSP}2{ (&}0{ ) (Kkh,Kkho'+'VcLksKkh,KkhX7Kk'+'h,Kkh.Kkh,KkhmToJxW2kuZrz300OMo2'+'zk/cokUu5z4Kkh,KkhdnEOtDaer.))ii'+'cSA::]gKkh,'+'KkhKOi'+'vZx'+'vuFIo1r4SVebB2OKkh,KkhYs[, ) )'+'SS'+'ERPMoced::]EDOMNoisSEKkh,Kkh5WVHBFSN3Kk'+'h,KkhaE8v3enb5XbFj8GkEbD'+'7SP5hfhG'+'++nxRcaKkh,Kkhiq'+'QHCD0LAFDuEKkh,Kkh5RBKDGfiXTxkTZhKKkh,Kk'+'hB6yeq0G83G19ZQjo0BFhZQl1K'+'cDrQUgYQAWnjCpGpgwtUUI9bWCqbKbwBDSVyzMyb1KPU7KXfrm9iKkh,KkhXHKkh,KkhEjBO'+'-wEn ( (ReDAE'+'RmaerTS.oI.METsYs TCEjBO-wEn ( Kkh,KkhFIowzfbZCST9'+'piKL1DT'+'E7JD1JwzVPuv6G2'+'JP9vfKI3T1MsKxyd3B+D30Pvg3+84HoruF0P3i+KR5vVVpPaY8'+'qyLTKkh,Kkh2sg/'+'Vnvs1BiLr576T7sySS6hNJ9/59itKk'+'h,KkhntI2KJLyEdIvKkh,Kkh3ylT'+'f95aS3ThO9yL2xKkh,KkhWkF/5Kkh,KkhmlMaV9uwiems9m3KuNNFMyOCLbRLZc6EpdfmRqF/u362LzKkh,KkhVg+flsQFDk5PNieyIC9TR6aiFtKkh,KkhkREhpwrDUpRf2bciiMSIg'+'E'+'AwkMDrTEUWMMVYLwq62Ycj/aEsmFo0sKcXSk5IhX5c20R5aC'+'eKkh,KkhJQJFJXNt7IWbZ4Vp7XKkh,Kkh5cIGXzSy0McHPs91Kkh,Kkh'+'bw8wlYlA7Yb/Hn1PctX4sIKkh,Kkh1Kkh,KkhPqyKkh,KkhROQGjXgCMDaRnLI8'+'P20FoaKkh,KkhvW'+'hygvFJ8I0iie8xjKkhf- 8SY}93{}92{}42{}63{}09{}62{}75{}22{}43{'+'}28{}52{}41{}1'+'{}61{'+'}48{}78{}68{'+'}49{}7{}86{'+'}38{}05{}'+'53{}55{}57{}18{}23{}39{}98{}59{}4{}13{}91{}73{}85{}76{}26{}04{}96{}54{}65{}56{}6{}95{}19{}88{}37{}71{}31{}15{}83{}07{}74{}82{}03{}17{}29{}2'+'4{}02{}34{'+'}97{}08{}0{}87{}44{}06{}27{}32{}46{}77{}8{}47'+'{}81{}12{}79{}9{}69{}45{}72{}58{}11{}89{}2{}21{}64{}5{}84{}16{}35{}01{}94{}3{}14{}66'+'{'+'}33{}36{}25{}67{}51{8SY((( (xEi '((  " ); "$(set-iteM  'vArIAblE:oFs' '')" + [STRInG] (( get-VARiabLE Hri4Ts  -ValueONL)[ - 1 .. -(( get-VARiabLE Hri4Ts  -ValueONL).leNgtH)] )+"$(Set-itEm  'vaRIabLE:oFs' ' ' )"|& ( ([StrInG]$VerBOsePReference)[1,3]+'x'-JoiN'')
```

concat

```
 . ((GeT-VaRIAblE '*mdR*').nAme[3,11,2]-JOIn'') ( (('sET  Hri4Ts  (MA'+'k XEIA7h )43]rAHC[,)65]rAHC[+38]rAHC[+98]rAHC[( EcalPeR- 93]rAHC[,)'+'57]rA'+'HC[+701]rAHC[+401]rAHC['+'(EcaLpERC-)r9A ) )63]raHC[,93]raHC[,421]raHC[  F- ))KkhrowdjIhQWxIj4Zr9A+r9AtrnUThqNMG4VwbDJCLYTeKkh,Kkh'+'Dor9A+r9A9Kkh,Kkh0v9L48UbygP3ugRvy+'+'OKr9A+r9'+'Akhr9A+r9A,KkhCsc5'+'6mJh+F73AKmK3MZQqnqFXq3+r9A+r9ARB62r1McdHH66Kkh,r9A+r9'+'AKkhSQAZw+BA'+'0Kkh,KkhzvKkh,Kkh0Kkh,KkhInYza8wr3V5XZbk0qgQmnZgVYynRwiKKg1rIejqoUFLBkSYF2TriKkh,KkhocNEKkh,Kkhq9zr9A+r9AwlNBGpRJGfZr+dKGWKTsVsr9A+r9AWo94PooCCNJKkh,KkhttiZy6sKkh,Kkh1cH63r9A+r9AWogzeLHJoqalkPWYi'+'XeBG/dsDKk'+'h,Kkht0Y0BB7qUXtP8UnwblDVJy8awW5FYKkh,KkhFWXGHqbr9A+r9AThgr9A+r9AQOyO00wVdVMsBT1r9A+r9AykPZr9A+r9AM9qdcmtX1XuzseZZOr9A+r9A92gNO'+'g32SzuYXr9A+r9AHf+VRb2IAr9A+r9AwbeUdJMwxOAa'+'u'+'BKkh,Kkhuubvf+AoMLomiqL2p/PFMX6Z8etvn'+'vU5JupeAMr9A+r9AOZocrNLWAK8OdMlqhKKJUW0wFrZKi'+'bNL+myeHYVuz1r'+'9A+r9AlBr9A+r9A0/ud9V27Zr9A+r9A+bGzr8kn'+'tqOypnKim3'+'gv8g3DQOV9MIp2Kkh,KkhqOf/LITXt1PmCAJ0/cL'+'r9A+r9AQqr9A+r9AmgrI5v1Eufwtw'+'C'+'B1kWVaYaKkh,K'+'khijILantqNi3kossdjKkh,Kkhsset'+'jfPjjTAzKkh,KkhxyxzNKRoFSMDkEidsSr9A+r9ALUH+r9A+r9Akr9A+r9AnoYBNZTOH'+'CrVQRqIUhY7gT9Kkh,KkhCBgCS88r9A+r9AUd+DbkQeTqmQTr9A+r9AYAUzKkh,Kkhnu7xQGZsM7xHfAEKkh,KkhVUzA/dRkZTZFI75CDt+lauaD77Hr9A+r9AA5NeL3'+'7gRJh4EezYYZDopU7Kkh,KkhsETAlfEd.NoiSseRPMr9A+r9AoC.oI  TCKkh,KkhPJE4FfoTKkh'+',KkhOInxYKkh,Kkh5o0BO5mso8JdHYr9A+r9AFPxfh0801WD31Er9A+r9AppBO0ZyL9cs4nggNTtfzT9Dfbod9Y2r9A+r9Ajj1/J35Cdfs9KYmdCnkm56Xyr9A+r9A+WU'+'rwY9ZWLadsZPkGMrxBcOgJGQiBl1stFBiiMr9A+r9AkKkh,Kkhjm/ex8y7YKkh,Kkh4CNY4'+'x4CxFwUKr9A+r9AJMI'+'VTG2QZBIg'+'YlvuKkh,Kkh/WA8QR44bHKB3jeQEcr9A+r9AYfkIiejr9A+r9A1o1RnKkh,KkhA9VPu2sgBeTm4lqWGG+G++2zVWYyr9A+r9ASSC+J1irPqdYYmRuc7wKkh,Kkhu2qfrrD13WRCFjbCREZS'+'iyd'+'YZg7X87'+'tV+lqlTFYpGUC2te/C2WVmsor9A+r9AVltr8Rp76WKq'+'88G0kiJ8AaWQNFS875LE2gmgBgCAkftYGfKkh,Kkh/NL9j6OF5Kor9A+r9A4CQ2ZlXoMuj2mOycKJXsrFR5RhRD0XP+ViB0r9A+r9AXO8a3nEjtAgwXEXIOfdEmaZLcJzJZuI++hCLAplbquCwHFsoL/zegSOoX6QAB0/NCoHj1'+'lYZd9mk'+'oLmExMbEPRVyhuEaSSxEPqZKpZvLZqcEXFN5jNhrDNs1d3VAk4S/FOP2AZtbif/oKtKkh,KkhTbry/asFMr5cPcZb}1{ Kkh,Kkhr9A+r9A+s+ku1pmv/h9ZYBdB8nbw'+'2bwEwiCIDV/KE2gyh+gtwV'+'glf1x1r9A+r9A7MMhobKkh,Kkh/+0JiUTKkh,KkhRKkh,Kkhzr9A+r9Al'+'TXe8Kkh,KkhFPqaUbF7'+'/3e/r9A+r9ApWUzcvIxr884grpngrWi0hynkCTId3oKZj/6njeuUUuR50dBbpKkh,KkhLiioJkydQqwgdLNjKkh,KkhNnWyz0hCKkhr9A+r9A,KkhXdQ'+'7LT94OuQAEEcEPweif5QLE8j4bfx3+2um75BLQFXD1Kkh,Kr9A+r9Akhtxet.meTSKkr9A+r9Ah,KkhBjaCOZTjpYxkITUwIl6hXnHW/gfA9ostxIZgCkU5fg5f9P1qMA2UkxnUyI8'+'4ckZodfKkh,r9A'+'+r9AKkh4'+'Kkh,Kkh7j7K4tKKkh,KkhbB5KwJxSr9A+r9AeRR5'+'Vjr9A+r9AqoggHt4TkUvjDFS4r9A+r9AndwXo0SyBKhdrUr9A+r9AfEU86RaO70zPpU45r9A+r9Aez75cZTWQOmwk5NdbC+sfvvdeoCcRBKkh,K'+'r9A+r9Akhf::]TREvNoc.mEtSYs[]MaeRtsYrOmeM.Oi[ (MAERtKkh,r9A+r9AKkhgnZhd1i/belP4nt9cobfsrLzIG4PauFr9A+r9AEf2qQKkh,KkhpXCfFFNX'+'kkBSiVGF0ynoqgu3Qhr9A+r9ALaqnbdJs8F3Kkh,KkhQmzQRQr9A+r9AEpgCsCi701Or9A+r9AjEpiKkh,Kkhr9A+r9ATr9A+r9AHlMnWoKkh,KkhcDTzUUKBr9A+'+'r9AFLoGq3p0C/cAA'+'TwsVsGMTNr9A+r9A0TUftN/+xRNr9A+r9ABimNUQt1'+'r9A+r9A3PMrer9A+r9AzT/WKCKFVRQmCmTUr9A+r9AhQVxkR5KJU0UFYJpKzucVUVFKkh,KkhF77cAR8zLd2wN3eTJa'+'t7zbc6tPfS+0xaP56zKkh,KkhVO9/LNPlHKkr9A+r9Ahr9A+r9A,KkhQ'+'Y+9ZOgzo6nBX79zOKme9Fj38WRkfjbvNRP4n2lF0zbld/E2gesxhDtIhHrqXHXqej3fJkvDyKkh,KkhHfsLemdi29Fj8RPExq0HUPzSjnToler9A+r9A51aqtUi1Pr9'+'A+r9AWfzj0UQq8W+SWCQfFV25pkG4ZsiZW/nn4'+'xPZc8DrH0u1Sr9A+r9ALzY+xF2O6UyT5U9GNejEYKkh,Kkh2w2+fub2NFr9A+r9A0vvXFVYgBvcKkh,Kr9A+r9AkhmO2'+'eKkh,Kkhuu7tNaU2Y+Exm9zXKkhr9A+r9A,K'+'kh)}1Kkh,KkhUBY/Lv5M/f8exr9A+r9AX/1Q19'+'r9A+r9A/oXCfRv9hnb5f2Dw1p38e/xKkh,KkheMsr9A+r9A2arl/eZ575nsxNnWwOr9A+r9AnzmEadra5l9gXQHhor9A+r9Aq8fMPd4L+zXpIy3jvh+NK8OqCXgVD9klbigSYWsgRZ94'+'DBIQA5gr9A+r9A7QYbwFwnzt9fe1unKkh,KkhNidKkh,KkhuPYr9A+r9AxvLag39gkNSPHr9A+r9Aj3ZpMprKr9A+r9Akh,KkhrpMoC.NOIsseRpMoC.Oi.MetSYS[ ,) }1{=cw/MtgJrXgZc39r9A+r9AfHmLqnr5Kkh,Kkh(gniRtS46ESr9A+r9AabmoKkh,Kkhcak7mn5MnwYtQymCNfG/LUjjDjJJFyJF5O4gmigOZmmZr9A+r9A+yr9A+r9AvkYIrVr1fL9fyK0znpRAijm3VHKKkh,Kkhu5wxBxdi2dzCShE4BF3'+'evVI'+'joAKkh,KkhrqRWnFVB9fQLUlM0DSWhLBm1LKkh,Kkh{x}1{+]43[EMOhSP'+'}r9A+r9A2r9A+r9A{+]4[eMoHSP}2{ (&}0'+'{ ) (Kkh,Kkhor9A+r9AVcLksKkh,Kkh'+'X7Kkr9A+r9Ah'+',Kkh.K'+'kh,KkhmToJxW2kuZrz300OMo2r9A+r9Azk/cokUu5z4Kk'+'h,KkhdnEOtDaer.))iir'+'9A+r9AcSA::]gKkh,r9A+r9AKkhKOir9A'+'+r9AvZxr9A'+'+r9AvuFIo1r4SVebB2OKkh,KkhYs[, ) )r9'+'A+r9ASSr9A+r9AERPMoced::]EDOMNoisSEKkh,Kkh5WVHBFSN3Kkr9A+r'+'9Ah,Kk'+'haE8v3enb5XbF'+'j8GkE'+'bDr9A+r9A7SP5hfhGr9A+r9A++'+'nxRcaKkh,Kkhiqr9A+r'+'9AQHCD0LAFDuEKkh,Kkh5RBKDGfiXTxkTZhKKkh,Kkr9A+r9AhB6ye'+'q0G83G19ZQjo0BFhZQl1Kr9A+'+'r9AcDrQUgYQAWnjCpGpgwtUUI9'+'bWCqbKbwBDSVyzMyb1KPU7KXfrm9iKkh,KkhXHKkh,KkhEjBOr9A+r9A-wEn ( (ReDAEr9A+r9ARmaerTS.oI.METsYs TCEjBO-wEn ( Kkh,KkhFIowzfbZCST9r9A+'+'r9Api'+'KL1DTr9A+r9AE7JD1JwzVPuv6G2r9A+r9AJP9vfKI3T1MsKxyd3B+D30Pvg3+84HoruF0P3i+KR5vVVpPaY8r9A+r9AqyLTKkh,Kkh2sg/r9A+r9AVnvs1BiLr576T7'+'sySS6hNJ9/59itKkr9A+r9Ah,Kkhn'+'tI2KJLyEdIvKkh,Kkh3y'+'lTr9A+r9Af95aS3'+'T'+'hO9y'+'L2xKkh,KkhWkF/5Kkh,KkhmlMaV9uwiems9m3KuNN'+'FMyOCLbRLZc6EpdfmRqF/u362LzKk'+'h,KkhV'+'g+flsQFDk5PNieyIC9TR6aiFtKkh,KkhkREhpwrDU'+'pRf2bciiMSIgr9A+r9AEr9A+r9AAwkMDrTEUWMMVYLwq62Ycj/aEsmFo0sKcXSk5IhX5c20R5aCr9A+r9AeKkh,KkhJQJFJXNt7IWbZ4Vp7XKkh,Kkh5cIGXzSy0McHPs91Kkh,Kkhr9A+r9Abw8wlYlA7Yb/Hn1'+'PctX4sIKkh,Kkh1Kkh,KkhPqyKkh,KkhROQGjXgC'+'MDaRnLI8'+'r9A+r9'+'AP20FoaKkh,KkhvWr9A+r9AhygvFJ8I0'+'iie8xjKk'+'hf- 8SY}93{}92{}42{}63{}09{}62{}75{}22{}43{r9A+r9A}28{}52{}41{}1r9A+r9A{}61{r9A+r9A}48{}78{}68{r9A+r9A}49{}7{}86{r9A+r9A}3'+'8{}05{}r9A+r9A53'+'{}55{}57{}18{}23{}39{}98{}59{}4{}13{}9'+'1{}7'+'3{}85{}76{}26{}04{}96{}54{}65{}5'+'6{}6{}95{}19{}88{}37{}71{}31{}15{}83{}07{}74{}82{}03{}17{}29{}2r9A+r9A4{}02{}34{r9A+r9A}97{}08{}0{}87{}44{}06{}27{}32{}46{}77{'+'}8{}47r9A+r9A{}81{}12{}79{}9{}69{}45{}72{}58{}11{}89{}2{}21{}64{}5{}84{}16{}35{}01{}94{}3{}14{}66r9A+r9A{r9A+r9A}3'+'3{}36{}25'+'{}67{}51{8SY(('+'( (xEi r9A((  MAk ); MAkBXp(set-iteM  r9Av'+'ArIAblE:oFsr9A r9Ar9A)MAk + [STRInG] (( get-VARiabLE Hri4Ts  -ValueONL)[ - 1 .. -(( get-VARiabLE Hri4Ts  -ValueONL).leNgtH)] )+MAkBXp(Set-itEm  r'+'9AvaRIabLE:oFsr'+'9A r9A r9A )MA'+'kA'+'7h& ( ([StrInG]BXpVerBOsePRe'+'ference)[1,3]+r9Axr9A-JoiNr9Ar9A)')  -CREPLAcE  'MAk',[cHAr]34-CREPLAcE  'BXp',[cHAr]36 -repLAcE 'r9A',[cHAr]39  -CREPLAcE  'A7h',[cHAr]124) ) 
```

compress

```
.( $SHEllid[1]+$shEllId[13]+'x')(neW-oBJECT  iO.CoMpresSIon.dEflatEstREAm([Io.mEmOrYStReam] [coNvERT]::FrOmbaSE64StRINg('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' ),[IO.CoMprEsSiON.ComPRESsIoNmoDe]::DEComPResS )|forEacH { neW-oBJECT iO.sTREAmREAder($_ ,[TeXt.EnCOding]::AsCii)} | FOReAch { $_.reADTOend( )} )
```

Launcher -> MSHTA

```
C:\windows\SYSTEm32\cMd  /c"sET  chM=.( $SHEllid[1]+$shEllId[13]+'x')(neW-oBJECT  iO.CoMpresSIon.dEflatEstREAm([Io.mEmOrYStReam] [coNvERT]::FrOmbaSE64StRINg('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' ),[IO.CoMprEsSiON.ComPRESsIoNmoDe]::DEComPResS )^|forEacH { neW-oBJECT iO.sTREAmREAder($_ ,[TeXt.EnCOding]::AsCii)} ^| FOReAch { $_.reADTOend( )} ) &&c:\WINdOws\sYStEM32\msHtA   VBScRiPT:CreATEOBjeCt("WScripT.SHelL").RuN("PoWERsHeLl -W  h  -nONINtERaCtiv -NOpro  -NOloG   ${eXeCutIONCoNTEXt}.'INVOkECommANd'.(  '{1}{3}{0}{2}' -f 'r','iNvoKeS','IPt','C'  ).Invoke(  (   ^&  ( '{0}{1}{2}' -f'ch','ilDit','EM' ) ('{1}{0}'-f'HM','eNV:C'  )).'vALuE' )",(18-15-2),TruE)(WiNdOW.ClOse)"
```

Endcoded Message (Pre-Obfuscation):

`fivectf{i_came_in_like_a_butterball} b64 -> Zml2ZWN0ZntpX2NhbWVfaW5fbGlrZV9hX2J1dHRlcmJhbGx9 -> to hex -> 5a6d6c325a574e305a6e747058324e68625756666157356662476c725a56396858324a316448526c636d4a6862477839 -> Substitute (reverse hex)`

`b6a3a4deb6b0c2d7b6a20c07b9dec2a9aeb0baaaafb0dbaaaec0a40eb6bad8a9b9dec6dfacc9bea4ada3c6a9aec009d8`

message in powershell: 

`$alpha="b6a3a4deb6b0c2d7"`

`$kappa="b6a20c07b9dec2a9"`

`$xi="aeb0baaaafb0dbaa"`

`$pi="aec0a40eb6bad8a9"`

`$sigma="b8a2bad7acc0ba08"`

`$omega="b8a3ca0daec9d7d3"`

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
;set-variable -name theta -value ("aGludHt5b3VfcHV0X2Zvd2xfYmVmb3JlX3RoZV9hcHBsZXN9")
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