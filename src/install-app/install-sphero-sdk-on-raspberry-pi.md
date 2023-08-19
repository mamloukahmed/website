---
title: Install Sphero SDK on Raspberry Pi | Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/Sphero SDK/icon-64.png" height=24> Sphero SDK on <img src=/img/other-icons/raspberrypi-icon.svg height=24> Raspberry Pi

## <img src="/img/app-icons/Sphero SDK/icon-64.png"> Sphero SDK
> Software Development Kit for the Sphero RVR Robot
> 
> This app can be used with the Sphero RVR Robot to code IR sensors, color sensors, LEDS, and much more, even programming servo's, and robotics arms to pick up and move items to another location.
> 
> To run this app: Most of the Instructions are provided after install. 
> Make sure to do - cd ~/sphero-sdk-raspberrypi-python/
> 
> (BEFORE INSTALLATION: ENABLE SERIAL PORT, THEN DISABLE SERIAL CONSOLE IN RASPBERRY PI CONFIG)
> 
> After reading the instructions, and rebooting, connecting to RVR is simple, using jumper wires, 
> Connect GND from the Raspberry Pi to GND on RVR.
> Connect TX from the Raspberry Pi to RX on RVR.
> Lastly, connect RX from the Raspberry Pi to TX on the RVR.
> 
> There you go! You are now ready to run your programs.

Fortunately, Sphero SDK is very easy to install on your Raspberry Pi in just two steps.
1. Install Pi-Apps - the best app installer for Raspberry Pi.
2. Use Pi-Apps to install Sphero SDK.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Raspberry Pi OS](https://www.raspberrypi.com/software/), which is currently version **Bullseye**.
Raspberry Pi OS has 32-bit and 64-bit variants, both of which will run on most Raspberry Pi computers, including the Pi 3 and the Pi 4.
Sphero SDK will run on either PiOS 32-bit or 64-bit.
</div>
<div class="simple-install-content content">

## Install Pi-Apps

Pi-Apps is a free tool that makes it incredibly easy to install the most useful programs on your Raspberry Pi with just a few clicks.

Open a terminal and run this command to install Pi-Apps:
```bash
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```
Feel free to check out the Pi-Apps source code here: https://github.com/Botspot/pi-apps
</div>
<div class="simple-install-content content">

## Install Sphero SDK

Now that you have Pi-Apps installed, it is time to install Sphero SDK.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the Programming category.
<img src="/img/category-selections/Programming.png">
Now scroll down to find Sphero SDK in the list.
<img src="/img/app-icons/Sphero SDK/app-selection.png">
Just click Install and Pi-Apps will install Sphero SDK for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>