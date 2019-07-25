Problem :

avrdude: ser_open(): can't open device "/dev/ttyACM1": Permission denied


Solution : 

`~$ ls /dev/ttyACM0               `

`~$ sudo chmod a+rw /dev/ttyACM0  `
