# Overview
This is a myled repository.  
Source code for lighting LEDs with Raspberry Pi 4.

# usage environment
ubuntu20.04

# usage device
Raspberry Pie 4

# Preparation
LED  
resistor  
leads  
Breadboard  

# install
After setting the LED etc. on the Raspberry Pi 4, enter the following command.  
```
$ sudo insmod myled.ko    
$ sudo rmmod myled  
$ sudo insmod myled.ko    
$ sudo chmod 666 /dev/myled0   
$ echo 1 > /dev/myled0    
$ echo 0 > /dev/myled0    
```
