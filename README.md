<h1>Galaxy s5 active (sm-870a)</h1> 2.0

<h4>Downgrade</h4>
- windows: 
	<br>open odin
	<br>click:AP (under file download)
	<br>browse to:G870A_NE4_Stock_Kernel.tar.md5

- phone:
	<br>turn off cell phone
	<br>press power, volume down, home button at same time 
	<br>plug usb cable to cell and the computer

- windows:
	<br>click start
	<br>format sd card:512 MB - FAT 32 & rest to EXT2

<h4>Root</h4>
- phone:
	<br>setting - security:unknown source
	<br>towelroot.com:click on the icon to download
	<br>root your phone by click on the button in the app

<h4>Kali</h4>
- google store:
	<br>linux deploy
	<br>terminal emulator for android
	<br>vnc viewer
	<br>busyboxfree

- linux deploy:
	<br>built-in shell
	<br>environment update

- reboot the phone

- linux deploy:
	<br>kali linux
	<br>installation path:/data/sdext2/linux.img
	<br>user name:root
	<br>desktop:gnome
	<br>all components except kali components
	<br>resolution width:1920,height:1080 480ppi
	<br>install

- phone terminal:
	<br>su -
	<br>cd /data/data/ru.meefik.linuxdeploy/linux/bin/
	<br>linuxdeploy shell
	<br>apt-get update
	<br>apt-get install kali-linux-all
	<br>(https://www.kali.org/news/kali-linux-metapackages/)

- linux deploy:start

- vnc viewer password:changeme



<h2>Others issues</h2>

- google store: selinux 

- google store: supersu (start the app to disable knox)

- phone terminal:
	<br>su -
	<br>cd /data/data/ru.meefik.linuxdeploy/
	<br>chmod -R 777 linux