Issue :

E: Could not get lock /var/lib/dpkg/lock – open (11: Resource temporarily unavailable)
E: Unable to lock the administration directory (/var/lib/dpkg/), is another process using it?

Solution : 

ps aux | grep -i apt

sudo kill -9 <process id>

or 

sudo killall apt apt-get
