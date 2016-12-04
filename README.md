# CME-BruteForcer
A little Python Script for cracking Windows Passwords with the help of CrackMapExec


This is a little Python Script i wrote to automate the "login" of [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec).
It basically bruteforce the Username/Password by running CME multiple times.

## How it works
You just provide a username and password list and a ip... then you are good to go :)
Just run

`pip install crackmapexec`

Next you need to find you targets ip by using 

`sudo crackmapexec 192.168.1.0/24` 

where as __*192.168.1.0*__ is the network you want to scan(obviously you need to be in that network...)

Next clone my repository if you havent already
`git clone https://github.com/ThoughtfulDev/CME-BruteForcer.git`

Then run
`sudo python CME-BF.py -u </path/to/userlist> -p </path/to/passwordlist> -ip <victimip>`

optionally you can specify the thread counts by using the `-t <threadcount>` option


**Have Fun :)**
