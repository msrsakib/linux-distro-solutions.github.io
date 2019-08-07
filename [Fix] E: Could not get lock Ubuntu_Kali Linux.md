While installing any application from terminal this issue is common for debian based linux OS users.

# Issue :

> E: Could not get lock /var/lib/dpkg/lock – open (11: Resource temporarily unavailable)

> E: Unable to lock the administration directory (/var/lib/dpkg/), is another process using it?

#  Solution : 

Watch the current process :

`~$ ps aux | grep -i apt `

Kill single process :

`~$ sudo kill -9 <process id> `

Kill all process :

`~$ sudo killall apt apt-get `
