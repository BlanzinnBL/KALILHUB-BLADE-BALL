local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v24,v25) local FlatIdent_76979=0;local v26;while true do if (FlatIdent_76979==1) then return v5(v26);end if (FlatIdent_76979==0) then v26={};for v41=1, #v24 do v6(v26,v0(v4(v1(v2(v24,v41,v41 + 1 )),v1(v2(v25,1 + (v41% #v25) ,1 + (v41% #v25) + 1 )))%256 ));end FlatIdent_76979=1;end end end local v8=tonumber;local v9=string.byte;local v10=string.char;local v11=string.sub;local v12=string.gsub;local v13=string.rep;local v14=table.concat;local v15=table.insert;local v16=math.ldexp;local v17=getfenv or function() return _ENV;end ;local v18=setmetatable;local v19=pcall;local v20=select;local v21=unpack or table.unpack ;local v22=tonumber;local function v23(v27,v28,...) local v29=1 + 0 ;local v30;v27=v12(v11(v27,5),v7("\159\141","\126\177\163\187\69\134\219\167"),function(v42) if (v9(v42,2 + 0 )==(146 -65)) then local FlatIdent_67C40=0;local v97;local v98;while true do if (1==FlatIdent_67C40) then while true do if (v97==(238 -(64 + 174))) then v98=0;while true do if (v98==(0 + 0)) then local FlatIdent_8D83D=0;local v120;while true do if (FlatIdent_8D83D==0) then v120=0 -0 ;while true do if (v120==(336 -(144 + 192))) then local FlatIdent_1743D=0;local v133;while true do if (FlatIdent_1743D==0) then v133=216 -(42 + 174) ;while true do if (v133==(0 + 0)) then local FlatIdent_7366E=0;while true do if (0==FlatIdent_7366E) then v30=v8(v11(v42,1 + 0 ,1 + 0 ));return "";end end end end break;end end end end break;end end end end break;end end break;end if (FlatIdent_67C40==0) then v97=0 -0 ;v98=nil;FlatIdent_67C40=1;end end else local FlatIdent_43862=0;local v99;local v100;while true do if (0==FlatIdent_43862) then v99=1504 -(363 + 1141) ;v100=nil;FlatIdent_43862=1;end if (FlatIdent_43862==1) then while true do if (v99==(1580 -(1183 + 397))) then v100=v10(v8(v42,48 -32 ));if v30 then local FlatIdent_31905=0;local v114;local v115;while true do if (FlatIdent_31905==1) then while true do local FlatIdent_61B23=0;local v121;while true do if (FlatIdent_61B23==0) then v121=0;while true do if ((0 + 0)==v121) then if (v114==(1 + 0)) then return v115;end if (v114==(1975 -(1913 + 62))) then local FlatIdent_7FAC9=0;while true do if (FlatIdent_7FAC9==1) then v114=1 + 0 ;break;end if (0==FlatIdent_7FAC9) then v115=v13(v100,v30);v30=nil;FlatIdent_7FAC9=1;end end end break;end end break;end end end break;end if (0==FlatIdent_31905) then v114=0;v115=nil;FlatIdent_31905=1;end end else return v100;end break;end end break;end end end end);local function v31(v43,v44,v45) if v45 then local FlatIdent_77C29=0;local v101;local v102;while true do if (FlatIdent_77C29==0) then v101=0 -0 ;v102=nil;FlatIdent_77C29=1;end if (FlatIdent_77C29==1) then while true do if (v101==(1933 -(565 + 1368))) then local FlatIdent_2AC68=0;while true do if (FlatIdent_2AC68==0) then v102=(v43/(((18 -13) -(1664 -(1477 + 184)))^(v44-(2 -(1 -0)))))%(((880 -(282 + 595)) -(1 + 0))^(((v45-((858 -(564 + 292)) -(1 -0))) -(v44-((1868 -1248) -((859 -(244 + 60)) + 50 + 14)))) + ((1408 -(41 + 435)) -(((3495 -(938 + 63)) -(1172 + 351 + 114)) + (1199 -(936 + 189)))))) ;return v102-(v102%((188 + 381) -((1980 -(1565 + 48)) + 201))) ;end end end end break;end end else local FlatIdent_1B51D=0;local v103;local v104;while true do if (FlatIdent_1B51D==1) then while true do if (v103==(0 + 0)) then local FlatIdent_25DF3=0;while true do if (FlatIdent_25DF3==0) then v104=(1140 -(782 + 356))^(v44-((1195 -(176 + 91)) -(214 + 641 + 72))) ;return (((v43%(v104 + v104))>=v104) and (1 + (0 -0))) or ((0 -0) + (1092 -(975 + 117))) ;end end end end break;end if (FlatIdent_1B51D==0) then v103=0;v104=nil;FlatIdent_1B51D=1;end end end end local function v32() local FlatIdent_5BA5E=0;local v46;local v47;while true do if (FlatIdent_5BA5E==1) then while true do local FlatIdent_295EB=0;local v81;while true do if (FlatIdent_295EB==0) then v81=0 + 0 ;while true do if (v81==(0 -0)) then if (v46==0) then local FlatIdent_981A3=0;while true do if (FlatIdent_981A3==1) then v46=1019 -(697 + 321) ;break;end if (FlatIdent_981A3==0) then v47=v9(v27,v29,v29);v29=v29 + (3 -2) ;FlatIdent_981A3=1;end end end if (v46==(2 -1)) then return v47;end break;end end break;end end end break;end if (FlatIdent_5BA5E==0) then v46=1875 -(157 + 1718) ;v47=nil;FlatIdent_5BA5E=1;end end end local function v33() local FlatIdent_52551=0;local v48;local v49;while true do if (FlatIdent_52551==0) then v48,v49=v9(v27,v29,v29 + (3 -1) );v29=v29 + ((4 -2) -0) ;FlatIdent_52551=1;end if (FlatIdent_52551==1) then return (v49 * ((515 + 806) -((127 -59) + (2672 -1675)))) + v48 ;end end end local function v34() local FlatIdent_2D88C=0;local v50;local v51;local v52;local v53;local v54;local v55;while true do if (1==FlatIdent_2D88C) then v52=nil;v53=nil;FlatIdent_2D88C=2;end if (FlatIdent_2D88C==3) then while true do if (v50==(613 -(602 + 9))) then v55=nil;while true do local v105=1189 -(449 + 740) ;local v106;while true do if (v105==(872 -(826 + 46))) then v106=947 -(245 + 702) ;while true do if (v106==(0 -0)) then if (v51==(0 + 0)) then local FlatIdent_68E92=0;while true do if (FlatIdent_68E92==1) then v51=1206 -(902 + 303) ;break;end if (FlatIdent_68E92==0) then v52,v53,v54,v55=v9(v27,v29,v29 + (((4128 -(260 + 1638)) -((1332 -(382 + 58)) + (208 -143))) -(226 + (2490 -(1202 + 244)))) );v29=v29 + ((35 -18) -(38 -25)) ;FlatIdent_68E92=1;end end end if ((1 -0)==v51) then return (v55 * (16777333 -((76 -44) + 85))) + (v54 * (64226 + 1310)) + (v53 * (57 + 18 + 181)) + v52 ;end break;end end break;end end end break;end if (v50==(1691 -(1121 + 569))) then local FlatIdent_2F37F=0;while true do if (FlatIdent_2F37F==1) then v50=216 -(22 + 192) ;break;end if (FlatIdent_2F37F==0) then v53=nil;v54=nil;FlatIdent_2F37F=1;end end end if (v50==(683 -(483 + 200))) then local FlatIdent_5F1CB=0;while true do if (FlatIdent_5F1CB==0) then v51=1463 -(1404 + 59) ;v52=nil;FlatIdent_5F1CB=1;end if (FlatIdent_5F1CB==1) then v50=2 -1 ;break;end end end end break;end if (FlatIdent_2D88C==0) then v50=1227 -(322 + 905) ;v51=nil;FlatIdent_2D88C=1;end if (2==FlatIdent_2D88C) then v54=nil;v55=nil;FlatIdent_2D88C=3;end end end local function v35() local FlatIdent_4D434=0;local v56;local v57;local v58;local v59;local v60;local v61;while true do if (FlatIdent_4D434==2) then v60=v31(v57,(51 + 0) -30 ,23 + (20 -12) );v61=((v31(v57,(305 -178) -(23 + 72) )==((2610 -1657) -((1244 -(293 + 123 + 14 + 12)) + (478 -(461 -133))))) and  -((2 + 0) -(164 -(92 + 71)))) or (1 -0) ;FlatIdent_4D434=3;end if (FlatIdent_4D434==3) then if (v60==(0 + 0 + (0 -0))) then if (v59==((1762 -(574 + 191)) -(915 + 82))) then return v61 * ((0 + 0) -0) ;else local FlatIdent_494F6=0;local v107;while true do if (FlatIdent_494F6==0) then v107=0;while true do if (v107==(0 + 0)) then v60=(2 -1) -0 ;v58=1187 -(1069 + 27 + 24 + (916 -(254 + 595))) ;break;end end break;end end end elseif (v60==(4643 -(2722 -(55 + 71)))) then return ((v59==(((1041 -250) -((2158 -(573 + 1217)) + 423)) -((0 -0) -(0 + 0)))) and (v61 * ((1 + (0 -0))/((939 -(714 + 225)) -(0 -0))))) or (v61 * NaN) ;end return v16(v61,v60-1023 ) * (v58 + (v59/((3 -(1 -0))^(6 + 46 + (0 -0))))) ;end if (FlatIdent_4D434==0) then v56=v34();v57=v34();FlatIdent_4D434=1;end if (FlatIdent_4D434==1) then v58=1 -(0 -0) ;v59=(v31(v57,(766 -(468 + 297)) -(562 -(334 + 228)) ,(1248 -878) -((201 -114) + 263) ) * (((329 -147) -(((25 + 60) -(10 + 8)) + ((670 -(141 + 95)) -321)))^(24 + 8))) + v56 ;FlatIdent_4D434=2;end end end local function v36(v62) local v63=806 -(118 + 688) ;local v64;local v65;while true do local FlatIdent_581C8=0;while true do if (FlatIdent_581C8==1) then if (v63==(1 -0)) then local FlatIdent_8ABD6=0;while true do if (FlatIdent_8ABD6==0) then v64=v11(v27,v29,(v29 + v62) -(431 -((141 -(11 + 86)) + (941 -555))) );v29=v29 + v62 ;FlatIdent_8ABD6=1;end if (FlatIdent_8ABD6==1) then v63=287 -(175 + 110) ;break;end end end if (v63==(6 -3)) then return v14(v65);end break;end if (FlatIdent_581C8==0) then if (v63==(48 -(25 + 23))) then local FlatIdent_32B97=0;while true do if (FlatIdent_32B97==0) then v64=nil;if  not v62 then local FlatIdent_580CB=0;while true do if (FlatIdent_580CB==0) then v62=v34();if (v62==(438 -(145 + 57 + 236))) then return "";end break;end end end FlatIdent_32B97=1;end if (FlatIdent_32B97==1) then v63=1887 -(927 + 959) ;break;end end end if (v63==2) then local FlatIdent_20FE3=0;while true do if (FlatIdent_20FE3==1) then v63=735 -(16 + 716) ;break;end if (FlatIdent_20FE3==0) then v65={};for v108=3 -2 , #v64 do v65[v108]=v10(v9(v11(v64,v108,v108)));end FlatIdent_20FE3=1;end end end FlatIdent_581C8=1;end end end end local v37=v34;local function v38(...) return {...},v20("#",...);end local function v39() local v66=0;local v67;local v68;local v69;local v70;local v71;local v72;local v73;local v74;while true do if (v66==(1797 -(503 + 1293))) then local FlatIdent_6AEED=0;while true do if (FlatIdent_6AEED==0) then v69=(function() return;end)();v70=(function() return;end)();FlatIdent_6AEED=1;end if (FlatIdent_6AEED==1) then v66=5 -3 ;break;end end end if ((0 + 0)==v66) then local FlatIdent_44265=0;while true do if (FlatIdent_44265==1) then v66=1 + 0 ;break;end if (0==FlatIdent_44265) then v67=(function() return (1351 -(810 + 251)) -(60 + 160 + 70) ;end)();v68=(function() return;end)();FlatIdent_44265=1;end end end if (v66==(3 + 0)) then v73=(function() return;end)();v74=(function() return;end)();v66=4;end if (v66==4) then while true do local v110=(function() return (2317 -(43 + 490)) -((1332 -(711 + 22)) + 1185) ;end)();while true do if (v110==((0 -0) + 0)) then if (1==v67) then local v124=(function() return (859 -(240 + 619)) + 0 + 0 ;end)();while true do if (v124==(0 -0)) then local FlatIdent_7F3C8=0;while true do if (FlatIdent_7F3C8==0) then v72=(function() return {v69,v70,nil,v71};end)();v73=(function() return v34();end)();FlatIdent_7F3C8=1;end if (1==FlatIdent_7F3C8) then v124=(function() return (406 -(255 + 150)) + 0 ;end)();break;end end end if (v124==((1149 + 309) -(282 + 629 + 545))) then v67=(function() return (3473 -2660) -((1837 -1268) + 242) ;end)();break;end if (v124==((3489 -(404 + 1335)) -((1419 -(183 + 223)) + (895 -159)))) then v74=(function() return {};end)();for v134= #"[",v73 do local v135=(function() return 0 -(0 + 0) ;end)();local v136=(function() return;end)();local v137=(function() return;end)();local v138=(function() return;end)();while true do if (v135==(0 + 0 + 0)) then local FlatIdent_5D802=0;while true do if (FlatIdent_5D802==1) then v135=(function() return 1 + 0 ;end)();break;end if (FlatIdent_5D802==0) then v136=(function() return 337 -(10 + 327) ;end)();v137=(function() return nil;end)();FlatIdent_5D802=1;end end end if (v135==((339 -(118 + 220)) + 0)) then v138=(function() return nil;end)();while true do if (v136==(0 + 0)) then local FlatIdent_92F66=0;local v150;while true do if (FlatIdent_92F66==0) then v150=(function() return (449 -(108 + 341)) -0 ;end)();while true do if (v150~=((2 + 1) -2)) then else v136=(function() return (5377 -4105) -((2438 -(711 + 782)) + (624 -298)) ;end)();break;end if (v150~=((1336 -(270 + 199)) -(179 + 371 + (2136 -(580 + 1239))))) then else local FlatIdent_44100=0;while true do if (FlatIdent_44100==1) then v150=(function() return (2 -1) -(0 + 0) ;end)();break;end if (FlatIdent_44100==0) then v137=(function() return v32();end)();v138=(function() return nil;end)();FlatIdent_44100=1;end end end end break;end end end if ((1 -(0 + 0))~=v136) then else if (v137== #",") then v138=(function() return v32()~=((0 + 0) -0) ;end)();elseif (v137==(702 -(271 + (1119 -690)))) then v138=(function() return v35();end)();elseif (v137== #v7("\36\197\43","\156\67\173\74\165")) then v138=(function() return v36();end)();end v74[v134]=(function() return v138;end)();break;end end break;end end end v124=(function() return 2 + 0 ;end)();end end end if (v67~=(287 -(134 + 151))) then else v72[ #v7("\51\191\72","\38\84\215\41\118\220\70")]=(function() return v32();end)();for v128= #" ",v34() do local v129=1167 -(645 + 522) ;local v130;local v131;while true do if (v129==(1791 -(1010 + 780))) then while true do if (v130==(0 + 0)) then v131=(function() return v32();end)();if (v31(v131, #"!", #"!")~=(0 -0)) then else local FlatIdent_512FF=0;local v146;local v147;local v148;local v149;while true do if (FlatIdent_512FF==2) then while true do if (v146==(1839 -(1045 + 791))) then if (v31(v148, #v7("\9\71\106","\158\48\118\66\114"), #v7("\172\44\17","\155\203\68\112\86\19\197"))~= #"[") then else v149[ #v7("\71\206\50\173","\152\38\189\86\156\32\24\133")]=(function() return v74[v149[ #v7("\163\94\163\27","\38\156\55\199")]];end)();end v69[v128]=(function() return v149;end)();break;end if (v146==((7 -4) -(1 -0))) then local FlatIdent_10DED=0;local v176;while true do if (FlatIdent_10DED==0) then v176=505 -(351 + 154) ;while true do if ((1575 -(1281 + 293))==v176) then v146=(function() return (1557 -(28 + 238)) -(993 + (658 -363)) ;end)();break;end if (v176==(1559 -(1381 + 178))) then local FlatIdent_835BC=0;while true do if (FlatIdent_835BC==1) then v176=1 + 0 ;break;end if (0==FlatIdent_835BC) then if (v31(v148, #"\\", #"~")~= #"{") then else v149[2 + 0 ]=(function() return v74[v149[(1607 + 385) -(249 + 333 + (4853 -3445)) ]];end)();end if (v31(v148,(564 + 524) -(461 + 625) ,472 -(381 + 89) )~= #"~") then else v149[ #v7("\176\101\100","\35\200\29\28\72\115\20\154")]=(function() return v74[v149[ #v7("\84\238\136","\84\121\223\177\191\237\76")]];end)();end FlatIdent_835BC=1;end end end end break;end end end if (((3 + 0) -(2 -0))==v146) then local v177=0;local v178;local v179;while true do if (v177==(1156 -(1074 + 82))) then local FlatIdent_8EA6E=0;local v382;while true do if (FlatIdent_8EA6E==0) then v382=0;while true do if (v382==1) then v177=1 -0 ;break;end if (v382==(1784 -(214 + 1570))) then local FlatIdent_86E18=0;while true do if (FlatIdent_86E18==1) then v382=1 + 0 ;break;end if (FlatIdent_86E18==0) then v178=(function() return 1455 -(990 + 465) ;end)();v179=(function() return;end)();FlatIdent_86E18=1;end end end end break;end end end if (v177==1) then while true do if (v178~=((0 + 0) -(0 + 0))) then else v179=(function() return (0 -0) + 0 ;end)();while true do if (v179==((1726 -(1668 + 58)) -0)) then v149=(function() return {v33(),v33(),nil,nil};end)();if (v147==(0 -(0 + 0))) then local FlatIdent_6147E=0;local v510;local v511;local v512;local v513;while true do if (FlatIdent_6147E==1) then v512=nil;v513=nil;FlatIdent_6147E=2;end if (FlatIdent_6147E==2) then while true do if (1==v510) then v513=nil;while true do if (v511==(1 + 0)) then while true do if (v512==((812 -571) -((2181 -(109 + 1885)) + 54))) then v513=(function() return (2249 -(1269 + 200)) -((310 -148) + (1433 -(98 + 717))) ;end)();while true do if (v513==((826 -(802 + 24)) + (0 -0))) then v149[ #v7("\234\15\129","\161\219\54\169\192\90\48\80")]=(function() return v33();end)();v149[ #v7("\72\81\4\116","\69\41\34\96")]=(function() return v33();end)();break;end end break;end end break;end if (0==v511) then local FlatIdent_1BAD7=0;local v560;while true do if (FlatIdent_1BAD7==0) then v560=0;while true do if ((0 -0)==v560) then local FlatIdent_9448C=0;while true do if (FlatIdent_9448C==0) then v512=(function() return 1171 -(62 + 356 + 579 + 174) ;end)();v513=(function() return;end)();FlatIdent_9448C=1;end if (FlatIdent_9448C==1) then v560=1 + 0 ;break;end end end if ((1 + 0)==v560) then v511=2 -1 ;break;end end break;end end end end break;end if (v510==(0 -0)) then v511=0;v512=nil;v510=1 + 0 ;end end break;end if (FlatIdent_6147E==0) then v510=0 + 0 ;v511=nil;FlatIdent_6147E=1;end end elseif (v147== #",") then v149[ #v7("\229\146\159","\75\220\163\183\106\98")]=(function() return v34();end)();elseif (v147==(2 + 0 + 0)) then v149[ #v7("\26\180\147","\185\98\218\235\87")]=(function() return v34() -((2 + 0)^(12 + 4)) ;end)();elseif (v147== #v7("\202\47\35","\202\171\92\71\134\190")) then local FlatIdent_5CA49=0;local v561;local v562;while true do if (1==FlatIdent_5CA49) then while true do if (v561==(0 + (1433 -(797 + 636)))) then v562=(function() return (0 -0) -(1619 -(1427 + 192)) ;end)();while true do if ((0 + 0)~=v562) then else v149[ #v7("\100\144\117","\232\73\161\76")]=(function() return v34() -((2 -0)^(6 + 10)) ;end)();v149[ #v7("\235\129\17\11","\126\219\185\34\61")]=(function() return v33();end)();break;end end break;end end break;end if (FlatIdent_5CA49==0) then v561=(function() return 0 + 0 + 0 ;end)();v562=(function() return;end)();FlatIdent_5CA49=1;end end end v179=(function() return (2 -1) + 0 ;end)();end if (v179~=(1 + 0)) then else v146=(function() return (743 + 895) -((1699 -(192 + 134)) + 263) ;end)();break;end end break;end end break;end end end if (v146~=(1000 -((1727 -(316 + 960)) + 549))) then else local FlatIdent_7AA3=0;local v180;local v181;while true do if (0==FlatIdent_7AA3) then v180=(function() return 0 + 0 ;end)();v181=(function() return;end)();FlatIdent_7AA3=1;end if (FlatIdent_7AA3==1) then while true do if (v180==((0 + 0) -(0 + 0))) then v181=(function() return 0 -(0 + 0) ;end)();while true do if (v181==(0 -0)) then local FlatIdent_14454=0;local v457;while true do if (FlatIdent_14454==0) then v457=551 -(83 + 468) ;while true do if (v457==(1807 -(1202 + 604))) then v181=(function() return (4 -3) -(0 -0) ;end)();break;end if ((0 -0)==v457) then local FlatIdent_3831=0;while true do if (FlatIdent_3831==0) then v147=(function() return v31(v131,1386 -(746 + (963 -(45 + 280))) , #v7("\20\192\70","\135\108\174\62\18\30\23\147"));end)();v148=(function() return v31(v131, #v7("\190\253\62\219","\167\214\137\74\171\120\206\83"),3 + 0 + 3 );end)();FlatIdent_3831=1;end if (FlatIdent_3831==1) then v457=1;break;end end end end break;end end end if ((1 + 0)==v181) then v146=(function() return 342 -(218 + 45 + 78) ;end)();break;end end break;end end break;end end end end break;end if (1==FlatIdent_512FF) then v148=(function() return;end)();v149=(function() return;end)();FlatIdent_512FF=2;end if (FlatIdent_512FF==0) then v146=(function() return 0 -0 ;end)();v147=(function() return;end)();FlatIdent_512FF=1;end end end break;end end break;end if (v129==(0 + 0)) then local FlatIdent_1F620=0;while true do if (FlatIdent_1F620==0) then v130=(function() return (293 + 1372) -((1796 -826) + 695) ;end)();v131=(function() return;end)();FlatIdent_1F620=1;end if (1==FlatIdent_1F620) then v129=1912 -(340 + 1571) ;break;end end end end end for v132= #"|",v34() do v70,v132,v39=(function() return v68(v70,v132,v39);end)();end return v72;end v110=(function() return (624 + 958) -((3307 -(1733 + 39)) + (126 -80)) ;end)();end if (((1036 -(125 + 909)) -(1949 -(1096 + 852)))==v110) then if (v67==(0 + 0)) then local FlatIdent_6F99F=0;local v126;local v127;while true do if (FlatIdent_6F99F==0) then v126=(function() return 0 -0 ;end)();v127=(function() return;end)();FlatIdent_6F99F=1;end if (FlatIdent_6F99F==1) then while true do if (v126~=0) then else v127=(function() return 0 + 0 ;end)();while true do if (v127==(1 + 1 + 0)) then v67=(function() return (1073 -(409 + 103)) -(306 + (490 -(46 + 190))) ;end)();break;end if (v127~=((96 -(51 + 44)) + 0)) then else local v139=0 + 0 ;while true do if ((1317 -(1114 + 203))==v139) then v70=(function() return {};end)();v71=(function() return {};end)();v139=727 -(228 + 498) ;end if (v139==1) then v127=(function() return 1 + 1 ;end)();break;end end end if ((584 -(32 + 25 + (1190 -(174 + 489))))~=v127) then else v68=(function() return function(v140,v141,v142) local v143=0 -0 ;local v144;local v145;while true do if (v143==1) then while true do if (v144==((3372 -(830 + 1075)) -((1423 -(303 + 221)) + (1837 -(231 + 1038))))) then v145=(function() return (86 + 17) -((1179 -(171 + 991)) + 86) ;end)();while true do if (v145==(0 + (0 -0))) then local FlatIdent_4F2F2=0;local v440;local v441;while true do if (FlatIdent_4F2F2==0) then v440=0 -0 ;v441=nil;FlatIdent_4F2F2=1;end if (FlatIdent_4F2F2==1) then while true 
