this is my second time writing the writeup coz up laptop closed thats sad but here we are .
  so journey was divided in three parts seeing a audio file i thought one of them might be inside of it but i foought nothing inside of it.
  first part was straight forward just exiftool and zsteg both gave me the flag.
  while using other tools i saw something was hidden inside using binwalk so i extracted it. 
  the zip file inside had a password required. usually i would use rockyou.txt but i remember seeing something related to password in chall png.
  i wrote a script to print also combination of journey_xxxx and pasted in txt and used zip2john to get journey_1503 as password.
  found another png inside . it said strings so started with using strings and the second flag was somewhere in it encoded in base64.
  till now the flag were in form of f1rst s3c0nd_ form so i tried to guess the third one like th1rd something but didnt work out.
  used other tools on png . foremost gave deleted png inside it which gave third flag. 
