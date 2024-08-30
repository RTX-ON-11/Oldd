
sudo apt get-update
sudo apt install wget
sudo install synaptic
sudo apt install git
sudo apt-get Gedit
sudo apt install gedit-plugins
sudo gedit /etc/apt/sources.list.d/ubuntu.sources
sudo apt-get clean
sudo apt --fix-broken install
sudo apt-get update && sudo apt-get dist-upgrade
git clone https://github.com/RTX-ON-11/Pulse-Secure-PCKG.git
sudo dpkg -i  ps-pulse-linux-22.7r3-b30227-64bit-installer.deb 
sudo apt-get -f install
sudo dpkg --configure -a
sudo apt-get install dconf
sudo dpkg -i anydesk_2.9.4-1_amd64.deb
cd etc/apt/sources.list.d/
sudo dpkg -i libnss3-tools_3.68.2-0ubuntu1_amd64.deb 
sudo dpkg -i libwebkit2gtk-4.0-37_2.36.0-2ubuntu1_amd64.deb 
im Synaptic checken 
sudo dpkg -i libjavascriptcoregtk-4.0-18_2.38.6-0ubuntu0.20.04.1_amd64.deb 
sudo dpkg -i libicu66_66.1-2ubuntu2_amd64.deb 
sudo dpkg -i libjavascriptcoregtk-4.0-18_2.38.6-0ubuntu0.20.04.1_amd64.deb 
sudo dpkg -i libwebkit2gtk-4.0-37_2.36.0-2ubuntu1_amd64.deb 
sudo dpkg -i libicu70_70.1-2_amd64.deb 
sudo dpkg -i libwebkit2gtk-4.0-37_2.36.0-2ubuntu1_amd64.deb 
sudo dpkg -i libjavascriptcoregtk-4.0-18_2.44.2-0ubuntu0.22.04.1_amd64.deb
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt --fix-broken install
sudo dpkg -i  ps-pulse-linux-22.7r3-b30227-64bit-installer.deb

https://github.com/bambulab/BambuStudio/issues/3973#issuecomment-2085476683
zuerst das hier anpassen


sudo gedit /etc/apt/sources.list.d/ubuntu.sources  soll so aussehen 

Types: deb
URIs: http://de.archive.ubuntu.com/ubuntu/
Suites: noble noble-updates noble-backports
Components: main restricted universe multiverse
Signed-By: /usr/share/keyrings/ubuntu-archive-keyring.gpg

Types: deb
URIs: http://security.ubuntu.com/ubuntu/
Suites: noble-security
Components: main restricted universe multiverse
Signed-By: /usr/share/keyrings/ubuntu-archive-keyring.gpg

Types: deb 
URIs: http://security.ubuntu.com/ubuntu/ 
Suites: jammy-security 
Components: main restricted universe multiverse 
Signed-By: /usr/share/keyrings/ubuntu-archive-keyring.gpg



