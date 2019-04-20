# luna

Pubkey -1: 029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae
Wallet - 1: RB6ugwoRJP6FZF1BfiS6CBfjxiBrPN1XVc
Tester - 1: Elif Selin Aksoy


Pubkey - 2: 0228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29
Wallet - 2: RJMmDzewzSgR8Q1Ecq3tDRQJWihk7wmNXM
Tester - 2: Dilşah İlayda Bekdemir


Pubkey - 3:76a91479a9f937d9a562ca906cee6390ad19ece2b0cf5288ac
Wallet - 3:RLNVThCiFmr3SyZ4Qtb5x1Zf26HxFhLweF
Tester - 3:Kübranur Özer

-----


Döngü Öncesi, marmarainfo 0 0 0 0 lar

Pubkey-1 : 

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarainfo 0 0 0 0
{
  "result": "success",
  "myaddress": "RB6ugwoRJP6FZF1BfiS6CBfjxiBrPN1XVc",
  "normal": 533.99940000,
  "myCCactivated": "RMhVWwH4vZmLAVj8DckFSTzzVSoUSdqEVF",
  "activated": 315.00000000,
  "activated16": 48.00000000,
  "myCCaddress": "RUQGarKsU965ZY5DCzinEmVdGmcgnASW4y",
  "CCutxos": 0.00010000,
  "firstheight": 0,
  "lastheight": 1073741824,
  "minamount": 0.00000000,
  "maxamount": 11529215046.06846976,
  "currency": "MARMARA",
  "n": 45,
  "pending": 45,
  "issuances": [


Pubkey-2: 

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarainfo                                                                                                              0 0 0 0
{
  "result": "success",
  "myaddress": "RJMmDzewzSgR8Q1Ecq3tDRQJWihk7wmNXM",
  "normal": 386.00000000,
  "myCCactivated": "RRsSfF7RBzXihxfmb8GBx5YhPvmE5rki8T",
  "activated": 309.00010000,
  "activated16": 48.00000000,
  "myCCaddress": "RTyNh2mmGKvRRUJJxjg52ejwk1sBhDc3mU",
  "CCutxos": 0.00020000,
  "firstheight": 0,
  "lastheight": 1073741824,
  "minamount": 0.00000000,
  "maxamount": 11529215046.06846976,
  "currency": "MARMARA",
  "n": 45,
  "pending": 45,
  "issuances": [

Pubkey-3:
marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarainfo 0 0 0 0
{
  "result": "success",
  "myaddress": "",
  "normal": 15.00000000,
  "myCCactivated": "RG2rYvx43owc6oCoCTqweJQq2LDpB9DKMi",
  "activated": 0.00000000,
  "activated16": 0.00000000,
  "myCCaddress": "RGLSRDnUqTB43bYtRtNVgmwSSd1sun2te8",
  "CCutxos": 0.00450000,
  "firstheight": 0,
  "lastheight": 1073741824,
  "minamount": 0.00000000,
  "maxamount": 11529215046.06846976,
  "currency": "MARMARA",
  "n": 45,
  "pending": 45,
  "issuances": [

-------------

Kredi döngü, vadeli çek dökümü
pubkey-2, pubkey-1 den 10 koin vadeli çek istedi. 

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarareceive  029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae 10 MARMARA 120
{
  "result": "success",
  "hex": "0400008085202f8901039564aad34c54204bbc5e2efc0115b6163243a60ab75c856d15ee2ccfb2f7be0000000049483045022100fedf82d2f88b7411d0a7a32c9457d2c048123310e531403163d39526f834265c02202b954fee82672e98799ca5870d798468c68927b7a0bd2e08eeccb5ca3fe21d3a01ffffffff03204e000000000000302ea22c80202cd85dfc4dd4525f45090a4e5975f957861a19676d09fca0924aa9f14cf31a048103120c008203000401ccd02de1110000000023210228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29ac00000000000000005b6a4c58ef52000000000000000000000000000000000000000000000000000000000000000021029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae00ca9a3b00000000a9a60100074d41524d4152410000000045a601000000000000000000000000",
  "funcid": "R",
  "createtxid": "0000000000000000000000000000000000000000000000000000000000000000",
  "senderpk": "029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae",
  "amount": 10.00000000,
  "matures": 108201,
  "currency": "MARMARA"
}

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 sendrawtransaction 0400008085202f8901039564aad34c54204bbc5e2efc0115b6163243a60ab75c856d15ee2ccfb2f7be0000000049483045022100fedf82d2f88b7411d0a7a32c9457d2c048123310e531403163d39526f834265c02202b954fee82672e98799ca5870d798468c68927b7a0bd2e08eeccb5ca3fe21d3a01ffffffff03204e000000000000302ea22c80202cd85dfc4dd4525f45090a4e5975f957861a19676d09fca0924aa9f14cf31a048103120c008203000401ccd02de1110000000023210228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29ac00000000000000005b6a4c58ef52000000000000000000000000000000000000000000000000000000000000000021029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae00ca9a3b00000000a9a60100074d41524d4152410000000045a601000000000000000000000000
9d771f69b96c364219c2d8bc2603e3854f3de2ed21f39cc9251188df460784d2

pupkey-1, pupkey-2 ye çeki yazdı
marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmaraissue 0228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29 10 MARMARA 108201 9d771f69b96c364219c2d8bc2603e3854f3de2ed21f39cc9251188df460784d2
{
  "result": "success",
  "hex": "0400008085202f8901d2840746df881125c99cf321ede23d4f85e30326bcd8c21942366cb9691f779d000000007b4c79a276a072a26ba067a5658021029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae8140b08e40ed9f1e678a382ab6c38cc3ae0a075ac0b04b10e584889b5735b0fb10071fae9476eefc4cde97999b7febd810b89af50978c953335c80422e10a9421b88a100af038001efa10001ffffffff031027000000000000302ea22c802068583b989d94369bfbc562c11ab70e103571419f8d8b7d471c3b6b4466a2c4ce8103120c008203000401cc1027000000000000302ea22c802025854dbc29292bf0f5f151d10764286c91245183f1edbd19b9974f3da25ab03c8103120c008203000401cc00000000000000005b6a4c58ef49d2840746df881125c99cf321ede23d4f85e30326bcd8c21942366cb9691f779d210228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab2900ca9a3b00000000a9a60100074d41524d4152410000000045a601000000000000000000000000",
  "funcid": "I",
  "createtxid": "9d771f69b96c364219c2d8bc2603e3854f3de2ed21f39cc9251188df460784d2",
  "approvaltxid": "9d771f69b96c364219c2d8bc2603e3854f3de2ed21f39cc9251188df460784d2",
  "receiverpk": "0228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29",
  "amount": 10.00000000,
  "matures": 108201,
  "currency": "MARMARA"
}

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 sendrawtransaction "0400008085202f8901d2840746df881125c99cf321ede23d4f85e30326bcd8c21942366cb9691f779d000000007b4c79a276a072a26ba067a5658021029d46b06fdd4e6e88d0e90841e95881ff9dcae7e26145d56d6b1f2f77ea0284ae8140b08e40ed9f1e678a382ab6c38cc3ae0a075ac0b04b10e584889b5735b0fb10071fae9476eefc4cde97999b7febd810b89af50978c953335c80422e10a9421b88a100af038001efa10001ffffffff031027000000000000302ea22c802068583b989d94369bfbc562c11ab70e103571419f8d8b7d471c3b6b4466a2c4ce8103120c008203000401cc1027000000000000302ea22c802025854dbc29292bf0f5f151d10764286c91245183f1edbd19b9974f3da25ab03c8103120c008203000401cc00000000000000005b6a4c58ef49d2840746df881125c99cf321ede23d4f85e30326bcd8c21942366cb9691f779d210228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab2900ca9a3b00000000a9a60100074d41524d4152410000000045a601000000000000000000000000"
80d34934a56b425f4938ef8ce8bad517333eed4b01d3dbe16824f3c0bdcc643b



Pupkey-3, pupkey-2 den çeki istedi

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarareceive 0228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29 10 MARMARA 108201 80d34934a56b425f4938ef8ce8bad517333eed4b01d3dbe16824f3c0bdcc643b
{
  "result": "success",
  "hex": "0400008085202f89013c69a9bec19d58d924c0acd14b26d018486ffbc28612fb9d16b7b572a06165170000000048473044022054d1a5e7fc9dc2ecc56957f5c180709f8b098ffa3f5facafb3a3b2e990041952022017439edf9a7656fcbe0550e0b0ec017424853786e0f4c0316779fa875d43e3d801ffffffff031027000000000000302ea22c802068583b989d94369bfbc562c11ab70e103571419f8d8b7d471c3b6b4466a2c4ce8103120c008203000401cce054e111000000000200ac00000000000000005b6a4c58ef52d2840746df881125c99cf321ede23d4f85e30326bcd8c21942366cb9691f779d210228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab2900ca9a3b00000000a9a60100074d41524d4152410000000046a601000000000000000000000000",
  "funcid": "R",
  "createtxid": "9d771f69b96c364219c2d8bc2603e3854f3de2ed21f39cc9251188df460784d2",
  "batontxid": "80d34934a56b425f4938ef8ce8bad517333eed4b01d3dbe16824f3c0bdcc643b",
  "senderpk": "0228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29",
  "amount": 10.00000000,
  "matures": 108201,
  "currency": "MARMARA"
}



./komodo-cli -ac_name=MTST3 sendrawtransaction "0400008085202f89013c69a9bec19d58d924c0acd14b26d018486ffbc28612fb9d16b7b572a06165170000000048473044022054d1a5e7fc9dc2ecc56957f5c180709f8b098ffa3f5facafb3a3b2e990041952022017439edf9a7656fcbe0550e0b0ec017424853786e0f4c0316779fa875d43e3d801ffffffff031027000000000000302ea22c802068583b989d94369bfbc562c11ab70e103571419f8d8b7d471c3b6b4466a2c4ce8103120c008203000401cce054e111000000000200ac00000000000000005b6a4c58ef52d2840746df881125c99cf321ede23d4f85e30326bcd8c21942366cb9691f779d210228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab2900ca9a3b00000000a9a60100074d41524d4152410000000046a601000000000000000000000000"

9396d2b298add680bef867720ce1672de810591a15e842f17b03b25068ee62ca
pupkey-2, pupkey-3’e çeki transfer etti.
 ./komodo-cli -ac_name=MTST3 marmaratransfer 76a91479a9f937d9a562ca906cee6390ad19ece2b0cf5288ac 10 MARMARA 120 9396d2b298add680bef867720ce1672de810591a15e842f17b03b25068ee62ca

{
  "result": "success",
  "hex": "0400008085202f8903ca62ee6850b2037bf142e8151a5910e82d67e10c7267f8be80d6                                                                                                             ad98b2d29693000000007b4c79a276a072a26ba067a565802103fcb9a53a92988d40476676473256                                                                                                             979ce0b6993a1698c45162098f62b90fc42d8140ef149371bb9ec56e047c90cb8d3ca2bbf2b0b66a                                                                                                             89a26daf7555554a060d8d0f3eafa15d2314ae1af1891a558a0f8ef3de07eee367afab7b220f1333                                                                                                             801940d1a100af038001efa10001ffffffff106c56b29aadf07f9f54b846a16753c8ae6beb0f4005                                                                                                             8f8eaad3b0ebb553d468000000007b4c79a276a072a26ba067a565802103fcb9a53a92988d404766                                                                                                             76473256979ce0b6993a1698c45162098f62b90fc42d8140fc9355ab29880648ef4b19ab80c1334d                                                                                                             879c1c11b97f0f19f169a6e8455305151e6c5eb0d126db0b193ba8d344cd8e6866b73cdd71f0f1a3                                                                                                             05224b12d510a7fba100af038001efa10001ffffffff1339cec1ea36ae8e9a4b3e0d343015c72060                                                                                                             3dd48e17b7704d2fdb37fafd2e1c00000000484730440220491e1448102b203a18ffe9082b4c5a0f                                                                                                             6378a158c4344f4d53469a41825980250220316303c5afb39e071b9973cc80716ba862f6b7f883d3                                                                                                             c90fcc86a5bf973d48f001ffffffff031027000000000000302ea22c80202685fca9cf67d911327d                                                                                                             caaa2591c3b22a494dcc41f33f2c8d5c9763261287e38103120c008203000401cc00a3e111000000                                                                                                             00232103fcb9a53a92988d40476676473256979ce0b6993a1698c45162098f62b90fc42dac000000                                                                                                             00000000005b6a4c58ef54becf927c3198020e4d532d0ec99da0564aac3faf507cded6870149048d                                                                                                             a1a21a210259922936d7d7753aa149c144aa52182b9b7e0ce34b88de2cbb818b16b852122200f205                                                                                                             2a01000000275b0100074d41524d41524100000000265b01000000000000000000000000",
  "funcid": "R",
  "createtxid": "9d771f69b96c364219c2d8bc2603e3854f3de2ed21f39cc9251188df460784d2",
  "batontxid": "80d34934a56b425f4938ef8ce8bad517333eed4b01d3dbe16824f3c0bdcc643b",
  "senderpk": "0228fe6d126afd36e85bdcb407713c25541cfd1e2c186ef5b13f5b3ae9d03fab29",
  "amount": 10.00000000,
  "matures": 108201,
  "currency": "MARMARA"
}

./komodo-cli -ac_name=MTST3 sendrawtransaction "0400008085202f8903ca62ee6850b2037bf142e8151a5910e82d67e10c7267f8be80d6                                                                                                             ad98b2d29693000000007b4c79a276a072a26ba067a565802103fcb9a53a92988d40476676473256                                                                                                             979ce0b6993a1698c45162098f62b90fc42d8140ef149371bb9ec56e047c90cb8d3ca2bbf2b0b66a                                                                                                             89a26daf7555554a060d8d0f3eafa15d2314ae1af1891a558a0f8ef3de07eee367afab7b220f1333                                                                                                             801940d1a100af038001efa10001ffffffff106c56b29aadf07f9f54b846a16753c8ae6beb0f4005                                                                                                             8f8eaad3b0ebb553d468000000007b4c79a276a072a26ba067a565802103fcb9a53a92988d404766                                                                                                             76473256979ce0b6993a1698c45162098f62b90fc42d8140fc9355ab29880648ef4b19ab80c1334d                                                                                                             879c1c11b97f0f19f169a6e8455305151e6c5eb0d126db0b193ba8d344cd8e6866b73cdd71f0f1a3                                                                                                             05224b12d510a7fba100af038001efa10001ffffffff1339cec1ea36ae8e9a4b3e0d343015c72060                                                                                                             3dd48e17b7704d2fdb37fafd2e1c00000000484730440220491e1448102b203a18ffe9082b4c5a0f                                                                                                             6378a158c4344f4d53469a41825980250220316303c5afb39e071b9973cc80716ba862f6b7f883d3                                                                                                             c90fcc86a5bf973d48f001ffffffff031027000000000000302ea22c80202685fca9cf67d911327d                                                                                                             caaa2591c3b22a494dcc41f33f2c8d5c9763261287e38103120c008203000401cc00a3e111000000                                                                                                             00232103fcb9a53a92988d40476676473256979ce0b6993a1698c45162098f62b90fc42dac000000                                                                                                             00000000005b6a4c58ef54becf927c3198020e4d532d0ec99da0564aac3faf507cded6870149048d                                                                                                             a1a21a210259922936d7d7753aa149c144aa52182b9b7e0ce34b88de2cbb818b16b852122200f205                                                                                                             2a01000000275b0100074d41524d41524100000000265b01000000000000000000000000"

432c0fe0e390326cc73cf6816556487fe27201ffb0c213bc1b90f39b42d0179f
Pupkey-3 çekin tahsilatını yaptı.
./komodo-cli -ac_name=MTST3 marmarasettlement 432c0fe0e390326cc73cf6816556487fe27201ffb0c213bc1b90f39b42d0179f
{
HATA
  "result": "error",
  "error": "no funds available at all"
}


Döngü Sonrası Marmara İnfo
Pubkey-1 : 

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarainfo 0 0 0 0
{
  "result": "success",
  "myaddress": "RB6ugwoRJP6FZF1BfiS6CBfjxiBrPN1XVc",
  "normal": 533.99930000,
  "myCCactivated": "RMhVWwH4vZmLAVj8DckFSTzzVSoUSdqEVF",
  "activated": 315.00000000,
  "activated16": 48.00000000,
  "myCCaddress": "RUQGarKsU965ZY5DCzinEmVdGmcgnASW4y",
  "CCutxos": 0.00010000,
  "firstheight": 0,
  "lastheight": 1073741824,
  "minamount": 0.00000000,
  "maxamount": 11529215046.06846976,
  "currency": "MARMARA",
  "n": 45,
  "pending": 45,
  "issuances": [


Pubkey-2: 

marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarainfo                                                                                                              0 0 0 0
{
  "result": "success",
  "myaddress": "RJMmDzewzSgR8Q1Ecq3tDRQJWihk7wmNXM",
  "normal": 387.00009000,
  "myCCactivated": "RRsSfF7RBzXihxfmb8GBx5YhPvmE5rki8T",
  "activated": 309.00010000,
  "activated16": 48.00000000,
  "myCCaddress": "RTyNh2mmGKvRRUJJxjg52ejwk1sBhDc3mU",
  "CCutxos": 0.00020000,
  "firstheight": 0,
  "lastheight": 1073741824,
  "minamount": 0.00000000,
  "maxamount": 11529215046.06846976,
  "currency": "MARMARA",
  "n": 45,
  "pending": 45,
  "issuances": [

Pubkey-3:
marmaratest4@marmaratest4:~/komodo/src$ ./komodo-cli -ac_name=MTST3 marmarainfo 0 0 0 0
{
  "result": "success",
  "myaddress": "",
  "normal": 14.00090000,
  "myCCactivated": "RG2rYvx43owc6oCoCTqweJQq2LDpB9DKMi",
  "activated": 0.00000000,
  "activated16": 0.00000000,
  "myCCaddress": "RGLSRDnUqTB43bYtRtNVgmwSSd1sun2te8",
  "CCutxos": 0.00450000,
  "firstheight": 0,
  "lastheight": 1073741824,
  "minamount": 0.00000000,
  "maxamount": 11529215046.06846976,
  "currency": "MARMARA",
  "n": 45,
  "pending": 45,
  "issuances": [

