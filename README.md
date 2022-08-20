# Ubuntu-commands
Most used ubuntu commands

```
sudo apt-get update
sudo chmod 777 -R /var/www/html

sudo dpkg --configure -a  ==> (Try configuring unconfigured packages)
sudo apt-get update   ==> (Update the contents of the repositories)

sudo apt --fix-broken install
sudo apt-get -f install ==> (Try to fix missing dependencies)
sudo apt-get -f install

sudo apt-get full-upgrade ==> (Update all packages with new versions available)
sudo apt update && sudo apt upgrade -y
sudo apt-get update && sudo apt-get dist-upgrade
sudo apt-get autoclean
sudo apt-get clean
sudo reboot  ==> (Reboot the system to see if the issue was resolved)


-----------------------------------------
# Install any package or repo

sudo apt-get install <software name>
sudo apt install ppa-purge
sudo ppa-purge ppa:morphis/anbox-support


# Uninstall any package or repo

sudo apt-add-repository -r ppa:morphis/anbox-support
sudo apt list --installed
sudo apt-get remove packagename
sudo apt-get remove --purge (package name)
sudo apt-get remove (package name)
sudo apt-get purge (package name)


# Reinstall Ubuntu desktop:

sudo apt-get install --reinstall ubuntu-desktop

-----------------------------------------
```

# PHP Version switch

```
-------------------------------

sudo update-alternatives --config php

# node version update

npm cache clean -f 
sudo npm install -g n
sudo n latest 

-------------------------------
```

# Connect SSH without putty
```
--------------------------------------------------------
Example:- sudo ssh -i "/home/shubham504/Documents/file.pem" ec2-user@12.123.1.123
Discription:- sudo ssh -i "/~file_path/~file_name.pem" {username}@{host}
--------------------------------------------------------
```
![Image of SSH.Ref1](https://github.com/shubham504/Ubuntu-commands/blob/main/images/PPKtoPEM.png)

# Docker Commands
```
#1 Commands to delete all images volues and  docker container.

sudo docker rm -f $(sudo docker ps -a -q)
sudo docker volume rm $(sudo docker volume ls -q)

Belog commands should run in case of space issue only and not on live.
sudo  docker image prune --all

-------------------------------------
#2 Commands to build and start servers. 

Go to directory of react and run first and second command to start server infinitely

sudo docker build -t public_html . ========> With . public_html is react folder
sudo docker run -p 8080:80 public_html:latest

Below command will execute and provide control to console so you can stop it and re-build
sudo docker run  -it --init -p 8080:80 public_html:latest

```
# Install and Uninstall environment (Ubuntu, Linux mint, Ubuntu mate)
```
$ sudo apt install -y cinnamon-desktop-environment
$ sudo reboot


$ sudo apt-get remove cinnamon-desktop-environment
$ sudo apt remove -y cinnamon cinnamon-*
$ sudo apt autoremove -y
$ sudo reboot

-------------------------------

skypeforlinux --secondary

''''''''''''''''''''''''''''''
Uninstalling software in wine

winecfg

wine uninstaller
wine64 uninstaller


wine gecko
wine mono



''''''''''''''''''''''''''''''
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
sudo apt-get remove --autoremove wine-stable wine-stable-amd64
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

It will ask you to continue in terminal press y and hit Enter, after complete its process run these 3 more commands,
```
# Mix commands
```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
sudo apt-get update
sudo apt update && sudo apt upgrade -y
sudo apt-get clean && sudo apt-get autoclean
sudo apt-get remove && sudo apt-get autoremove

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Lockscreen wallpaper change
wget -qO - https://github.com/PRATAP-KUMAR/focalgdm3/archive/TrailRun.tar.gz | tar zx --strip-components=1 focalgdm3-TrailRun/focalgdm3

libglib2.0-dev

sudo ./focalgdm3 /usr/share/backgrounds/Yaru-MATE.jpg
sudo ./focalgdm3 --reset



# Linux app icon update paths
-------------------------------------
/usr/share/applications
/usr/bin
/home/w3care/.config
-------------------------------------
```

# GitHub Formating Markup
```
https://guides.github.com/features/mastering-markdown/
```
