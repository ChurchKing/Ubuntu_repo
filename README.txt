## This project is established for the configuration for Ubuntu/ROS"

###  Vim ###
put 
python.vim  >>>>>  /usr/share/vim/vim74/syntax/  

vimrc       >>>>>  /etc/vim/

### apt source ###

sources.liat  >>>>> /etc/apt/


### ROS ###
INSTALL :
sudo apt-get install ros-kinetic-desktop-full

ERROR:
	depends: ros-kinetic-simulators

	SOLUTION: update the source


### Zsh ###
INSTALL:
	sudo apt-get install zsh
	sudo sh ohmyz.sh

###  FAQ  ####

ERROR in sogopinyin
	SOLUTION: install depends: libqtwebkit4



