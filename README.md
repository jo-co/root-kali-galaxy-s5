
Galaxy s5 active (sm-870a)

__________________________Downgrade__________________________________

- On windows - 
	open odin
	click:AP (under file download)
	browse to:G870A_NE4_Stock_Kernel.tar.md5

- On cell phone -
	turn off cell phone
	press power, volume down, home button at same time 
	plug usb cable to cell and the computer

on windows:click start

__________________________Root_______________________________________
	
- On cell phone -
	setting - security:unknown source
	towelroot.com:click on the icon to download
	root your phone by click on the button in the app

__________________________Kali_______________________________________

- Google store -
	linux deploy
	terminal emulator for android
	vnc viewer
	busyboxfree
	selinux mode changer

selinux : permissive

- linux deploy -
	built-in shell
	environement update

- terminal emulator- 
	su -
	cd /data/data/ru.meefik.linuxdeploy/
	chmod -R 777 linux

reboot cell phone

- linux deploy -
	kali linux
	all composante except kai composante
	resolution width:1920,height:1080 432ppi
	desktop:gnome
	install

- Terminal -
	su -
	cd data/data/ru.meefik.linuxdeploy/linux/bin/
	linuxdeploy shell
	apt-get update
	apt-get install kali-linux-full

linux deploy:start
vnc viewer:root, changeme

You are now in your vserver logged as root. You can change your password and add your user "android" in /etc/sudoers
