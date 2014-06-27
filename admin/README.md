![Pi Logo](../images/Pi-Logo.png)

Basic Setup for school
=================

##Change your hostname

Your raspberry pi currently has a **hostname** of *raspberrypi* if we all connect to the same network with the same hostnames this could cause a problem. So lets change our hostname to the same but put a number on the end. Eg raspberrypi-01

To do this from **raspi-conf** (type *sudo raspi-conf*, if you closed it), use the arrow keys to select
**Advanced Options --> Hostname**

Enter your new hostname with your number and press enter.

![rpc01](../images/rpc01.png)

##Enable the Raspberry Pi Camera
We will aim to us the Raspberry Pi camera board next year and perhaps today, therefore you will need to enable it. From raspi-config select:
**Enable Camera --> Enabled**

Now select Finish from raspi-config and allow your Pi to reboot.

##Setup Remote log in
The Remote log in option allows you to connect your Pi to a network without a screen and view the screen via a network connection.

###Get connected
To get started you'll need an internet connection, connect your ethernet cable and run:
```
ping www.google.com
```

If this gets data back from google it will display messages like:
```64 bytes from lhr14s20-in-f19.1e100.net (173.194.34.115): icmp_req=3 ttl=57 time=17.9 ms```

To stop them (or any other active command) press the keys **CTRL + C**.

###Install TightVNCServer
TightVNCServer allows your screen to be visable over the network to install it we type:
```
sudo apt-get install tightvncserver
```
When asked about space press y for yes.

[![What is a Raspberry Pi](http://img.youtube.com/vi/m9YL0uf0uj0/0.jpg)](http://www.youtube.com/watch?v=m9YL0uf0uj0)

###Make it visible from other computers
Install Avahi-daemon to make you pi visible from other devices.
[![What is a Raspberry Pi](http://img.youtube.com/vi/YuTKA3fJAAM/0.jpg)](http://www.youtube.com/watch?v=YuTKA3fJAAM)

