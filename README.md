# Ducky-Scripts
A collection of the Ducky scripts that i modified / wrote

## Table of Contents  
[What i used](#Whatiused)<br>
[How you can learn](#Howyoucanlearn)<br>
[Your Targets](#YourTargets)<br>

___
<a name="Whatiused"></a>
### What i used
Normally Ducky script is used with a [Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky-deluxe). 
The Rubber Ducky mimics a real keyboard, which makes it possible to run scripts as if you were on the Victims keyboard. Now, i used what's called a [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/), which esentially is the same thing but cheaper.
<img src="https://cdn-reichelt.de/bilder/web/xxl_ws/A300/RASP_PI_PICO_01.png" alt="The Raspberry Pi Pico" width="600" height="auto" border="10" /><br>
The Raspberry Pi Pico is a microcontroller which you can reprogramm to do the same thing as the Rubber Ducky. Here is a [great video](https://www.youtube.com/watch?v=e_f9p-_JWZw) from Network Chuck about that topic.


<a name="Howyoucanlearn"></a>
### How you can learn
If you want a real turtorial how to write your own Duckyscript you should check out [this.](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript).

<a name="Example"></a>
### Example
Here is a litte example on how Duckycode looks like:
```
DELAY 3000
GUI r
DELAY 200
STRING a
DELAY 800
LEFT
DELAY 400
ENTER
DELAY 1000
```
This Script can open Powershell as an administrator. And all without the user ever needing to touch the keyboard.

<a name="YourTargets"></a>
### Your Targets
You should only use this on someone else if you have their permission. Don't use this for illegal activities.

