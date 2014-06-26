![Raspberry Pi Logo](../images/Pi_Logo.png)What is a Raspberry Pi
=================

In this session we will discuss what a Raspberry Pi is and connect it up for the first time.

###1 - What the heck is is?
[![What is a Raspberry Pi](http://img.youtube.com/vi/e0wkVVVLvR8/0.jpg)](http://www.youtube.com/watch?v=e0wkVVVLvR8)

:notebook:#####*Label the parts of you Raspberry Pi using the printed [worksheet](Pi-label.pdf), describe* what each part does.


###2 - Connecting it up.
When setting up your Raspberry Pi, there is an order you should follow to avoid problems.
1. Insert the SD card (or check it's in correctly)
2. Connect you chosen screen connector (and switch the screen on).
3. Connect any USB devices (keyboard, mouse, etc)
3. Connect the ethernet cable (if available)
4. Connect the power cable. (**This must always be the last connection made**)

:notebook:#####*Make a note of this setup sequence on your printed diagram.*

###3 - First Boot
Your Raspberry Pi will now boot up display a series of screens as it does. An important one is the NOOBs screen which allows you to reset your Pi in the event of something going really wrong. You would lose your data but reset your pi to it's factory state.
[Noobs Screen](../images/noobs.png)

After a short boot sequence you will be presented with the raspi-config menu for configuring some options with the Pi.
[Raspi-config](../images/raspi-config.png)
If you don't see this screen you will likely need to log in with:
```
login : pi
password : raspberry
```
*you won't see the password being displayed, why not?*

When you have logged in, type this command to get to the **raspi-config** mspienu.
```
sudo raspi-config
```
When this has loaded you are ready to continue on to the next section.
###[>>>Configuring you Raspberry Pi>>>](../config/README.md)

:bangbang:####Finished Early?
Why not build your Pibow case?
[![What is a Raspberry Pi](http://img.youtube.com/vi/2Pwc9QTgz_8/0.jpg)](http://www.youtube.com/watch?v=2Pwc9QTgz_8)