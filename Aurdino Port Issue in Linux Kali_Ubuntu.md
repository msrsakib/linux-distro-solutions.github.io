# Problem :


![](https://github.com/msrsakib/solution/blob/master/img/arduino.png)

-> avrdude: ser_open(): can't open device "/dev/ttyACM1": Permission denied




# Solution : 


![](https://github.com/msrsakib/solution/blob/master/img/arduino_01.png)

`~$ ls /dev/ttyACM0               `

`~$ sudo chmod a+rw /dev/ttyACM0  `
