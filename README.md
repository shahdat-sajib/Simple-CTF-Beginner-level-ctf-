# Simple-CTF-Beginner-level-ctf-
Step 1: To scan the open ports of target IP:
nmap IP
![image](https://user-images.githubusercontent.com/59218362/210261196-56d5557b-1604-4c46-898b-84da17f0dccd.png)

Step 2: For further information:
nmap -sC -sT IP
![image](https://user-images.githubusercontent.com/59218362/210261619-cebcd7fe-2d15-4453-97e5-0d9bbe066fc9.png)

Step 3: as http port open we are ry to open the IP in browser. As it shoes the default ubuntu webpage, for further information we are going to brute force the directory
dirb http://IP

Interestingly we are getting two directory 1. /robots.txt 2. /simple/

Step 4: Now we will go to robots.txt via browser
![image](https://user-images.githubusercontent.com/59218362/210262245-0f8ca688-74c5-4ba8-82ba-22d909d906a7.png)
Here we can find it disallow openemr-5_0_1_3
