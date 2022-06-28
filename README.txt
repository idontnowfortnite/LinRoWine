Roblox Linux:


Make sure to install the latest version of WineHQ before running Roblox-Installer in the terminal.

You can find the information needed to install it here:

https://wiki.winehq.org/Download

If you do otherwise, you will break the install and possibly end up with broken dependencies.

After installing roblox through the handy installer, install Firefox-Esr through the terminal.

Search up: "Firefox-Esr Linux Install (Insert Distro Here)" into your browser and find an appropriate site to install from.



Have a nice install!


Roblox on Chromebook (Debian 11 Bullseye)
 
 
Install Wine:

$ sudo sh -c 'echo " deb https://dl.winehq.org/wine-builds/debian/ bullseye main" >> /etc/apt/sources.list.d/wine.list'

$ wget -nc https://dl.winehq.org/wine-builds/winehq.key

$ sudo apt-key add winehq.key

$ sudo dpkg --add-architecture i386

$ sudo apt update

$ sudo apt install --install-recommends winehq-stable

Unzip the file:

$ tar -xf Roblox-Installer

Right click the folder and run through terminal

Run the file:

$ bash Roblox.sh

Select OpenGL for the best results.

Afterwards, Install Firefox ESR:

$ sudo apt install firefox-esr
