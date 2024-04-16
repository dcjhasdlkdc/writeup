so my basic approach in ctf is to see the name of challenge first because it gives a lot of hint. so the name says themer means something related to theme which was a bit
unclear untill i saw the cold and warm thing. when i clicked on one of those i can see theme= in the url and knew i have to change that. didnt know to what tho. 
when i opened the dockerfile it had a file "COPY Flag.txt /" 
which gave it away i had to change the them to Flag.txt with 

http://ctf.copsiitbhu.co.in:21338/?theme=/flag.txt
which gave flag in page source .
