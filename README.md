# Ubuntu-commands
Most used ubuntu commands

```
sudo apt-get update
sudo chmod 777 -R /var/www/html

sudo apt-get update
sudo apt update && sudo apt upgrade -y
sudo apt-get update && sudo apt-get dist-upgrade
sudo apt-get autoclean
sudo apt-get clean
sudo apt-get autoremove

$ sudo apt install ppa-purge
$ sudo ppa-purge ppa:morphis/anbox-support

wine uninstaller
sudo apt list --installed
sudo apt-get remove --purge (package name)
sudo apt-get remove (package name)
sudo apt-get purge (package name)

```

`````````````````````````````

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

It will ask you to continue in terminal press y and hit Enter,
after complete its process run these 3 more commands,

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
