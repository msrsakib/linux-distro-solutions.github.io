Mailspring is a mail client. The speciality of this client software is the UI looks very clean and it's recognized very well.
I tried lots of way to install Mailspring in Kali Linux. But got failed. Lasty I succeded to install Mailspring by following this instruction.

## Step 1 : Install Snap 

Follow this procedure to install snap : https://github.com/msrsakib/solution/blob/master/Linux_Setup_FirstTime/Install_Snap_in_Kali_LInux.md

## Step 2 : Install Mailspring via Snap from treminal or from Snap store.

Install using terminal 

`~$ sudo snap install mailspring`

After exicuting the command mailspring wil be ready to use. But there may be an issue. To skip or solve the issue follow step 3.

# Step 3 : Install libsecret

`~$ sudo apt install libsecret-1-dev`

Now Mailspring is completely ready to use.

Now open Mailspring using terminal `~$ mailspring` or from app search bar manually. Create an account if you didn't have and enjoy.

I successfully install Mailspring in my Kali system.
