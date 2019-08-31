Here is the procedure of installing Snap and Snap Store in Kali Linux.

## Step 1 : Install Snap

Try to install snap using following command.

`~$sudo apt update  `

[](https://github.com/msrsakib/solution/blob/master/img/kali/03_snap_installation.png)

`~$ sudo apt install snap  `

![](https://github.com/msrsakib/solution/blob/master/img/kali/00_snap_installation.png)

But it shows something missing.To fix this we need to exicute another command.

`~$ sudo apt --fix-broken install `

![](https://github.com/msrsakib/solution/blob/master/img/kali/01_snap_installation.png)

Now again try to install Snap.

`~$ sudo apt install Snap  `

![](https://github.com/msrsakib/solution/blob/master/img/kali/02_snap_installation.png)

It works! Time to go next step.

## Step 2 : Install Snapd

To install Snapd follow the commands. 

`~$ sudo apt install snapd`

![](https://github.com/msrsakib/solution/blob/master/img/kali/04_snap_installation.png)

## Step 3 : Start and add the service to autoload

`~$ sudo systemctl start snapd`
`~$ sudo systemctl enable snapd`

![](https://github.com/msrsakib/solution/blob/master/img/kali/05_snap_installation.png)

## Step 4 :Enable Systemd Unit

`~$ systemctl start apparmor`
`~$ systemctl enable apparmor`

![](https://github.com/msrsakib/solution/blob/master/img/kali/06_snap_installation.png)

## Step 5 : Check it's workable or not

Exicuting following command snap 'core' will be installed too if it's not installed in system.

`~$ snap install hello-world`

![](https://github.com/msrsakib/solution/blob/master/img/kali/07_snap_installation.png)

Now restart the system and try to download via snap.

## If getting any error related to path just follow this instructions:

After restart PC if Snap doesn't work then need to edit bash file. To do this follow the istructions.

Step 1 : Edit Bash File 

`~$ gedit ~/.bashrc`

![](https://github.com/msrsakib/solution/blob/master/img/kali/08_snap_installation.png)

Step 2 : Add new line and declare the path of snap 

> export PATH=$PATH:/snap/bin

![](https://github.com/msrsakib/solution/blob/master/img/kali/09_snap_installation.png)

Save the bash file.

Step 3 : Exicute Bash.

`~$ source ~/.bashrc`

![](https://github.com/msrsakib/solution/blob/master/img/kali/10_snap_installation.png)

Restart the system and enjoy Snap .

## Getting more help snap :

`~$ snap help refresh`

## Install Snap-store :

To install snap store follow the command: 

`~$ sudo snap install snap-store`

To open Snap store after finishing installation.

`~$ snap-store`

## Extra :

# Find Package :

`~$ sudo snap find <package name> '



 






