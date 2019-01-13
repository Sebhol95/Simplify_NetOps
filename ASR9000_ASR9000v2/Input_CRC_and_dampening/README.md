![alt text](https://imgur.com/LxImKqy.png)

## How to use
First we need to clone this repo, by logging into our linux machine we can do so with : ```git clone https://github.com/Sebhol95/Simplify_NetOps/ASR9000_ASR9000v2/Input_CRC_and_dampening```. just run the main and see under to get an example. 

## Example of use
```
[Unknown@Unknown Python_Sat]$ main

How many satellittes to check? 1
Enter IP address: xx.xx.xx.xx
Enter username: Unknown
Enter password: 


Checking Satellite 100 for input/crc errors ...
--------------------------------------------

Interface Gi100/0/0/0
Fri Jan  x 22:33:49.713 CET
     x input errors, x CRC, x frame, x overrun, x ignored, x abort
     x output errors, x underruns, x applique, x resets

Interface Gi100/0/0/1
Fri Jan  x 22:33:50.916 CET
     x input errors, x CRC, x frame, x overrun, x ignored, x abort
     x output errors, x underruns, x applique, x resets
     
     
And it continues to interface Gi100/0/0/43 and does a new round with dampening. 
```
