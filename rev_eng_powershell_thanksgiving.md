All of these were created with Invoke-obfuscation

***********************************
Easy - 1 item only
***********************************
1.
Flag: fivectf{turkeys_go_gobble_gobble}

Question:

Encoding:

  inVOKe-ExPRessION ( ('xiz'+'turkey=3UN'+'f'+'ivect'+'f{tur'+'keys_'+'g'+'o_gob'+'b'+'le_'+'gobble}3UN').REpLACE(([ChAr]120+[ChAr]105+[ChAr]122),[StRiNG][ChAr]36).REpLACE(([ChAr]51+[ChAr]85+[ChAr]78),[StRiNG][ChAr]34)) 

Endcoded Message:

$turkey="fivectf{turkeys_go_gobble_gobble}"

Obfuscation Technique:

String Concatenate x1

***********************************
2.
Flag: fivectf{lets_get_basted}

Question:

Encoding:

(("{7}{8}{5}{0}{6}{2}{3}{10}{1}{4}{11}{9}"-f'6nf','_g','v','ectf{l','et_ba','te=5','i','h5Gb','as','ted}56n','ets','s')).rePLAce('h5G','$').rePLAce(([ChAR]53+[ChAR]54+[ChAR]110),[STrING][ChAR]34)| &((geT-VARiAbLe '*mDR*').naME[3,11,2]-JOIn'')

Endcoded Message:

$baste="fivectf{lets_get_basted}"

Obfuscation Technique:

Reorder x1

***********************************
3.
Flag: fivectf{oh_my_gourd}

Question:

Encoding:

$BRS69A =  [chAR[] ]")'x'+]03[emOhSp$+]12[emOhsP$ (.|)63]rAHc[]gNirts[,)611]rAHc[+86]rAHc[+511]rAHc[((EcALpER.)43]rAHc[]gNirts[,'5xn'(EcALpER.)'5xn}'+'d'+'r'+'uo'+'g_y'+'m_h'+'o'+'{ftc'+'evif5x'+'n='+'druo'+'gtDs'( " ; [ARraY]::RevErsE( $brS69A ) ; .( $SHELLId[1]+$SHEllid[13]+'X') (" $( sEt-ITem  'vArIABle:ofs'  '' )" + [StRINg] ( $brS69A ) +"$( sET-VAriAblE  'OFS' ' ')" )

Endcoded Message:

$gourd="fivectf{oh_my_gourd}"

Obfuscation Technique:

reverse x1

***********************************
4.
Flag: fivectf{silence_of_the_yams}

Question:

Encoding:

 -JOIn ( (36,121, 97, 109, 61 , 34 , 102 ,105,118 , 101,99, 116, 102, 123 ,115, 105 , 108,101,110,99 ,101, 95,111 , 102 ,95 ,116 ,104 ,101 ,95, 121, 97 , 109, 115, 125, 34 )| foREacH{( [chaR] [iNT]$_) })|&((vAriAblE '*MdR*').nAMe[3,11,2]-joIN'')

Endcoded Message:

$yam="fivectf{silence_of_the_yams}"

Obfuscation Technique:

Encoding ASCII x1

***********************************
5.
Flag: fivectf{gobble_til_you_wobble}

Question:

Encoding:

 "$( seT-item  'vARIABlE:Ofs'  '' )" + [strING]('24x77W6f}62o62o6c{65;3d{22;66o69;76x65g63}74;66g7b_67x6fW62;62{6c;65o5fx74o69x6c;5fx79o6fW75}5f_77}6fx62o62{6co65g7d{22;3b;52x65_6d_6fx76W65}2dx56x61W72g69W61}62_6c{65}20_77o6fg62;62{6c_65'.sPlit('_{xW;}go') | FOReAcH-ObJECT { ( [cHar]([coNvErT]::TOiNT16(($_.tOsTrInG() ),16))) } )+"$( sEt-VAriaBle  'Ofs' ' ') " | Iex

Endcoded Message:

$wobble="fivectf{gobble_til_you_wobble}";Remove-Variable wobble

Obfuscation Technique:

Encoding Hex x1

***********************************
6.
Flag: fivectf{this_is_how_i_roll}

Question:

Encoding:

&( $PshoMe[4]+$PshOmE[34]+'X')( -JOIN('44E162L157s154B154;75N42B146s151t166;145E143E164B146t173N164t150B151k163s137k151N163B137t150;157s167L137N151N137t162t157i154E154i175k42i73t122f145N155t157L166E145L55i126N141s162B151t141N142i154;145s40N162;157N154;154'.SPLIT(';NkfLEsiBt' ) | forEach {([ChAr]( [coNVert]::toINt16(($_.toStRIng() ),8 ))) }) ) 

Endcoded Message:

$roll="fivectf{this_is_how_i_roll}";Remove-Variable roll

Obfuscation Technique:

encoding octal x1

***********************************
7.
Flag: fivectf{off_the_rails_on_gray_train}

Question:

Encoding:

invOKE-exprEsSioN (" $( sEt-IteM  'vAriABLe:OFS'  '') "+ [STRInG]( ( 100100 , 1100111 ,1110010, 1100001 , 1110110 , 1111001,111101, 100010 ,1100110 ,1101001 , 1110110, 1100101 , 1100011, 1110100, 1100110, 1111011 , 1101111 ,1100110, 1100110 ,1011111, 1110100, 1101000, 1100101 ,1011111 , 1110010,1100001 ,1101001 , 1101100, 1110011 ,1011111 , 1101111 ,1101110 , 1011111 , 1100111 ,1110010 , 1100001,1111001 ,1011111 ,1110100, 1110010 , 1100001 ,1101001 , 1101110 ,1111101,100010 , 111011 , 1110010 ,1100101 , 1101101, 1101111,1110110 , 1100101 ,101101,1110110, 1100001, 1110010 ,1101001, 1100001 , 1100010 , 1101100, 1100101,100000 , 1100111 ,1110010, 1100001,1110110, 1111001 ) |foREAch{ ( [CHaR] ([ConVErT]::Toint16(( $_.TOStRiNG() ) ,2) )) } )+" $( sEt-ItEm 'VaRiable:OFs' ' ') ")

Endcoded Message:

$gravy="fivectf{off_the_rails_on_gray_train}";Remove-Variable gravy

Obfuscation Technique:

encoding binary x1

***********************************
8.
Flag: fivectf{feast_mode}

Question:

Encoding:

[sTrIng]::jOin( '' , ('127}61,62@58@40,47}102}121Q61,50t45&62,56}47<61t32X61@62,58<40v47@4G54v52v63X62<38t121}96}9X62&54}52G45G62Q118&13Q58,41G50X58v57X55<62&123G61v62&58<40v47'.SpLiT('XG,&}v<@tQ') |% { [cHAR] ( $_-bxOr'0x5b') }) )|.( $Env:COmSPEC[4,26,25]-joIN'')

Endcoded Message:

$feast="fivectf{feast_mode}";Remove-Variable feast

Obfuscation Technique:

encoding BXOR x1

***********************************
9. 
Flag: fivectf{im_stuffed}

Question:

Encoding:

