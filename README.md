# FrameBot

**PLEASE READ THE WHOLE CONTENT OF THIS PAGE CAREFULLY**

## Requirements
* ~~Python3 Download Python3 from https://www.python.org/downloads/~~
* ~~Install required packages `sudo pip3 install -r requirements.txt`~~

## How to use:
* Open in Colab : <a href="https://colab.research.google.com/github/izu14/FrameBot/blob/master/FrameBot_Colab.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
* ~~Make a page on facebook~~
* ~~Head over to http://maxbots.ddns.net/token/ and get the access token for your page~~
* ~~[Checkout this tutorial](generateToken.md)~~
* ~~Copy the token and paste it in assets/token.txt~~
* ~~Place the video in assets/video~~
* ~~Open your Terminal/Powershell(as administrator)/Command Prompt(as administrator) in the main folder of this repository~~
* ~~Run `python3 main.py` or `sudo python3 main.py` if you are on a Mac/Linux~~
* ~~Enjoy!~~

## Warning!
* ~~After setting everything up you have to host the bot somewhere, i.e, let it run by itself without having to close the script. Preferably you could do it on a VPS like Amazon's EC2/Lambda and Google Cloud, although I personally would prefer EC2 with Amazon Linux(CentOS 7).~~

**Note** : ~~You can also host it in your PC/laptop but it will tremendously slow your workflow. An old laptop/pc/raspberry pi is ideal as well~~
* As of now the script can only process single episodes/movies. The source code for whole series can be obtained by supporting me at https://www.patreon.com/etjfo
* Don't hesitate to hit me up here if you face any problems or if you donated at semolini#2344 (discord)

**Most Importantly** : DO NOT TRY TO SCHEDULE IT MANUALLY FOR EVERY ONE MINUTE! There is a reason why I set it to 1 hour.
You can set it to a MINIMUM of 30 minutes if you like, **DO NOT TRY TO SET IT TO 1 MINUTE OR 5 MINUTES WHATSOEVER**

If anything happens to your facebook account after lowering time interval any further, ***I'M NOT RESPONSIBLE***

**~~~~~~~~~~~~~~~~~~~~~**

**WARNING** THIS FORKED REPO USE 15 sec schedule/delay for each frame post, i decided to use this value after i saw that ESFIO(Every Spongebob Frame In Order) posted 12 frame every minutes which means they use 5 sec delay

**I've only tried using a video with 108 frames**

***I DON'T KNOW WHAT WILL HAPPEN, SO PROCEED AT YOUR OWN RISK, I'M NOT RESPONSIBLE***

**TODO**
<br>Add customizable form for post interval/delay
<br>Stop the code automatically after last frame posted
<br>Remove some unused code from YoutubeDL(or maybe switch to another method)
<br><br>I guess i need some times to do these small changes, i just taking interest into programming around 2w ago, tbh i don't know where to start or which language i should learn

**Sorry for my bad english ;_;**
