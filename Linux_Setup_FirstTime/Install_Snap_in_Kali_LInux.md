sudo apt install snap
sudo apt --fix-broken install


sudo apt install snapd
sudo systemctl start snapd
sudo systemctl enable snapd

systemctl start apparmor
systemctl enable apparmor

snap install hello-world

## Getting more help from snap

snap help refresh

Restrat PC 

## Install Snap-store

sudo snap install snap-store

After restart PC if Snap doesn't work then need to edit bash file. To do this follow the istructions. 

Edit Bash File :
gedit ~/.bashrc

Declare path [add new line]
export PATH=$PATH:/snap/bin

exicute Bash.
source ~/.bashrc

Restart 
