Here is the procedure of installing Snap and Snap Store in Kali Linux.

## Step 1 : Install Snap

Try to install snap using following command.

`~$sudo apt install snap  `

![](https://github.com/msrsakib/solution/blob/master/img/kali/00_snap_installation.png)

But it shows something missing.To fix this we need to exicute another command.

`~$sudo apt --fix-broken install `

![](https://github.com/msrsakib/solution/blob/master/img/kali/01_snap_installation.png)

Now again try to install Snap.

`~$sudo apt install Snap  `

![](https://github.com/msrsakib/solution/blob/master/img/kali/02_snap_installation.png)

It works!

`~$sudo apt install snapd`
`~$sudo systemctl start snapd`
`~$sudo systemctl enable snapd`

`~$systemctl start apparmor`
`~$systemctl enable apparmor`

`~$snap install hello-world`

## Getting more help from snap

`~$snap help refresh`

Restrat PC 

## Install Snap-store

`~$sudo snap install snap-store`

After restart PC if Snap doesn't work then need to edit bash file. To do this follow the istructions. 

Edit Bash File :
`~$gedit ~/.bashrc`

Declare path [add new line]
export PATH=$PATH:/snap/bin

exicute Bash.
`~$source ~/.bashrc`

Restart 
