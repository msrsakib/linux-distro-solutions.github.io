# For Debian based Linux OS. Ubuntu , Kali Linux.

Using this process, the git project can be build in Linux OS .

`~$ sudo apt-get install git`

`~$ sudo apt-get install autoconf`

`~$ sudo apt-get install automake`

`~$ sudo apt-get install libgtk-3-dev`

# Clone git 

`~$ git clone <repositoriess link> `

# Build and install

`~$ ./autogen.sh --prefix=/usr`
`~$ sudo make install`

# Uninstall

`~$ sudo make uninstall`

or

`~$ sudo rm -rf <path>`
