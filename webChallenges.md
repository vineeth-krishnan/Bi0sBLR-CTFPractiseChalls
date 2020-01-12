# Instructions
- Start with Level 1 and then move up to other levels
- Try the challanges by exploring the webpage and hints within the question (Don't look at the Hints given at the end)
- If the webpage and question still doesn't give a clue consult the hints
- Tip: Google the words in the question and the hints that you find important


# Challenges


## Level 1

1. Can you connect to 2018shell.picoctf.com at port 22847 to get the flag? 
2. Inpect this code! [Webpage](http://2018shell.picoctf.com:56252/)


## Level 2

3. I forgot my password again, 
   but this time there doesn't seem to be a reset, can you help me? 
   [Webpage](http://2018shell.picoctf.com:55790)
4. Made a website so now you can log on to! 
   I don't seem to have the admin password. See if you can't get to the flag. 
   [Webpage](http://2018shell.picoctf.com:37861) 
5. We captured some [Traffic](https://2018shell.picoctf.com/static/19129d64f5676ff5661da65b9772aff5/data.pcap) logging into the admin panel, can you find the password?
6. Do you see the same things I see? The glimpses of the flag hidden away? 
   [Webpage](http://2018shell.picoctf.com:40064) 
   
   
## Level 3

7. See if you can leak the whole database. The flag is in there somwhere… 
   [Webpage](https://web.ctflearn.com/web4/)
8. I created a database of all known types of hashbrowns! 
   Try to see if you can find a way to authenticate as an admin and retrieve the flag. [Hashbrown Database](http://138.197.193.132:5000/login)
9. These website requires authentication, via POST. However, it seems as if someone has defaced our site. 
   Maybe these is still some way to authenticate? [Webpage](http://165.227.106.113/post.php)
-
-
-
-
-
-

   
   # STOP Don't Look at the Hints. Try Exploring the webpage and question first
-
-
-
-
-
-
-
-
-
-
-  
   
# Hints
1. https://linux.die.net/man/1/nc
2. How do you inspect a website's code on a browser?
3. Client Side really is a bad way to do it.
4. Hmm it doesn't seem to check anyone's password, except for admins
5. Analyzing pcap files are good with Shark.
6. What part of the website could tell you where the creator doesn't want you to look?


- Author: Vineeth Krishnan
- Sources: PicoCTF 2018
           CTF Learn
