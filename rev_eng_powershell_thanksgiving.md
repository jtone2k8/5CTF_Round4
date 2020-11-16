All of these were created with Invoke-obfuscation

***********************************
Easy - 1 item only
***********************************
1.

Flag: `fivectf{turkeys_go_gobble_gobble}`

Question:

Encoding:

`
  inVOKe-ExPRessION ( ('xiz'+'turkey=3UN'+'f'+'ivect'+'f{tur'+'keys_'+'g'+'o_gob'+'b'+'le_'+'gobble}3UN').REpLACE(([ChAr]120+[ChAr]105+[ChAr]122),[StRiNG][ChAr]36).REpLACE(([ChAr]51+[ChAr]85+[ChAr]78),[StRiNG][ChAr]34)) 
`

Endcoded Message:

`$turkey="fivectf{turkeys_go_gobble_gobble}"`

Obfuscation Technique:

String Concatenate x1

***********************************
2.

Flag: `fivectf{lets_get_basted}`

Question:

Encoding:

`
(("{7}{8}{5}{0}{6}{2}{3}{10}{1}{4}{11}{9}"-f'6nf','_g','v','ectf{l','et_ba','te=5','i','h5Gb','as','ted}56n','ets','s')).rePLAce('h5G','$').rePLAce(([ChAR]53+[ChAR]54+[ChAR]110),[STrING][ChAR]34)| &((geT-VARiAbLe '*mDR*').naME[3,11,2]-JOIn'')
`

Endcoded Message:

`$baste="fivectf{lets_get_basted}"`

Obfuscation Technique:

Reorder x1

***********************************

3. 

Flag: `fivectf{im_stuffed}`

Question:

Encoding:

`
${+ }=  +  $(  );${=$%}  =${+ };${!=%}=++  ${+ }  ;  ${-}  =(  ${+ }=  ${+ }  +  ${!=%}  );  ${!}  =(${+ }  =${+ }+  ${!=%}  );${/@+}=  (${+ }  =  ${+ }+  ${!=%})  ;${;.(}=  (  ${+ }=${+ }+${!=%}  )  ;  ${;}  =(${+ }  =${+ }  +${!=%}  );${=*}=(  ${+ }  =  ${+ }  +${!=%}  )  ;  ${$}  =(${+ }=  ${+ }+  ${!=%});${[%-}=(  ${+ }  =  ${+ }  +  ${!=%})  ;${([!}  =  "["  +"$(  @{}  )"[${=*}  ]  +  "$(@{})"["${!=%}${[%-}"  ]  +  "$(  @{  })"[  "${-}${=$%}"]  +  "$?"[${!=%}]  +"]"  ;  ${+ }=  "".("$(@{  }  )"["${!=%}${/@+}"]+  "$(  @{  })  "[  "${!=%}${;}"  ]  +"$(@{}  )"[${=$%}  ]  +"$(@{})"[  ${/@+}]  +  "$?  "[  ${!=%}  ]  +"$(@{  })"[${!}  ])  ;  ${+ }="$(  @{  }  )"["${!=%}"  +  "${/@+}"  ]+  "$(  @{}  )"[${/@+}]+  "${+ }"["${-}"+  "${=*}"  ]  ;"${([!}${!}${;}+  ${([!}${!=%}${!=%}${;.(}+${([!}${!=%}${!=%}${;}+  ${([!}${!=%}${!=%}${=*}  +${([!}${!=%}${=$%}${-}+${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}+${([!}${!=%}${=$%}${=$%}  +  ${([!}${;}${!=%}+${([!}${!}${/@+}  +${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${=$%}${;.(}  +  ${([!}${!=%}${!=%}${$}+${([!}${!=%}${=$%}${!=%}+  ${([!}${[%-}${[%-}+${([!}${!=%}${!=%}${;}+${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${-}${!}+${([!}${!=%}${=$%}${;.(}  +${([!}${!=%}${=$%}${[%-}+${([!}${[%-}${;.(}  +${([!}${!=%}${!=%}${;.(}  +${([!}${!=%}${!=%}${;}  +${([!}${!=%}${!=%}${=*}  +${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}  +${([!}${!=%}${=$%}${=$%}+  ${([!}${!=%}${-}${;.(}  +  ${([!}${!}${/@+}  +${([!}${;.(}${[%-}  +  ${([!}${!=%}${!=%}${/@+}+${([!}${!=%}${=$%}${!=%}  +  ${([!}${!=%}${=$%}${[%-}  +  ${([!}${!=%}${!=%}${!=%}+${([!}${!=%}${!=%}${$}  +${([!}${!=%}${=$%}${!=%}  +${([!}${/@+}${;.(}+${([!}${!=%}${!=%}${$}+  ${([!}${[%-}${=*}+${([!}${!=%}${!=%}${/@+}  +${([!}${!=%}${=$%}${;.(}+${([!}${[%-}${=*}+  ${([!}${[%-}${$}+  ${([!}${!=%}${=$%}${$}  +  ${([!}${!=%}${=$%}${!=%}  +${([!}${!}${-}  +${([!}${!=%}${!=%}${;.(}+  ${([!}${!=%}${!=%}${;}+${([!}${!=%}${!=%}${=*}  +  ${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}  +${([!}${!=%}${=$%}${=$%}  |${+ }"  |.${+ }  
`

Endcoded Message:

`$stuffed="fivectf{im_stuffed}";remove-variable stuffed`

Obfuscation Technique:

encoding special characters x1

***********************************

4.

Flag: `fivectf{i_yam_what_i_yam}`

Question:

Encoding:

`
&( $env:cOMSpec[4,24,25]-JOiN'') ( ([RuNtimE.InTeropsERvICEs.MArsHaL]::PTrtostRiNGauto([rUNtimE.INtEROPSERViCes.marShaL]::SeCUrEstRiNGTOBSTr( $('76492d1116743f0423413b16050a5345MgB8AFcAZgArAGkATgBMAGYAdAB2AFUAdQBWAFQANAAxAEwANgByAFoARwB6AHcAPQA9AHwAYgBiAGMAMgBlADYAYwAyADIAYgA0ADYAYwA4ADcAMQAzADUANQA5ADkAMAA4ADgAZQA3ADgAOAAxAGEAYQA1ADYAMABiADEAMwAwAGIAYwAyAGQAYQAxADQAZQA4ADMAMQAxADUAYwA1ADUAOQA1AGEAOQBmADgANwA1AGMAZgA5ADYAMwA5ADAAOQA3ADEAZABlAGMAZAAyADMAYwAxADEAYQBhAGUAMAA3ADIAOABmAGMAZABkAGIAMABiAGEANgA4ADEANwBhADQANABiAGEAMQAwAGYAMgBiAGUAZQA0AGQANwBlADQAYQAxADQAMgBiADEANQAxAGQAOQA2ADMAMQA1ADgANgBkAGIAZAA5AGQANQAyADUAZgA1ADAANgAyADMANQA1AGEAYgBmADUAMAA1ADEAOAA0AGQAMwBkAGIAMABkADQAOQA0ADUAMwA0AGMAZQBlAGUAMAAzAGIANgBiAGIAYQBjADcANwAwADkAMQBlADQAZQBkAGQANgBjADAANgBjAGEANAA2ADUAYQA0ADIAZAA5ADcAZQA2ADcAYwAxADkANwA5ADkANABmAGUAYgAwADUANgAyADAAMgA3ADAANgBmADIAYgAxADgAYgBmADMAZAA0ADMAYgBiADEAZgBiADgAOQA3AGEAZQBjAGMAYwA2ADAAYQA=' | ConVerttO-secUReStRIng -K 105,96,78,5,118,178,158,144,131,126,145,80,44,50,161,3)) )) )
`

Endcoded Message:

`$yammy="fivectf{i_yam_what_i_yam}";remove-variable yammy`

Obfuscation Technique:

encoding secure-string x1


***********************************
Medium 2x items
***********************************

5.

Flag: `fivectf{your_the_apple_of_my_pie}`

Decoded Message Step by Step:

reverse x1

`
$UpX8B3=" )''NIOj-]52,51,4[cepsmOc:VNe$ ( &|)43]raHC[]gNIrts[,)15]raHC[+48]raHC[+57]raHC[((ecalPEr.)63]raHC[]gNIrts[,'vnc'(ecalPEr.)'elppa e'+'l'+'ba'+'irav-evomer;'+'3T'+'K}'+'eip_ym_fo_'+'elppa_eh'+'t_r'+'uoy'+'{ftce'+'v'+'if3TK=e'+'lp'+'pavnc'( "; iEx(" $(seT-ItEm 'vARiaBLe:ofS' '')" + [STRiNg] ( $UPX8b3[ - 1.. - ( $UPX8b3.LEnGTH) ])+" $( seT-iTEm 'VAriable:ofS'  ' ' ) " )
`

reorder x1

`
((("{106}{71}{112}{109}{60}{39}{38}{15}{7}{30}{75}{27}{3}{63}{20}{58}{104}{107}{25}{35}{16}{11}{24}{92}{45}{31}{108}{14}{64}{115}{94}{65}{37}{116}{55}{66}{59}{69}{56}{88}{96}{89}{46}{50}{42}{98}{102}{51}{8}{110}{57}{74}{103}{47}{44}{99}{68}{34}{21}{114}{91}{19}{85}{33}{72}{113}{28}{32}{70}{48}{17}{2}{95}{101}{26}{22}{29}{10}{84}{90}{9}{0}{62}{49}{81}{105}{73}{53}{52}{100}{1}{4}{41}{61}{78}{54}{83}{43}{86}{80}{77}{5}{6}{111}{76}{97}{13}{82}{87}{36}{79}{12}{18}{40}{93}{67}{23}"-f'eT-It','9','vncY','[]gNI','E)o0L + ',' ( ','8x','2,51,4[cepsmOc:VNe8xG ','9E','(s','0','cal','Ariabl',')','s[,','9ENIOj-]5','e','a','e:of','+Y9E{ftceY9','[','9E','x',' Y9E ) o0L ) ','PEr.','aHC[+57]raH','E','C','9','(o','( &DkT)4',']','E+Y9E','Ev','_rY9E+Y','C[((','9E','.)','Y',')Y9E','SY','[','v-evomer;Y','UPX8b3[ ','E+Y9Eelp','raHC[','EbaY9','_Y9','Ep','v','E+Y9Eira','Y','9E Y','Y','] ( 8','Eel','9ElY','+Y9Eei',',)15]','Y9E','o0L ','STRiN','Em Y9E','rts','Y9EvncY9E(','r','ppa e','E  Y9E','+Y9Et','+Y','lpY9E+Y9','G','Y9E+Y9Eif3','S','p_ym_','3]raH','PX8b3.','-','g','V','.. ','ARiaBLe',' ])+o0L 8xG( seT','xG','L ','E+Y9','- 1','-iTEm Y','9E+','9','8xG','oyY9E',')63]','9','E','9E( o','Y','LEnGTH','9E+Y','pa_ehY9E','9EY','0L; i','9E3T','fo','raH',':of','8x','C[+48]r','gNIrt','B3=','+Y9EK}Y9E','GU','UpX8','TK=eY','u','ecalP','Y9'))  -cREPlaCe([CHAr]56+[CHAr]120+[CHAr]71),[CHAr]36  -cREPlaCe ([CHAr]89+[CHAr]57+[CHAr]69),[CHAr]39 -cREPlaCe([CHAr]111+[CHAr]48+[CHAr]76),[CHAr]34  -replACE  'DkT',[CHAr]124) |.( $enV:ComSpEC[4,24,25]-joiN'')
`

Launch CMD

Encoding:

`
c:\wInDOws\sYsTeM32\cMD.exe  /c pOwErShelL -nOniNTErAct   "(((\"{106}{71}{112}{109}{60}{39}{38}{15}{7}{30}{75}{27}{3}{63}{20}{58}{104}{107}{25}{35}{16}{11}{24}{92}{45}{31}{108}{14}{64}{115}{94}{65}{37}{116}{55}{66}{59}{69}{56}{88}{96}{89}{46}{50}{42}{98}{102}{51}{8}{110}{57}{74}{103}{47}{44}{99}{68}{34}{21}{114}{91}{19}{85}{33}{72}{113}{28}{32}{70}{48}{17}{2}{95}{101}{26}{22}{29}{10}{84}{90}{9}{0}{62}{49}{81}{105}{73}{53}{52}{100}{1}{4}{41}{61}{78}{54}{83}{43}{86}{80}{77}{5}{6}{111}{76}{97}{13}{82}{87}{36}{79}{12}{18}{40}{93}{67}{23}\"-f'eT-It','9','vncY','[]gNI','E)o0L + ',' ( ','8x','2,51,4[cepsmOc:VNe8xG ','9E','(s','0','cal','Ariabl',')','s[,','9ENIOj-]5','e','a','e:of','+Y9E{ftceY9','[','9E','x',' Y9E ) o0L ) ','PEr.','aHC[+57]raH','E','C','9','(o','( &DkT)4',']','E+Y9E','Ev','_rY9E+Y','C[((','9E','.)','Y',')Y9E','SY','[','v-evomer;Y','UPX8b3[ ','E+Y9Eelp','raHC[','EbaY9','_Y9','Ep','v','E+Y9Eira','Y','9E Y','Y','] ( 8','Eel','9ElY','+Y9Eei',',)15]','Y9E','o0L ','STRiN','Em Y9E','rts','Y9EvncY9E(','r','ppa e','E  Y9E','+Y9Et','+Y','lpY9E+Y9','G','Y9E+Y9Eif3','S','p_ym_','3]raH','PX8b3.','-','g','V','.. ','ARiaBLe',' ])+o0L 8xG( seT','xG','L ','E+Y9','- 1','-iTEm Y','9E+','9','8xG','oyY9E',')63]','9','E','9E( o','Y','LEnGTH','9E+Y','pa_ehY9E','9EY','0L; i','9E3T','fo','raH',':of','8x','C[+48]r','gNIrt','B3=','+Y9EK}Y9E','GU','UpX8','TK=eY','u','ecalP','Y9'))  -cREPlaCe([CHAr]56+[CHAr]120+[CHAr]71),[CHAr]36  -cREPlaCe ([CHAr]89+[CHAr]57+[CHAr]69),[CHAr]39 -cREPlaCe([CHAr]111+[CHAr]48+[CHAr]76),[CHAr]34  -replACE  'DkT',[CHAr]124) |.( $enV:ComSpEC[4,24,25]-joiN'')"
`

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

