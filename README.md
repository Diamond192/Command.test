PPDF> bytes 0 100

%PDF-1.1

1 0 obj
<</Type /Catalog
/Pages 2 0 R
>>
endobj

2 0 obj
<</Type /Pages
/Kids [ 3 0 R ]
/C
Usage: changelog [version]

Show the changelog of the document or version of the document
PPDF> changelog

Changes in version 1:
	Producer: Acrobat Web Capture 8.0
	Modification date: 2009-03-05T21:46:22+08:00
	Added objects: [48]
	Modified objects: [27, 29, 31]
  Usage: create pdf simple|(open_action_js [js_file])

Create a new simple PDF file or one with Javascript code to be executed when opening the file. It's possible to specify
the file where the Javascript code is stored or do it manually.
PPDF> create pdf open_action_js

Please, specify the Javascript code you want to include in the file (if the code includes EOL characters use a
js_file instead):

app.alert("Hello World!!",3);

PDF structure created successfully!!
Usage: create object_stream [version]

Create an object stream choosing the objects to be compressed.
Usage: decode variable var_name filter1 [filter2 ...]
Usage: decode file file_name filter1 [filter2 ...]
Usage: decode raw offset num_bytes filter1 [filter2 ...]

Decode the content of the specified variable, file or raw bytes using the following filters or algorithms:
	base64,b64: Base64
	asciihex,ahx: /ASCIIHexDecode
	ascii85,a85: /ASCII85Decode
	lzw: /LZWDecode
	flatedecode,fl: /FlateDecode
	runlength,rl: /RunLengthDecode
	ccittfax,ccf: /CCITTFaxDecode
	jbig2: /JBIG2Decode (Not implemented)
	dct: /DCTDecode (Not implemented)
	jpx: /JPXDecode (Not implemented)
  PPDF> bytes 70 37