${+ }=  +  $(  );${=$%}  =${+ };${!=%}=++  ${+ }  ;  ${-}  =(  ${+ }=  ${+ }  +  ${!=%}  );  ${!}  =(${+ }  =${+ }+  ${!=%}  );${/@+}=  (${+ }  =  ${+ }+  ${!=%})  ;${;.(}=  (  ${+ }=${+ }+${!=%}  )  ;  ${;}  =(${+ }  =${+ }  +${!=%}  );${=*}=(  ${+ }  =  ${+ }  +${!=%}  )  ;  ${$}  =(${+ }=  ${+ }+  ${!=%});${[%-}=(  ${+ }  =  ${+ }  +  ${!=%})  ;${([!}  =  "["  +"$(  @{}  )"[${=*}  ]  +  "$(@{})"["${!=%}${[%-}"  ]  +  "$(  @{  })"[  "${-}${=$%}"]  +  "$?"[${!=%}]  +"]"  ;  ${+ }=  "".("$(@{  }  )"["${!=%}${/@+}"]+  "$(  @{  })  "[  "${!=%}${;}"  ]  +"$(@{}  )"[${=$%}  ]  +"$(@{})"[  ${/@+}]  +  "$?  "[  ${!=%}  ]  +"$(@{  })"[${!}  ])  ;  ${+ }="$(  @{  }  )"["${!=%}"  +  "${/@+}"  ]+  "$(  @{}  )"[${/@+}]+  "${+ }"["${-}"+  "${=*}"  ]  ;"${([!}${!}${;}+  ${([!}${!=%}${!=%}${;.(}+${([!}${!=%}${!=%}${;}+  ${([!}${!=%}${!=%}${=*}  +${([!}${!=%}${=$%}${-}+${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}+${([!}${!=%}${=$%}${=$%}  +  ${([!}${;}${!=%}+${([!}${!}${/@+}  +${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${=$%}${;.(}  +  ${([!}${!=%}${!=%}${$}+${([!}${!=%}${=$%}${!=%}+  ${([!}${[%-}${[%-}+${([!}${!=%}${!=%}${;}+${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${-}${!}+${([!}${!=%}${=$%}${;.(}  +${([!}${!=%}${=$%}${[%-}+${([!}${[%-}${;.(}  +${([!}${!=%}${!=%}${;.(}  +${([!}${!=%}${!=%}${;}  +${([!}${!=%}${!=%}${=*}  +${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}  +${([!}${!=%}${=$%}${=$%}+  ${([!}${!=%}${-}${;.(}  +  ${([!}${!}${/@+}  +${([!}${;.(}${[%-}  +  ${([!}${!=%}${!=%}${/@+}+${([!}${!=%}${=$%}${!=%}  +  ${([!}${!=%}${=$%}${[%-}  +  ${([!}${!=%}${!=%}${!=%}+${([!}${!=%}${!=%}${$}  +${([!}${!=%}${=$%}${!=%}  +${([!}${/@+}${;.(}+${([!}${!=%}${!=%}${$}+  ${([!}${[%-}${=*}+${([!}${!=%}${!=%}${/@+}  +${([!}${!=%}${=$%}${;.(}+${([!}${[%-}${=*}+  ${([!}${[%-}${$}+  ${([!}${!=%}${=$%}${$}  +  ${([!}${!=%}${=$%}${!=%}  +${([!}${!}${-}  +${([!}${!=%}${!=%}${;.(}+  ${([!}${!=%}${!=%}${;}+${([!}${!=%}${!=%}${=*}  +  ${([!}${!=%}${=$%}${-}  +  ${([!}${!=%}${=$%}${-}+  ${([!}${!=%}${=$%}${!=%}  +${([!}${!=%}${=$%}${=$%}  |${+ }"  |.${+ }  

Endcoded Message:

$stuffed="fivectf{im_stuffed}";remove-variable stuffed

Obfuscation Technique:

encoding special characters x1

***********************************
10.
Flag: fivectf{i_yam_what_i_yam}

Question:

Encoding:
'				 							  		 			 		  										 								  		 	 										  		 	 										  		 			 		  							 		  				 					  		 	 			  		 	 						  		 		 									  		 	 		  										 										  		 		 							  		 	 			  		 			 				  		 	 						  										 						  		 			 		  										 								  		 	 										  										 						  		 		 										  		 	 					  										 								  		 		 							  										 						  		 	 						  										 						  		 			 		  										 								  		 	 										  		 			 						  				 					' | %{$riBwML=$_ -ISPliT '  ' | % {' '; $_ -ISPliT ' ' | % {$_.lengTh - 1 } } ; &( ''.norMALiZe.TostRiNg()[55,41,46]-jOin'') ( -jOIn (((-jOIn($riBwML[0..($riBwML.lengTh-1)]) ).triM('  ').SplIt(' ' ) |%{( [CHAR] [int] $_) })) ) }

Endcoded Message:
$yammy="fivectf{i_yam_what_i_yam}"

Obfuscation Technique:
encoding whitespace x1

***********************************
11.
Flag: fivectf{eat_drink_and_cranberry}

Question:

Encoding:
 ( NEw-obJeCt sYsTem.Io.ComPResSIOn.DeFlAtestreAm([Io.mEmORysTrEAM] [CONVeRt]::FrOMbase64sTrinG( 'U0kuSsxLSi0qqrRVSsssS00uSatOTSyJTynKzMuOT8xLiYcrqFUCAA=='), [SYsTem.IO.ComPressION.COMPReSSionmODe]::deCOMPRESs ) |% {NEw-obJeCt SYSTEm.IO.stReaMrEADER($_, [SystEM.texT.eNCODinG]::asCii )} ).reAdToEnD() | .((gv '*mDR*').Name[3,11,2]-Join'')

Endcoded Message:
$cranberry="fivectf{eat_drink_and_cranberry}"

Obfuscation Technique:
compress x1

***********************************
Medium 2x items
***********************************
12.
Flag: fivectf{your_the_apple_of_my_pie}

Decoded Message Step by Step:
reverse x1
Set ('57'+'IC')  ([chAr[] ]"))43]RaHC[,'vil' EcALpER-63]RaHC[,)77]RaHC[+011]RaHC[+121]RaHC[(EcALpER-  )'v'+'i'+'l'+'}e'+'ip'+'_'+'ym_'+'f'+'o_elppa_e'+'ht'+'_ruoy'+'{ft'+'cevi'+'fvil='+'elppaMny'((()''nIoJ-'x'+]3,1[)(gniRTSoT.ecNeReFerPesobREv$ ( . "); [aRrAy]::ReveRSE($57Ic) ; &((vaRIaBle '*MdR*').NAme[3,11,2]-JOin'')( "$( seT  'OFs' '' ) " + [sTRiNG]( $57Ic )+" $(sEt-Item 'VArIAbLE:oFS'  ' ' )" ) 

reoder x1
(("{58}{10}{90}{89}{20}{117}{121}{94}{129}{107}{54}{91}{80}{35}{44}{55}{126}{141}{62}{135}{77}{104}{22}{15}{132}{26}{87}{19}{110}{49}{113}{23}{34}{53}{111}{66}{33}{63}{142}{38}{40}{125}{109}{84}{13}{0}{100}{124}{30}{127}{50}{45}{131}{85}{138}{47}{17}{43}{12}{67}{115}{27}{137}{120}{134}{82}{8}{106}{16}{48}{4}{61}{1}{59}{36}{81}{75}{102}{18}{2}{42}{69}{25}{78}{99}{68}{24}{96}{136}{21}{31}{95}{118}{7}{98}{71}{3}{73}{83}{123}{56}{140}{29}{128}{74}{60}{119}{108}{103}{39}{76}{6}{52}{86}{97}{32}{65}{92}{112}{105}{9}{122}{130}{139}{70}{51}{41}{72}{88}{28}{14}{64}{79}{5}{133}{93}{37}{116}{46}{114}{101}{57}{11}"-f 'f','ecNe','0X9)','dR','qL','E',' 0X9vts( se','aBl','LU','qLU ) ','t (qLU57',' ) ','+qLUceviqL','LU+qLU','rI','cAL','nIoJ-','U+qLU{ftq','bREvvts ( . ',' ','LUI','ts','[(E','qLU+qL','veR','aR','ER','fvil=q',' qLUVA','1,2','qL','5','q','U+q','Ui','LUvil','Fe','Sq','eqLU+',')','qLUipqLU+q','c )+0X9 vts(sE',';','LU','qLU EcAL','pp','U  ','L','qLUx',')qL','_el','ts57I','T','qLU+qL',']RaHC[','pER-63]RaHC[','.NA','LU )0X9','Se','Re','inq','U+]3,1[)(gniRTSoT.','aHC[+','L','Ab','L','L','U+','::Re',' [','( v',' qLU*M','t-It','*','JO','Pes','(','RaHC[+','rA','L','q','r','((()q','q','ym_q','tqLU+qL','  q','-','em','LU+q','q',',','U','oF','9','7Ic) ','S','LUOFs','e','y]','qL','U q','o','qLU','121]RaHC','LU','qLU','3','U','LU',' ','Ulq',' q','Uv','qL','qLU','L','CqLU)  ([chA','; &((vaRI','L','LUelppa','r[] ]0X','0X9 + [sT','LU)','U+','LU_qLU+q',',)','Uo',']-','))4','RiNG','a_eqLU+qLUh','p',':','MnyqLU','011]','E(v','LU+q','U_ruoyq',']','me[3,1','77]R','U}')).rEplaCe(([Char]48+[Char]88+[Char]57),[StRiNg][Char]34).rEplaCe(([Char]113+[Char]76+[Char]85),[StRiNg][Char]39).rEplaCe('vts',[StRiNg][Char]36)| . ( $PSHOmE[4]+$pShoME[34]+'x')

Launch CMD

Encoding:
cmd.eXE  /C  PoWErShell   "((\"{58}{10}{90}{89}{20}{117}{121}{94}{129}{107}{54}{91}{80}{35}{44}{55}{126}{141}{62}{135}{77}{104}{22}{15}{132}{26}{87}{19}{110}{49}{113}{23}{34}{53}{111}{66}{33}{63}{142}{38}{40}{125}{109}{84}{13}{0}{100}{124}{30}{127}{50}{45}{131}{85}{138}{47}{17}{43}{12}{67}{115}{27}{137}{120}{134}{82}{8}{106}{16}{48}{4}{61}{1}{59}{36}{81}{75}{102}{18}{2}{42}{69}{25}{78}{99}{68}{24}{96}{136}{21}{31}{95}{118}{7}{98}{71}{3}{73}{83}{123}{56}{140}{29}{128}{74}{60}{119}{108}{103}{39}{76}{6}{52}{86}{97}{32}{65}{92}{112}{105}{9}{122}{130}{139}{70}{51}{41}{72}{88}{28}{14}{64}{79}{5}{133}{93}{37}{116}{46}{114}{101}{57}{11}\"-f 'f','ecNe','0X9)','dR','qL','E',' 0X9vts( se','aBl','LU','qLU ) ','t (qLU57',' ) ','+qLUceviqL','LU+qLU','rI','cAL','nIoJ-','U+qLU{ftq','bREvvts ( . ',' ','LUI','ts','[(E','qLU+qL','veR','aR','ER','fvil=q',' qLUVA','1,2','qL','5','q','U+q','Ui','LUvil','Fe','Sq','eqLU+',')','qLUipqLU+q','c )+0X9 vts(sE',';','LU','qLU EcAL','pp','U  ','L','qLUx',')qL','_el','ts57I','T','qLU+qL',']RaHC[','pER-63]RaHC[','.NA','LU )0X9','Se','Re','inq','U+]3,1[)(gniRTSoT.','aHC[+','L','Ab','L','L','U+','::Re',' [','( v',' qLU*M','t-It','*','JO','Pes','(','RaHC[+','rA','L','q','r','((()q','q','ym_q','tqLU+qL','  q','-','em','LU+q','q',',','U','oF','9','7Ic) ','S','LUOFs','e','y]','qL','U q','o','qLU','121]RaHC','LU','qLU','3','U','LU',' ','Ulq',' q','Uv','qL','qLU','L','CqLU)  ([chA','; &((vaRI','L','LUelppa','r[] ]0X','0X9 + [sT','LU)','U+','LU_qLU+q',',)','Uo',']-','))4','RiNG','a_eqLU+qLUh','p',':','MnyqLU','011]','E(v','LU+q','U_ruoyq',']','me[3,1','77]R','U}')).rEplaCe(([Char]48+[Char]88+[Char]57),[StRiNg][Char]34).rEplaCe(([Char]113+[Char]76+[Char]85),[StRiNg][Char]39).rEplaCe('vts',[StRiNg][Char]36)| . ( $PSHOmE[4]+$pShoME[34]+'x')"

Endcoded Message:
$apple="fivectf{your_the_apple_of_my_pie}"

Obfuscation Technique:
Reverse x1
reorder x1
Launcher CMD

***********************************
13.
Flag: fivectf{dont_be_jerky_eat_some_turkey}

Decoded Message Step by Step:
Concate X1
 (('s'+'o0je'+'rky='+'JHIfi'+'vect'+'f{dont_be_jerky_e'+'a'+'t_so'+'me_tu'+'rkey}'+'JHI')  -repLAcE ([char]74+[char]72+[char]73),[char]34-repLAcE 'so0',[char]36)| & ( $env:cOmsPeC[4,15,25]-join'')

reverse x1
. ( $sHElLiD[1]+$ShElLid[13]+'x')(( [rEGEX]::MaTCHeS( " ))93]RAhc[]gnIRTs[,)67]RAhc[+65]RAhc[+021]RAhc[((ecAlPer.)421]RAhc[]gnIRTs[,'bh4'(ecAlPer.)'$','snG'(ecAlPer.)')L8'+'xL'+'8'+'xnioj-]5'+'2,5'+'1,4['+'CePs'+'mO'+'c:vnesnG ('+' '+'&'+' b'+'h'+'4)'+'63]rah'+'c[,L8x'+'0'+'o'+'s'+'L8x E'+'c'+'AL'+'pe'+'r-43]r'+'ahc[,)37]r'+'ahc'+'[+27]r'+'a'+'h'+'c[+'+'47]rah'+'c[( EcALper-'+'  )L'+'8xIHJL8'+'x+L8x}yek'+'rL8x+L8xut_'+'emL8x+L8x'+'o'+'s_t'+'L'+'8x+L'+'8'+'xaL8x+L8xe_ykrej_'+'eb'+'_'+'tnod{'+'fL'+'8x+L'+'8xtcevL8x+L8xif'+'I'+'H'+'JL8'+'x+'+'L8x=ykrL'+'8x+L'+'8xej'+'0oL8x+'+'L8'+'xsL8'+'x(('+' '(()''nioJ-'x'+]3,1[)eCNeREFErPesoBREV$]GNIrtS[( (&" , '.', 'RIgHt'+'tol'+'EF'+'t' )-JoIn'' )  )
launcher CMD

Encoding:
CMd.EXE  /cPoWerSHeLl   ". ( $sHElLiD[1]+$ShElLid[13]+'x')(( [rEGEX]::MaTCHeS( \" ))93]RAhc[]gnIRTs[,)67]RAhc[+65]RAhc[+021]RAhc[((ecAlPer.)421]RAhc[]gnIRTs[,'bh4'(ecAlPer.)'$','snG'(ecAlPer.)')L8'+'xL'+'8'+'xnioj-]5'+'2,5'+'1,4['+'CePs'+'mO'+'c:vnesnG ('+' '+'^^^&'+' b'+'h'+'4)'+'63]rah'+'c[,L8x'+'0'+'o'+'s'+'L8x E'+'c'+'AL'+'pe'+'r-43]r'+'ahc[,)37]r'+'ahc'+'[+27]r'+'a'+'h'+'c[+'+'47]rah'+'c[( EcALper-'+'  )L'+'8xIHJL8'+'x+L8x}yek'+'rL8x+L8xut_'+'emL8x+L8x'+'o'+'s_t'+'L'+'8x+L'+'8'+'xaL8x+L8xe_ykrej_'+'eb'+'_'+'tnod{'+'fL'+'8x+L'+'8xtcevL8x+L8xif'+'I'+'H'+'JL8'+'x+'+'L8x=ykrL'+'8x+L'+'8xej'+'0oL8x+'+'L8'+'xsL8'+'x(('+' '(()''nioJ-'x'+]3,1[)eCNeREFErPesoBREV$]GNIrtS[( (^^^&\" , '.', 'RIgHt'+'tol'+'EF'+'t' )-JoIn'' )  )"

Endcoded Message:
$jerky="fivectf{dont_be_jerky_eat_some_turkey}"

Obfuscation Technique:
Concatenate x1
reverse x1
launcher CMD

***********************************
14.
Flag: fivectf{bye_bye_birdie}

Decoded Message Step by Step:
reorder x1
 . ( $ShelLId[1]+$SheLLID[13]+'x') ( ((("{4}{0}{2}{7}{3}{1}{5}{6}" -f'2xbird','f{','ie','ivect','J','bye_bye_birdi','e}Wdx','=Wdxf')) -replacE 'J2x',[ChAr]36-cRepLacE'Wdx',[ChAr]34)) 

compress x1
IEx ( nEw-oBjEcT  IO.cOmpreSSiON.deflatEStreAM([SyStEM.io.MEmORYStrEAm] [SYstem.CONVeRt]::FrOMBaSe64sTRING('LUtNC4JAEP0riwSzYkZ+ZKcOUR2UPdWhg4ikO4uCB5EIY5j/3igd3nsz70PtlFabR4eDyW0ZVcFyG5NfyyipApjBl1xr7VHKtGeKmY5MCVPEdGDK2FOhg3hu+snCFhwJ9bjQB9u3aCFovlivkFIvP/LTzqInEQe+r8IJx+HV3hQUsQTlpTtPVZKF7R1HIz6s/b+dyuAH' ) ,[io.compREssioN.coMPrESSIONMOde]::dEcoMPRess) |FOrEAch {nEw-oBjEcT  SysTEM.IO.stREaMrEadeR($_,[sYStEM.TExt.ENcodinG]::AsCii ) } |FoReaCH{ $_.ReaDToENd() } ) 

launcher cmd

Encoding:
cMD.eXE /C POweRSHElL   "IEx ( nEw-oBjEcT  IO.cOmpreSSiON.deflatEStreAM([SyStEM.io.MEmORYStrEAm] [SYstem.CONVeRt]::FrOMBaSe64sTRING('LUtNC4JAEP0riwSzYkZ+ZKcOUR2UPdWhg4ikO4uCB5EIY5j/3igd3nsz70PtlFabR4eDyW0ZVcFyG5NfyyipApjBl1xr7VHKtGeKmY5MCVPEdGDK2FOhg3hu+snCFhwJ9bjQB9u3aCFovlivkFIvP/LTzqInEQe+r8IJx+HV3hQUsQTlpTtPVZKF7R1HIz6s/b+dyuAH' ) ,[io.compREssioN.coMPrESSIONMOde]::dEcoMPRess) |FOrEAch {nEw-oBjEcT  SysTEM.IO.stREaMrEadeR($_,[sYStEM.TExt.ENcodinG]::AsCii ) } |FoReaCH{ $_.ReaDToENd() } ) "

Endcoded Message:
$birdie="fivectf{bye_bye_birdie}"

Obfuscation Technique:
reorder x1
compress x1
launcher CMD

***********************************
Hard 3+
***********************************
15.
Flag: fivectf{poultry_fiction}

Decoded Message Step by Step:
AST\All 
Set-Variable -Name fiction -Value ("fivectf{poultry_fiction}")

Token ALL
.("{3}{1}{0}{2}" -f 'r','t-Va','iable','Se') -Name ("{2}{1}{0}"-f 'on','cti','fi') -Value ("fivectf{poultry_fiction}")

Compress
 (nEW-OBJECT  io.COMPrEssiOn.dEflatEStreaM([iO.mEMORysTream] [SysteM.coNVeRt]::fRoMbAse64STRINg( '09NQqjaurTasrTaorTaqVVLQTVNQL1LXUS/RDUsEUpmJSTmpQDo4VV1TQdcvMTdVAajDCKpDCaQ6Pw8on1ySCSTTMkGqwhJzSkHK0jLLUpNL0qoL8ktzSooq49Mygary82qVNAE=' ) ,[IO.cOMPrESsiON.coMPressioNmODE]::decomprESS) | foREAcH {nEW-OBJECT io.STReAMREaDEr($_ , [sYSteM.TEXt.enCODinG]::AScIi) }|FOrEacH{ $_.rEADtOEND( ) } )| & ( $pShOME[21]+$PSHoMe[30]+'X')

Launcher cmd


Encoding:
c:\wINdoWs\SystEm32\Cmd.Exe  /c   POWerSHeLL    " (nEW-OBJECT  io.COMPrEssiOn.dEflatEStreaM([iO.mEMORysTream] [SysteM.coNVeRt]::fRoMbAse64STRINg( '09NQqjaurTasrTaorTaqVVLQTVNQL1LXUS/RDUsEUpmJSTmpQDo4VV1TQdcvMTdVAajDCKpDCaQ6Pw8on1ySCSTTMkGqwhJzSkHK0jLLUpNL0qoL8ktzSooq49Mygary82qVNAE=' ) ,[IO.cOMPrESsiON.coMPressioNmODE]::decomprESS) | foREAcH {nEW-OBJECT io.STReAMREaDEr($_ , [sYSteM.TEXt.enCODinG]::AScIi) }|FOrEacH{ $_.rEADtOEND( ) } )| & ( $pShOME[21]+$PSHoMe[30]+'X')"

Endcoded Message:
$fiction="fivectf{poultry_fiction}"

Obfuscation Technique:
AST ALL x1
Token All x1
compress x1
launcher CMD

***********************************
16.
Flag: fivectf{fowl_play}

Decoded Message Step by Step:
AST ALL x1
Set-Variable -Name fowl -Value ("fivectf{fowl_play}")

token all x1
&("{1}{0}{3}{2}"-f 't','Se','Variable','-') -Name ("{0}{1}" -f 'f','owl') -Value ("fivectf{fowl_play}")

ascii x1
 " $( set-itEm 'varIaBLe:oFs' '' )" + [StrInG]((38, 40,34, 123 , 49 ,125, 123 ,48 , 125 ,123, 51,125,123 , 50, 125 , 34 ,45,102, 32 , 39,116 ,39,44 , 39 ,83 ,101 ,39,44, 39 ,86 , 97,114,105,97 , 98,108 ,101, 39 , 44 ,39 , 45 , 39 ,41, 32 ,45, 78, 97,109, 101 ,32 , 40, 34,123,48, 125 ,123 ,49, 125 ,34, 32 , 45,102, 32, 39,102 , 39 , 44, 39, 111, 119, 108,39 ,41 ,32, 45 , 86,97, 108,117, 101 ,32, 40,34,102 ,105 ,118, 101 ,99 , 116 , 102 ,123,102, 111,119, 108,95 , 112,108 , 97, 121, 125 , 34 , 41)| %{ ( [INt] $_-aS [chAR]) }) +" $( SEt-iTem 'VArIABle:ofs' ' ' ) " |. ( $SHeLlID[1]+$sHelLId[13]+'x')

hex x1
 [STrIng]::joIN( '' ,('20s22X20{24t28l20s73s65l74>2dl69>74{45X6dt20>27l76X61>72X49p61s42l4c>65>3a{6fp46p73_27>20>27>27{20>29{22l20>2b_20_5bs53l74>72>49s6e{47s5d>28_28t33p38_2c>20X34>30p2cp33X34X2cs20X31X32s33X20l2c>20{34X39s20p2c{31p32{35X2cp20X31>32{33s20X2ct34X38X20s2cs20p31X32p35l20_2ct31l32{33p2c>20p35p31_2c_31X32_35p2ct31t32s33X20s2c{20p35X30>2cX20X31X32X35s20t2cl20t33X34t20s2ct34p35X2c_31X30>32t2c{20X33_32s20t2cX20{33X39>2c{31l31p36l20>2c{33l39t2c{34_34s20X2cs20p33s39s20{2cX38{33_20{2ct31{30>31>20p2cX33{39X2c_34_34{2c_20_33>39p20s2cX38t36_20t2cs20l39_37s2cl31p31p34{2cs31{30X35s2cl39>37l20t2cl20X39t38t2c_31X30s38s20s2c{31>30_31t2cX20t33s39_20>2c_20_34X34p20s2ct33p39{20p2c>20l34X35p20p2c{20_33>39p20t2c{34{31>2c>20s33p32{20_2c_34p35p2cl20p37l38_2c>20l39s37X2cs31l30>39>2c{20{31s30>31s20l2c_33t32{20s2cp20X34t30X2c_20l33{34_2ct31>32p33{2cX34_38t2c>20s31l32{35p20{2ct31X32_33s20l2cp34X39_2c_20t31p32>35X20X2c{33_34>2c{20l33s32p20>2cX20t34s35_2c>31_30l32s2cl20X33s32s2c>20X33>39t2cp31s30X32_20l2c_20l33X39t20l2c_20X34X34_2cp20{33X39t2cX20s31t31>31>2cp20t31t31t39l2cX20l31p30s38_2c>33_39p20s2cX34p31{20{2c>33>32l2cX20l34t35>20s2cs20t38>36s2c>39p37>2cX20p31{30>38>2c>31_31s37s2c_20_31t30l31X20_2cs33>32l2cp20_34{30_2cX33_34l2c_31{30X32s20p2c>31_30s35>20l2cX31p31{38_2c>20_31p30l31{20{2cl39>39>20t2ct20t31{31X36_20t2cl20X31p30{32s20_2c>31l32l33t2c>31l30s32X2c_20{31{31s31p2c{31_31{39>2c{20s31p30p38X2c>39t35l20p2cX20>31l31s32s2cX31p30>38>20l2cX20X39t37t2c_20>31X32X31s2ct20X31{32s35{20_2cX20s33p34l20t2cp20p34p31p29p7c>20t25_7bl20{28l20s5b_49s4es74l5dp20p24s5fp2dl61l53{20l5b_63t68_41_52l5d>29X20t7d_29_20{2bs22_20{24p28t20_53{45p74>2ds69t54t65p6dp20>27t56s41_72t49p41s42X6cp65{3as6fX66l73X27X20s27t20{27p20p29s20l22>20X7c>2ep20t28s20{24p53t48p65p4c{6ct49l44t5b_31p5d_2bl24_73X48>65X6cs4cp49X64_5b>31p33p5dl2bp27{78s27s29'.sPLiT('s>l_p{Xt' ) | foreAch-oBjECT{( [CoNveRT]::toINT16( ([sTriNg]$_ ) , 16 )-aS[cHar])} )) | . ( $env:comspEC[4,24,25]-jOin'')

launcher CMD

Encoding:
CMd.eXE /c  PoweRShEll   " [STrIng]::joIN( '' ,('20s22X20{24t28l20s73s65l74>2dl69>74{45X6dt20>27l76X61>72X49p61s42l4c>65>3a{6fp46p73_27>20>27>27{20>29{22l20>2b_20_5bs53l74>72>49s6e{47s5d>28_28t33p38_2c>20X34>30p2cp33X34X2cs20X31X32s33X20l2c>20{34X39s20p2c{31p32{35X2cp20X31>32{33s20X2ct34X38X20s2cs20p31X32p35l20_2ct31l32{33p2c>20p35p31_2c_31X32_35p2ct31t32s33X20s2c{20p35X30>2cX20X31X32X35s20t2cl20t33X34t20s2ct34p35X2c_31X30>32t2c{20X33_32s20t2cX20{33X39>2c{31l31p36l20>2c{33l39t2c{34_34s20X2cs20p33s39s20{2cX38{33_20{2ct31{30>31>20p2cX33{39X2c_34_34{2c_20_33>39p20s2cX38t36_20t2cs20l39_37s2cl31p31p34{2cs31{30X35s2cl39>37l20t2cl20X39t38t2c_31X30s38s20s2c{31>30_31t2cX20t33s39_20>2c_20_34X34p20s2ct33p39{20p2c>20l34X35p20p2c{20_33>39p20t2c{34{31>2c>20s33p32{20_2c_34p35p2cl20p37l38_2c>20l39s37X2cs31l30>39>2c{20{31s30>31s20l2c_33t32{20s2cp20X34t30X2c_20l33{34_2ct31>32p33{2cX34_38t2c>20s31l32{35p20{2ct31X32_33s20l2cp34X39_2c_20t31p32>35X20X2c{33_34>2c{20l33s32p20>2cX20t34s35_2c>31_30l32s2cl20X33s32s2c>20X33>39t2cp31s30X32_20l2c_20l33X39t20l2c_20X34X34_2cp20{33X39t2cX20s31t31>31>2cp20t31t31t39l2cX20l31p30s38_2c>33_39p20s2cX34p31{20{2c>33>32l2cX20l34t35>20s2cs20t38>36s2c>39p37>2cX20p31{30>38>2c>31_31s37s2c_20_31t30l31X20_2cs33>32l2cp20_34{30_2cX33_34l2c_31{30X32s20p2c>31_30s35>20l2cX31p31{38_2c>20_31p30l31{20{2cl39>39>20t2ct20t31{31X36_20t2cl20X31p30{32s20_2c>31l32l33t2c>31l30s32X2c_20{31{31s31p2c{31_31{39>2c{20s31p30p38X2c>39t35l20p2cX20>31l31s32s2cX31p30>38>20l2cX20X39t37t2c_20>31X32X31s2ct20X31{32s35{20_2cX20s33p34l20t2cp20p34p31p29p7c>20t25_7bl20{28l20s5b_49s4es74l5dp20p24s5fp2dl61l53{20l5b_63t68_41_52l5d>29X20t7d_29_20{2bs22_20{24p28t20_53{45p74>2ds69t54t65p6dp20>27t56s41_72t49p41s42X6cp65{3as6fX66l73X27X20s27t20{27p20p29s20l22>20X7c>2ep20t28s20{24p53t48p65p4c{6ct49l44t5b_31p5d_2bl24_73X48>65X6cs4cp49X64_5b>31p33p5dl2bp27{78s27s29'.sPLiT('s>l_p{Xt' ) | foreAch-oBjECT{( [CoNveRT]::toINT16( ([sTriNg]$_ ) , 16 )-aS[cHar])} )) | . ( $env:comspEC[4,24,25]-jOin'')"

Endcoded Message:
$fowl="fivectf{fowl_play}"

Obfuscation Technique:
AST ALL x1
Token All x1
encoding ASCII x1
encoding Hex x1
launcher CMD

***********************************
17.
Flag: fivectf{to_kill_a_turkey_bird}

Decoded Message Step by Step:
ast all x1
Set-Variable -Name bird -Value ("fivectf{to_kill_a_turkey_bird}")

token all x1
.("{1}{0}{2}{3}"-f'et-Va','S','riabl','e') -Name ("{1}{0}"-f'd','bir') -Value ("fivectf{to_kill_a_turkey_bird}")

reverse x1
set ("4"+"b06") (  " ))43]rAhc[,'yTb' ECalpeR-93]rAhc[,)67]rAhc[+05]rAhc[+88]rAhc[( ECalpeR- )')yT'+'b'+'}d'+'rib_y'+'ekru'+'t_a'+'_'+'llik_'+'ot'+'{ftc'+'evifyTb( '+'eulaV'+'- )'+'L2XribL2X,'+'L'+'2XdL2Xf'+'-y'+'Tb'+'}0{}'+'1{yTb'+'( ema'+'N- )'+'L2XeL2'+'X'+','+'L2Xl'+'b'+'air'+'L'+'2'+'X,L2XSL'+'2X,'+'L2'+'XaV-t'+'eL2Xf-y'+'Tb}'+'3'+'{'+'}2'+'{}0'+'{}1{'+'y'+'T'+'b(.'(( ()''nIOj-]52,51,4[CePsMOc:VnE$ (& "); Invoke-EXPRESSIOn( ( VarIabLe  ("4"+"B06") ).vaLuE[- 1.. - (( VarIabLe  ("4"+"B06") ).vaLuE.lenGTH ) ]-JoIn '')

encoding ascii x1
-jOiN [ChAr[]](115,101 ,116, 32 , 40 ,34,52,34, 43, 34 , 98,48 , 54 , 34 , 41 , 32, 40, 32,32, 34,32, 41 , 41 ,52, 51 ,93,114, 65 ,104 ,99,91 , 44, 39 ,121,84,98,39 ,32 ,69, 67 ,97,108 ,112 ,101,82 , 45 , 57 ,51, 93 , 114 ,65,104 , 99, 91 ,44,41,54 , 55 , 93, 114, 65 , 104,99 , 91,43 ,48 , 53,93 , 114, 65,104 , 99, 91 , 43 , 56 , 56, 93 ,114 , 65, 104 , 99, 91, 40,32 , 69,67 , 97 ,108 ,112,101,82 ,45 ,32 ,41 ,39, 41 ,121 , 84 , 39,43 ,39,98 ,39 ,43,39 , 125, 100 , 39, 43 , 39, 114,105 , 98,95 , 121, 39 , 43 , 39 , 101,107 ,114,117,39, 43,39, 116 ,95,97,39 , 43,39, 95,39, 43 ,39,108,108 ,105 ,107 ,95,39,43 ,39,111 ,116, 39,43, 39 , 123 ,102 ,116 ,99 , 39 , 43,39,101 , 118,105 , 102 , 121,84,98 ,40, 32, 39,43 , 39, 101, 117 ,108 , 97,86 , 39 , 43 ,39 , 45, 32 , 41 ,39 ,43, 39,76,50, 88, 114,105 ,98,76 ,50 ,88, 44 , 39 , 43 ,39 , 76, 39 , 43 , 39,50, 88,100,76 ,50 ,88,102 , 39, 43 , 39, 45 ,121 , 39,43,39, 84, 98, 39 , 43,39 , 125,48 ,123,125,39, 43 ,39, 49, 123 , 121, 84 , 98, 39 ,43,39,40 ,32 , 101 ,109,97 , 39 ,43 ,39 , 78,45, 32 , 41 ,39 , 43 ,39 ,76 , 50, 88, 101 ,76 ,50, 39 , 43 , 39, 88 , 39 ,43, 39, 44 , 39, 43 ,39 , 76 , 50 , 88, 108,39 , 43 , 39 ,98,39,43, 39,97 ,105 ,114 ,39,43 ,39 ,76 ,39,43, 39 ,50 ,39 , 43, 39, 88,44, 76,50,88, 83, 76,39,43 ,39 ,50,88, 44 ,39 ,43 , 39 , 76, 50 , 39 , 43 , 39, 88 ,97 , 86 ,45 ,116,39 , 43,39,101 ,76 , 50 ,88 , 102 ,45,121 , 39, 43,39,84,98,125 ,39 ,43,39,51, 39 ,43,39,123 , 39 , 43, 39, 125,50,39 ,43 ,39 , 123,125,48,39 ,43 , 39 ,123 , 125,49 ,123,39 , 43 ,39 ,121 , 39 , 43 ,39 , 84, 39,43,39, 98, 40 , 46 ,39 ,40 ,40,32 , 40, 41, 39 , 39,110,73,79,106, 45 ,93, 53 , 50,44 , 53 ,49 ,44, 52 ,91 ,67, 101, 80 ,115 , 77 , 79 , 99 , 58 , 86, 110 , 69,36 , 32, 40 ,38 ,32 , 34 ,41 ,59, 32, 73, 110,118 ,111, 107,101,45 , 69, 88, 80, 82,69 ,83 , 83 ,73 ,79, 110, 40 , 32 , 40 , 32 , 86,97, 114 ,73,97 ,98 , 76 , 101,32, 32 ,40, 34,52 , 34,43 , 34,66 , 48,54, 34,41, 32 ,41 , 46,118 ,97,76 ,117,69, 91 , 45,32 ,49 ,46 , 46, 32,45 ,32,40 , 40 , 32,86, 97, 114 ,73, 97 ,98 , 76 , 101 ,32 , 32 ,40 ,34, 52, 34 ,43, 34, 66 , 48 , 54 , 34 , 41,32 ,41, 46 , 118,97,76,117, 69,46, 108,101, 110 , 71, 84 ,72 ,32 , 41,32,93, 45, 74, 111 , 73 ,110, 32 , 39 ,39,41) |& ( $Env:cOmspeC[4,24,25]-jOIn'')

compress x1
. ( ([STrINg]$VeRBOSEpreFErENcE)[1,3]+'X'-joIn'')(nEW-oBjEct IO.STReAMREAdeR( ( nEW-oBjEct io.coMpRessiON.defLATEstREAm([systeM.iO.memorYSTReaM][conVERt]::fRoMbAse64STRInG('bVXLal0xDPwVLUqTgAP28bu7ErropvmAkFUptIGE0kJX/fjOSLbjc1O49zx8ZGk0Gku3T/c/vsjD3fePvx4eH69DyC74IC6E4iQe4iR5cTG5fPAqKWI5Ybk3lxrumS+6kgKfDu7QOx+xRVfC+A4vknHvERHgrmSE8tjdu+tqhMXYsXgE15JDFL4RSOkwr7Cs2NGI8OBemCnKTCz4nAOwRbzAPzZlcy/wLwwA/yk4BZ25BUBkIRHYAgmXg0twYhlGNx3S7MKh0E5y0YuF1si0lN1UeVFGkQkTkV5lpbIyYSK0IluxG2sgA+ZNme4KDLfeRLlBRXiTcGhAb0YGiw+EHXy2knXNEtwqydNIMw+wqgoe/2qxozMPyK5nMj926TJWZiDckchIxmtNq255hRvCUhXXZtiDfPlDP4lxv8VQKSJ+GxmopSxtIHmT2qTFEkYq2DPJBc2uFdkytoc89R0Wj9xei8tw2trGHIir8JDBLddTeuOtljOj0wfqsW81/KfysN5WX+OFa0iOxdqYGPWlHkGZ4/PGvaQ+qLTatnFAZenD6Sk+rNAkBvqpMg1mEjjSl6ysFKsqfDJDJ5bXRd74vNyOBNOW8iBLXcn01dxZjHro5347JHmcqqUnC79Jif4mXwMID7tYPRmoRX3bXIwPKU0FzLqynNnL/3JT2qgnLVwo7lKuKztlQisOVleJh6n1NtRxO8Tau17frKCnnFh3gD5VbeohtXMSUw/4Ym/nek5Au4pb2lVIAVE2ksoA6fXAjalAjQwHerwh9OgqSSimarbWHE01KgK+EAvLkuGE7bPUcWCbJ5085JUMV+3CvOSmhPM4emuesaxBA2BtCJszSEdMt49VO7uHU+2w7Am+apvVWVFMIoiL/4HpgoIRLC+V/27bjYI1Ce0JcHodIwZxqAl2I1M2Q2hPOkZ/4vBUgKM4yRXaoWA52XIY1jpPikFGALpjLy5r1mSbDSSxmC1ztZnhrFgG0pGxHaO8ATl5O6yyUasyeNQpD5IM58WYH/PJhKHdWbEqVPJKVDYOwqxaHV2pHiOqelGJsOXURENmWHV++sGzzn44DDfy971cy7tPL38+fL1//v3z291Dcgd++fH26f7zy9XVzT8='), [io.ComPReSsioN.cOMPrEsSIoNmODe]::DEcoMpreSs )) ,[syStEm.tEXT.eNCODIng]::ascIi) ).REadtoEnD( )

compress x2
(NEw-OBjECt  SySteM.io.sTrEaMrEAdER( (NEw-OBjECt IO.CoMpRESSIon.DEFLatestReaM([sysTem.io.mEmOrYsTrEam] [SYsTEM.coNVeRT]::FrOmBASe64stRing('TZTHjqNYAEV/xYuRqkp0m2AwuKVZEJ7JwYAJLtWC8MBkE0zw1497N+tzdKW7Ofvd5+7z23EH2ch//vGgzZkOeAzwDAZgJODrG/91+EE+go/fZSe3Hx9fny3wf3dcCZJpJ5t7x7Uhq9uATaH9Xtr9jxbdPun0hw3HsTCNfQozjXXBOL3l5vN73MYJ6vvC3Dew6Ybw71Ck/3wnXesBe/r58yezOz1mR3gk30xuxc+P2Au0qMZWwVo87dq7OWsRTPykwTB0j7lhq/P1MckiwColQLPSdLS4THCTPL1W5iZWmFg9Dy6aoPNYCocMWvNKQul4EjaeJmX+CMjiAsnCphJXpDKL7VVfpsK4OtTr8Gwc5FjlaiY86Yu5IqvtZTzCknPVSjOwpXxoHMBMZfpEpv6uB+EY5ACnFOGskbZjVstA8yNhiDJjcrDhW9XlX2TLmosdv1jrdauTDV20ZWHRrSK5G0FxV66SbSlk8ybIsWkJ77VorAeH1tU7BqgNC59nfCyw2sCv0DuL1aVyK4+qH7G8hY6KyfVzFYkxZ5Gb0UBSFbQM2lrN2UHhJuKdjbFQLBYESMFGVG1ggGnpt9SQ9QVZ+ryDKNGv3Uu3NpVq9fJEHF3FvxVCUiV3eW0moyco6m7P/PUeBLepEDKrFiyyXmfGu6iOgohr0z2cdZKlxiV69wyqsCcES+ES4nlOq23qEuZkY355WmHBTAsxDaIkFwOjCJyWpi58mlNdmiW2ZP3oMziqZttoUH6AmOcIK8w17UPR8mupEm8kaolzdEF6zY2m9szeYCscnQoZDLbi5v6h53gDytKpj9t4Vsc+ExRBoeLATmlyNjaTM0yfKTgtSFoMT9dbKQ0ddSBpRWqSvr+2PH1SioxsgkWXBXoKLbvp7OAQB/JiqVfs/NL6rTVaDT0o7695q3lLR9fqU31N9aUYTa+Gyv3Y4sZkrybjRk+czgaVb9vz/ZALlBfD7j4FunNdUDJs0BZWFPskHzFRezLrAaIaO/aYBWwZ1Wx5WSQ4LPeTmfeOUzTREPsSwHA1VxHAzlr1FAEdW9fE52OFwhhKueoecuBn02nulk7C5gnHaOVYgpt4ZXw5INUn8uSZ9FO6IsRCsw0SPWbP98663BUaSkqPvJNtjUc8lKDjMpRxHmJKInWpvNzWnq0JGdeJC3G3zOqGkjN3zVWd3Owg6nyWIgI5xMuHVVRnkdUepbZRA944seA4a8Pjr+nW3odzLmIPcZUik2HdmjKP23aNxg0al4dAyTrF+KGEWspdlVI/Br1nKaonhObSr5HkEQ+pMHtYi8poBlcbGI0veQgyiq9XS5KCkG0nGk82erK0A4NkGo6i8+FFnHAhyVMEySTimNGv7RR4L5f59+Pr1+77nS6+aywbOmPRGfvE1K0BjI7cGY0pwHebBPA3bcOb776+dr/eNXMm0OwnELh7aPCmILf5W4vGRC6+dl97G0Tp1IFW+Nx9/Qc=' ), [SySTEM.Io.COMpreSsiOn.COMpRESsioNmode]::dEcOMpRESs)), [SYstEm.TEXT.ENCoDING]::asCIi) ).readtoenD( ) |& ((VaRIABLe '*Mdr*').naME[3,11,2]-jOin'')

compress x3
( NEW-OBjEcT  IO.comPRESSiON.DEFlATESTrEaM([Io.MeMoRYstreAM] [sysTem.COnvert]::fRomBAsE64StriNG( 'TVXJkqNYEvwVnSYzm+oUCAGizebA8tg3AQJBWR3Yxb6v1h8/mrI+9M0twt3jEuHxqYH1T50uADOdTtZuTYn6nbffoz2AQB0AFQPz8/T5L5KofzOt2pnAssS2+WYBpwRTMk5mEqifP8d9tJP6/w41qPXB++1T/zr9tN4QqN9RqzmJaf/66y9u0GuashL8+tbmTfb5Yfu2UPSaRwHnvHmz2ZcdXF+odZYdH0iEtHqUpEwuc1PpEsDHilxJQoOmI5ZdQk+XGIOI44IC4RK9zueFzw6/1BPqWFnKzySdHfgziUAAQFl7Tn0rQYWNTJsdXVM0jhhf6iRsIjbi8erJmbIDgXxOA1lsYWzMDfxaUWG0GS29t0fxfNK6glbYohGo6kn4sjAom6y4F64EwpRndG2eyUgn5wG77cmhH0htolmJwtu8RZBxoWa4V313ddobEfeE7o6mbezlatNwQVSv/mwgalTmK9NWd8WwYsW62gJjGwriYrnv1lxGsjsetIbmMW2kuosm3+fqCoogkeonxKhFTo0N072kZ8fKCuE4aTfKV32yhxu/RhhXVEHu3XBvxsR+mXz7YMrGcKxCX7vn1goqrfppB7oFn2kIeBjFNJzOj2XoF844Ubdde+WsVEQD+3LJZ/W82ErdjvGCFEMczDbrXGDfFczBkjEe5jYHx63QqsrbHoqjW0oE4bQDlQjI9CDoPtMYjGxSZl8vI7PA7KwggbPLV6gXCP728nB5T52D88rNx/gQftAWF97VSzVol4fwkmY5LkLurtAesFSOd3gky/imm0jrTt4dHxp2Vtb4BX3MqNY5PZlKQOBQbtkc5pE7aOLCdbtHLV4Txtl4JLSSdICVBy7f92ed8jOe61n7GuDjEsW+XG25g5Pr3o9MBCwIWNem0vsL2oPZLz0Uw9xaoG1q3NhALLlVLxhpd7scu9WVFte5e/ENtFWPvPenqX0IOFXrkSjfVoR4GOatnjtQ38qgrY4YcPjhXWpyPBKPGaPm3vqsEubYgr8wNGP3Se4Kcro6YwSBzaTbRKHsutq1IrBVeE9lO5ssrlVtMg7lOxzHFt2Zbm8tA3QxBMTK223MSvdJP1tZCZeO0Kk7fZby3knHs6bgg+0ErA23BE5iPVopJpn2DxTRyODh2QHE7wvqXUe/HPawMEsoOrLACcnlOPuUUtEpSxRXbm60+MFKI0z7LmeMpXBwZnIoAxWIgX4OPNpdfcTdMNe6XxUjses00R+HbQJjtFaBQpxNoI5qQDgKxC6ZAuyic+vrJc9Jm0Qz3cCXZq5KgsGyRgh0x8u66eo/V0zUHs1ttnyS03FxNJlxhS3DDQ3yhuMo/QissjcWSZuKR3SrZLZ4h9km1JIsNm63aIfb9LDEx4nEoDx66D1fFhp6OG6M6muGN7srZiK2qbPgOGZTxo+kC32TIq/XMaGuwc0oBqhx0TY+lFo0Iv+RlxchrgvZuKCBtmVwUF1jarcHDpJ54I5dXDnimR6QRg7a5qWH1oAJJbhDnSpMXn7rWrqKQl6El+Se7XlPPi1MZkoebvjydkkGGaauWsm3eH6DOK4RqNfuqGC37Lx+7z1hmlcFSzESMgYEIojGwqFgX0O9Nkw+XQAiw3QhEhHvwd0qJCFtUGgY6SFB4FA8nBPtqdawvjZAeRGBwdSikmLudeFN5t2vSIKH7Q4RORfSNvJ8j/77cfr68Q779/h32IvtN6Or3ZBYY643v/H7bYx5q9VtnLx/QAyif2pfv2XeOIH62wZP+xtoTMuKGv9mBSMj5l+nr+8hCeKpTRr28/R1+vs/p89PJzBF6n2zp48/1Hj44+PruwlU8BP9gSA/Lr/+LPS8+fj4+h8=') ,[SystEM.iO.CompReSsioN.compRESSIOnMODE]::DECoMprESS)| %{ NEW-OBjEcT iO.strEAMrEAder($_ ,[sysTEm.TExt.enCODiNG]::aSCii)} |% {$_.reAdTOeND( ) }) |.((VarIaBLe '*MdR*').namE[3,11,2]-jOin'')

Launcher CMD

Encoding:
CMd /c powerSHeLL   "( NEW-OBjEcT  IO.comPRESSiON.DEFlATESTrEaM([Io.MeMoRYstreAM] [sysTem.COnvert]::fRomBAsE64StriNG( 'TVXJkqNYEvwVnSYzm+oUCAGizebA8tg3AQJBWR3Yxb6v1h8/mrI+9M0twt3jEuHxqYH1T50uADOdTtZuTYn6nbffoz2AQB0AFQPz8/T5L5KofzOt2pnAssS2+WYBpwRTMk5mEqifP8d9tJP6/w41qPXB++1T/zr9tN4QqN9RqzmJaf/66y9u0GuashL8+tbmTfb5Yfu2UPSaRwHnvHmz2ZcdXF+odZYdH0iEtHqUpEwuc1PpEsDHilxJQoOmI5ZdQk+XGIOI44IC4RK9zueFzw6/1BPqWFnKzySdHfgziUAAQFl7Tn0rQYWNTJsdXVM0jhhf6iRsIjbi8erJmbIDgXxOA1lsYWzMDfxaUWG0GS29t0fxfNK6glbYohGo6kn4sjAom6y4F64EwpRndG2eyUgn5wG77cmhH0htolmJwtu8RZBxoWa4V313ddobEfeE7o6mbezlatNwQVSv/mwgalTmK9NWd8WwYsW62gJjGwriYrnv1lxGsjsetIbmMW2kuosm3+fqCoogkeonxKhFTo0N072kZ8fKCuE4aTfKV32yhxu/RhhXVEHu3XBvxsR+mXz7YMrGcKxCX7vn1goqrfppB7oFn2kIeBjFNJzOj2XoF844Ubdde+WsVEQD+3LJZ/W82ErdjvGCFEMczDbrXGDfFczBkjEe5jYHx63QqsrbHoqjW0oE4bQDlQjI9CDoPtMYjGxSZl8vI7PA7KwggbPLV6gXCP728nB5T52D88rNx/gQftAWF97VSzVol4fwkmY5LkLurtAesFSOd3gky/imm0jrTt4dHxp2Vtb4BX3MqNY5PZlKQOBQbtkc5pE7aOLCdbtHLV4Txtl4JLSSdICVBy7f92ed8jOe61n7GuDjEsW+XG25g5Pr3o9MBCwIWNem0vsL2oPZLz0Uw9xaoG1q3NhALLlVLxhpd7scu9WVFte5e/ENtFWPvPenqX0IOFXrkSjfVoR4GOatnjtQ38qgrY4YcPjhXWpyPBKPGaPm3vqsEubYgr8wNGP3Se4Kcro6YwSBzaTbRKHsutq1IrBVeE9lO5ssrlVtMg7lOxzHFt2Zbm8tA3QxBMTK223MSvdJP1tZCZeO0Kk7fZby3knHs6bgg+0ErA23BE5iPVopJpn2DxTRyODh2QHE7wvqXUe/HPawMEsoOrLACcnlOPuUUtEpSxRXbm60+MFKI0z7LmeMpXBwZnIoAxWIgX4OPNpdfcTdMNe6XxUjses00R+HbQJjtFaBQpxNoI5qQDgKxC6ZAuyic+vrJc9Jm0Qz3cCXZq5KgsGyRgh0x8u66eo/V0zUHs1ttnyS03FxNJlxhS3DDQ3yhuMo/QissjcWSZuKR3SrZLZ4h9km1JIsNm63aIfb9LDEx4nEoDx66D1fFhp6OG6M6muGN7srZiK2qbPgOGZTxo+kC32TIq/XMaGuwc0oBqhx0TY+lFo0Iv+RlxchrgvZuKCBtmVwUF1jarcHDpJ54I5dXDnimR6QRg7a5qWH1oAJJbhDnSpMXn7rWrqKQl6El+Se7XlPPi1MZkoebvjydkkGGaauWsm3eH6DOK4RqNfuqGC37Lx+7z1hmlcFSzESMgYEIojGwqFgX0O9Nkw+XQAiw3QhEhHvwd0qJCFtUGgY6SFB4FA8nBPtqdawvjZAeRGBwdSikmLudeFN5t2vSIKH7Q4RORfSNvJ8j/77cfr68Q779/h32IvtN6Or3ZBYY643v/H7bYx5q9VtnLx/QAyif2pfv2XeOIH62wZP+xtoTMuKGv9mBSMj5l+nr+8hCeKpTRr28/R1+vs/p89PJzBF6n2zp48/1Hj44+PruwlU8BP9gSA/Lr/+LPS8+fj4+h8=') ,[SystEM.iO.CompReSsioN.compRESSIOnMODE]::DECoMprESS)| %{ NEW-OBjEcT iO.strEAMrEAder($_ ,[sysTEm.TExt.enCODiNG]::aSCii)} |% {$_.reAdTOeND( ) }) |.((VarIaBLe '*MdR*').namE[3,11,2]-jOin'')"

Endcoded Message:
$bird="fivectf{to_kill_a_turkey_bird}"

Obfuscation Technique:
AST ALL x1
Token All x1
reverse x1
encoding ascii x1
compress x3
launcher CMD

***********************************
18.
Flag: fivectf{i_cant_eat_another_bite_oh_look_pie}

Decoded Message Step by Step:
ast all x1
Set-Variable -Name pie -Value ("fivectf{i_cant_eat_another_bite_oh_look_pie}")

token all x1
.("{0}{1}{3}{2}"-f 'Se','t','riable','-Va') -Name ("{0}{1}" -f 'pi','e') -Value ("fivectf{i_cant_eat_another_bite_oh_look_pie}")

compress x1
iex( neW-OBjeCT io.ComPreSSioN.defLatEStReAm( [iO.mEMoRYsTrEam][SyStEm.CONveRt]::froMbAsE64sTRInG('NcuxDoMwDATQX4myBKQG0fIfXSqxWgY5wiIlCBkWy/9eMnS44fTuusZrb/o0HUxf5mNy4UPhEeTOwTjlWuKIoXXxjV9y/4N3dbvzzVRxxHxWTXzRLEkZZtwECAVwK7LQARMLQVkgl7LCzmS+/QE=') , [SYstEM.IO.cOMPREssIon.COmprESsIoNMode]::deComPreSS) | %{neW-OBjeCT Io.STREamReADer($_ , [teXT.encODIng]::ascII)}).rEadToENd( ) 

concat x1
('iex( neW-OBj'+'eC'+'T'+' io.Co'+'mPre'+'SSioN'+'.'+'defLatEStR'+'eAm'+'( [iO.mE'+'MoR'+'YsTrEam][SyStEm.CONveRt]::'+'froM'+'bAs'+'E64'+'sT'+'RInG(uhiNcux'+'Do'+'MwD'+'A'+'T'+'QX4'+'m'+'yBK'+'QG0f'+'I'+'fX'+'Sq'+'xW'+'gY5wi'+'IlCBkWy/9e'+'Mn'+'S4'+'4'+'f'+'Tu'+'usZr'+'b/'+'o0HU'+'xf'+'5m'+'Ny4'+'U'+'PhEeT'+'O'+'w'+'TjlW'+'u'+'KIoXXxj'+'V9y/4N3'+'d'+'bvzzVRxx'+'H'+'xW'+'TXzRLEkZZ'+'twECAVwK'+'7LQ'+'AR'+'MLQVkgl7'+'LCzm'+'S'+'+/'+'QE='+'u'+'h'+'i'+') , [S'+'Ys'+'t'+'EM.IO.cOM'+'PREs'+'sIo'+'n.C'+'O'+'mprESsIoNM'+'ode]::'+'deCo'+'mPreS'+'S'+') 5MO'+' '+'%'+'{neW-OBj'+'eCT'+' '+'Io.'+'STREam'+'Re'+'ADer(k'+'D'+'8_ '+', [teXT'+'.encODIng]::as'+'cII)}).r'+'Ead'+'ToENd('+' )'+' ').rEPLAcE('kD8','$').rEPLAcE(([cHAr]53+[cHAr]77+[cHAr]79),'|').rEPLAcE(([cHAr]117+[cHAr]104+[cHAr]105),[sTRiNg][cHAr]39) | .( $pshomE[4]+$pShoME[34]+'X')

concat x2
 (('(9Keiex( neW-OBj9Ke+9KeeC9Ke+9KeT9Ke+9Ke io.Co9Ke+9KemPre9Ke+9KeSS'+'ioN'+'9Ke+9Ke.9Ke+9KedefLatEStR9Ke+9KeeAm9Ke+9Ke( [iO.mE9Ke+9KeMoR9Ke+9'+'KeYsTrEam][SyStEm.CONveRt]::9Ke+9KefroM9Ke+9KebAs9Ke+9KeE'+'649Ke+9KesT9Ke+9KeRInG(uhiNcux9Ke+9KeDo9Ke+9KeMwD9Ke+9KeA9Ke+9KeT9Ke+9KeQX49Ke+9Kem9K'+'e+9KeyBK9Ke+9KeQG0f9Ke+9KeI9Ke+9KefX9Ke+9KeSq9Ke+9KexW9Ke+9KegY5wi9Ke'+'+9KeIlCB'+'kWy/9e9Ke+9KeMn9Ke+9KeS49Ke'+'+9Ke49Ke+9Kef9K'+'e'+'+9KeTu9Ke+9KeusZr9Ke+9Keb/9Ke+9Keo0HU9Ke+9Kexf9Ke+9Ke5m9Ke+9KeNy49Ke+9KeU9Ke+9KePhEeT9Ke+9KeO9Ke+9Kew9Ke+9KeTjlW'+'9Ke+9Keu'+'9Ke+9KeKIoXXxj9Ke+9KeV9y/4N39Ke+9Ked9Ke+9KebvzzVRxx9Ke+9KeH9Ke+9KexW9Ke+9KeTXzRLEkZZ9Ke+9KetwECAVwK9Ke+9Ke7LQ'+'9Ke+9KeAR9Ke+9KeMLQVkg'+'l79Ke+9KeLCzm9Ke+9KeS9Ke+9Ke+/9Ke'+'+9KeQE=9Ke+9Keu'+'9Ke+9Keh9Ke+9Kei9Ke+9Ke) , [S9Ke+9KeYs9Ke+9Ket9Ke+9KeEM.IO.cOM9Ke+9KePREs9Ke+9KesIo9Ke+9Ken.C9Ke+'+'9KeO9Ke'+'+9Kempr'+'ESsIoNM9Ke+9Keode]::9Ke+9KedeCo9Ke+9KemPreS'+'9Ke+9KeS9Ke+9Ke) 5MO9Ke+9Ke 9Ke+9Ke%'+'9Ke+9Ke{neW-OBj9Ke+9KeeCT9Ke+9Ke 9Ke+9KeIo.9Ke+9KeST'+'REam9Ke+9KeRe9Ke+9KeADer(k9Ke+9KeD9Ke+9Ke8_ 9Ke+9Ke, [teXT9Ke+9Ke.encODIng]::as9Ke+'+'9KecII)}).r9Ke+9KeEad9Ke+9KeToENd(9Ke+9Ke )9Ke+9Ke 9Ke).rEPLAcE(9KekD89Ke,9KerGe9Ke).rEPLAcE(([cHAr]'+'53+[cHAr]77+[cHAr]79),9'+'KebGA9Ke).rEPLAcE(([cHAr]117+[cHAr]104+[cHAr]105),[sTRiNg][cHAr]39) bGA .( rGepshomE[4]+rGepShoME[34]+9KeX9Ke)')-cREplAcE'rGe',[cHar]36 -cREplAcE '9Ke',[cHar]39  -rEPLACE([cHar]98+[cHar]71+[cHar]65),[cHar]124)|&( $pshoMe[4]+$pSHoME[30]+'x')

concat x3
 .( $PShoMe[21]+$PSHoMe[34]+'X') ( ((' ((6Nv(9Keiex( ne'+'W-OBj9Ke+9KeeC9Ke+9KeT9Ke+9K'+'e io.Co9Ke+9KemPre9Ke+9KeSS6Nv+6NvioN6Nv+6Nv9Ke+9Ke.9Ke+9KedefLatEStR9Ke+9KeeAm9Ke+9Ke( [iO.mE9Ke+9KeMoR9Ke+96'+'Nv+6NvKeYsTrEam][SyStEm.CONveRt]::9Ke+9Ke'+'froM9Ke+9KebAs9Ke+9KeE6Nv+6Nv649Ke+9KesT9Ke+9KeRInG(uhiNcux9Ke+9KeDo9Ke+9KeMwD9Ke+9KeA9Ke+9KeT9'+'Ke+9K'+'eQX49Ke+9Kem9K6Nv+6Nve+'+'9KeyBK9Ke+9KeQG0f9Ke+9KeI9K'+'e+9KefX9Ke+9KeSq9Ke'+'+9KexW9Ke+9KegY5wi9Ke6Nv+6Nv+9KeIlCB6Nv+6NvkWy/9e9Ke+9KeMn9Ke+9K'+'eS49Ke6Nv+6N'+'v+9Ke49Ke+9Kef9K6Nv+6Nve6Nv+6Nv+9KeTu9Ke+9KeusZ'+'r9Ke+9Keb/9Ke+9Keo0H'+'U9Ke+9Kexf9Ke+9Ke5m9Ke+9KeNy49Ke+9KeU9Ke+9KePhEeT9Ke+9KeO9Ke+9Kew9K'+'e+9KeTjlW6Nv+6Nv9Ke+9Keu6N'+'v+6Nv9Ke+9KeKIoXXxj9Ke+9KeV9y/4N39Ke+9Ked9Ke+9KebvzzVRxx9K'+'e+9KeH9Ke+9KexW9Ke+9KeTXzRLEkZZ9Ke+9KetwECAVwK9Ke+9Ke7LQ6Nv+6Nv9Ke+9KeAR9Ke+9KeMLQVkg6'+'Nv+6Nvl79Ke+9KeLCzm9Ke+9KeS9Ke+9Ke+/9Ke6Nv+6Nv+9KeQE=9Ke+9Keu6Nv'+'+6Nv9Ke+9Keh9Ke+9Kei9'+'Ke+9Ke) , [S9Ke+9KeY'+'s9Ke+9Ke'+'t9K'+'e+9KeEM.IO.cOM9Ke+9KeP'+'REs9Ke+9KesIo9Ke+9Ken.C9Ke+6Nv+6Nv9KeO9Ke6Nv+6Nv+9Kempr6Nv+6NvESsIoNM9Ke+9Keode]::9Ke+9KedeCo9Ke+9KemPreS6Nv+6Nv9Ke+9KeS9Ke'+'+'+'9Ke) 5MO9Ke+9Ke 9Ke+9Ke%6Nv+6Nv9Ke+9Ke{neW-OBj9Ke+9KeeCT9Ke+9Ke 9Ke+9KeIo.9Ke+9KeST6Nv+6NvREam9Ke+9KeRe9Ke+9KeADer(k9Ke+9KeD9Ke+9Ke8_ 9Ke+9Ke, [teXT9Ke+9Ke.encODIng]::as9Ke+6Nv+6Nv9KecII)}).r9Ke+9KeEad9Ke+9KeToENd(9Ke+9Ke )9Ke+9Ke 9Ke).rEPLAcE(9KekD89Ke,9KerGe9Ke).rEPLAcE(('+'[cHAr]6Nv+6Nv53+['+'cHAr]77+[cHAr]79),96Nv+6N'+'vKebGA9Ke).rEPLAcE(([cHAr]117+[cHAr]104+[cHAr]105),[sTRiNg][cHAr]39) bGA .( rGepshomE['+'4]+rGepShoME[34]+9Ke'+'X9Ke)6Nv)-cREplAcE6NvrGe6Nv,[cHar'+']36 -cREplAcE 6Nv9Ke6Nv,[cHar]39  -rEP'+'LACE([cHar]98+[cHar]71+[cHar]65),[cHar]124)psd&( gFMpshoMe[4]+gFMpSHoME[30]+6Nvx6Nv)')  -RePlacE 'psd',[chAR]124 -CREpLACE'6Nv',[chAR]39 -RePlacE 'gFM',[chAR]36) ) 

launcher CMD

Encoding:
cmD.eXE   /c   POweRsHELl    " .( $PShoMe[21]+$PSHoMe[34]+'X') ( ((' ((6Nv(9Keiex( ne'+'W-OBj9Ke+9KeeC9Ke+9KeT9Ke+9K'+'e io.Co9Ke+9KemPre9Ke+9KeSS6Nv+6NvioN6Nv+6Nv9Ke+9Ke.9Ke+9KedefLatEStR9Ke+9KeeAm9Ke+9Ke( [iO.mE9Ke+9KeMoR9Ke+96'+'Nv+6NvKeYsTrEam][SyStEm.CONveRt]::9Ke+9Ke'+'froM9Ke+9KebAs9Ke+9KeE6Nv+6Nv649Ke+9KesT9Ke+9KeRInG(uhiNcux9Ke+9KeDo9Ke+9KeMwD9Ke+9KeA9Ke+9KeT9'+'Ke+9K'+'eQX49Ke+9Kem9K6Nv+6Nve+'+'9KeyBK9Ke+9KeQG0f9Ke+9KeI9K'+'e+9KefX9Ke+9KeSq9Ke'+'+9KexW9Ke+9KegY5wi9Ke6Nv+6Nv+9KeIlCB6Nv+6NvkWy/9e9Ke+9KeMn9Ke+9K'+'eS49Ke6Nv+6N'+'v+9Ke49Ke+9Kef9K6Nv+6Nve6Nv+6Nv+9KeTu9Ke+9KeusZ'+'r9Ke+9Keb/9Ke+9Keo0H'+'U9Ke+9Kexf9Ke+9Ke5m9Ke+9KeNy49Ke+9KeU9Ke+9KePhEeT9Ke+9KeO9Ke+9Kew9K'+'e+9KeTjlW6Nv+6Nv9Ke+9Keu6N'+'v+6Nv9Ke+9KeKIoXXxj9Ke+9KeV9y/4N39Ke+9Ked9Ke+9KebvzzVRxx9K'+'e+9KeH9Ke+9KexW9Ke+9KeTXzRLEkZZ9Ke+9KetwECAVwK9Ke+9Ke7LQ6Nv+6Nv9Ke+9KeAR9Ke+9KeMLQVkg6'+'Nv+6Nvl79Ke+9KeLCzm9Ke+9KeS9Ke+9Ke+/9Ke6Nv+6Nv+9KeQE=9Ke+9Keu6Nv'+'+6Nv9Ke+9Keh9Ke+9Kei9'+'Ke+9Ke) , [S9Ke+9KeY'+'s9Ke+9Ke'+'t9K'+'e+9KeEM.IO.cOM9Ke+9KeP'+'REs9Ke+9KesIo9Ke+9Ken.C9Ke+6Nv+6Nv9KeO9Ke6Nv+6Nv+9Kempr6Nv+6NvESsIoNM9Ke+9Keode]::9Ke+9KedeCo9Ke+9KemPreS6Nv+6Nv9Ke+9KeS9Ke'+'+'+'9Ke) 5MO9Ke+9Ke 9Ke+9Ke%6Nv+6Nv9Ke+9Ke{neW-OBj9Ke+9KeeCT9Ke+9Ke 9Ke+9KeIo.9Ke+9KeST6Nv+6NvREam9Ke+9KeRe9Ke+9KeADer(k9Ke+9KeD9Ke+9Ke8_ 9Ke+9Ke, [teXT9Ke+9Ke.encODIng]::as9Ke+6Nv+6Nv9KecII)}).r9Ke+9KeEad9Ke+9KeToENd(9Ke+9Ke )9Ke+9Ke 9Ke).rEPLAcE(9KekD89Ke,9KerGe9Ke).rEPLAcE(('+'[cHAr]6Nv+6Nv53+['+'cHAr]77+[cHAr]79),96Nv+6N'+'vKebGA9Ke).rEPLAcE(([cHAr]117+[cHAr]104+[cHAr]105),[sTRiNg][cHAr]39) bGA .( rGepshomE['+'4]+rGepShoME[34]+9Ke'+'X9Ke)6Nv)-cREplAcE6NvrGe6Nv,[cHar'+']36 -cREplAcE 6Nv9Ke6Nv,[cHar]39  -rEP'+'LACE([cHar]98+[cHar]71+[cHar]65),[cHar]124)psd&( gFMpshoMe[4]+gFMpSHoME[30]+6Nvx6Nv)')  -RePlacE 'psd',[chAR]124 -CREpLACE'6Nv',[chAR]39 -RePlacE 'gFM',[chAR]36) ) "


Endcoded Message:
$pie="fivectf{i_cant_eat_another_bite_oh_look_pie}"

Obfuscation Technique:
AST ALL x1
Token All x1
compress x1
string concatenate x3
launcher CMD

***********************************
19.
Flag: fivectf{i_came_in_like_a_butterball}

Decoded Message Step by Step:
AST ALL x1
Set-Variable -Name butterball -Value ("fivectf{i_came_in_like_a_butterball}")

Token All x1
Set-Variable -Name butterball -Value ("fivectf{i_came_in_like_a_butterball}")

encoding Hex x1
"$( SEt-ItEM 'vARiABlE:oFs' '') " +[StRinG]('26Q28r22o7bo30r7do7bN32o7dQ7bu31N7d>7b>33r7dQ22~20o2dN66u27u53N65@27o2c>27r69@27r2cQ27Q74Q2do56r61Q72o27u2c>27o61Q62>6c@65o27N29u20~2d~4er61u6d>65@20o28Q22>7bo30o7dr7b~31N7d@7bu32>7dN22r2dN66o20~27N62@75>74N74o65u27o2cQ27N72N62~27N2cr27r61r6c~6c@27N29Q20u2do56>61r6co75r65~20r28@22~66N69Q76Q65>63>74N66o7bu69~5f@63@61Q6du65@5fr69u6eu5f~6cQ69~6bN65r5fu61N5fo62Q75r74o74@65Q72~62~61Q6c@6c>7d@22Q29'.SPLiT('@>QuNro~' ) | % {( [CHAR] ( [ConVerT]::toint16( ([StrIng]$_) ,16 ) )) }) +" $( SeT-Item  'vaRIable:oFs'  ' ')" | iex

string concatenate x1
. ((VARIAbLE '*MdR*').NAmE[3,11,2]-joIn'')( ('B6'+'V'+'Ijt( '+'SE'+'t-ItEM S97'+'vARiA'+'BlE:oFsS97 '+'S97'+'S97)'+' B6V +['+'S'+'t'+'RinG](S9726Q28'+'r22o7bo3'+'0r'+'7do7bN32'+'o7d'+'Q'+'7'+'bu31'+'N7d'+'>7'+'b'+'>33r7'+'dQ2'+'2~20o2'+'d'+'N66u2'+'7'+'u53N'+'6'+'5@'+'27o2c>'+'27r69@2'+'7r2'+'cQ27Q74Q2do56'+'r'+'61Q'+'72o'+'27'+'u2c>27'+'o61Q'+'62>'+'6'+'c'+'@'+'6'+'5'+'o'+'27N29u'+'20'+'~2d~4er6'+'1u6d'+'>65@2'+'0'+'o'+'28Q22>'+'7bo30'+'o'+'7dr7b'+'~31N7d@7bu'+'3'+'2>7dN22'+'r2dN6'+'6'+'o20~2'+'7N62'+'@'+'7'+'5'+'>74'+'N74o'+'65u'+'27'+'o2'+'cQ27N72N62'+'~2'+'7N2'+'cr'+'27r61r6c~6'+'c'+'@2'+'7N29'+'Q20u'+'2do5'+'6'+'>61r'+'6'+'co'+'75r'+'6'+'5~20'+'r'+'2'+'8@'+'22'+'~66N69'+'Q'+'76'+'Q'+'65>63>'+'74'+'N'+'66'+'o'+'7bu69~'+'5f@63@6'+'1'+'Q6d'+'u6'+'5@5fr69u6'+'eu'+'5f~6cQ69'+'~6b'+'N'+'6'+'5r5fu'+'61N5fo62Q7'+'5'+'r74o7'+'4@65Q72'+'~62'+'~61'+'Q'+'6c@'+'6'+'c>7d@22Q'+'29'+'S97.SPL'+'i'+'T'+'('+'S'+'97@>'+'Qu'+'Nro'+'~S97'+' '+') 2D'+'k % {( '+'[CHAR] ('+' ['+'ConV'+'erT]:'+':'+'t'+'o'+'int16('+' ('+'['+'StrIng'+']I'+'jt_'+') ,16'+' ) '+'))'+' }) +'+'B6V '+'I'+'jt( S'+'e'+'T-'+'Ite'+'m '+' '+'S'+'9'+'7vaR'+'Ia'+'ble:oFs'+'S'+'97  S'+'9'+'7 S97)'+'B6V 2'+'D'+'k iex').RePlACe('B6V',[sTRINg][cHAr]34).RePlACe('Ijt','$').RePlACe(([cHAr]50+[cHAr]68+[cHAr]107),'|').RePlACe(([cHAr]83+[cHAr]57+[cHAr]55),[sTRINg][cHAr]39))

reverse x1
sV  ("G"+"B254x") (" ))63]RaHc[,)37]RaHc[+48]RaHc[+27]RaHc[( ecalper-  421]RaHc[,)011]RaHc[+67]RaHc[+84]RaHc[(ECALpERC-  93]RaHc[,'8nG'  ECALpERC-  )'))93]rAHc[]gNIRTs[,)55]rAHc[+75]rAHc'+'[+38]r'+'AHc[((eCAlPeR.)8nGnL08nG,)701]rAHc[+86]rAHc[+05]rAHc[((eCAlPeR.)8nGITH8nG,8nGtjI8nG(eCAlPeR.)43]rAHc[]gNIRTs[,8nGV6B8nG(eCAlPeR.)8nGxei k8nG+8nGD8nG+8nG2 V6B8nG+8nG)79S 78nG+8nG98nG+8nGS  798nG+8nGS8nG+8nGsFo:elb8nG+8nGaI8nG+8nGRav78nG+8nG98nG+8nGS8nG+8nG 8nG+8nG m8nG+8nGetI8nG+8nG-T8nG+8nGe8nG+8nGS (tj8nG+8nGI8nG+8nG V6B8nG+8nG+ )} 8'+'nG+'+'8nG))8nG+8nG ) 8nG+8nG61, )8nG+8nG_tj8nG+8nGI]8nG+8nGgnIrtS8nG+8nG[8nG+8nG( 8nG+8nG(61tni8nG+8nGo8nG+8nGt8nG+8nG:8nG+8nG'+':]Tre8nG+8nGVnoC8nG+8nG[ 8nG+8nG( ]RAHC[8nG+8nG ({ % k8n'+'G'+'+8nGD2 )8'+'nG+8nG 8nG+8n'+'G79S~8nG+8nGorN8nG+8nGuQ8nG+8nG>@798nG+8n'+'GS8nG+8nG(8nG+8nG'+'T8nG+8nGi8'+'nG+8nGLPS.79S8nG+8nG928nG+8nGQ22@d7>c8nG+8nG68nG+8nG@c68nG+8nGQ8nG+8nG16~8nG+8nG26~8nG+8nG27Q56@48nG+8nG7o47r8nG+8nG'+'58nG+8nG7Q26of5N168nG+8nGuf5r58nG+8nG68nG+8nGN8nG+8nGb6~8nG+8nG96Qc6~f58nG+'+'8nGue8nG+8nG6u96rf5@58nG+8nG6u8nG+8nGd6Q8nG+8nG18nG+8nG6@36@f58nG'+'+8nG~96ub78nG+8nGo8nG'+'+8nG668nG+8nGN8nG+8nG478nG+8nG>36>568nG+8nGQ8nG+8nG678nG+8nGQ8nG+8'+'nG96N6'+'6~8nG+8nG228nG+8nG@88n'+'G+8nG28nG+8nGr8nG+8nG02~58nG+8nG68'+'nG+8nGr578nG+8'+'nGoc8nG+8nG68nG+8nGr16>8nG+8nG68nG+8nG5od28nG+8nGu02Q8nG+8nG92N78nG+8nG2@8nG+8nGc8nG'+'+8nG6~c6r'+'16r728nG+8nGrc8nG+8nG2N78nG+8nG2~8nG+8nG'+'26N27N7'+'2Qc8nG+8nG2o8nG+8nG728nG+8nGu568nG+8nGo47N8nG+8nG47>8nG+8nG58nG+8nG78nG+8nG@8nG+8nG26N78nG+8nG2~02o8nG+8nG68nG+8nG6Nd2r8nG+8nG22Nd7>28nG+8nG38nG+8nGub7@d7N13~8nG+8nGb7rd78nG+8nGo8nG+8nG03ob78nG+8nG>22Q828nG+8nGo8nG+8nG08nG+8nG2@5'+'6>8nG+8nGd6u18nG+8nG6re4~d2~8n'+'G+8nG'+'028nG+8nGu92N728nG+8nGo8nG+8nG58nG+8nG68'+'nG+8'+'nG@8nG+8nGc8nG+8nG68'+'nG+8nG>268nG+8nGQ16o8nG+8nG72>c2u8nG+8nG728nG+8nGo278nG+8nGQ168nG+8nGr8'+'nG+8n'+'G65od2Q47Q72Qc8nG+8nG2r78nG+8nG2@96r728nG+8nG>c2o728nG+8nG@58nG+8nG68nG+8nGN35u8nG+8nG78nG+8nG2u66N8nG+8nGd8nG+8nG2o02~28nG+8nG2Qd8nG'+'+8nG7r33>8nG+8nGb8nG+8nG7>8nG+8nGd7N8nG+8nG13ub8nG+8nG78n'+'G+8nGQ8nG+8nGd7o8n'+'G+8nG23Nb7od78nG+'+'8nGr08nG+8nG3ob7o22r8nG+8nG82Q6279'+'S(]GniR8nG+8nGt8nG+8nGS8nG+8nG[+ V6B 8nG+8nG)'+'79S8nG+8nG79S8nG+8nG 79SsFo:ElB8nG+8nGAiRAv8nG+8nG79S MEtI-t8n'+'G+8nGES8nG+8nG (tjI8nG+8nGV8nG+8nG6B8nG( ()8nG8nGnIoj-]2,11,3[EmAN.)8nG*RdM*8nG E'+'LbAIRAV(( .'(( ()''nIOj-]52,62,4[cePsMOC:VnE$ ( ."  ) ; $Gb254x[ -1..-( $Gb254x.LEngth )] -JOin ''| INVokE-ExPreSsIon

launcher CMD

Encoding:
cmD.exe/c   powErSheLl   "sV  (\"G\"+\"B254x\") (\" ))63]RaHc[,)37]RaHc[+48]RaHc[+27]RaHc[( ecalper-  421]RaHc[,)011]RaHc[+67]RaHc[+84]RaHc[(ECALpERC-  93]RaHc[,'8nG'  ECALpERC-  )'))93]rAHc[]gNIRTs[,)55]rAHc[+75]rAHc'+'[+38]r'+'AHc[((eCAlPeR.)8nGnL08nG,)701]rAHc[+86]rAHc[+05]rAHc[((eCAlPeR.)8nGITH8nG,8nGtjI8nG(eCAlPeR.)43]rAHc[]gNIRTs[,8nGV6B8nG(eCAlPeR.)8nGxei k8nG+8nGD8nG+8nG2 V6B8nG+8nG)79S 78nG+8nG98nG+8nGS  798nG+8nGS8nG+8nGsFo:elb8nG+8nGaI8nG+8nGRav78nG+8nG98nG+8nGS8nG+8nG 8nG+8nG m8nG+8nGetI8nG+8nG-T8nG+8nGe8nG+8nGS (tj8nG+8nGI8nG+8nG V6B8nG+8nG+ )} 8'+'nG+'+'8nG))8nG+8nG ) 8nG+8nG61, )8nG+8nG_tj8nG+8nGI]8nG+8nGgnIrtS8nG+8nG[8nG+8nG( 8nG+8nG(61tni8nG+8nGo8nG+8nGt8nG+8nG:8nG+8nG'+':]Tre8nG+8nGVnoC8nG+8nG[ 8nG+8nG( ]RAHC[8nG+8nG ({ % k8n'+'G'+'+8nGD2 )8'+'nG+8nG 8nG+8n'+'G79S~8nG+8nGorN8nG+8nGuQ8nG+8nG^^^>@798nG+8n'+'GS8nG+8nG(8nG+8nG'+'T8nG+8nGi8'+'nG+8nGLPS.79S8nG+8nG928nG+8nGQ22@d7^^^>c8nG+8nG68nG+8nG@c68nG+8nGQ8nG+8nG16~8nG+8nG26~8nG+8nG27Q56@48nG+8nG7o47r8nG+8nG'+'58nG+8nG7Q26of5N168nG+8nGuf5r58nG+8nG68nG+8nGN8nG+8nGb6~8nG+8nG96Qc6~f58nG+'+'8nGue8nG+8nG6u96rf5@58nG+8nG6u8nG+8nGd6Q8nG+8nG18nG+8nG6@36@f58nG'+'+8nG~96ub78nG+8nGo8nG'+'+8nG668nG+8nGN8nG+8nG478nG+8nG^^^>36^^^>568nG+8nGQ8nG+8nG678nG+8nGQ8nG+8'+'nG96N6'+'6~8nG+8nG228nG+8nG@88n'+'G+8nG28nG+8nGr8nG+8nG02~58nG+8nG68'+'nG+8nGr578nG+8'+'nGoc8nG+8nG68nG+8nGr16^^^>8nG+8nG68nG+8nG5od28nG+8nGu02Q8nG+8nG92N78nG+8nG2@8nG+8nGc8nG'+'+8nG6~c6r'+'16r728nG+8nGrc8nG+8nG2N78nG+8nG2~8nG+8nG'+'26N27N7'+'2Qc8nG+8nG2o8nG+8nG728nG+8nGu568nG+8nGo47N8nG+8nG47^^^>8nG+8nG58nG+8nG78nG+8nG@8nG+8nG26N78nG+8nG2~02o8nG+8nG68nG+8nG6Nd2r8nG+8nG22Nd7^^^>28nG+8nG38nG+8nGub7@d7N13~8nG+8nGb7rd78nG+8nGo8nG+8nG03ob78nG+8nG^^^>22Q828nG+8nGo8nG+8nG08nG+8nG2@5'+'6^^^>8nG+8nGd6u18nG+8nG6re4~d2~8n'+'G+8nG'+'028nG+8nGu92N728nG+8nGo8nG+8nG58nG+8nG68'+'nG+8'+'nG@8nG+8nGc8nG+8nG68'+'nG+8nG^^^>268nG+8nGQ16o8nG+8nG72^^^>c2u8nG+8nG728nG+8nGo278nG+8nGQ168nG+8nGr8'+'nG+8n'+'G65od2Q47Q72Qc8nG+8nG2r78nG+8nG2@96r728nG+8nG^^^>c2o728nG+8nG@58nG+8nG68nG+8nGN35u8nG+8nG78nG+8nG2u66N8nG+8nGd8nG+8nG2o02~28nG+8nG2Qd8nG'+'+8nG7r33^^^>8nG+8nGb8nG+8nG7^^^>8nG+8nGd7N8nG+8nG13ub8nG+8nG78n'+'G+8nGQ8nG+8nGd7o8n'+'G+8nG23Nb7od78nG+'+'8nGr08nG+8nG3ob7o22r8nG+8nG82Q6279'+'S(]GniR8nG+8nGt8nG+8nGS8nG+8nG[+ V6B 8nG+8nG)'+'79S8nG+8nG79S8nG+8nG 79SsFo:ElB8nG+8nGAiRAv8nG+8nG79S MEtI-t8n'+'G+8nGES8nG+8nG (tjI8nG+8nGV8nG+8nG6B8nG( ()8nG8nGnIoj-]2,11,3[EmAN.)8nG*RdM*8nG E'+'LbAIRAV(( .'(( ()''nIOj-]52,62,4[cePsMOC:VnE$ ( .\"  ) ; $Gb254x[ -1..-( $Gb254x.LEngth )] -JOin ''| INVokE-ExPreSsIon"

Endcoded Message:
$butterball="fivectf{i_came_in_like_a_butterball}"

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
Set-Variable -Name baste -Value ("fivectf{im_all_abut_that_baste}")

Token All x1
.("{0}{2}{1}"-f'Set-V','ble','aria') -Name ("{1}{0}"-f 'aste','b') -Value ("fivectf{im_all_abut_that_baste}")

encoding BXOR x1
 " $( SEt-ITEm  'VArIaBle:OfS' '' ) "+ [sTRInG]([chAR[]](115, 117, 127,38, 109, 32 ,38 , 111 ,32 , 38 , 108,32, 127,112 , 59,122,14,56, 41 ,112 , 11,122 ,113,122 ,63 ,49, 56 , 122,113,122, 60 ,47,52, 60,122 , 116, 125 ,112 ,19,60 , 48, 56, 125,117,127 ,38,108, 32 , 38 , 109, 32 , 127 , 112 ,59,125, 122 ,60,46 ,41 , 56,122 , 113 , 122,63,122,116,125,112 ,11, 60 , 49, 40 , 56 ,125 ,117,127, 59 ,52 , 43 ,56, 62, 41,59,38, 52, 48, 2,60,49, 49,2 , 60,63 ,40, 41 ,2, 41 ,53 ,60, 41,2 , 63 ,60,46 ,41,56 , 32,127 ,116 ) | fOreach-OBJEcT{ [chAR]($_ -bxoR'0x5d') })+" $( sEt-iTEM  'VarIAbLe:ofs'  ' ' )" | IeX

encoding BXOR x2
 & ( $SHeLLID[1]+$SheLlId[13]+'X')( -jOIN('111x109o111m107x103{111o28-10h59q98{6h27c10-34h111c111o104-25x14G61o6o46h13Z35q42-117q0q41q28q104o111q104o104Z111c102h111o109-100m111Z20h60G27h29x6-33{8x18o103{20h44h39x14Z29o20h18q18Z103x126{126x122Z99c111Z126G126{120Z99o111c126o125o120x99Z124h119m99o111Z126q127{118h99{111m124o125m111G99-124o119q111c99-111h126-126G126c111G99c124-125Z111{99x111Z124-119c111Z99q111h126q127o119-99h124{125{99G111m126o125o120h99x126q126x125c111Z99{111o122{118c99G126o125m125q99x126o123{99x122o121-99c111c123q126{111-99x126-126c125h111{99q111G126q126Z99m126h125m125q111x99{126m126Z124c99c126-125c125Z111Z99q121m124-111h99q123c118q99m111m122Z121h111c99{111G126h125G125o99m126q126-124m99{126m125h125h99x111o121o127c111o99x123h120c99o122m125Z99x111Z121o127q99q126Z125Z125c111c99q111o126c126x121{99q111-126x125q122c111Z99c126h126h125m111x99q126{118h99c121x127x111m99{111Z123Z119Z99c111q122{121q99{111Z126G125x122-99m126h126Z120q99Z126-125Z120c111x99{124c119o99G126o127x119q99-111x124h125q111-99Z111c124m119G111{99G111-126Z127-118Z99Z111-124c125-111x99o111x126o125x120o111o99m111-126q126{125h111c99h122{118o99x126c125q122q99o111{126x125{125q111Z99G121h127-99c123c121o111-99o123o126q111Z99x111m122q121h99Z126x125o125c111c99m111x126G126-124m111{99o111o126c125o125o99q121m124o99-126c125h125o99x126q126m121-99Z126h125m122m99o126-126o125h111G99{126G126h99c111G121o127c111x99Z111G123o118m99x111o123Z127G111x99o111-122h121x111c99{126m125q122{111G99o126h126c120x99G126q125q120-99c111h122q118-111q99Z122m125G111Z99c111-123o124m111m99h122m121x99c111h121Z125{99Z111m123G126{99-122G118x99c124m119c99{111Z122q125m99Z111c123h119q99h111-125m99{121c127q99q123{118x99Z111h123-118h99Z125G111x99-111-121G127h99{121Z124{111m99Z123-127x99m111c123G126x111h99G125o99q111{123{126G111{99G122x124c111Z99o121q127q99m111{123q126Z99c125-111-99m111o121Z124c111h99x121-127q99h123h121o111m99q123h126o99q122Z121o111x99o111c124h125Z99Z126{125q120c111x99m126h126x121q111q102{111-51x111{41o0m61m42c46m44Z39h98c0G13G5Z10o44G27x52c111-20q44Z39q14o29x18h103G107x16{111o98c45h55G32x29m104m127q55q122c43G104{102Z111h50G102x100h109q111x107q103c111h60o10Z59h98q38o27{10q2c111o111G104h25Z46x61q6G14G45G3q42x117x32q41c60m104x111c111Z104h111m104c111Z102q109c111o51c111{6o42m23' -SPliT 'g'-SPlIT'C' -sPlIT'x'-spLIT'm'-spLiT'{' -SpLIt 'Z' -SplIt'H'-SpLIt'Q'-spLit'-'-SpLIT 'O'| % { [cHAR]($_ -BXoR'0x4F')} ) ) 

launcher CMD


Encoding:
CmD.exE   /C POWeRSHELl   "& ( $SHeLLID[1]+$SheLlId[13]+'X')( -jOIN('111x109o111m107x103{111o28-10h59q98{6h27c10-34h111c111o104-25x14G61o6o46h13Z35q42-117q0q41q28q104o111q104o104Z111c102h111o109-100m111Z20h60G27h29x6-33{8x18o103{20h44h39x14Z29o20h18q18Z103x126{126x122Z99c111Z126G126{120Z99o111c126o125o120x99Z124h119m99o111Z126q127{118h99{111m124o125m111G99-124o119q111c99-111h126-126G126c111G99c124-125Z111{99x111Z124-119c111Z99q111h126q127o119-99h124{125{99G111m126o125o120h99x126q126x125c111Z99{111o122{118c99G126o125m125q99x126o123{99x122o121-99c111c123q126{111-99x126-126c125h111{99q111G126q126Z99m126h125m125q111x99{126m126Z124c99c126-125c125Z111Z99q121m124-111h99q123c118q99m111m122Z121h111c99{111G126h125G125o99m126q126-124m99{126m125h125h99x111o121o127c111o99x123h120c99o122m125Z99x111Z121o127q99q126Z125Z125c111c99q111o126c126x121{99q111-126x125q122c111Z99c126h126h125m111x99q126{118h99c121x127x111m99{111Z123Z119Z99c111q122{121q99{111Z126G125x122-99m126h126Z120q99Z126-125Z120c111x99{124c119o99G126o127x119q99-111x124h125q111-99Z111c124m119G111{99G111-126Z127-118Z99Z111-124c125-111x99o111x126o125x120o111o99m111-126q126{125h111c99h122{118o99x126c125q122q99o111{126x125{125q111Z99G121h127-99c123c121o111-99o123o126q111Z99x111m122q121h99Z126x125o125c111c99m111x126G126-124m111{99o111o126c125o125o99q121m124o99-126c125h125o99x126q126m121-99Z126h125m122m99o126-126o125h111G99{126G126h99c111G121o127c111x99Z111G123o118m99x111o123Z127G111x99o111-122h121x111c99{126m125q122{111G99o126h126c120x99G126q125q120-99c111h122q118-111q99Z122m125G111Z99c111-123o124m111m99h122m121x99c111h121Z125{99Z111m123G126{99-122G118x99c124m119c99{111Z122q125m99Z111c123h119q99h111-125m99{121c127q99q123{118x99Z111h123-118h99Z125G111x99-111-121G127h99{121Z124{111m99Z123-127x99m111c123G126x111h99G125o99q111{123{126G111{99G122x124c111Z99o121q127q99m111{123q126Z99c125-111-99m111o121Z124c111h99x121-127q99h123h121o111m99q123h126o99q122Z121o111x99o111c124h125Z99Z126{125q120c111x99m126h126x121q111q102{111-51x111{41o0m61m42c46m44Z39h98c0G13G5Z10o44G27x52c111-20q44Z39q14o29x18h103G107x16{111o98c45h55G32x29m104m127q55q122c43G104{102Z111h50G102x100h109q111x107q103c111h60o10Z59h98q38o27{10q2c111o111G104h25Z46x61q6G14G45G3q42x117x32q41c60m104x111c111Z104h111m104c111Z102q109c111o51c111{6o42m23' -SPliT 'g'-SPlIT'C' -sPlIT'x'-spLIT'm'-spLiT'{' -SpLIt 'Z' -SplIt'H'-SpLIt'Q'-spLit'-'-SpLIT 'O'| % { [cHAR]($_ -BXoR'0x4F')} ) )"

Endcoded Message:
$baste="fivectf{im_all_abut_that_baste}"

Obfuscation Technique:
AST ALL x1
Token All x1
encoding BXOR x2
launcher CMD

***********************************