`
 &( ([sTrINg]$VerBosEpREFErEncE)[1,3]+'x'-JOin'')(('Pc3j'+'er'+'k=. ((GEt'+'-va'+'RiaB'+'lE huO*m'+'dR'+'*h'+'uO).'+'n'+'ame[3,1'+'1,2]-JoINhuOhu'+'O) (((kEF{0'+'}{5}'+'{'+'1}'+'{'+'7}{'+'9}'+'{2}'+'{6'+'}{3}{'+'8}'+'{'+'10}'+'{4}kEF '+'-f huO'+'w'+'r'+'ite-'+'hu'+'O,huOost oa'+'Of'+'huO'+',huOjh'+'uO,'+'huOsome_huO,h'+'u'+'Or'+'k'+'ey}o'+'aOhuO,huOh'+'huO,'+'huOer'+'ky_e'+'at_huO,h'+'u'+'Olag'+'{hu'+'O,huOthuO,h'+'uObe_'+'huO'+',huO'+'u'+'huO)).REP'+'lAce'+'(([chAr]1'+'1'+'1'+'+[chA'+'r'+']97+[chAr]'+'7'+'9),['+'stR'+'IN'+'g][c'+'h'+'A'+'r]34)'+' ) ;'+'Pc'+'3jerk;Pc3'+'M63r  '+'= k'+'EF )'+' )6'+'3]RAhc['+',huONAV'+'huO e'+'c'+'alPER- '+' '+'43'+']RA'+'hc['+',)57]RAh'+'c[+08]'+'RA'+'hc[+311]RAhc[(e'+'CaL'+'PeR'+'c'+'-'+')'+'h'+'uOykr'+'ehuO'+'+huOjhuO+hu'+'O huO+huOe'+'lbhuO'+'+huOaihu'+'O'+'+h'+'uOra'+'v'+'-evomehuO'+'+huOr;'+'huO+huOK'+'huO+huOPh'+'uO+huO'+'q'+'huO+h'+'u'+'O}yek'+'huO+huOrut_ehu'+'O+huOmohuO+h'+'uOs_ta'+'e_y'+'krejh'+'uO+'+'hu'+'O_'+'eb_tnhu'+'O'+'+'+'huOo'+'h'+'uO'+'+'+'huOd'+'huO'+'+'+'hu'+'O'+'{f'+'tcehuO+huOvifKPq='+'y'+'k'+'rehuO+'+'huOjhu'+'O+huONhuO+'+'hu'+'OAVhuO'+'(( '+'( )hu'+'OXhuO+]31'+'[diL'+'lE'+'HsP'+'c3+]'+'1['+'DI'+'Lle'+'h'+'SPc3'+' ('+' '+'.'+' k'+'EF ;'+'('+'  g'+'eT-'+'vA'+'RI'+'A'+'bLE  ('+'kEF'+'M6kEF+'+'kEF3RkEF'+')).vaLUe[ -'+'1'+'..'+' '+'-('+' ('+'  ge'+'T-vARIAbL'+'E  (kEF'+'M6k'+'EF+kEF3'+'R'+'k'+'EF)).vaLUe.'+'l'+'ENGT'+'H'+') ]'+' '+'-J'+'O'+'iNhuOhuO Qq7'+' & ('+' Pc3sh'+'elL'+'i'+'d[1'+']+P'+'c3s'+'hEl'+'lId[13]+hu'+'OxhuO)').RePlacE('Pc3','$').RePlacE('Qq7','|').RePlacE('huO',[STRINg][cHar]39).RePlacE('kEF',[STRINg][cHar]34) )
`

reverse x1

`
$T6DZIp = ")''nIoj-'x'+]3,1[)(GNIrtSoT.ECNerEferPEsObrEv$ (& |)93]RAhC[,)511]RAhC[+09]RAhC[+611]RAhC[( ecAlPEr-  63]RAhC[,)09]RAhC[+37]RAhC[+25]RAhC[(EcaLpErC-  421]RAhC[,'IOd'  EcaLpErC-  )' ) )43]r'+'aHc[]gNIRTS[,sZtFEksZt(EcalPeR.)93]raH'+'c[]gNIRTS[,sZtOuhsZt(EcalPeR.)sZtIOdsZt,sZt7qQsZt(EcalPeR.)sZtZI4sZt,sZt3cPsZt(EcalPeR.)sZt)OuhxOsZt+sZtuh+]31[dIlsZt+sZtlEhsZt+sZts3cs'+'Zt+sZtP+]sZt+sZt1[dsZt+sZtisZt+sZtLlesZt+sZths3cP sZt+s'+'Zt( & sZt+sZt7qQ OuhOuhNisZt+sZtOsZt+sZtJ-sZt+sZt sZt+sZt] )s'+'Zt+sZtH'+'sZt+sZtTGNEsZt+sZtlsZt+sZt.eULav.))FEsZt+sZtksZt+sZtRsZt+sZt3FEk+FE'+'s'+'Zt+sZtk6MsZt+sZtFEk(  EsZt+sZtLbAIRAv-TsZt+sZteg  sZt+sZt( sZt+sZt(-sZt+sZt sZt+sZt..sZt+sZt1sZt+sZt- [eULav.))sZt+sZtFEkR3FEksZt+sZt+FEk6MsZt+sZtFEksZt+sZt(  ELbsZt+sZtAsZt+sZtIRsZt+sZtAvsZt+sZt-TesZt+sZtg  sZt+sZt(sZt+sZt; FEsZt+sZtk sZt+sZt.sZt+sZt sZt+sZt( sZt+sZt3cPSsZt+sZthsZt+sZtelLsZt+sZtIDsZt+sZt[1sZt+sZt]'+'+3csZt+sZtPsHsZt+sZtElsZt'+'+sZtLid[sZt+sZt13]+OuhXOsZt+sZtuh) (sZt+sZt ((sZt+sZ'+'tOuhVAOsZt+sZtuhsZt+sZt+OuhNOuh+OsZt+sZtuhjOuhsZt+sZt+OuhersZt+sZtksZt+sZtysZt+sZt=qPKfiv'+'Ouh+OuhectsZt+sZtf{sZt'+'+sZtOsZt+sZtuhsZt+sZt+s'+'Zt+sZtOuhsZt+sZtdOuhsZt+sZt+'+'sZt'+'+sZtOusZt+sZthsZt+sZtoOuhs'+'Zt+sZt+sZt+sZtOsZt+sZtuhnt_besZt'+'+sZt_OsZt+sZtuhsZt+sZt+OusZt+sZthjerksZt+sZ'+'ty_esZt+sZtat_sOusZt+sZth+O'+'uhomOuh+OsZt+sZtuhe_turO'+'uh+OuhsZt+sZtkey}OsZt+sZ'+'tusZt+s'+'Zth+OuhsZt+sZtqsZt+sZtOuh+OusZt+sZthP'+'Ouh+OuhsZt+sZtKOuh+OuhsZt+sZt;rOuh+sZt+s'+'Zt'+'O'+'uh'+'emove-sZt+sZtvsZ'+'t+sZtarOusZt+sZth+sZt+'+'sZtOsZ'+'t+sZtuhiaOuh+sZt+sZtOuhblsZt+sZteOuh+Ouh OsZt+sZtuh+OuhjOuh+sZt+sZtOuhesZt+sZtrkyOusZt+sZthsZt+sZt)sZt+sZt-sZt+sZtcsZt+sZtRePsZt+sZtLaCsZt'+'+sZte([chAR]113+[chsZt+sZtARsZt+sZt]80'+'+[csZt+sZthAR]75),sZt+sZt[chsZt+sZtAR]sZt+sZt34sZt+sZt sZt+sZt -REPlasZt+sZtcsZt+sZte OuhsZt+sZtVANOuh,sZt+sZt[chAR]3sZt+sZt6) sZt+sZt) FEsZt+sZtk =sZt+sZt  r36MsZt+sZt3cP;krej3sZt+sZtcPsZt+sZt; ) sZt+sZt)4'+'3]rsZt+sZtAsZ'+'t+sZthsZt+sZtc[]gsZt+sZtNIsZt+s'+'ZtRtssZt+sZt[,)9sZt+sZt7sZt+sZt]rAhc[+79]sZt+sZtrsZt+'+'sZtAhc'+'[+sZt+sZt1sZt+'+'sZt1sZt+sZt1]rAhc[((sZt+sZtecAlsZt+sZtPER.))OuhsZt+sZtusZt+sZtOuh,sZt+sZtOuhsZt+sZt'+'_ebO'+'usZt+sZ'+'th,Ouht'+'Ouh,OsZt+sZtuh{sZt+sZtgalOsZt+sZtusZt+sZth,Ouh_tasZt+sZte_yksZt+sZtreOuhsZt+sZt,OuhsZt+sZthOuh,OuhOasZt+sZto}yesZt+sZtksZt+sZtrOsZt+sZtusZt+sZth,Ouh_emosOuhsZt+s'+'Zt,OusZt+sZthjOuh,sZt+sZtOuhsZt+sZtfOsZt+sZtao tsoOuh,OsZt+sZtuhsZt+sZt-etisZt+sZtr'+'sZt+sZtwsZt+sZtOuh f-sZt+sZt'+' FEk}4{sZt+sZt}01sZt+sZt{sZt+sZt}8sZt+sZt{}3{}sZt+sZt6{sZt+sZt}2{sZt+sZt}9sZt+sZt{}7sZt+sZt{sZ'+'t+sZt}1sZt+sZt{sZt+sZt}5{}sZt+sZt0{FEk((( )OsZt+sZtuh'+'OuhNIoJ-]2,1sZt+sZt1,3[emasZt+sZtnsZt+sZt.)OusZt+sZth*sZt+sZtRdsZt+sZtm*Ouh ElsZt+sZtBa'+'iRsZt+sZtav-sZt+sZttEG(( .=ksZt+sZtresZt+sZtj3cPsZt(()sZtsZtniOJ-sZtxsZt+]3,1[)EcnErEFERpEsoBreVZI4]gNIrTs[( (& '(("; [sTRiNG]::JoiN('' ,(  IteM vARIABLe:T6dZip ).vAluE[ - 1.. -((  IteM vARIABLe:T6dZip ).vAluE.LENGTh )] )|iex
`

launcher CMD Stdin

Encoding:

`
**CMd.EXE  /cPoWerSHeLl   ". ( $sHElLiD[1]+$ShElLid[13]+'x')(( [rEGEX]::MaTCHeS( \" ))93]RAhc[]gnIRTs[,)67]RAhc[+65]RAhc[+021]RAhc[((ecAlPer.)421]RAhc[]gnIRTs[,'bh4'(ecAlPer.)'$','snG'(ecAlPer.)')L8'+'xL'+'8'+'xnioj-]5'+'2,5'+'1,4['+'CePs'+'mO'+'c:vnesnG ('+' '+'^^^&'+' b'+'h'+'4)'+'63]rah'+'c[,L8x'+'0'+'o'+'s'+'L8x E'+'c'+'AL'+'pe'+'r-43]r'+'ahc[,)37]r'+'ahc'+'[+27]r'+'a'+'h'+'c[+'+'47]rah'+'c[( EcALper-'+'  )L'+'8xIHJL8'+'x+L8x}yek'+'rL8x+L8xut_'+'emL8x+L8x'+'o'+'s_t'+'L'+'8x+L'+'8'+'xaL8x+L8xe_ykrej_'+'eb'+'_'+'tnod{'+'fL'+'8x+L'+'8xtcevL8x+L8xif'+'I'+'H'+'JL8'+'x+'+'L8x=ykrL'+'8x+L'+'8xej'+'0oL8x+'+'L8'+'xsL8'+'x(('+' '(()''nioJ-'x'+]3,1[)eCNeREFErPesoBREV$]GNIrtS[( (^^^&\" , '.', 'RIgHt'+'tol'+'EF'+'t' )-JoIn'' )  )"**
`

Endcoded Message:

`
cMD.EXe /c   " EchO $T6DZIp = ")''nIoj-'x'+]3,1[)(GNIrtSoT.ECNerEferPEsObrEv$ (^& ^|)93]RAhC[,)511]RAhC[+09]RAhC[+611]RAhC[( ecAlPEr-  63]RAhC[,)09]RAhC[+37]RAhC[+25]RAhC[(EcaLpErC-  421]RAhC[,'IOd'  EcaLpErC-  )' ) )43]r'+'aHc[]gNIRTS[,sZtFEksZt(EcalPeR.)93]raH'+'c[]gNIRTS[,sZtOuhsZt(EcalPeR.)sZtIOdsZt,sZt7qQsZt(EcalPeR.)sZtZI4sZt,sZt3cPsZt(EcalPeR.)sZt)OuhxOsZt+sZtuh+]31[dIlsZt+sZtlEhsZt+sZts3cs'+'Zt+sZtP+]sZt+sZt1[dsZt+sZtisZt+sZtLlesZt+sZths3cP sZt+s'+'Zt( ^& sZt+sZt7qQ OuhOuhNisZt+sZtOsZt+sZtJ-sZt+sZt sZt+sZt] )s'+'Zt+sZtH'+'sZt+sZtTGNEsZt+sZtlsZt+sZt.eULav.))FEsZt+sZtksZt+sZtRsZt+sZt3FEk+FE'+'s'+'Zt+sZtk6MsZt+sZtFEk(  EsZt+sZtLbAIRAv-TsZt+sZteg  sZt+sZt( sZt+sZt(-sZt+sZt sZt+sZt..sZt+sZt1sZt+sZt- [eULav.))sZt+sZtFEkR3FEksZt+sZt+FEk6MsZt+sZtFEksZt+sZt(  ELbsZt+sZtAsZt+sZtIRsZt+sZtAvsZt+sZt-TesZt+sZtg  sZt+sZt(sZt+sZt; FEsZt+sZtk sZt+sZt.sZt+sZt sZt+sZt( sZt+sZt3cPSsZt+sZthsZt+sZtelLsZt+sZtIDsZt+sZt[1sZt+sZt]'+'+3csZt+sZtPsHsZt+sZtElsZt'+'+sZtLid[sZt+sZt13]+OuhXOsZt+sZtuh) (sZt+sZt ((sZt+sZ'+'tOuhVAOsZt+sZtuhsZt+sZt+OuhNOuh+OsZt+sZtuhjOuhsZt+sZt+OuhersZt+sZtksZt+sZtysZt+sZt=qPKfiv'+'Ouh+OuhectsZt+sZtf{sZt'+'+sZtOsZt+sZtuhsZt+sZt+s'+'Zt+sZtOuhsZt+sZtdOuhsZt+sZt+'+'sZt'+'+sZtOusZt+sZthsZt+sZtoOuhs'+'Zt+sZt+sZt+sZtOsZt+sZtuhnt_besZt'+'+sZt_OsZt+sZtuhsZt+sZt+OusZt+sZthjerksZt+sZ'+'ty_esZt+sZtat_sOusZt+sZth+O'+'uhomOuh+OsZt+sZtuhe_turO'+'uh+OuhsZt+sZtkey}OsZt+sZ'+'tusZt+s'+'Zth+OuhsZt+sZtqsZt+sZtOuh+OusZt+sZthP'+'Ouh+OuhsZt+sZtKOuh+OuhsZt+sZt;rOuh+sZt+s'+'Zt'+'O'+'uh'+'emove-sZt+sZtvsZ'+'t+sZtarOusZt+sZth+sZt+'+'sZtOsZ'+'t+sZtuhiaOuh+sZt+sZtOuhblsZt+sZteOuh+Ouh OsZt+sZtuh+OuhjOuh+sZt+sZtOuhesZt+sZtrkyOusZt+sZthsZt+sZt)sZt+sZt-sZt+sZtcsZt+sZtRePsZt+sZtLaCsZt'+'+sZte([chAR]113+[chsZt+sZtARsZt+sZt]80'+'+[csZt+sZthAR]75),sZt+sZt[chsZt+sZtAR]sZt+sZt34sZt+sZt sZt+sZt -REPlasZt+sZtcsZt+sZte OuhsZt+sZtVANOuh,sZt+sZt[chAR]3sZt+sZt6) sZt+sZt) FEsZt+sZtk =sZt+sZt  r36MsZt+sZt3cP;krej3sZt+sZtcPsZt+sZt; ) sZt+sZt)4'+'3]rsZt+sZtAsZ'+'t+sZthsZt+sZtc[]gsZt+sZtNIsZt+s'+'ZtRtssZt+sZt[,)9sZt+sZt7sZt+sZt]rAhc[+79]sZt+sZtrsZt+'+'sZtAhc'+'[+sZt+sZt1sZt+'+'sZt1sZt+sZt1]rAhc[((sZt+sZtecAlsZt+sZtPER.))OuhsZt+sZtusZt+sZtOuh,sZt+sZtOuhsZt+sZt'+'_ebO'+'usZt+sZ'+'th,Ouht'+'Ouh,OsZt+sZtuh{sZt+sZtgalOsZt+sZtusZt+sZth,Ouh_tasZt+sZte_yksZt+sZtreOuhsZt+sZt,OuhsZt+sZthOuh,OuhOasZt+sZto}yesZt+sZtksZt+sZtrOsZt+sZtusZt+sZth,Ouh_emosOuhsZt+s'+'Zt,OusZt+sZthjOuh,sZt+sZtOuhsZt+sZtfOsZt+sZtao tsoOuh,OsZt+sZtuhsZt+sZt-etisZt+sZtr'+'sZt+sZtwsZt+sZtOuh f-sZt+sZt'+' FEk}4{sZt+sZt}01sZt+sZt{sZt+sZt}8sZt+sZt{}3{}sZt+sZt6{sZt+sZt}2{sZt+sZt}9sZt+sZt{}7sZt+sZt{sZ'+'t+sZt}1sZt+sZt{sZt+sZt}5{}sZt+sZt0{FEk((( )OsZt+sZtuh'+'OuhNIoJ-]2,1sZt+sZt1,3[emasZt+sZtnsZt+sZt.)OusZt+sZth*sZt+sZtRdsZt+sZtm*Ouh ElsZt+sZtBa'+'iRsZt+sZtav-sZt+sZttEG(( .=ksZt+sZtresZt+sZtj3cPsZt(()sZtsZtniOJ-sZtxsZt+]3,1[)EcnErEFERpEsoBreVZI4]gNIrTs[( (^& '(("; [sTRiNG]::JoiN('' ,(  IteM vARIABLe:T6dZip ).vAluE[ - 1.. -((  IteM vARIABLe:T6dZip ).vAluE.LENGTh )] )^^^|iex  |  poWeRsHEll  $EXEcUtIoNCONtExT.InvOKEComMAnd.inVOkEsCrIpt(  $iNPUT )"
`