78 9c 4b 2c 28 d0 4b cc 49 2d 2a d1 50 f2 48 cd   |x.K,(.K.I-*.P.H.|
c9 c9 57 08 cf 2f ca 49 51 54 54 d2 31 d6 b4 06   |..W../.IQTT.1...|
00 96 69 09 15                                    |..i..|

PPDF> decode raw 70 37 fl

app.alert("Hello World!!",3);
Usage: decrypt $password

Decrypts the file with the specified password
[Index](#showing-information)
<br />
### encode ###
[Index](#showing-information)
<br />
### encode ###
[Index](#showing-information)
<br />
### encode\_strings ###
[Index](#showing-information)
<br />
### encode\_[Index](#showing-information)
<br />
### exit ###
strings ###
[Index](#showing-information)
<br />
### filters ###
[Index](#showing-information)
<br />
### filters ###
[Index](#showing-information)
<br />
### js\_analyse ###
[Index](#showing-information)
<br />
### js\_beautify ###
<br />
### js\_code ###
If the Javascript code found in the object can be executed and generates another Javascript code stage all
the stages can be shown.
================== Original Javascript code ================== function nofaq(lgc){var ppwsd="";for(rxr=0;rxr<lgc.length;rxr+=2){ ppwsd+=(String.fromCharCode(parseInt(lgc.substr(rxr,5),19))); } eval(ppwsd); } nofaq("0D0A6452...");
================== Next stage of Javascript code ==================
	var i388Ag8 = 0x400000;
	var JKn0PaC = rpifVgf.length * 2;
	var NPvAvQ = i388Ag8 - (JKn0PaC + 0x38);
	var E79yB = unescape("%u9090%u9090");
	E79yB = lRUWC(E79yB, NPvAvQ);
	var fwdFfLgn = (NTLv7BP - 0x400000) / i388Ag8;
	for (var HEUAQgED = 0; HEUAQgED < fwdFfLgn; HEUAQgED ++ ){
	tX1PnUHy[HEUAQgED] = E79yB + rpifVgf;
  	var i388Ag8 = 0x400000;
	var JKn0PaC = rpifVgf.length * 2;
	var NPvAvQ = i388Ag8 - (JKn0PaC + 0x38);
	var E79yB = unescape("%u9090%u9090");
	E79yB = lRUWC(E79yB, NPvAvQ);
	var fwdFfLgn = (NTLv7BP - 0x400000) / i388Ag8;
	for (var HEUAQgED = 0; HEUAQgED < fwdFfLgn; HEUAQgED ++ ){
	tX1PnUHy[HEUAQgED] = E79yB + rpifVgf;
  	var i388Ag8 = 0x400000;
	var JKn0PaC = rpifVgf.length * 2;
	var NPvAvQ = i388Ag8 - (JKn0PaC + 0x38);
	var E79yB = unescape("%u9090%u9090");
	E79yB = lRUWC(E79yB, NPvAvQ);
	var fwdFfLgn = (NTLv7BP - 0x400000) / i388Ag8;
	for (var HEUAQgED = 0; HEUAQgED < fwdFfLgn; HEUAQgED ++ ){
	tX1PnUHy[HEUAQgED] = E79yB + rpifVgf;
  <br />
### js\_join ###
[Index](#showing-information)
<br />
### malformed\_output ###
[Index](#showing-information)
<br />
### metadata ###
[Index](#showing-information)
<br />
### metadata ###
[Index](#showing-information)
<br />
### object ###
   0 Header
  17
    Object  1 (260)
 276
 279
    Object  2 (19)
 297
 300
    Object  3 (48)
 347
 350
    Object  4 (77)
 426
 430
    Object  5 (33)
 462
 465
    Object  6 (21)
 485
 488
    Object  7 (41)
 528
 531
    Object  8 (68)
 598
 601
    Object  9 (187)
 787
 790
    Object  10 (52)
 841
 844
    Object  11 (85)
 928
 931
    Object  12 (50)
 980
 983
    Object  13 (5903)
6885
6887
    Object  14 (204)
7090
7093
    Xref Section (325)
7417
7420
    Trailer (69)
7488
7489 EOF
[Index](#showing-information)
<br />
### open ###
[Index](#showing-information)
<br />
### quit ###
[Index](#showing-information)
<br />
### rawobject ###
[Index](#showing-information)
<br />
### rawobject ###
PPDF> rawobject xref

xref 0 15 0000000000 65535 f 0000000015 00000 n 0000000261 00000 n 0000000279 00000 n 0000000324 00000 n 0000000397 00000 n 0000000428 00000 n 0000000448 00000 n 0000000487 00000 n 0000000553 00000 n 0000000731 00000 n 0000000781 00000 n 0000000862 00000 n 0000000909 00000 n 0000004186 00000 n
PPDF> rawobject xref
[Index](#showing-information)
<br />
### references ###
[Index](#showing-information)
<br />
### replace ###
[Index](#showing-information)
<br />
### save ###
It's recommended to use this command when we make modifications in the document to keep it free of
conflicts. For example, if we don't save the changes we can have inconsistent results when we use
"object" and "rawobject" commands, because one of them is related to the file before the modifications
and the other one after them.
<br />
### save\_version ###
[Index](#showing-information)
<br />
### sctest ###
[Index](#showing-information)
<br />
### sctest ###
[Index](#showing-information)
<br />
### search ###
[Index](#showing-information)
<br />
### search ###
PPDF> rawstream 5

78 da 05 c1 7b 7f 6a 60 00 00 e0 cf 72 dc 5e 8b |x...{j....r.^.| 5a 26 22 8a 37 62 ea 87 cd ad 8b cb ab 25 e4 54 |Z&".7b.......%.T| a7 da fa 77 9f fd 3c cf 92 bd 3f 18 bd 89 47 50 |...w..<...?...GP| 69 69 d2 81 34 6b 3b f5 c2 17 cc d3 6b bb 90 f8 |ii..4k;.....k...| b7 b0 f5 5e 58 48 7c 7f 84 1a 1c b8 ed f9 4e 23 |...^XH|......N#| 40 2a 68 5e 43 af eb 7b 8e f2 35 cb f0 2a 2b 3f |@*h^C..{..5..*+?| 41 95 64 b0 a9 af d8 a1 f0 af 51 eb 39 e3 b7 34 |A.d.......Q.9..4| 2a 84 9d 41 1c 5f ad 59 82 3b fd e9 4a 35 39 9b |*..A._.Y.;..J59.| db 30 64 3e 92 d4 6c 21 98 e4 0b 2b 31 e7 e8 6e |.0d>..l!...+1..n| 21 89 2e f6 d4 96 57 b4 54 1e 26 61 b7 b6 16 93 |!.....W.T.&a....| 67 68 b8 be 8b 79 f1 fe 82 ee eb e2 99 92 f7 68 |gh...y.........h| b0 b4 5c 14 10 dc 38 3f dc f8 d0 ac 60 ff 36 a5 |..\...8?.....6.| d6 d8 e3 b2 61 75 0c 2b 1f a6 b6 17 5a cd ea 3a |....au.+....Z..:| 7f ff a3 11 b6 38 e0 29 5c e0 6e 72 a9 73 1b 6d |....8.).nr.s.m| 2e c7 9c 92 83 a3 48 96 bb 3f cc 64 85 af a8 44 |......H..?.d...D| 92 ed a6 50 e9 56 fa 4b f5 6f e2 67 e0 43 e6 56 |...P.V.K.o.g.C.V| 7d d8 58 10 a9 70 a8 e0 3b 25 d1 29 e3 ab 2a 7b |}.X..p..;%.)..{| f2 2a bd c8 9d c1 51 64 80 d5 8c e0 70 f6 74 0b |.....Qd....p.t.| bc 73 47 52 c8 e3 3a 2c 66 2f c1 bf 1f 10 27 ea |.sGR..:,f/....'.| ee 31 b2 4c 15 80 51 c5 1e 76 bc 7b 9a 65 c4 7b |.1.L..Q..v.{.e.{| ef a4 20 66 b9 42 43 8e 96 3b 28 9e 45 4b a2 c4 |.. f.BC..;(.EK..| a9 21 74 6c 93 15 44 b9 05 5a 63 e7 66 d4 a8 48 |.!tl..D..Zc.f..H| 2e e7 39 18 c7 c6 58 19 82 0d 16 7c 5f 7b c7 8b |..9...X....|_{..| 8a ab 6b 2f e5 eb 24 3c 6c f5 8a d8 ca 68 51 3c |..k/..$<l....hQ<| 9e cb 89 f3 3b fb 0f 6c d4 7d d7 0d 0a |....;..l.}...|

PPDF> rawstream 5 $> stream5

78 da 05 c1 7b 7f 6a 60 00 00 e0 cf 72 dc 5e 8b |x...{j....r.^.| 5a 26 22 8a 37 62 ea 87 cd ad 8b cb ab 25 e4 54 |Z&".7b.......%.T| a7 da fa 77 9f fd 3c cf 92 bd 3f 18 bd 89 47 50 |...w..<...?...GP| 69 69 d2 81 34 6b 3b f5 c2 17 cc d3 6b bb 90 f8 |ii..4k;.....k...| b7 b0 f5 5e 58 48 7c 7f 84 1a 1c b8 ed f9 4e 23 |...^XH|......N#| 40 2a 68 5e 43 af eb 7b 8e f2 35 cb f0 2a 2b 3f |@*h^C..{..5..*+?| 41 95 64 b0 a9 af d8 a1 f0 af 51 eb 39 e3 b7 34 |A.d.......Q.9..4| 2a 84 9d 41 1c 5f ad 59 82 3b fd e9 4a 35 39 9b |*..A._.Y.;..J59.| db 30 64 3e 92 d4 6c 21 98 e4 0b 2b 31 e7 e8 6e |.0d>..l!...+1..n| 21 89 2e f6 d4 96 57 b4 54 1e 26 61 b7 b6 16 93 |!.....W.T.&a....| 67 68 b8 be 8b 79 f1 fe 82 ee eb e2 99 92 f7 68 |gh...y.........h| b0 b4 5c 14 10 dc 38 3f dc f8 d0 ac 60 ff 36 a5 |..\...8?.....6.| d6 d8 e3 b2 61 75 0c 2b 1f a6 b6 17 5a cd ea 3a |....au.+....Z..:| 7f ff a3 11 b6 38 e0 29 5c e0 6e 72 a9 73 1b 6d |....8.).nr.s.m| 2e c7 9c 92 83 a3 48 96 bb 3f cc 64 85 af a8 44 |......H..?.d...D| 92 ed a6 50 e9 56 fa 4b f5 6f e2 67 e0 43 e6 56 |...P.V.K.o.g.C.V| 7d d8 58 10 a9 70 a8 e0 3b 25 d1 29 e3 ab 2a 7b |}.X..p..;%.)..{| f2 2a bd c8 9d c1 51 64 80 d5 8c e0 70 f6 74 0b |.....Qd....p.t.| bc 73 47 52 c8 e3 3a 2c 66 2f c1 bf 1f 10 27 ea |.sGR..:,f/....'.| ee 31 b2 4c 15 80 51 c5 1e 76 bc 7b 9a 65 c4 7b |.1.L..Q..v.{.e.{| ef a4 20 66 b9 42 43 8e 96 3b 28 9e 45 4b a2 c4 |.. f.BC..;(.EK..| a9 21 74 6c 93 15 44 b9 05 5a 63 e7 66 d4 a8 48 |.!tl..D..Zc.f..H| 2e e7 39 18 c7 c6 58 19 82 0d 16 7c 5f 7b c7 8b |..9...X....|_{..| 8a ab 6b 2f e5 eb 24 3c 6c f5 8a d8 ca 68 51 3c |..k/..$<l....hQ<| 9e cb 89 f3 3b fb 0f 6c d4 7d d7 0d 0a |....;..l.}...|

PPDF> show stream5

78 da 05 c1 7b 7f 6a 60 00 00 e0 cf 72 dc 5e 8b |x...{j....r.^.| 5a 26 22 8a 37 62 ea 87 cd ad 8b cb ab 25 e4 54 |Z&".7b.......%.T| a7 da fa 77 9f fd 3c cf 92 bd 3f 18 bd 89 47 50 |...w..<...?...GP| 69 69 d2 81 34 6b 3b f5 c2 17 cc d3 6b bb 90 f8 |ii..4k;.....k...| b7 b0 f5 5e 58 48 7c 7f 84 1a 1c b8 ed f9 4e 23 |...^XH|......N#| 40 2a 68 5e 43 af eb 7b 8e f2 35 cb f0 2a 2b 3f |@*h^C..{..5..*+?| 41 95 64 b0 a9 af d8 a1 f0 af 51 eb 39 e3 b7 34 |A.d.......Q.9..4| 2a 84 9d 41 1c 5f ad 59 82 3b fd e9 4a 35 39 9b |*..A._.Y.;..J59.| db 30 64 3e 92 d4 6c 21 98 e4 0b 2b 31 e7 e8 6e |.0d>..l!...+1..n| 21 89 2e f6 d4 96 57 b4 54 1e 26 61 b7 b6 16 93 |!.....W.T.&a....| 67 68 b8 be 8b 79 f1 fe 82 ee eb e2 99 92 f7 68 |gh...y.........h| b0 b4 5c 14 10 dc 38 3f dc f8 d0 ac 60 ff 36 a5 |..\...8?.....6.| d6 d8 e3 b2 61 75 0c 2b 1f a6 b6 17 5a cd ea 3a |....au.+....Z..:| 7f ff a3 11 b6 38 e0 29 5c e0 6e 72 a9 73 1b 6d |....8.).nr.s.m| 2e c7 9c 92 83 a3 48 96 bb 3f cc 64 85 af a8 44 |......H..?.d...D| 92 ed a6 50 e9 56 fa 4b f5 6f e2 67 e0 43 e6 56 |...P.V.K.o.g.C.V| 7d d8 58 10 a9 70 a8 e0 3b 25 d1 29 e3 ab 2a 7b |}.X..p..;%.)..{| f2 2a bd c8 9d c1 51 64 80 d5 8c e0 70 f6 74 0b |.....Qd....p.t.| bc 73 47 52 c8 e3 3a 2c 66 2f c1 bf 1f 10 27 ea |.sGR..:,f/....'.| ee 31 b2 4c 15 80 51 c5 1e 76 bc 7b 9a 65 c4 7b |.1.L..Q..v.{.e.{| ef a4 20 66 b9 42 43 8e 96 3b 28 9e 45 4b a2 c4 |.. f.BC..;(.EK..| a9 21 74 6c 93 15 44 b9 05 5a 63 e7 66 d4 a8 48 |.!tl..D..Zc.f..H| 2e e7 39 18 c7 c6 58 19 82 0d 16 7c 5f 7b c7 8b |..9...X....|_{..| 8a ab 6b 2f e5 eb 24 3c 6c f5 8a d8 ca 68 51 3c |..k/..$<l....hQ<| 9e cb 89 f3 3b fb 0f 6c d4 7d d7 0d 0a |....;..l.}...|

[Index](#showing-information)
<br />
### show ###
[Index](#showing-information)
### vtcheck ###
             nProtect	     2013-07-01.01	  20130701	Exploit.TIFF.Gen
               McAfee	      5.400.0.1158	  20130701	Artemis!7101F6998958
          K7AntiVirus	        9.170.8927	  20130628	Exploit
               F-Prot	         4.7.1.166	  20130630	CVE-0188
             Symantec	     20131.1.0.101	  20130701	Trojan.Pidief.I
               Norman	           7.01.04	  20130701	Exploit_Gen.KDB
 TrendMicro-HouseCall	      9.700.0.1001	  20130701	TROJ_GEN.R4FH1KI
                Avast	      8.0.1489.320	  20130701	JS:Pdfka-gen [Expl]
            Kaspersky	         9.0.0.837	  20130701	HEUR:Exploit.Script.Generic
          BitDefender	               7.2	  20130701	Exploit.TIFF.Gen
              Agnitum	           5.5.1.3	  20130630	Exploit.CVE-2010-0188
             Emsisoft	         3.0.0.583	  20130701	Exploit.TIFF.Gen (B)
               Comodo	             16523	  20130701	UnclassifiedMalware
             F-Secure	     11.0.19100.45	  20130701	Exploit.TIFF.Gen
                DrWeb	                  	  20130701	SCRIPT.Virus
              AntiVir	        7.11.88.12	  20130701	EXP/Pdfjsc.EH.14
           TrendMicro	      9.740.0.1012	  20130701	EXPL_CVE20100188
               Sophos	            4.90.0	  20130701	Troj/PDFJs-II
            Microsoft	            1.9607	  20130701	Exploit:Win32/Pdfjsc.EX
                GData	                22	  20130701	Exploit.TIFF.Gen
            Commtouch	           5.4.1.7	  20130630	CVE-0188
              PCTools	           9.0.0.2	  20130701	Trojan.Pidief
               Ikarus	        T3.1.4.3.0	  20130701	Exploit.Win32.CVE-2010-0188
             Fortinet	         5.1.146.0	  20130701	W32/PDFJs.II!tr
                  AVG	       10.0.0.1190	  20130630	Exploit
                Pand             nProtect	     2013-07-01.01	  20130701	Exploit.TIFF.Gen
               McAfee	      5.400.0.1158	  20130701	Artemis!7101F6998958
          K7AntiVirus	        9.170.8927	  20130628	Exploit
               F-Prot	         4.7.1.166	  20130630	CVE-0188
             Symantec	     20131.1.0.101	  20130701	Trojan.Pidief.I
               Norman	           7.01.04	  20130701	Exploit_Gen.KDB
 TrendMicro-HouseCall	      9.700.0.1001	  20130701	TROJ_GEN.R4FH1KI
                Avast	      8.0.1489.320	  20130701	JS:Pdfka-gen [Expl]
            Kaspersky	         9.0.0.837	  20130701	HEUR:Exploit.Script.Generic
          BitDefender	               7.2	  20130701	Exploit.TIFF.Gen
              Agnitum	           5.5.1.3	  20130630	Exploit.CVE-2010-0188
             Emsisoft	         3.0.0.583	  20130701	Exploit.TIFF.Gen (B)
               Comodo	             16523	  20130701	UnclassifiedMalware
             F-Secure	     11.0.19100.45	  20130701	Exploit.TIFF.Gen
                DrWeb	                  	  20130701	SCRIPT.Virus
              AntiVir	        7.11.88.12	  20130701	EXP/Pdfjsc.EH.14
           TrendMicro	      9.740.0.1012	  20130701	EXPL_CVE20100188
               Sophos	            4.90.0	  20130701	Troj/PDFJs-II
            Microsoft	            1.9607	  20130701	Exploit:Win32/Pdfjsc.EX
                GData	                22	  20130701	Exploit.TIFF.Gen
            Commtouch	           5.4.1.7	  20130630	CVE-0188
              PCTools	           9.0.0.2	  20130701	Trojan.Pidief
               Ikarus	        T3.1.4.3.0	  20130701	Exploit.Win32.CVE-2010-0188
             Fortinet	         5.1.146.0	  20130701	W32/PDFJs.II!tr
                  AVG	       10.0.0.1190	  20130630	Exploit
                Panda	          10.0.3.5	  20130630	Exploit/PDF.Gen.B
                a	          10.0.3.5	  20130630	Exploit/PDF.Gen.B
                             nProtect	     2013-07-01.01	  20130701	Exploit.TIFF.Gen
               McAfee	      5.400.0.1158	  20130701	Artemis!7101F6998958
          K7AntiVirus	        9.170.8927	  20130628	Exploit
               F-Prot	         4.7.1.166	  20130630	CVE-0188
             Symantec	     20131.1.0.101	  20130701	Trojan.Pidief.I
               Norman	           7.01.04	  20130701	Exploit_Gen.KDB
 TrendMicro-HouseCall	      9.700.0.1001	  20130701	TROJ_GEN.R4FH1KI
                Avast	      8.0.1489.320	  20130701	JS:Pdfka-gen [Expl]
            Kaspersky	         9.0.0.837	  20130701	HEUR:Exploit.Script.Generic
          BitDefender	               7.2	  20130701	Exploit.TIFF.Gen
              Agnitum	           5.5.1.3	  20130630	Exploit.CVE-2010-0188
             Emsisoft	         3.0.0.583	  20130701	Exploit.TIFF.Gen (B)
               Comodo	             16523	  20130701	UnclassifiedMalware
             F-Secure	     11.0.19100.45	  20130701	Exploit.TIFF.Gen
                DrWeb	                  	  20130701	SCRIPT.Virus
              AntiVir	        7.11.88.12	  20130701	EXP/Pdfjsc.EH.14
           TrendMicro	      9.740.0.1012	  20130701	EXPL_CVE20100188
               Sophos	            4.90.0	  20130701	Troj/PDFJs-II
            Microsoft	            1.9607	  20130701	Exploit:Win32/Pdfjsc.EX
                GData	                22	  20130701	Exploit.TIFF.Gen
            Commtouch	           5.4.1.7	  20130630	CVE-0188
              PCTools	           9.0.0.2	  20130701	Trojan.Pidief
               Ikarus	        T3.1.4.3.0	  20130701	Exploit.Win32.CVE-2010-0188
             Fortinet	         5.1.146.0	  20130701	W32/PDFJs.II!tr
                  AVG	       10.0.0.1190	  20130630	Exploit
                Panda	          10.0.3.5	  20130630	Exploit/PDF.Gen.B
                
