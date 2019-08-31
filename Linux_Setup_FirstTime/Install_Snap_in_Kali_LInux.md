sudo apt install snap
sudo apt --fix-broken install


sudo apt install snapd
sudo systemctl start snapd
sudo systemctl enable snapd

systemctl start apparmor
systemctl enable apparmor

snap install hello-world

snap help refresh

gedit ~/.bashrc

export PATH=$PATH:/snap/bin

source ~/.bashrc