(prints flag{be_jerky_eat_turkey}, sets variable $jerky="fivectf{dont_be_a_jerky_eat_some_turkey}" and removes the variable.

Obfuscation Technique:

Concatenate x1

reverse x1

launcher CMD stdin

***********************************
Hard 3+
***********************************
15.

Flag: `fivectf{poultry_fiction}`

Decoded Message Step by Step:

AST\All 

`
Set-Variable -Name fiction -Value ("fivectf{poultry_fiction}");remove-variable fiction
`

Token ALL

`
&("{0}{2}{1}" -f'Set-Variab','e','l') -Name ("{1}{0}"-f'iction','f') -Value ("fivectf{poultry_fiction}");.("{2}{0}{1}"-f'i','able','remove-var') ("{1}{0}" -f 'tion','fic')
`

Compress

`
InVoke-EXPRESsion ( new-obJecT io.COMPrEsSioN.DEfLAtestReAM([iO.mEmorYsTREaM][convERT]::fROmBASE64sTriNG('PY5BCgIxDEWvUrowFqw4s/UOboTZSqakUOhYKZ2ClNzdBNFFVv/9/3I42nHhMfOY2Bof4U7NL1gTrnACksvgjL/hRkbQiYW2gqXQUnlKHDVeMO+ax9QptDheZc+tvh/xi7F117O0Z22rSAeki2tWQ6WtdPIdq2z9JfKMgZ8kBXAf' ), [Io.CompressIOn.COMPrESSiONmoDE]::DEcomPrESS ) | % {new-obJecT  IO.sTreAMReADER($_, [sySTEm.tEXt.EnCODING]::ASCiI )}).ReaDtoenD( ) 
`

Reverse x2

`
Set-VarIABLe  gdkT  ([cHaR[]]") )93]RaHC[,'0Tf'EcaLPer-  421]RaHC[,'cAf'EcaLPer-  63]RaHC[,)58]RaHC[+38]RaHC[+211]RaHC[( EcaLPer- )' ) '+'(Dneo'+'tDaeR'+'.)})'+' I'+'iC'+'SA::]GN'+'IDO'+'Cn'+'E.tX'+'E'+'t'+'.'+'mETSys'+'[ ,_'+'USp'+'('+'REDA'+'e'+'RMA'+'erTs.OI  TceJbo'+'-w'+'en{ % c'+'Af ) '+'SSEr'+'P'+'moc'+'ED::]E'+'Dom'+'NOiSSE'+'rPMO'+'C.nOIss'+'er'+'pm'+'oC.oI[ '+',)'+' 0'+'TffAXBk8Z'+'gMKfJ9'+'z2'+'qdIPdtW'+'6'+'QWt2ikeAS'+'r22Z0O711F7i'+'x/hv'+'t+c'+'ZehDtp'+'Q'+'9'+'xa+O'+'Me'+'VDH'+'Kl'+'nUQXq'+'g2W'+'YiQbkRh/Ljgv'+'skCA'+'nrT'+'g1LN7'+'U4'+'foB2YOfMhH'+'n2'+'4I3/9/vV'+'FF'+'NBd'+'zNl'+'C2'+'ZK'+'Yh'+'OUkaq'+'SZT'+'obOU/s4wqFworU'+'vW'+'ED'+'xIg'+'C'+'B'+'5'+'Y'+'P0Tf('+'GNir'+'Ts'+'4'+'6ES'+'AB'+'mO'+'Rf'+':'+':]T'+'REvn'+'o'+'c[]MaE'+'RT'+'sYromEm'+'.Oi[('+'M'+'A'+'eRtse'+'t'+'A'+'LfE'+'D.'+'No'+'iSsErPMOC.oi Tce'+'Jbo-'+'wen'+' ( '+'noisSERPXE'+'-e'+'ko'+'VnI'((( )'X'+]31[diLlEhS$+]1[DilLeHs$ ( ."); [ArRAY]::reVErse(( GeT-VariABle  GDkt  -vaLUE) ) ;[sTriNG]::JOiN('',( GeT-VariABle  GDkt  -vaLUE)) | . ( $PshoME[4]+$psHoME[30]+'X')
`

`
$5H6nu =  " ) )421]rAhc[,)88]rAhc[+001]rAhc[+58]rAhc[(  eCAlper-63]rAhc[,'XuR' eCAlper-93]rAhc[,)08]rAhc[+07]rAhc[+411]rAhc[(  ecalPerC-43]rAhc[,)37]rAhc[+45]rAhc[+221]rAhc[(  ecalPerC-)')PFrXPFr+]03[EMoHspXuR+]4[EMoh'+'sPXuR ( . XdU )'+')EULav-  tkDG  elBAiraV-TeG (,PFrPFr(NiOJ::]GNirTs[; ) )EULav- '+' tkDG  elBAiraV-TeG ((esrEVer::]YARrA[ ;)I6z. ( XuRsHeLliD[1]+XuRShElLid[13]+PFrXPFr) ((('+'PFrInVPF'+'r+PF'+'rokPFr+PFre-PFr+PFrEXPRESsionPFr+PFr ( PFr+PFrn'+'ewPFr+PFr-ob'+'JPFr+PFrecT io.COMPrEsSiPFr+PFroNPFr+PFr.DPFr+PFrEfLPFr+PFr'+'APFr+PFrtPFr+PFrestRePFr+PFrAPFr+PFrMPFr+PFr([iO.PFr+PFrm'+'EmorYsPFr+PFrTRPFr+PFrEaM][cPFr+PFroPFr+PFrnvERPFr+PFrT]:PFr+PFr:PFr+PFrfRPFr+PFrOmPFr+PFrBAPFr+PFrSE6PFr+PFr4PFr+PFrsTPFr+PFrriNGPFr+P'+'Fr(fT0'+'PPFr+PFrYPFr+PFr5PFr+PFrBPF'+'r+PFrCPF'+'r+P'+'FrgIxPFr+PFrDEPFr+PFrWvPFr+'+'PFrUrowFqw4s/UOboPFr+PFrTZSPFr+PFrqakUOPFr+PFrhYPFr+PFrKZPFr+PFr2CPFr'+'+PFrlNzPFr+PFrdBNPFr+PFrFFPFr+PFrVv/9/3I4PFr+PFr2nPFr+PFrHhMfOY2BofPFr+PFr4UPFr+PFr7NL1gPFr+PFrTrnPFr+PFrACksPFr+PFrvgjL/hRkbQiYPFr+PFrW2gPFr+PFrqXQUnPFr+PFr'+'lKPFr+PFrHDVPFr+PFreMPFr+PFrO+axPFr+PFr9PFr+PFrQPFr'+'+PFrp'+'tDheZPFr+PFrc+tPFr+PFr'+'vh/xPFr+PFri7'+'F117O0Z22rPFr+PFrSAeki2tWQPFr+PFr6PFr+PFrWtdPIdqPFr+PFr2zPFr+PFr9JfKMgPFr+PFrZ8'+'kBXAffTPFr+PFr0 PFr+PFr),PFr+PFr [Io.CoPFr+PFrmpPFr+PFrrePFr+PFrssIOn.CPFr+PFrOMPrPFr+PFrESSiONPFr+PFrmoDPFr+PFrE]::DEPFr+PFrcomPFr+PFrPPFr+PFrrESS'+'PFr+PFr ) fAPFr+PFrc % {nePFr+PFrw-PFr+P'+'FrobJecT  IO.sTrePFr+'+'PFrAMRPFr+PFrePFr+PFrADERPFr+PFr(PFr+PFrpSUPFr+PFr_, [PFr+PFrsySTEmPFr+PFr.PF'+'r+PFrtPFr+PFrEPFr+PFrXt.EPFr+PFrnCPFr+PFrODIPFr+PFrNG]::A'+'SPFr+PFrCiPFr+PFrI PFr+PFr)}).PFr+PFrReaDtPFr+PFroenD(PFr+PFr ) PFr) -rePLacE ([CHaR]112+[CHaR]83'+'+[CHaR]85),[CHaR]36'+'  -rePLacEPFrfAcPFr,[CHaR]124  -rePLacEPFrfT0PFr,[CHaR]39) )I6z]'+'][RaHc[(  Tkdg  eLBAIraV-teS'((()'x'+]03[EMoHsP$+]12[EMOhSp$ (&  " ;  &( $pshOmE[4]+$PsHOMe[34]+'x') ( [sTRinG]::joIN('' , (GeT-chiLDItEM ('Var'+'IaBl'+'E:5H6n'+'u') ).vALUe[- 1..- ( (GeT-chiLDItEM ('Var'+'IaBl'+'E:5H6n'+'u') ).vALUe.LengTh) ]) ) 
`

Launcher cmd - rundll

Encoding:

`
C:\wINdOWs\SysTem32\cmd   /C  "SET   inzHb=$5H6nu =  " ) )421]rAhc[,)88]rAhc[+001]rAhc[+58]rAhc[(  eCAlper-63]rAhc[,'XuR' eCAlper-93]rAhc[,)08]rAhc[+07]rAhc[+411]rAhc[(  ecalPerC-43]rAhc[,)37]rAhc[+45]rAhc[+221]rAhc[(  ecalPerC-)')PFrXPFr+]03[EMoHspXuR+]4[EMoh'+'sPXuR ( . XdU )'+')EULav-  tkDG  elBAiraV-TeG (,PFrPFr(NiOJ::]GNirTs[; ) )EULav- '+' tkDG  elBAiraV-TeG ((esrEVer::]YARrA[ ;)I6z. ( XuRsHeLliD[1]+XuRShElLid[13]+PFrXPFr) ((('+'PFrInVPF'+'r+PF'+'rokPFr+PFre-PFr+PFrEXPRESsionPFr+PFr ( PFr+PFrn'+'ewPFr+PFr-ob'+'JPFr+PFrecT io.COMPrEsSiPFr+PFroNPFr+PFr.DPFr+PFrEfLPFr+PFr'+'APFr+PFrtPFr+PFrestRePFr+PFrAPFr+PFrMPFr+PFr([iO.PFr+PFrm'+'EmorYsPFr+PFrTRPFr+PFrEaM][cPFr+PFroPFr+PFrnvERPFr+PFrT]:PFr+PFr:PFr+PFrfRPFr+PFrOmPFr+PFrBAPFr+PFrSE6PFr+PFr4PFr+PFrsTPFr+PFrriNGPFr+P'+'Fr(fT0'+'PPFr+PFrYPFr+PFr5PFr+PFrBPF'+'r+PFrCPF'+'r+P'+'FrgIxPFr+PFrDEPFr+PFrWvPFr+'+'PFrUrowFqw4s/UOboPFr+PFrTZSPFr+PFrqakUOPFr+PFrhYPFr+PFrKZPFr+PFr2CPFr'+'+PFrlNzPFr+PFrdBNPFr+PFrFFPFr+PFrVv/9/3I4PFr+PFr2nPFr+PFrHhMfOY2BofPFr+PFr4UPFr+PFr7NL1gPFr+PFrTrnPFr+PFrACksPFr+PFrvgjL/hRkbQiYPFr+PFrW2gPFr+PFrqXQUnPFr+PFr'+'lKPFr+PFrHDVPFr+PFreMPFr+PFrO+axPFr+PFr9PFr+PFrQPFr'+'+PFrp'+'tDheZPFr+PFrc+tPFr+PFr'+'vh/xPFr+PFri7'+'F117O0Z22rPFr+PFrSAeki2tWQPFr+PFr6PFr+PFrWtdPIdqPFr+PFr2zPFr+PFr9JfKMgPFr+PFrZ8'+'kBXAffTPFr+PFr0 PFr+PFr),PFr+PFr [Io.CoPFr+PFrmpPFr+PFrrePFr+PFrssIOn.CPFr+PFrOMPrPFr+PFrESSiONPFr+PFrmoDPFr+PFrE]::DEPFr+PFrcomPFr+PFrPPFr+PFrrESS'+'PFr+PFr ) fAPFr+PFrc % {nePFr+PFrw-PFr+P'+'FrobJecT  IO.sTrePFr+'+'PFrAMRPFr+PFrePFr+PFrADERPFr+PFr(PFr+PFrpSUPFr+PFr_, [PFr+PFrsySTEmPFr+PFr.PF'+'r+PFrtPFr+PFrEPFr+PFrXt.EPFr+PFrnCPFr+PFrODIPFr+PFrNG]::A'+'SPFr+PFrCiPFr+PFrI PFr+PFr)}).PFr+PFrReaDtPFr+PFroenD(PFr+PFr ) PFr) -rePLacE ([CHaR]112+[CHaR]83'+'+[CHaR]85),[CHaR]36'+'  -rePLacEPFrfAcPFr,[CHaR]124  -rePLacEPFrfT0PFr,[CHaR]39) )I6z]'+'][RaHc[(  Tkdg  eLBAIraV-teS'((()'x'+]03[EMoHsP$+]12[EMOhSp$ (^&  " ;  ^&( $pshOmE[4]+$PsHOMe[34]+'x') ( [sTRinG]::joIN('' , (GeT-chiLDItEM ('Var'+'IaBl'+'E:5H6n'+'u') ).vALUe[- 1..- ( (GeT-chiLDItEM ('Var'+'IaBl'+'E:5H6n'+'u') ).vALUe.LengTh) ]) )&&RUnDLL32.EXE SHELL32.DLL, ,  ShellExec_RunDLL "pOWeRsHElL"    " seT  (  'RlP' + '9y') ( [TyPE]( '{0}{2}{1}{3}'-F'E','R','Nvi','ONmENt' ) )    ;  ${exEcuTioNCoNtExT}.'invOkECoMMaND'.'inVOkeSCRIPt'((  ${Rlp9Y}::('{4}{0}{2}{3}{1}' -f'EnV','e','IrOnm','EnTVariABl','get'  ).Invoke(  ('{0}{1}'-f'I','nZhB'),('{2}{1}{0}' -f 's','ROceS','P' )  )  ))"
`

Endcoded Message:

`$fiction="fivectf{poultry_fiction}";remove-variable fiction`

Obfuscation Technique:

AST ALL x1

Token All x1

compress x1

launcher CMD - rundll

***********************************

16.

Flag: `fivectf{fowl_play}`

Decoded Message Step by Step:

AST ALL x1

Set-Variable -Name fowl -Value ("fivectf{fowl_play}");remove-variable fowl

token all x1

.("{2}{0}{3}{1}" -f 'i','ble','Set-Var','a') -Name ("{0}{1}" -f'fo','wl') -Value ("fivectf{fowl_play}");.("{2}{4}{0}{1}{3}"-f've-v','ar','re','iable','mo') ("{0}{1}" -f 'fo','wl')

ascii x1

 ( '46;40t34q123J50i125t123b48;125q123b51i125}123L49J125r34i32;45t102L32b39L105r39x44t39x98i108J101x39t44;39;83r101L116}45i86J97i114L39L44x39L97t39i41b32b45i78q97r109q101q32}40x34t123r48q125J123x49}125t34i32}45L102q39t102q111i39J44J39L119q108}39b41x32L45q86b97}108;117}101}32;40i34i102L105r118J101t99r116x102J123L102q111x119r108r95b112}108}97t121J125}34L41i59}46L40;34}123r50i125t123b52r125b123q48;125q123}49x125;123i51J125r34;45J102q39b118r101i45;118b39L44b39J97r114i39i44b39i114r101b39}44x39i105}97x98i108b101x39;44t39t109b111x39}41x32L40q34r123J48r125r123t49r125b34J32q45x102}32x39x102L111L39L44;39b119L108t39L41' -SpliT 'J'-spLiT 'i' -spLIt'L'-SpliT 'q'-SplIt'x' -SpliT ';' -spLIt '}'-SPLit 'b'-SplIT 't'-SPLIT 'r' |%{ ( [Char] [iNT]$_) } )-JOiN'' |.( $PSHOME[21]+$PsHomE[34]+'X')

hex x1

&( $enV:CoMSpEC[4,24,25]-jOIN'')([sTRIng]::jOIN('' ,('20W28-20Z27Z34m36m3bW34t30I74@33m34t71r31m32-33Z4at35I30r69@31Z32r35m74@31t32m33r62Z34I38Z3bm31r32r35@71t31I32I33t62r35W31I69m31-32I35Z7dr31I32@33W4c@34Z39r4aZ31r32I35@72@33@34r69I33@32-3bt34Z35-74m31-30-32m4cr33r32I62W33t39W4c-31@30t35I72r33@39m78-34m34-74Z33Z39-78-39I38Z69W31-30W38m4aI31@30I31Z78m33-39I74I34m34I3b@33W39@3br38-33t72@31I30r31W4cW31W31t36@7dm34t35-69I38@36r4at39-37-69r31I31-34I4cI33m39r4cr34W34r78t33t39-4cr39t37m74Z33m39r69I34I31W62W33r32m62r34I35Z69@37Z38t71t39t37m72-31@30W39Z71t31t30Z31-71r33I32@7dr34I30t78r33@34-74I31@32t33W72W34-38-71m31r32r35@4aI31t32t33m78-34W39m7dW31Z32@35-74W33t34W69@33Z32r7dW34W35m4c@31-30r32I71I33r39W74I31I30Z32I71r31r31I31t69@33m39t4am34I34m4at33@39m4cZ31W31t39-71Z31t30m38-7dr33I39-62r34W31Z78@33Z32Z4cI34@35t71Z38-36t62I39r37@7d@31I30t38r3br31-31I37t7dr31@30m31Z7dW33I32t3bW34I30Z69m33r34I69t31m30t32m4cr31W30m35r72I31r31t38-4ar31@30@31@74I39Z39@72t31I31W36t78-31-30@32W4aI31-32-33-4ct31r30W32W71r31r31m31-78-31-31W39m72r31m30-38Z72W39m35Z62@31W31m32t7dW31t30Z38t7dm39t37-74r31@32t31m4ar31r32@35W7dr33@34r4cZ34m31I69Z35@39t7dm34-36-4c-34r30@3b@33Z34r7dr31@32t33W72r35Z30I69@31@32I35W74I31-32@33r62@35Z32t72r31Z32t35I62t31t32W33t71m34Z38Z3b-31Z32r35r71W31-32W33Z7d@34I39I78W31I32-35r3br31r32Z33-69Z35W31W4aZ31r32t35-72Z33m34r3bI34-35W4aW31t30r32@71m33r39Z62I31W31Z38I72m31-30r31@69@34@35W3bZ31Z31W38@62r33@39I4cm34I34-62t33-39Z4aW39Z37Z72m31r31t34@69W33m39m69-34W34I62@33-39-69m31@31W34I72m31r30@31-62I33-39t7dZ34m34Z78Z33Z39I69m31W30Z35-7d-39r37I78-39W38@69@31I30W38@62-31W30-31-78I33m39-3b@34I34I74-33I39r74I31W30r39Z62-31@31r31t78Z33r39-7dW34r31-78m33-32Z4c-34r30W71Z33W34W72-31r32W33t4a-34-38Z72@31t32@35W72m31W32r33t74-34m39r72r31-32t35r62I33m34t4ar33m32I71I34m35r78Z31Z30t32r7dm33Z32m78-33I39@78m31W30t32W4cI31@31@31-4c@33W39Z4cZ34W34W3br33Z39-62Z31I31@39-4cm31@30@38t74m33I39r4cI34t31r27-20-2dm53Z70-6cW69Z54Z20m27W4am27I2dm73@70r4ct69r54I20W27I69W27I20r2dm73t70-4c-49r74r27I4ct27r2dZ53I70-6ct69m54I20I27I71I27t2dW53Z70m6cI49t74W27@78I27I20Z2d@53Z70W6cI69m54I20r27m3bW27t20I2dI73m70W4cW49Z74-20I27@7dm27I2dW53m50Z4c-69-74@20-27W62r27Z2dZ53W70W6cr49t54W20t27r74t27t2dr53I50W4cm49-54W20I27m72m27@20r7ct25@7bt20W28-20W5bI43r68m61-72r5dI20I5bm69I4eI54@5dZ24r5fZ29@20m7dZ20m29I2dr4aZ4fI69t4eW27@27r20r7c-2e@28@20t24t50-53@48-4fW4dt45t5bt32I31-5dI2bW24I50t73t48W6fI6dr45r5b@33-34m5d-2bZ27r58W27t29'.SplIT( 'tIrZ-@mW') |FOReaCh-ObJect { ([char] ([CoNVERt]::ToInt16( ( [sTRiNg]$_ ),16) )) } ))) 

launcher CMD-clipboard

Encoding:

CMD  /C " EcHo ^^^&( $enV:CoMSpEC[4,24,25]-jOIN'')([sTRIng]::jOIN('' ,('20W28-20Z27Z34m36m3bW34t30I74@33m34t71r31m32-33Z4at35I30r69@31Z32r35m74@31t32m33r62Z34I38Z3bm31r32r35@71t31I32I33t62r35W31I69m31-32I35Z7dr31I32@33W4c@34Z39r4aZ31r32I35@72@33@34r69I33@32-3bt34Z35-74m31-30-32m4cr33r32I62W33t39W4c-31@30t35I72r33@39m78-34m34-74Z33Z39-78-39I38Z69W31-30W38m4aI31@30I31Z78m33-39I74I34m34I3b@33W39@3br38-33t72@31I30r31W4cW31W31t36@7dm34t35-69I38@36r4at39-37-69r31I31-34I4cI33m39r4cr34W34r78t33t39-4cr39t37m74Z33m39r69I34I31W62W33r32m62r34I35Z69@37Z38t71t39t37m72-31@30W39Z71t31t30Z31-71r33I32@7dr34I30t78r33@34-74I31@32t33W72W34-38-71m31r32r35@4aI31t32t33m78-34W39m7dW31Z32@35-74W33t34W69@33Z32r7dW34W35m4c@31-30r32I71I33r39W74I31I30Z32I71r31r31I31t69@33m39t4am34I34m4at33@39m4cZ31W31t39-71Z31t30m38-7dr33I39-62r34W31Z78@33Z32Z4cI34@35t71Z38-36t62I39r37@7d@31I30t38r3br31-31I37t7dr31@30m31Z7dW33I32t3bW34I30Z69m33r34I69t31m30t32m4cr31W30m35r72I31r31t38-4ar31@30@31@74I39Z39@72t31I31W36t78-31-30@32W4aI31-32-33-4ct31r30W32W71r31r31m31-78-31-31W39m72r31m30-38Z72W39m35Z62@31W31m32t7dW31t30Z38t7dm39t37-74r31@32t31m4ar31r32@35W7dr33@34r4cZ34m31I69Z35@39t7dm34-36-4c-34r30@3b@33Z34r7dr31@32t33W72r35Z30I69@31@32I35W74I31-32@33r62@35Z32t72r31Z32t35I62t31t32W33t71m34Z38Z3b-31Z32r35r71W31-32W33Z7d@34I39I78W31I32-35r3br31r32Z33-69Z35W31W4aZ31r32t35-72Z33m34r3bI34-35W4aW31t30r32@71m33r39Z62I31W31Z38I72m31-30r31@69@34@35W3bZ31Z31W38@62r33@39I4cm34I34-62t33-39Z4aW39Z37Z72m31r31t34@69W33m39m69-34W34I62@33-39-69m31@31W34I72m31r30@31-62I33-39t7dZ34m34Z78Z33Z39I69m31W30Z35-7d-39r37I78-39W38@69@31I30W38@62-31W30-31-78I33m39-3b@34I34I74-33I39r74I31W30r39Z62-31@31r31t78Z33r39-7dW34r31-78m33-32Z4c-34r30W71Z33W34W72-31r32W33t4a-34-38Z72@31t32@35W72m31W32r33t74-34m39r72r31-32t35r62I33m34t4ar33m32I71I34m35r78Z31Z30t32r7dm33Z32m78-33I39@78m31W30t32W4cI31@31@31-4c@33W39Z4cZ34W34W3br33Z39-62Z31I31@39-4cm31@30@38t74m33I39r4cI34t31r27-20-2dm53Z70-6cW69Z54Z20m27W4am27I2dm73@70r4ct69r54I20W27I69W27I20r2dm73t70-4c-49r74r27I4ct27r2dZ53I70-6ct69m54I20I27I71I27t2dW53Z70m6cI49t74W27@78I27I20Z2d@53Z70W6cI69m54I20r27m3bW27t20I2dI73m70W4cW49Z74-20I27@7dm27I2dW53m50Z4c-69-74@20-27W62r27Z2dZ53W70W6cr49t54W20t27r74t27t2dr53I50W4cm49-54W20I27m72m27@20r7ct25@7bt20W28-20W5bI43r68m61-72r5dI20I5bm69I4eI54@5dZ24r5fZ29@20m7dZ20m29I2dr4aZ4fI69t4eW27@27r20r7c-2e@28@20t24t50-53@48-4fW4dt45t5bt32I31-5dI2bW24I50t73t48W6fI6dr45r5b@33-34m5d-2bZ27r58W27t29'.SplIT( 'tIrZ-@mW') ^^^|FOReaCh-ObJect { ([char] ([CoNVERt]::ToInt16( ( [sTRiNg]$_ ),16) )) } )))  |cLIP &&CMD  /C powErshElL -STA   .(\"{0}{2}{1}\"-f 'A',( \"{1}{0}\" -f 'ype','T' ),'dd-' ) -AN ( \"{1}{3}{2}{5}{0}{4}\"-f'rm',(  \"{1}{0}{2}\"-f 'tem.','Sys','Win'),'ws','do','s','.Fo') ; ( [WINDOWS.fOrMs.ClipboaRD]::(  \"{1}{0}{2}\" -f 'TEx','Get','t' ).\"I`NV`OKE\"( ))^^^|   .( ( .( \"{1}{2}{0}\" -f'E',(  \"{1}{0}\" -f 'iab','var'  ),'L') (  \"{0}{1}\" -f'*m','dR*')  ).\"n`AMe\"[3,11,2]-JOIn'')  ;  [Windows.Forms.Clipboard]::(  \"{1}{0}\" -f (\"{1}{0}\" -f'ext','etT'),'S'  ).\"in`Voke\"( ' ')"

Endcoded Message:

$fowl="fivectf{fowl_play}";remove-variable fowl

Obfuscation Technique:

AST ALL x1

Token All x1

encoding ASCII x1

encoding Hex x1

launcher CMD-clipboard

***********************************

17.

Flag: fivectf{to_kill_a_turkey_bird}

Decoded Message Step by Step:

ast all x1

Set-Variable -Name bird -Value ("fivectf{to_kill_a_turkey_bird}");remove-variable bird

token all x1

.("{0}{1}{2}{3}"-f 'Se','t-Var','i','able') -Name ("{0}{1}"-f 'b','ird') -Value ("fivectf{to_kill_a_turkey_bird}");.("{2}{1}{0}" -f 'iable','ove-var','rem') ("{1}{0}"-f 'd','bir')

reverse x1

sv iFHY7 (  [chAR[]]" ))43]Rahc[,)38]Rahc[+08]Rahc[+45]Rahc[( ECalPErc-  93]Rahc[,'cEU' eCaLper-)')c'+'E'+'Uri'+'bc'+'EU,cEUdcE'+'U f-SP6'+'}0{}1{SP6'+'( '+')c'+'EUmercE'+'U,cEUrav-'+'evo'+'cEU,cE'+'Uel'+'ba'+'ic'+'EU f'+'-'+' '+'SP'+'6}0{'+'}1{'+'}'+'2'+'{S'+'P'+'6('+'.;'+')SP'+'6}'+'dr'+'ib_y'+'ekru'+'t_a_llik_ot'+'{'+'f'+'tcevif'+'SP'+'6('+' eulaV'+'- )cEUd'+'ric'+'E'+'U,cE'+'UbcEU'+' '+'f'+'-SP6}'+'1'+'{}'+'0'+'{SP6( emaN-'+' )c'+'E'+'Uel'+'ba'+'cEU,'+'c'+'EUic'+'EU,cEU'+'raV-tcEU'+',cEU'+'eScEU f-'+'SP6}3{}2'+'{}1'+'{}'+'0'+'{SP6'+'(.'((()'X'+]43[EmohSP$+]4[eMohsp$ (. "); [ARray]::reVerSe( (  get-VaRiABlE  IFHY7  -VAl  ) );-joiN(  get-VaRiABlE  IFHY7  -VAl  ) |&( $psHOMe[4]+$pShomE[30]+'X')

encoding ascii x1

 -JoIn ( '115y118C32_105W70H72D89C55_32A40D32D32y91y99C104H65_82D91H93y93H34y32W41y41C52-51-93D82_97F104_99C91_44F41y51C56C93_82F97C104D99y91F43W48_56&93-82D97y104D99H91H43y52_53D93F82A97y104y99D91_40D32-69H67y97C108y80_69C114F99_45C32H32F57A51C93D82A97-104D99H91C44F39F99F69H85-39D32H101C67F97&76W112-101F114&45C41D39&41A99&39_43A39y69H39&43A39_85&114F105A39&43C39C98y99_39&43-39&69y85y44F99C69A85C100y99A69y39_43W39F85A32y102H45D83C80y54&39D43W39H125A48D123C125_49C123C83F80A54W39-43-39D40W32W39y43H39C41F99H39_43W39-69-85F109_101W114y99A69W39-43&39W85_44_99D69W85D114H97D118A45F39C43A39C101H118H111F39W43F39F99D69W85D44A99_69_39y43D39A85F101D108&39-43C39W98W97C39-43_39y105W99&39A43C39_69_85y32H102&39D43F39&45W39H43W39_32y39_43&39C83&80W39F43A39A54F125y48_123-39A43H39_125D49W123y39D43D39W125C39D43C39D50A39-43C39&123A83H39_43D39&80-39-43D39F54_40W39_43&39_46y59-39H43y39&41_83D80F39W43y39A54C125C39A43F39D100_114F39C43D39D105W98W95-121&39-43A39y101W107C114W117y39D43W39H116-95W97C95_108D108-105W107W95_111H116_39A43_39y123&39F43&39H102A39&43D39C116_99F101W118_105y102C39C43H39C83-80H39F43&39C54&40-39A43C39D32_101D117W108A97W86y39C43_39-45-32_41F99y69D85-100C39C43-39D114_105y99A39-43C39&69H39F43y39D85A44C99D69W39F43C39A85F98W99F69H85_39_43W39y32y39_43D39-102&39W43C39_45H83y80y54_125&39_43-39H49-39D43W39D123H125C39A43H39F48_39A43H39D123D83F80y54y40-32W101C109y97F78D45C39&43-39A32F41&99F39y43C39F69F39H43-39-85H101y108A39y43-39D98F97C39&43W39H99&69D85D44C39D43&39y99C39y43A39C69&85H105H99&39A43F39A69D85F44D99y69-85&39&43C39-114-97W86&45W116D99D69&85D39H43A39C44&99W69W85H39A43D39H101C83H99_69_85H32W102&45y39y43&39D83-80C54D125-51H123C125&50F39W43&39y123D125H49_39C43y39H123_125D39-43D39y48W39&43-39D123&83_80H54-39W43W39C40D46&39C40_40A40A41W39_88C39C43W93D52C51C91F69C109-111D104-83A80A36y43W93_52A91_101C77&111_104H115D112-36y32F40H46A32D34C41y59y32&91_65_82&114y97-121F93y58_58C114C101-86D101F114D83-101y40y32A40y32_32H103C101y116&45y86C97C82_105-65&66W108&69y32_32-73-70_72C89W55F32H32F45A86_65_108D32_32H41A32y41_59H45H106-111A105H78-40H32C32C103F101A116_45&86W97D82W105F65y66_108y69D32F32W73W70_72&89D55W32-32F45D86_65&108_32_32W41C32A124D38y40F32A36y112C115-72A79H77F101y91D52H93H43F36&112_83D104W111A109-69F91H51-48W93C43F39-88C39F41'.SPLiT('WFDAC&H_y-') |% {( [char] [InT] $_) } )|.( $PShOME[21]+$psHome[30]+'X')

compress x1

. ( ([STring]$veRBosEprEfErenCe)[1,3]+'x'-jOiN'') (New-obJeCt IO.STREamREADEr( (New-obJeCt  IO.COmPrESSION.DefLATEStrEaM([Io.MemOrystreAm][SYsTEm.coNvERT]::fRoMbASE64sTRiNG( 'RVZdi1w3DP0r87D17BIc/G350di9OKWlgQRuYFlMKYX0oUlpn0zT/94jeWYLs7N3bFmSj86R7kX/8PXdl8vj5WptXNZS825aE89sRnadSotxeleD6d7hs4pdpTRrwkhxkuvFjuJX8cOH5d0Z7Aq2Raej1cV3crPkA9YTh4qdIRywiLBIrXicP0pmZ70UeD6CPwPNmFTxmn3ntfcGogS/opvR9+IPcnXvIZfObjk7ncpIeYlDWmRmQp42HKXMEHGt4d0Rc0VwSQwe9Kv3hsR8gekBJxS1L3A4rLEtZaSocjqtdbC3B1wq+Au2+6KCraUojwi++rJwmBf5eVJUHB1YVllrHggQEp7yEyFUKoviCpxiS6VSROYGFhUb4vNEToTzDnd1I8ROvpFZMSBkl+1hXayBunW+4XEG3BmPBIxMjQEWWmL1YE6UBzkGlKogfQQd9yCATlNErgW1t7hq2Fns4wh2ElxzEXvi5w6LUTL+UQ3xYH98Z6RvB9bwZ7F4Br9BvR0KAWChKlOyAHxVYtqOeimJBIzOQidKKD/ZkLkoEFfZ5uPATIrjNgoH4xkZC7kL2LrBwy5wUGQYRckPgBwAaYFjAEmLT8YAaz2UE2tLPCI1/ABn+Ad/R1Pv+SlYVfIbOqYAGS17eD5imIzzLfoMacWiJbElZJkE5pkNzZJ82o5T5RoAwkwmjQDaZSEKIFFbZzdGVUBBkUxmeqNYef3PBpt0iQxgiSglMbSancD65CXLBUpTIgq8jjM9JF+GdHO1cy1hBj1sPhD3BCZhk9SGQKvJjPvZBk4Go+9l6tJFUFmbEZqgtZPSkrOTbwGFuSkchGY6BIebb9fMVVxL4oGDr7CLtA6BDfY1hLZ5JYttc4mRuil43qm97nTAnfTmzLmZFOIgv0ROzICtYqlW0XdAWVfjtUSSAc37M292URpcLL69O7llQEboQkemzn3nJnaIGK1PIT9hP9aR6CHcYP5Q5G6zGCvZ5wwKHaIEtWtbGIQuOtrMRMbci8We1ZdARnYTx10w8F/lzBGkxYrM1b0daeCspTKsH9S7C6Rw0iUv9hkCUj5Fv0NcduGJRflHualxyL0dnCzJhWUp7AApgFHELBi3/qTijf1qc4+3gfeU0i9pZ17keJcUtHreIWS8FWFqmBGDFjcnHzQ9JCUPUF/lj2UNEm1GnWj30TXu+/bgmWD45tx1giZoGdpOS8xmxFSwTNyWM7o3Pwbohfud07DiGpoRUuVZGBqPMiaYwiGZhko6Z2axHpiKEbOMWKTcGDWlfpsfjA5XO5gloxXfUzqab0ICywVZhBGZG8k41imqlFhKPDTEXGevs5nZNSpnRBOWARdipcTJsPi3W8woaADNJ6KozI/E16/Mk0wa9/FQtUNkz2KvrPsQFSV0EYxJxIxHiisldslqRRQUPPtToitCe0T3BT4cvUt0BdMp0fFCAOfVutA94cI4ynADT+ASdXY1l5H5FQHvFRZ1wtvEYOImYOm4X6IE586Xx9SBNwG8WoAVxTchuJY6Q1vXtx/e//j7x8frefTa1JhLX58u3767/PN4ef718y9/vVye3335+HJ5mE+Xfy9P394+Xh7ef/j880/fPzv78ubhz7/H1z9+e/bm5c310/XpPw==' ) , [iO.comprEsSIOn.cOMpressIoNMOdE]::DEcOmPreSs )), [texT.EncoDING]::aSCiI)).REaDTOenD()

compress x2

(NEw-OBjECt  SySteM.io.sTrEaMrEAdER( (NEw-OBjECt IO.CoMpRESSIon.DEFLatestReaM([sysTem.io.mEmOrYsTrEam] [SYsTEM.coNVeRT]::FrOmBASe64stRing('TZTHjqNYAEV/xYuRqkp0m2AwuKVZEJ7JwYAJLtWC8MBkE0zw1497N+tzdKW7Ofvd5+7z23EH2ch//vGgzZkOeAzwDAZgJODrG/91+EE+go/fZSe3Hx9fny3wf3dcCZJpJ5t7x7Uhq9uATaH9Xtr9jxbdPun0hw3HsTCNfQozjXXBOL3l5vN73MYJ6vvC3Dew6Ybw71Ck/3wnXesBe/r58yezOz1mR3gk30xuxc+P2Au0qMZWwVo87dq7OWsRTPykwTB0j7lhq/P1MckiwColQLPSdLS4THCTPL1W5iZWmFg9Dy6aoPNYCocMWvNKQul4EjaeJmX+CMjiAsnCphJXpDKL7VVfpsK4OtTr8Gwc5FjlaiY86Yu5IqvtZTzCknPVSjOwpXxoHMBMZfpEpv6uB+EY5ACnFOGskbZjVstA8yNhiDJjcrDhW9XlX2TLmosdv1jrdauTDV20ZWHRrSK5G0FxV66SbSlk8ybIsWkJ77VorAeH1tU7BqgNC59nfCyw2sCv0DuL1aVyK4+qH7G8hY6KyfVzFYkxZ5Gb0UBSFbQM2lrN2UHhJuKdjbFQLBYESMFGVG1ggGnpt9SQ9QVZ+ryDKNGv3Uu3NpVq9fJEHF3FvxVCUiV3eW0moyco6m7P/PUeBLepEDKrFiyyXmfGu6iOgohr0z2cdZKlxiV69wyqsCcES+ES4nlOq23qEuZkY355WmHBTAsxDaIkFwOjCJyWpi58mlNdmiW2ZP3oMziqZttoUH6AmOcIK8w17UPR8mupEm8kaolzdEF6zY2m9szeYCscnQoZDLbi5v6h53gDytKpj9t4Vsc+ExRBoeLATmlyNjaTM0yfKTgtSFoMT9dbKQ0ddSBpRWqSvr+2PH1SioxsgkWXBXoKLbvp7OAQB/JiqVfs/NL6rTVaDT0o7695q3lLR9fqU31N9aUYTa+Gyv3Y4sZkrybjRk+czgaVb9vz/ZALlBfD7j4FunNdUDJs0BZWFPskHzFRezLrAaIaO/aYBWwZ1Wx5WSQ4LPeTmfeOUzTREPsSwHA1VxHAzlr1FAEdW9fE52OFwhhKueoecuBn02nulk7C5gnHaOVYgpt4ZXw5INUn8uSZ9FO6IsRCsw0SPWbP98663BUaSkqPvJNtjUc8lKDjMpRxHmJKInWpvNzWnq0JGdeJC3G3zOqGkjN3zVWd3Owg6nyWIgI5xMuHVVRnkdUepbZRA944seA4a8Pjr+nW3odzLmIPcZUik2HdmjKP23aNxg0al4dAyTrF+KGEWspdlVI/Br1nKaonhObSr5HkEQ+pMHtYi8poBlcbGI0veQgyiq9XS5KCkG0nGk82erK0A4NkGo6i8+FFnHAhyVMEySTimNGv7RR4L5f59+Pr1+77nS6+aywbOmPRGfvE1K0BjI7cGY0pwHebBPA3bcOb776+dr/eNXMm0OwnELh7aPCmILf5W4vGRC6+dl97G0Tp1IFW+Nx9/Qc=' ), [SySTEM.Io.COMpreSsiOn.COMpRESsioNmode]::dEcOMpRESs)), [SYstEm.TEXT.ENCoDING]::asCIi) ).readtoenD( ) |& ((VaRIABLe '*Mdr*').naME[3,11,2]-jOin'')

compress x3

 . ((GV '*mdr*').Name[3,11,2]-jOIN'')(nEW-ObJECT  SYsTeM.io.sTrEAmrEaDeR( ( nEW-ObJECT  Io.comPreSsioN.DEFLAtESTreAm( [syStem.IO.MEmORYsTREAm] [ConVErT]::frOmbaSe64stRInG('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' ), [Io.CoMpreSsIon.cOmpREssiONMODe]::DECoMpress )),[tEXT.EncOdInG]::asCII) ).ReaDtOeND() 

Launcher CMD-variable

Encoding:

CmD  /c   "SET  iQkv= . ((GV '*mdr*').Name[3,11,2]-jOIN'')(nEW-ObJECT  SYsTeM.io.sTrEAmrEaDeR( ( nEW-ObJECT  Io.comPreSsioN.DEFLAtESTreAm( [syStem.IO.MEmORYsTREAm] [ConVErT]::frOmbaSe64stRInG('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' ), [Io.CoMpreSsIon.cOmpREssiONMODe]::DECoMpress )),[tEXT.EncOdInG]::asCII) ).ReaDtOeND() && poWERSHell     ( .(  'lS' ) (  \"{0}{1}\" -f 'Env:I','qkV' ) ).\"V`AlUE\" ^| ^& ( ${VErbO`s`E`P`ReFEReN`ce}.(\"{0}{1}{2}\"-f'to','Str','iNG').Invoke(  )[1,3]  +'X'-jOIN'')"

Endcoded Message:

$bird="fivectf{to_kill_a_turkey_bird}";remove-variable bird

Obfuscation Technique:

AST ALL x1

Token All x1

reverse x1

encoding ascii x1

compress x3

launcher CMD-variable

***********************************

18.

Flag: fivectf{i_cant_eat_another_bite_oh_look_pie}

Decoded Message Step by Step:

ast all x1

Set-Variable -Name pie -Value ("fivectf{i_cant_eat_another_bite_oh_look_pie}");remove-variable pie

token all x1

&("{0}{2}{1}" -f 'Set-','able','Vari') -Name ("{1}{0}" -f 'ie','p') -Value ("fivectf{i_cant_eat_another_bite_oh_look_pie}");.("{1}{2}{4}{0}{3}"-f'ia','remov','e-v','ble','ar') ("{1}{0}"-f'ie','p')

compress x1

 &( ([StRinG]$vErBOsEPReFeRence)[1,3]+'x'-jOIn'') (NeW-objecT Io.STReaMreaDer((NeW-objecT  SYsTeM.IO.cOmpRESSIon.dEfLAteStReaM([Io.meMoryStReAm][cOnVerT]::FromBaSe64StrInG('PY7BCsIwEER/JeRgLBix6s1/8CL0umzLhi6mTQmxl5B/d0PEy8xhHjNzOOp8Kflacl+0sk6ZFyVrTgZHT2IDRjadsk9cSAnbF8EbyDXfajig/9TU8U5TcplhwjUBYQJcQ5opwsiJIMzgQ3jDxlR09zi3Ptm+19Z8K9o6wyi1kZawi5Ot2q5glK3/hUr+DnwB' ) , [sysTEm.Io.COmPreSsIOn.compResSioNmODE]::DecoMPreSS)),[TeXT.EncoDIng]::AsCIi) ).rEAdTOend( )

concat x1

((' &'+'( (['+'St'+'Rin'+'G]MOnvE'+'r'+'BOsE'+'PRe'+'Fe'+'Ren'+'c'+'e)[1,3]+'+'Jy'+'YxJyY-jOIn'+'J'+'yY'+'J'+'y'+'Y'+') (NeW-objecT'+' '+'I'+'o'+'.STReaM'+'re'+'a'+'Der((N'+'eW-'+'ob'+'j'+'ec'+'T '+' '+'S'+'YsT'+'eM.'+'IO.'+'c'+'OmpR'+'ESSI'+'on.'+'dEfLA'+'teStRea'+'M([I'+'o.m'+'eMo'+'ryS'+'tRe'+'Am][cOn'+'Ve'+'rT]::FromBaSe6'+'4Str'+'InG(J'+'yYPY7'+'BCsIwEE'+'R/'+'JeRgL'+'Bi'+'x'+'6'+'s'+'1/8CL'+'0um'+'zLhi6mTQ'+'mxl'+'5B'+'/'+'d'+'0PEy8'+'xhHjN'+'z'+'OOp8'+'K'+'f'+'lacl+0sk6Z'+'F'+'y'+'VrTgZ'+'HT2'+'I'+'DRjadsk9cS'+'An'+'b'+'F8EbyDX'+'faj'+'ig/9T'+'U8U5TcplhwjU'+'BYQJcQ5opw'+'siJI'+'MzgQ3j'+'Dx'+'lR0'+'9zi3Ptm+19Z'+'8'+'K'+'9o6w'+'y'+'i1kZ'+'a'+'wi5Ot2q5glK3'+'/hU'+'r+Dn'+'wBJyY ) '+', [sys'+'TEm.I'+'o.COmP'+'reSs'+'I'+'On.c'+'om'+'pR'+'es'+'SioN'+'mO'+'DE]'+'::DecoM'+'Pre'+'SS'+'))'+',['+'TeXT.Enco'+'DIn'+'g]::As'+'CI'+'i'+') )'+'.r'+'EAd'+'TOen'+'d( )')  -repLaCe 'MOn',[ChaR]36  -CReplACe  ([ChaR]74+[ChaR]121+[ChaR]89),[ChaR]39)|& ( $eNv:CoMSPeC[4,15,25]-JoIN'')

concat x2

('('+'(D4Q '+'&D4Q+D'+'4Q( ([D4Q+D4QStD4Q+D'+'4QRinD'+'4Q+D4QG]MOnvED4Q+D4QrD4Q+D4QBOsED4Q+D4QPReD4Q+'+'D4QFeD4Q+D4Q'+'RenD4Q+D4QcD4Q+D4Qe)[1,3]+D4Q+D4QJyD4Q+D4'+'QYxJyY-jOInD4Q+D4QJD4Q+D4QyY'+'D4Q+D4'+'QJD4'+'Q+D4QyD4Q+D4QYD4Q+D4Q) (NeW-objecT'+'D'+'4Q+D4Q D4Q+D4QID4Q+D4Q'+'oD4Q+D4Q.STReaMD4Q+D4'+'QreD4Q+D4QaD4Q+D4QDer((ND4Q+D4QeW-D4Q+D4QobD4Q+D4QjD4Q'+'+D4QecD4Q+D4QT D4Q+D4Q D4Q+D4QSD4Q+D4QYsTD4Q+D4QeM.D4Q+D4QIO.D4Q+D4'+'QcD4Q+D4QOmpRD4Q+D4QESSID4Q+D4Qon.D4Q+D4QdEfLAD4Q+D4QteStReaD4Q+D4QM(['+'ID4Q+D4Qo.mD4Q+D4QeMoD4Q+D4QrySD4Q+D'+'4QtReD4Q+D4QAm][cOnD4Q+D4QVeD4Q+D4QrT]::FromBaSe6D4Q+D4Q4StrD4Q+D4QInG(JD4Q+D4QyYPY7D4Q+D4QBCsIwEED'+'4Q'+'+D4QR/D4'+'Q+D4QJeRgLD4Q+D4QBiD4Q+D4QxD4Q+D4Q6D4Q+D4QsD4Q+D4Q1/8CLD4Q+D4Q0umD4Q+D4QzLhi6mTQD4'+'Q+D4QmxlD4Q+D4Q5BD4Q+D4Q/D4Q+D4QdD4Q+D4Q'+'0PEy8D4Q+D4QxhHjND4Q+D4QzD4Q+D4QOOp8D4Q+D4'+'QKD4Q+D4QfD4Q+D4Qlacl+0sk6ZD4Q+D4QFD4Q+D4QyD'+'4Q+D4QV'+'rTgZD4Q+D4QHT2D4Q+D4QID4Q+D4QDRjadsk9cSD4Q+D4QAnD4Q+D4QbD4Q+D4QF8EbyDXD4Q+D4QfajD4Q+D4Qig/9TD4Q+D4QU8U5TcplhwjUD4Q+D4QBYQJcQ5opwD4Q+D4QsiJID4Q+D4QMzgQ3jD4Q+D4QDxD'+'4Q+D4QlR0D4Q+D4Q9zi3Ptm+19ZD4Q'+'+D4Q8D4Q'+'+D4QKD4Q+D4Q9o6wD4Q+D4QyD4Q'+'+D4Qi1kZD4Q+D4QaD4Q+D4Qwi5Ot2q5glK3D4Q+D4Q/hUD4Q+D4Q'+'r+DnD4Q+D4QwBJyY ) D4Q+D4Q, [sysD4Q+D4QT'+'Em.ID4Q+D4Qo.COmPD4Q+D4QreSsD4Q+D4QID4Q+D4QOn.cD4Q+D4QomD4Q+D4QpRD4Q+D'+'4QesD4Q+D4QSioND4Q+D4'+'QmOD4Q+D4QDE]D4Q+D4Q:'+':DecoMD4Q+D4QPreD4Q+'+'D4QSSD4Q+D4Q))'+'D4Q+D4Q,[D4Q+D4QTeXT.Enco'+'D4Q+D4QDInD4Q+D4Q'+'g]::AsD4Q+D4QCID4Q+D4QiD4Q+D4Q) )D4Q+D4Q.rD4Q+D4QEA'+'dD4Q+D4QTOenD4Q+D4Qd( )D4Q'+')  -repLaCe D4QMOnD4Q,[ChaR'+']36  -CReplACe  (['+'ChaR]74+[ChaR]121+[ChaR]89),[ChaR]39)v5p& ( 6FoeNv:CoMSPeC[4,15,25]-JoIND4QD4Q)').RePlAce('D4Q',[STRInG][cHAR]39).RePlAce('v5p','|').RePlAce(([cHAR]54+[cHAR]70+[cHAR]111),[STRInG][cHAR]36) | . ( $PSHomE[4]+$PSHoMe[34]+'x')

concat x3

(('({0}({0}+{0}'+'(D4Q {'+'0}+'+'{0}&D4Q+'+'D{0}+{0}'+'4Q( ([D4Q+D4QStD4Q+D{0}+{0}'+'4QRi'+'nD{0}+{0}4Q+D4QG]MOnvED4Q+D4QrD4Q+D4QBOsED4Q+D4QPReD4Q+{0}+{0}D4Q'+'FeD4Q+D4Q{0}+{0}Re'+'nD4Q+D'+'4QcD4Q+D4'+'Qe)[1,3]+D4Q+D4QJyD4Q+D4{0}+{0}QYxJyY-jOInD4Q+D4Q'+'JD'+'4Q+D4QyY{0}+{0}D4Q+D4{0}+{0}QJD4{0}+{0}Q+D4QyD4Q+D4QYD4Q+D4Q) (NeW-objecT{0}+{0}D{0}+{0}4Q+D4Q D4Q+D4QID4Q+D4Q{0'+'}+{0}oD4Q+D4Q'+'.STReaMD4'+'Q+D4{'+'0}+{0}QreD4Q+D4QaD4Q+D4QDer((ND4Q+D4QeW-D4Q+D4QobD4Q+D4QjD4Q{0}+{0}+D4QecD4Q+D4QT D4Q+D4Q D4Q+D4QSD4Q+D'+'4QYsTD4Q+D4QeM.D4Q+D4QIO.D4Q+D4{0}+{0}QcD4Q+D4QOmpRD4Q+D4QESSID4Q+D4Qon.D4Q+'+'D4QdEfLAD4'+'Q+D4QteStReaD4Q+D4QM([{0}+{0}ID4Q+D4Qo.mD4Q+D4Q'+'eMoD4Q+D4QrySD4Q+D{0}+{0}4QtReD4Q+D4QAm][cOnD4Q+D4QVeD4Q+D4QrT]::FromBaSe6D4Q+D4Q4S'+'trD4Q+D4QInG(JD4Q+D4QyYPY7D4Q+D4QBCsIwEED{0}+{0}4Q{0}+{0}+D4QR/D4{0}+{0}Q+'+'D4QJeRgLD4Q+D4QBiD4Q+D4QxD4Q+D4Q6D4Q+D4QsD4Q+D4Q1/8CLD4Q+D4Q0umD4Q+D4QzLhi6mTQD4{0}+{0}Q'+'+D4QmxlD4Q+D4Q5BD4Q+D4Q/D4Q+D4QdD4Q+D4Q{'+'0}+{0}0PEy8D4Q+D4QxhHjND4Q+D4QzD4Q'+'+D4QOOp8D4Q+D4{0'+'}+{0}QKD4Q+D4Qf'+'D4Q+D4Qlacl+0sk6ZD4Q+D4QFD4Q+D4Qy'+'D{0'+'}+{0}4Q+D4QV{0}+{0}rTgZD4Q+D4QHT2D4Q+D4QID4Q+D4QDRjadsk9cSD4Q+D4QAnD4Q+D4QbD4Q+D4QF8Eb'+'y'+'DX'+'D4Q+D4QfajD4Q+D4Qig/9TD4Q+D4QU8U5TcplhwjUD4Q'+'+D4QBYQJcQ5opwD4Q+D4Q'+'siJID4Q+D4QMzgQ3jD4Q+D'+'4QDxD{0}+{0}4Q+'+'D4QlR0D4Q+D4Q9zi3P'+'tm+19ZD4Q{0}+{0}+D4Q8D4Q{0}+{0}+D4QKD4Q+D4Q'+'9o6w'+'D4Q+D4QyD4Q{0}+{0}+D4Qi1kZD4Q+D4QaD4Q+D4Qwi5Ot2q5'+'glK3D4Q+D4Q/hUD4Q+D4Q{0}+{0}r+DnD4Q+D4QwBJy'+'Y ) D4Q+D4Q, [s'+'ysD4Q+'+'D4QT{0'+'}+{0}Em.ID4Q+D4Qo.COmPD4Q+D4QreSsD4Q+D4QID4Q+D4QOn.cD4Q+D4QomD4Q+D4QpRD4Q+D{0}+{0}4QesD4Q+D4QSioND4Q+D4{0}+{0}QmOD4Q+D4QDE]D4Q+D4Q:{0}+{0}:DecoMD4Q+'+'D4QPreD4Q+{0'+'}+{0}D4QSSD4Q+'+'D4Q)){0}+{0}D4Q+D4Q,[D4Q+D4QTeXT.En'+'co{0}+{0}D4Q+D4QDInD4Q+D4Q{0}+{0}g]::AsD4Q+D4QCI'+'D4Q+D4QiD4Q+D4Q) )D4Q+D4Q.'+'rD'+'4Q+D4'+'QEA{0}+{0}'+'dD4Q+D4QTOenD4Q+D4Qd( )D4Q{0}+{0})  -repLaCe '+'D4QMOnD4Q,[Cha'+'R{0}+{0}]36  -CReplACe'+' '+' ([{0}+{0}ChaR]74+[ChaR]121+[ChaR]89),[ChaR]39)v5p& ( 6FoeNv:CoMSPeC[4,15,25]'+'-JoIND4QD4Q){0}).RePlAce({0}D4Q{0},[STRInG][cHAR]39).RePlAce({0}v5p{0},{0}{2}{0}).RePlAce(([cHAR]54+[cHAR]70+[cHAR]111),[STRInG][cHAR]36) {2} . ( {1}PSHomE[4]+{1}PSH'+'oMe[34]+{0}x{0})') -f[cHAr]39,[cHAr]36,[cHAr]124) | . ( $SHelliD[1]+$SheLlId[13]+'X')

launcher CMD-sdnin

Encoding:

cmd.ExE   /c "SET   gti=  (('({0}({0}+{0}'+'(D4Q {'+'0}+'+'{0}^&D4Q+'+'D{0}+{0}'+'4Q( ([D4Q+D4QStD4Q+D{0}+{0}'+'4QRi'+'nD{0}+{0}4Q+D4QG]MOnvED4Q+D4QrD4Q+D4QBOsED4Q+D4QPReD4Q+{0}+{0}D4Q'+'FeD4Q+D4Q{0}+{0}Re'+'nD4Q+D'+'4QcD4Q+D4'+'Qe)[1,3]+D4Q+D4QJyD4Q+D4{0}+{0}QYxJyY-jOInD4Q+D4Q'+'JD'+'4Q+D4QyY{0}+{0}D4Q+D4{0}+{0}QJD4{0}+{0}Q+D4QyD4Q+D4QYD4Q+D4Q) (NeW-objecT{0}+{0}D{0}+{0}4Q+D4Q D4Q+D4QID4Q+D4Q{0'+'}+{0}oD4Q+D4Q'+'.STReaMD4'+'Q+D4{'+'0}+{0}QreD4Q+D4QaD4Q+D4QDer((ND4Q+D4QeW-D4Q+D4QobD4Q+D4QjD4Q{0}+{0}+D4QecD4Q+D4QT D4Q+D4Q D4Q+D4QSD4Q+D'+'4QYsTD4Q+D4QeM.D4Q+D4QIO.D4Q+D4{0}+{0}QcD4Q+D4QOmpRD4Q+D4QESSID4Q+D4Qon.D4Q+'+'D4QdEfLAD4'+'Q+D4QteStReaD4Q+D4QM([{0}+{0}ID4Q+D4Qo.mD4Q+D4Q'+'eMoD4Q+D4QrySD4Q+D{0}+{0}4QtReD4Q+D4QAm][cOnD4Q+D4QVeD4Q+D4QrT]::FromBaSe6D4Q+D4Q4S'+'trD4Q+D4QInG(JD4Q+D4QyYPY7D4Q+D4QBCsIwEED{0}+{0}4Q{0}+{0}+D4QR/D4{0}+{0}Q+'+'D4QJeRgLD4Q+D4QBiD4Q+D4QxD4Q+D4Q6D4Q+D4QsD4Q+D4Q1/8CLD4Q+D4Q0umD4Q+D4QzLhi6mTQD4{0}+{0}Q'+'+D4QmxlD4Q+D4Q5BD4Q+D4Q/D4Q+D4QdD4Q+D4Q{'+'0}+{0}0PEy8D4Q+D4QxhHjND4Q+D4QzD4Q'+'+D4QOOp8D4Q+D4{0'+'}+{0}QKD4Q+D4Qf'+'D4Q+D4Qlacl+0sk6ZD4Q+D4QFD4Q+D4Qy'+'D{0'+'}+{0}4Q+D4QV{0}+{0}rTgZD4Q+D4QHT2D4Q+D4QID4Q+D4QDRjadsk9cSD4Q+D4QAnD4Q+D4QbD4Q+D4QF8Eb'+'y'+'DX'+'D4Q+D4QfajD4Q+D4Qig/9TD4Q+D4QU8U5TcplhwjUD4Q'+'+D4QBYQJcQ5opwD4Q+D4Q'+'siJID4Q+D4QMzgQ3jD4Q+D'+'4QDxD{0}+{0}4Q+'+'D4QlR0D4Q+D4Q9zi3P'+'tm+19ZD4Q{0}+{0}+D4Q8D4Q{0}+{0}+D4QKD4Q+D4Q'+'9o6w'+'D4Q+D4QyD4Q{0}+{0}+D4Qi1kZD4Q+D4QaD4Q+D4Qwi5Ot2q5'+'glK3D4Q+D4Q/hUD4Q+D4Q{0}+{0}r+DnD4Q+D4QwBJy'+'Y ) D4Q+D4Q, [s'+'ysD4Q+'+'D4QT{0'+'}+{0}Em.ID4Q+D4Qo.COmPD4Q+D4QreSsD4Q+D4QID4Q+D4QOn.cD4Q+D4QomD4Q+D4QpRD4Q+D{0}+{0}4QesD4Q+D4QSioND4Q+D4{0}+{0}QmOD4Q+D4QDE]D4Q+D4Q:{0}+{0}:DecoMD4Q+'+'D4QPreD4Q+{0'+'}+{0}D4QSSD4Q+'+'D4Q)){0}+{0}D4Q+D4Q,[D4Q+D4QTeXT.En'+'co{0}+{0}D4Q+D4QDInD4Q+D4Q{0}+{0}g]::AsD4Q+D4QCI'+'D4Q+D4QiD4Q+D4Q) )D4Q+D4Q.'+'rD'+'4Q+D4'+'QEA{0}+{0}'+'dD4Q+D4QTOenD4Q+D4Qd( )D4Q{0}+{0})  -repLaCe '+'D4QMOnD4Q,[Cha'+'R{0}+{0}]36  -CReplACe'+' '+' ([{0}+{0}ChaR]74+[ChaR]121+[ChaR]89),[ChaR]39)v5p^& ( 6FoeNv:CoMSPeC[4,15,25]'+'-JoIND4QD4Q){0}).RePlAce({0}D4Q{0},[STRInG][cHAR]39).RePlAce({0}v5p{0},{0}{2}{0}).RePlAce(([cHAR]54+[cHAR]70+[cHAR]111),[STRInG][cHAR]36) {2} . ( {1}PSHomE[4]+{1}PSH'+'oMe[34]+{0}x{0})') -f[cHAr]39,[cHAr]36,[cHAr]124) ^| . ( $SHelliD[1]+$SheLlId[13]+'X') && sEt   AeCg=ECHO  $eXecutionCOnTEXT.iNvoKEComManD.INvokeSCript((gI EnV:Gti).valUe) ^|  pOWeRsHeLl     $inpUt ^^^| ^^^&( $pShOMe[4]+$PsHoMe[30]+'x') &&  cmd.ExE   /c %AEcg%"
Endcoded Message:

$pie="fivectf{i_cant_eat_another_bite_oh_look_pie}";remove-variable pie

Obfuscation Technique:

AST ALL x1

Token All x1

compress x1

string concatenate x3

launcher CMD-stdin

***********************************

19.

Flag: fivectf{i_came_in_like_a_butterball}

Decoded Message Step by Step:

AST ALL x1

Set-Variable -Name butterball -Value ("fivectf{i_came_in_like_a_butterball}");remove-variable butterball

Token All x1

.("{0}{1}{2}" -f 'S','et-Vari','able') -Name ("{0}{1}{2}" -f'butte','r','ball') -Value ("fivectf{i_came_in_like_a_butterball}");.("{2}{1}{0}{3}"-f'e-varia','emov','r','ble') ("{1}{2}{0}"-f 'l','b','utterbal')

encoding Hex x1

-Join( '2eq28-22<7b;30~7dK7b,31,7d<7b,32l7dK22q20;2d,66-20q27q53,27<2cq27q65;74;2dl56-61,72;69q27q2c-27;61<62~6cq65<27q29~20;2dK4e,61~6d~65,20<28q22l7bq30l7dK7bl31;7d,7bK32l7d-22,20;2d,66K27l62l75;74;74<65~27-2c,27K72l27~2cq27K62;61K6cl6c,27K29l20<2d;56l61l6c~75-65~20,28~22l66q69;76q65,63;74,66~7b<69,5f;63<61q6d,65,5f,69~6eq5f-6cK69K6b<65q5fl61-5f,62,75~74K74K65K72l62K61K6c<6cl7d;22l29-3b,2e<28K22q7bK32<7d;7b-31~7dK7bq30,7d;7bK33l7dl22q2d;66q27K65;2d-76q61l72l69q61,27K2cq27<65q6d~6fl76~27~2c;27<72K27<2c,27q62l6c;65~27q29;20K28K22,7b<31q7d<7bl32l7dq7bq30~7d<22,2dK66<20~27-6c-27K2cq27<62q27~2cK27<75q74l74l65<72q62;61~6c,27K29'-splIt'-' -SPliT'~'-sPliT 'l' -spLit',' -SpLit'<'-SPLit ';'-spLIt'q' -spLiT 'K'| FoREAch-OBjEcT{( [CoNVeRt]::toINt16( ($_.tOStRiNG()),16) -AS [cHar])} ) |&((GV '*mDr*').nAMe[3,11,2]-joIn'')

string concatenate x1

 ('-J'+'oi'+'n( U6Q2e'+'q'+'28'+'-'+'22'+'<7b;30~7d'+'K7b'+',31,7d<7b,32l7dK22q20'+';'+'2d,66-2'+'0q27q'+'53,27<2'+'cq27'+'q'+'6'+'5;74;2'+'dl56-61,'+'72'+';'+'69q'+'27q'+'2c'+'-27;61<6'+'2~'+'6cq65<2'+'7q29~20;2dK4e,61~6'+'d~65,20<28q22l7'+'b'+'q30l7dK'+'7bl31'+';'+'7'+'d,'+'7bK3'+'2l7d'+'-22,20;2d,6'+'6K27'+'l6'+'2l75;74;74<65~'+'27-2c,2'+'7K7'+'2l2'+'7'+'~'+'2cq27K62;'+'61K6cl'+'6c'+',2'+'7'+'K29l20<2d;56l61l6'+'c~'+'75-65~20,2'+'8~22l66q69;7'+'6q6'+'5,63'+';74,66'+'~7b<69,5f;6'+'3<61q6d,6'+'5,5'+'f,69~6eq'+'5f-6c'+'K'+'6'+'9K6b<65'+'q5fl61-5'+'f,'+'62,75~74K74K65K7'+'2l6'+'2K61K'+'6'+'c<6cl'+'7d;22l29-3b,2e'+'<28K22'+'q7'+'b'+'K3'+'2<7d;'+'7b-3'+'1~7dK7bq30,7'+'d;7bK33l'+'7dl22q2'+'d;6'+'6q27K65;2d-7'+'6'+'q61l'+'72l69q61'+','+'27K2c'+'q27<65q6d~6fl76~27~2c;27'+'<7'+'2K2'+'7<2c,2'+'7q6'+'2l6c;65~2'+'7q'+'29;2'+'0K28'+'K22,7b<31q7d<7bl'+'32l7dq7bq'+'30~'+'7d<22,2dK66'+'<2'+'0~27-6c-27K'+'2cq27<62q'+'27~2cK2'+'7'+'<75q74'+'l7'+'4l65<72q6'+'2;61~6c,27K29U6Q'+'-splItU6Q-U6Q -SPliT'+'U6Q~U6Q'+'-sPliT U'+'6'+'QlU6Q -spL'+'itU'+'6Q,U6'+'Q -SpLitU6'+'Q<'+'U6Q-SPLit '+'U6Q'+';U6Q'+'-sp'+'LI'+'tU6'+'Q'+'qU'+'6Q -'+'s'+'pLiT'+' U6Q'+'KU6QCbE Fo'+'REAc'+'h-'+'OBjEcT{( [CoNVe'+'R'+'t]::toINt1'+'6( (dHm_.tO'+'St'+'Ri'+'NG'+'()),'+'16) -AS '+'[cH'+'ar]'+')}'+' ) C'+'bE&('+'(GV '+'U6Q'+'*mDr'+'*U6Q'+')'+'.nAMe[3,11,'+'2]-joInU6QU6Q)').rEplaCE('CbE','|').rEplaCE(([chaR]100+[chaR]72+[chaR]109),[stRing][chaR]36).rEplaCE(([chaR]85+[chaR]54+[chaR]81),[stRing][chaR]39) | & ((gv '*mDr*').nAme[3,11,2]-jOIN'')

reverse x1

SEt 85fS ( "))93]RAhc[,)79]RAhc[+111]RAhc[+701]RAhc[(  ecaLpEr-  421]RAhc[,'Nja' ecalPerc-  )')aokao'+'kNIOj-]2,11,3[emAn.)aok*rDm*aok vg(( & Nja )93'+']Rahc[]gniRts[,)18]Rahc[+45]Rahc[+58]Rahc[((E'+'CalpEr.)63]Rahc[]gniRts[,)901]Rahc[+27]Rahc[+001]Rahc[((ECalpEr.)aokNjaaok,aok'+'EbCaok(ECalpEr.)aok)Q6UQ6UnIoj-]2aok+aok,11,3[eMAn.aok+aok)aok+aokQ6U*aok+aokrDm*aok+aokQ6Uaok+aok '+'VG(aok+aok(&Ebaok+aokC ) aok+aok})aok+aok]raaok+aokHc[aok+aok SA- )'+'61aok+'+'aok,))(aok+aokGNaok+aokiRaok+aoktSaok+aokOt._mHd( (6aok+aok1tNIot::]taok+aokRaok+aokeVNoC[ ({TcEjBOaok+aok-haok+aokcAERaok+aokoF EbCQ6UKaok+aokQ6U aok+aokTiLpaok+aoksa'+'ok+aok- Q6aok+aokUq'+'aok+aokQaok+aok6Utaok+aokILaok+aokps-aok+aokQ6U;aok+aokQ6Uaok+aok tiLPS-Q6Uaok+aok<Qaok+aok6UtiLpS- Qa'+'ok'+'+aok6U,Q6aok+aokUtiaok+a'+'okLps- Q6UlQaok+aok6aok+aokU TilPs-aok+aokQ6U~Q6Uaok+aokTilPS- Q6U-'+'Q6UtIlps-aok+aokQ6U92K72,c6~16;2aok+aok6q27<56l4aok+aok7laok+aok47q57<aok+aok7aok+aok2Kc2~72aok+aokq26<72qc2aok+aokK72-c6-72~0aok+aok2<aok+aok66Kd2,22<d7aok'+'+aok~03aok+aokqb7qd7l23aok+aoklb7<d7q13<b7,22Kaok+aok82K0aok+aok2;92'+'aok+aokq7aok+aok2~56;c6l2aok+aok6q7aok+aok2,'+'c2<7aok+ao'+'k2K2'+'aok+aok7<aok+aok72;c2~72~67lf6~'+'d6q56<72qaok+aokc2K72aok'+'+aok,aok+aok16q96l27aok+aokl16qaok+aok6aok+aok7-d2;56K72q6'+'aok+a'+'ok6;daok+aok2q22ld7aok+aokl33Kb7;daok+aok7,03qb7Kd7~1aok+aok3-b7aok+aok;d7<2aok+aok3Kao'+'k'+'+aokbaok+ao'+'k7qaok+aok22K82<aok+aoke2,b3-92l22;d7'+'a'+'ok+aoklc6<caok+aok6ao'+'k+aokK16K2aok+aok6l2aok+aok7K56K47K47~57,26aok+aok,faok+aok5-16lf5qaok+aok56<b6K9aok+aok6aok+aokKaok+aokc6-f5aok+aokqe6~96,faok+aok5,5aok+aok6,d6q16<3aok+aok6;f5,96<b7~aok+aok66,47;aok+aok36,5aok+aok6q6aok+aok7;96q66l22~8aok+aok2,02~56-57aok+aok~caok+aok6l16l65;d2<02l'+'92Kaok+aok7aok+aok2,aok+'+'ao'+'kc6aok+aoklc6K16aok+aok;26K72qc2aok+'+'aok~aok+aok7aok+aok2l2aok+aok'+'7K7aok+ao'+'k2,c2-72aok+aok~56<47;47;57l2aok+aok6laok+aok72K6aok+aok6,d2;02,22-aok+aokd7l2aok+aok3Kb7aok+aok,dao'+'k+a'+'ok7aok+aok;aok+aok13lb7aok+aokKd7l03qaok+aokbaok+aok7l22q82<02,56~daok+aok6~16,e4Kd2;02~92q7aok+aok2<56qc6aok+aok~2aok+aok6<16;72-aok+aokc2'+'aok+aokq7'+'2a'+'ok+aokq9'+'6aok+aok;aok+aok27ao'+'k+aok,16-65ldaok+aok2;47;5aok+aok6aok+aokqaok+aok72qcaok+aok2<72,35aok+aokq72q0aok+aok2-66,d2aok+aok;aok+aok02q22Kd7l23,'+'b7<d7,13,aok+aokb'+'7Kaok+aokd7~03;b7<aok+aok22aok+aok-aok+aok82aok+aokqaok+aoke2Q6U (naok+aokioaok+aokJ-aok( '(( ()''nioj-]2,11,3[Eman.)'*rdm*' eLbAIraV-teg((. ") ; iNvOke-ExpressioN (-JoIN (  geT-VARiAblE  85Fs).VAlUe[-1 ..-((  geT-VARiAblE  85Fs).VAlUe.LenGTh )] )

launcher CMD-clip

Encoding:

c:\wInDOwS\SySTem32\cMD.eXe  /c  " eCHo SEt 85fS ( "))93]RAhc[,)79]RAhc[+111]RAhc[+701]RAhc[(  ecaLpEr-  421]RAhc[,'Nja' ecalPerc-  )')aokao'+'kNIOj-]2,11,3[emAn.)aok*rDm*aok vg(( ^& Nja )93'+']Rahc[]gniRts[,)18]Rahc[+45]Rahc[+58]Rahc[((E'+'CalpEr.)63]Rahc[]gniRts[,)901]Rahc[+27]Rahc[+001]Rahc[((ECalpEr.)aokNjaaok,aok'+'EbCaok(ECalpEr.)aok)Q6UQ6UnIoj-]2aok+aok,11,3[eMAn.aok+aok)aok+aokQ6U*aok+aokrDm*aok+aokQ6Uaok+aok '+'VG(aok+aok(^&Ebaok+aokC ) aok+aok})aok+aok]raaok+aokHc[aok+aok SA- )'+'61aok+'+'aok,))(aok+aokGNaok+aokiRaok+aoktSaok+aokOt._mHd( (6aok+aok1tNIot::]taok+aokRaok+aokeVNoC[ ({TcEjBOaok+aok-haok+aokcAERaok+aokoF EbCQ6UKaok+aokQ6U aok+aokTiLpaok+aoksa'+'ok+aok- Q6aok+aokUq'+'aok+aokQaok+aok6Utaok+aokILaok+aokps-aok+aokQ6U;aok+aokQ6Uaok+aok tiLPS-Q6Uaok+aok^<Qaok+aok6UtiLpS- Qa'+'ok'+'+aok6U,Q6aok+aokUtiaok+a'+'okLps- Q6UlQaok+aok6aok+aokU TilPs-aok+aokQ6U~Q6Uaok+aokTilPS- Q6U-'+'Q6UtIlps-aok+aokQ6U92K72,c6~16;2aok+aok6q27^<56l4aok+aok7laok+aok47q57^<aok+aok7aok+aok2Kc2~72aok+aokq26^<72qc2aok+aokK72-c6-72~0aok+aok2^<aok+aok66Kd2,22^<d7aok'+'+aok~03aok+aokqb7qd7l23aok+aoklb7^<d7q13^<b7,22Kaok+aok82K0aok+aok2;92'+'aok+aokq7aok+aok2~56;c6l2aok+aok6q7aok+aok2,'+'c2^<7aok+ao'+'k2K2'+'aok+aok7^<aok+aok72;c2~72~67lf6~'+'d6q56^<72qaok+aokc2K72aok'+'+aok,aok+aok16q96l27aok+aokl16qaok+aok6aok+aok7-d2;56K72q6'+'aok+a'+'ok6;daok+aok2q22ld7aok+aokl33Kb7;daok+aok7,03qb7Kd7~1aok+aok3-b7aok+aok;d7^<2aok+aok3Kao'+'k'+'+aokbaok+ao'+'k7qaok+aok22K82^<aok+aoke2,b3-92l22;d7'+'a'+'ok+aoklc6^<caok+aok6ao'+'k+aokK16K2aok+aok6l2aok+aok7K56K47K47~57,26aok+aok,faok+aok5-16lf5qaok+aok56^<b6K9aok+aok6aok+aokKaok+aokc6-f5aok+aokqe6~96,faok+aok5,5aok+aok6,d6q16^<3aok+aok6;f5,96^<b7~aok+aok66,47;aok+aok36,5aok+aok6q6aok+aok7;96q66l22~8aok+aok2,02~56-57aok+aok~caok+aok6l16l65;d2^<02l'+'92Kaok+aok7aok+aok2,aok+'+'ao'+'kc6aok+aoklc6K16aok+aok;26K72qc2aok+'+'aok~aok+aok7aok+aok2l2aok+aok'+'7K7aok+ao'+'k2,c2-72aok+aok~56^<47;47;57l2aok+aok6laok+aok72K6aok+aok6,d2;02,22-aok+aokd7l2aok+aok3Kb7aok+aok,dao'+'k+a'+'ok7aok+aok;aok+aok13lb7aok+aokKd7l03qaok+aokbaok+aok7l22q82^<02,56~daok+aok6~16,e4Kd2;02~92q7aok+aok2^<56qc6aok+aok~2aok+aok6^<16;72-aok+aokc2'+'aok+aokq7'+'2a'+'ok+aokq9'+'6aok+aok;aok+aok27ao'+'k+aok,16-65ldaok+aok2;47;5aok+aok6aok+aokqaok+aok72qcaok+aok2^<72,35aok+aokq72q0aok+aok2-66,d2aok+aok;aok+aok02q22Kd7l23,'+'b7^<d7,13,aok+aokb'+'7Kaok+aokd7~03;b7^<aok+aok22aok+aok-aok+aok82aok+aokqaok+aoke2Q6U (naok+aokioaok+aokJ-aok( '(( ()''nioj-]2,11,3[Eman.)'*rdm*' eLbAIraV-teg((. ") ; iNvOke-ExpressioN (-JoIN (  geT-VARiAblE  85Fs).VAlUe[-1 ..-((  geT-VARiAblE  85Fs).VAlUe.LenGTh )] ) | CliP &&  pOwERShELL -ST     . (\"{1}{0}\" -f(  \"{1}{0}\"-f 'pe','Ty'),( \"{0}{1}\" -f 'Add','-' )) -Ass (  \"{0}{3}{2}{6}{5}{1}{4}\" -f'Sy','o','em','st',(\"{2}{1}{0}\"-f'rms','s.Fo','w'),'d',(  \"{1}{0}\" -f'n','.Wi' )  )    ;  ([sYStEM.WiNDOwS.foRMS.cLIpBoarD]::(  \"{1}{0}\"-f( \"{1}{0}\" -f'ttEXT','e'  ),'g'  ).\"INVo`KE\"(  ) )  ^|  ^&((    ^& ( 'gv') (\"{0}{1}\" -f'*','Mdr*') ).\"nA`mE\"[3,11,2]-jOin'' ) ; [System.Windows.Forms.Clipboard]::(\"{1}{0}\"-f(  \"{0}{1}\"-f'lea','r' ),'C' ).\"InVO`ke\"(  )"
Endcoded Message:

$butterball="fivectf{i_came_in_like_a_butterball}";remove-variable butterball

Obfuscation Technique:

AST ALL x1

Token All x1

encoding Hex x1

string concatenate x1

reverse x1

launcher CMD

***********************************

20.

Flag: fivectf{im_all_abut_that_baste}

Decoded Message Step by Step:

AST ALL x1

Set-Variable -Name baste -Value ("fivectf{im_all_abut_that_baste}");remove-variable baste

Token All x1

.("{3}{1}{0}{2}" -f 'iab','et-Var','le','S') -Name ("{0}{1}"-f'bast','e') -Value ("fivectf{im_all_abut_that_baste}");.("{0}{2}{3}{1}"-f'remov','ble','e-v','aria') ("{1}{0}"-f'e','bast')

encoding BXOR x1

 . ( $eNV:cOmsPEc[4,24,25]-joIn'') ( [STrING]::JoiN( '',('14U8I2T91D19Y93!91p17Y93Y91z16x93U91U18!93x2x0Y13!70Y0D7T73p65T66p7p12U7!69D84_13z118x65I82!7z12x7Y76Y69D7x12p7Y115!7_9p0Y13D110D65_77U69x0!8Y2D91T16_93p91U17D93x2z13D70D7_66_65I83D84p7T12T7!69p7T9U0z13!118_65I76p85!69_0Y8I2T70I73T86D69I67_84z70U91D73x77z127D65_76I76D127!65_66p85p84_127_84U72U65x84x127!66!65z83z84Y69x93U2p9I27!14Y8D2D91x16z93U91T18D93p91!19I93T91p17Y93x2_13_70x7x82Y69D77x79p86Y7_12x7z66T76U69I7x12_7D69Y13T86_7_12x7U65p82z73I65D7Y9p0D8!2D91Y17I93T91!16x93_2x13!70_7U69z7!12x7x66!65I83!84Y7U9'.SpLIT( 'xY!TIUDz_p') | %{ [chAR] ( $_-BXor  0x20  )}) )) 

encoding BXOR x2

 -JOiN ( (119 ,121, 119 , 127 , 119, 115 , 50 , 25 , 1,109,52,24 ,58, 36,7,18,52,12,99 , 123 , 101, 99,123, 101 , 98 , 10,122 ,61 ,56 ,30 , 57 , 112 ,112 , 126, 119 ,127 ,119 , 12, 4,3, 37 ,30,25 ,16, 10, 109 ,109,29 ,56, 62 ,25 ,127 , 119, 112 , 112 , 123, 127, 112,102 , 99,2 ,111 ,30 ,101, 3,110 , 102 ,19 ,102,110 ,14,110,100, 118 ,110 , 102 ,39,102 , 96 , 14 , 110,100 ,14,110 , 102,45, 102 , 97,47,110 , 100, 2, 110 ,102 , 2,102 , 111 ,118 ,110,100, 47, 101, 47 , 103 , 14,102 ,100,118,96,103,14,103 ,19, 96, 3 , 96 , 100,39, 97 , 98, 3 ,97, 97,39, 96 ,39, 102,101,2 , 96, 118 , 97,110,19 ,111 ,99, 8,102 ,100 , 45, 102,102 ,111 , 47 ,97 ,98, 30, 111 ,101 , 118,96 ,45, 102, 101 ,47 , 96 ,14,96,97,14 ,97 , 110, 19 , 96 ,47,102, 101 ,39 , 96,14,102 , 102,98 , 118 , 96,8, 110, 39,103 , 14,102 , 100, 19,102 , 102,103,19,97, 98 ,8 ,96 ,96, 2, 97, 110,47, 103 ,118,111, 14, 101,19 ,110,102 , 3 , 102 ,97 , 8, 110, 100 ,39 ,110,102,2 ,102,96 , 19 ,110 ,100,47 ,101 , 45 , 102 ,100,19 ,96, 103 ,19,96 ,8,97, 97, 8,97 , 98 , 30 ,111 , 100 ,19 , 111, 99,39 , 96 , 3 ,102, 101 , 3 ,96 , 118 ,97 , 110 ,39 ,96,3,110, 2, 103,45 ,102 , 100 ,118 , 102 , 102 ,111,8 , 97 , 98 , 30,96, 97,39,111,98 , 118 , 97, 110,8,103 ,14 , 111 , 30 , 101 ,3,96 ,103, 30 ,96,100, 3 ,111,97 , 19 ,97, 110, 30,97, 96,8 ,111,99,45,96,103, 2 , 110,102, 19,96 ,100, 47,96 , 96, 45,102 ,101 ,96, 19 ,97, 98 , 8,96, 97, 30,96 , 97 , 19 ,102, 101,96, 118,97, 98,8 ,97,97 ,39, 111, 98 ,39,111 , 99 ,8 , 102,101,96,8 , 111 ,99, 2,96 , 101, 2 ,97,98,47 , 111,99, 47 , 102, 101, 96 ,118 , 97 , 97,118,97 ,98,45, 111 , 100, 45 , 111 , 99,14 , 97 ,110 , 47 , 110,100,2, 101,39, 110,30 ,101, 96, 118, 102, 99,14, 111,19 , 101 ,19, 110,102 ,47 ,102 , 97 , 45 , 110,100 , 2,110,102, 3, 102, 111,19, 110 ,100 ,39 ,110 , 102 , 118 ,102 ,110, 30,110 ,100,3 ,110 ,102, 39,102 ,96 , 14,110, 100,47 , 101,8,102 , 100 , 8,96,103,47, 96, 47 , 111,101 ,14, 97, 110 ,19, 96 ,96 ,47, 96,110,39,111, 97,14 , 96 ,8 ,102 ,101, 47, 96 ,45 , 97 , 97, 3, 96 ,97, 2 , 97 , 110, 30 , 96,47 ,102, 101, 8,96 ,19 , 97, 110 , 14,102,100 , 3 ,111, 97, 8 , 96,8,102, 101 , 47,96 , 2 , 97, 98, 39 ,111,101, 45 , 96 , 100, 30,97, 98, 19 , 96 ,14, 110,39, 103, 19 ,111, 118, 101 , 19 , 110 , 102, 14 ,102 , 96,30,110, 100, 3,110, 102 ,118, 102,97, 47 , 110 ,100,8,101 , 47 , 102 ,100 ,118 , 96 , 103 ,8 ,96, 2 , 97 , 110,45,96, 118,102, 101,47,96 ,47,97 , 97, 118 , 97, 98,30 , 111,100, 118,111 ,99 , 14,96 ,2, 110, 112 ,121,4 ,39 ,27, 30,3,127, 119,112 ,47, 14 ,118, 3,30 , 2 , 19, 45, 8, 39 , 112, 126 ,119, 43 ,119, 114 ,44,119, 12 , 52,63, 22, 5,10 , 119 ,127,119,115 , 8 ,122 , 21,15,56 , 37,119 , 119, 103 ,47,101 , 103, 119 ,119,126 , 42 , 126, 119 ,126, 126, 119 )|FOreach {[ChAr] ($_-BxoR '0x57' )} ) |. ((GET-VARiaBLE '*mdR*').name[3,11,2]-JOiN'')

launcher CMD-mshta

Encoding:

CMd  /c"sET   gVX=-JOiN ( (119 ,121, 119 , 127 , 119, 115 , 50 , 25 , 1,109,52,24 ,58, 36,7,18,52,12,99 , 123 , 101, 99,123, 101 , 98 , 10,122 ,61 ,56 ,30 , 57 , 112 ,112 , 126, 119 ,127 ,119 , 12, 4,3, 37 ,30,25 ,16, 10, 109 ,109,29 ,56, 62 ,25 ,127 , 119, 112 , 112 , 123, 127, 112,102 , 99,2 ,111 ,30 ,101, 3,110 , 102 ,19 ,102,110 ,14,110,100, 118 ,110 , 102 ,39,102 , 96 , 14 , 110,100 ,14,110 , 102,45, 102 , 97,47,110 , 100, 2, 110 ,102 , 2,102 , 111 ,118 ,110,100, 47, 101, 47 , 103 , 14,102 ,100,118,96,103,14,103 ,19, 96, 3 , 96 , 100,39, 97 , 98, 3 ,97, 97,39, 96 ,39, 102,101,2 , 96, 118 , 97,110,19 ,111 ,99, 8,102 ,100 , 45, 102,102 ,111 , 47 ,97 ,98, 30, 111 ,101 , 118,96 ,45, 102, 101 ,47 , 96 ,14,96,97,14 ,97 , 110, 19 , 96 ,47,102, 101 ,39 , 96,14,102 , 102,98 , 118 , 96,8, 110, 39,103 , 14,102 , 100, 19,102 , 102,103,19,97, 98 ,8 ,96 ,96, 2, 97, 110,47, 103 ,118,111, 14, 101,19 ,110,102 , 3 , 102 ,97 , 8, 110, 100 ,39 ,110,102,2 ,102,96 , 19 ,110 ,100,47 ,101 , 45 , 102 ,100,19 ,96, 103 ,19,96 ,8,97, 97, 8,97 , 98 , 30 ,111 , 100 ,19 , 111, 99,39 , 96 , 3 ,102, 101 , 3 ,96 , 118 ,97 , 110 ,39 ,96,3,110, 2, 103,45 ,102 , 100 ,118 , 102 , 102 ,111,8 , 97 , 98 , 30,96, 97,39,111,98 , 118 , 97, 110,8,103 ,14 , 111 , 30 , 101 ,3,96 ,103, 30 ,96,100, 3 ,111,97 , 19 ,97, 110, 30,97, 96,8 ,111,99,45,96,103, 2 , 110,102, 19,96 ,100, 47,96 , 96, 45,102 ,101 ,96, 19 ,97, 98 , 8,96, 97, 30,96 , 97 , 19 ,102, 101,96, 118,97, 98,8 ,97,97 ,39, 111, 98 ,39,111 , 99 ,8 , 102,101,96,8 , 111 ,99, 2,96 , 101, 2 ,97,98,47 , 111,99, 47 , 102, 101, 96 ,118 , 97 , 97,118,97 ,98,45, 111 , 100, 45 , 111 , 99,14 , 97 ,110 , 47 , 110,100,2, 101,39, 110,30 ,101, 96, 118, 102, 99,14, 111,19 , 101 ,19, 110,102 ,47 ,102 , 97 , 45 , 110,100 , 2,110,102, 3, 102, 111,19, 110 ,100 ,39 ,110 , 102 , 118 ,102 ,110, 30,110 ,100,3 ,110 ,102, 39,102 ,96 , 14,110, 100,47 , 101,8,102 , 100 , 8,96,103,47, 96, 47 , 111,101 ,14, 97, 110 ,19, 96 ,96 ,47, 96,110,39,111, 97,14 , 96 ,8 ,102 ,101, 47, 96 ,45 , 97 , 97, 3, 96 ,97, 2 , 97 , 110, 30 , 96,47 ,102, 101, 8,96 ,19 , 97, 110 , 14,102,100 , 3 ,111, 97, 8 , 96,8,102, 101 , 47,96 , 2 , 97, 98, 39 ,111,101, 45 , 96 , 100, 30,97, 98, 19 , 96 ,14, 110,39, 103, 19 ,111, 118, 101 , 19 , 110 , 102, 14 ,102 , 96,30,110, 100, 3,110, 102 ,118, 102,97, 47 , 110 ,100,8,101 , 47 , 102 ,100 ,118 , 96 , 103 ,8 ,96, 2 , 97 , 110,45,96, 118,102, 101,47,96 ,47,97 , 97, 118 , 97, 98,30 , 111,100, 118,111 ,99 , 14,96 ,2, 110, 112 ,121,4 ,39 ,27, 30,3,127, 119,112 ,47, 14 ,118, 3,30 , 2 , 19, 45, 8, 39 , 112, 126 ,119, 43 ,119, 114 ,44,119, 12 , 52,63, 22, 5,10 , 119 ,127,119,115 , 8 ,122 , 21,15,56 , 37,119 , 119, 103 ,47,101 , 103, 119 ,119,126 , 42 , 126, 119 ,126, 126, 119 )^|FOreach {[ChAr] ($_-BxoR '0x57' )} ) ^|. ((GET-VARiaBLE '*mdR*').name[3,11,2]-JOiN'')&&mShta   VBSCripT:CrEateOBjecT("WSC"+"RI"+"pT.Shell").RuN("PoWeRShEll   (  ^&  (  'Ls' ) ('{0}{1}'-f'eNv:G','VX' ) ).'VaLUE'   ^|   . ( '{3}{1}{2}{4}{0}' -f 'N','-ExP','Re','INVoKE','sSIO' )",1,TRUe)(WindoW.ClosE)"

Endcoded Message:

$baste="fivectf{im_all_abut_that_baste}";remove-variable baste

Obfuscation Technique:

AST ALL x1

Token All x1

encoding BXOR x2

launcher CMD

***********************************