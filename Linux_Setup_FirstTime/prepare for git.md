# For Debian based Linux OS. Ubuntu , Kali Linux.

sudo apt-get install git

sudo apt-get install autoconf

sudo apt-get install automake

sudo apt-get install libgtk-3-dev

#clone git 

git clone <repositoriess link>

#Build and install

./autogen.sh --prefix=/usr
sudo make install

#Uninstall

sudo make uninstall

sudo rm -rf <path>
