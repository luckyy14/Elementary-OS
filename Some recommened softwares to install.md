Oracle Java
-
	$ sudo add-apt-repository ppa:linuxuprising/java
	$ sudo apt update
	$ sudo apt install oracle-java11-installer

Mysql
-
	$ apt-get install mysql-server
	$ mysqsl_secure_installation
	$ mysql_install_db

Reduce overheating by tlp
-
	$ sudo add-apt-repository ppa:linrunner/tlp
	$ sudo apt-get install tlp tlp-rdw
	$ sudo tlp start

youtuble-dl
-
	$ sudo wget https://yt-dl.org/latest/youtube-dl -O /usr/local/bin/youtube-dl
	$ sudo chmod a+x /usr/local/bin/youtube-dlsudo chmod a+x /usr/local/bin/youtube-dl

ffmpeg
	$ sudo apt-get install ffmpeg


Script to auto update :
-
Copy and save the code bellow in a file called "updater.sh" (no quotes). Go to that directory and open in terminal. run using "sudo bash updater.sh" without the quotes


	#!/bin/bash

	# Update and upgrade
		sudo echo ""
		sudo apt-fast update -y
		echo ""
		sudo apt-fast upgrade -y
		echo ""
		sudo apt-get dist-upgrade
		echo ""
		sudo apt-get upgrade --fix-missing
		echo ""
		sudo apt autoremove
		echo ""
	read h

Install pip
-
	$ sudo apt-get install python-pip python-dev build-essential 
	$ sudo pip install --upgrade pip 

