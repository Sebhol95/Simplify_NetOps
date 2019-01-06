![alt text](https://imgur.com/LxImKqy.png)

## Project
This repository is created to effectively gather information of Cisco ASR9000, ASR9000v2, IOS-XR , IOS and other nodes. By doing so the repo is divided by their version and the different dumps they produce. 

## Status 
[ASR9000 & ASR9000v2](https://github.com/Sebhol95/Simplify_NetOps/tree/master/ASR9000_ASR9000v2/Input_CRC_and_dampening) Input/CRC + dampening collection (up-to 17 satellittes)

## Installation and use
Using linux we can create a folder ```mkdir xxxx``` when we know the folders location we can start implementing the scripts. The code/s are buildt upon one main and sidescripts, alle we need to do is the following: 

**1:** go the the folder you created ```cd /home/somefolder/thecreatedfolder```

**2:** go into bashrc and create a alias for you'r excecutable script ```nano .bashrc``` and enter an alias ```alias = main/home/somefolder/thecreatedfolder/scriptname``` you need to create an alias for all the scripts in the folder. 

**3:** then make them excecutable with ```chmod +x filename``` you also need to do this for all the scripts.

**4:** at last we need to use the bashrc from the folder by typing ```. .bashrc```

## How it works
Using netmiko we are able to establish connection the the targets by using the secure shell (SSH). The code the use the modules netmiko has in store like ```net_connect.send_command_expect``` ```net_connect = ConnectHandler(**device)``` and more. 
```
from netmiko import ConnectHandler

device = {
        'device_type': 'cisco_ios',
        'ip': ip_address,
        'username': username,
        'password': password,
        'port': 22,
        }
```

## Code Example
Yet to come...
