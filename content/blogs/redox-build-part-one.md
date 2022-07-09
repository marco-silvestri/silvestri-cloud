---
title: "My Redox build - part 1"
date: 2022-07-08T22:57:38+02:00
draft: false
toc: false
---
#### Sasa!
I must admit that I am a custom made keyboard enthusiast, and over the past year this hobby has really kept me busy.
For almost a year my daily driver has been the [Redox Wireless keyboard](https://github.com/mattdibi/redox-keyboard), an open source split mechanical keyboard created by Mattia Dal Ben. I've also contributed to this project creating my [own case](https://github.com/marco-silvestri/redox-big-battery), that can carry 2 18650 batteries. I mean, the bigger the better!

Although, of lately, the bluetooth receiver broke down, and after a careful decision, I decided to build the cabled version of the same keyboard, still with a personal touch to it.
This decision has been taken after taking in consideration few factors:
1. The bluetooth capabilities of the Redox Wireless are very limited: as the range of the bluetooth does not go past the meter;
2. It still occupy a precious usb port, since it still need the Pro Micro to receive the signal from the 2 halves of the keyboard;
3. The receiver is bulky, hard to fix or reassemble and mandatory to have. Hence kills the benefit of the whole wireless thingy;
4. The Redox Wireless lacks a layer led! As it uses a specific protocol, customize this build by adding a display, an encoder or even just an led, seems to be very hard!

So, I checked the [shopping list](https://github.com/mattdibi/redox-keyboard/tree/master/redox#bill-of-materials) and ordered few stuff from [JLCPCB](https://jlcpcb.com/) and [AliExpress](https://www.aliexpress.com). Everything came in less than 3 weeks.

The only negative note was with JLCPCB: despite the easy uploads, the high quality and the fast shipping, few days after I have placed my order, I received a communication where basically I should have been charged extra. Luckily it was just 15 bucks more, but it almost doubled the PCB cost!
<img src="https://res.cloudinary.com/marco-silvestri/image/upload/c_scale,w_623/v1657315935/silvestri-dot-cloud/assets/jlcpcb_rzfwvd.png" alt="JLCPCB message" class="img-fluid rounded-lg mx-auto d-block pt-5 pb-5">

As I was waiting for the stuff to arrive, I started to customized the Redox case, I needed to:
1. Add a tenting kit, so I have customized [this tenting kit](https://www.thingiverse.com/thing:4491679) by adding some holes for the screws and a backplate to mount inside to case, in order to have a better grip;
2. Add an led slot to the front plate: one thing the original build lacks is a layer indication of any sort;
3. Resize the key switches holes on the front plate, as the one in the original STL are a way too tight. Otherwise the switches wouldn't have fit; 
3. Place some holes to attach the tenting kit to the case. 

Here the links to the STLs:
1. [Resized front plate](https://www.tinkercad.com/things/9fA3w6hhU53?2.sharecode=YrELQbIeyLU8pPNg0jahHX-r79_xh8UbxR5l4wy3fYI)
2. [Bottom case](https://www.tinkercad.com/things/cMTdpGcl75s?3.sharecode=HENULeK7goEUYDydG1RAxwzijo8Qbt0dVtQT1YhhGco)
3. [Tenting kit base and plate](https://www.tinkercad.com/things/jshyc9QUV3a?sharecode=C8Uvqfl6wTthxXLnYjmqZZMPp9ej8MsIZ2yKqbGhNgs)
4. [Tenting leg](https://www.tinkercad.com/things/4Wybzxdor9c?sharecode=Zv-piKt55bCm_MIwKSvdLE-qeTKwELyXWOtfTToIQyI)

The front plate and the bottom case are symmetrical, so you can just flip them in your slicer, in case you would want to print them.
For the material I've picked a plain black PLA+. This has been one of the most suffered prints: blackouts, extrusion problems, problem with the roll itself... so, even tho I am not fully happy with the print, enough is enough! I'll test it a bit and if I won't like it anymore I will reprint it later on.
After printing I have proceeded to mount the tenting kit. 
Let me show you the result:
<img src="https://res.cloudinary.com/marco-silvestri/image/upload/c_scale,q_70,w_700/v1657313632/silvestri-dot-cloud/assets/1657313281707_zp3m7k.jpg" alt="3D printed case" class="img-fluid rounded-lg mx-auto d-block pt-5 pb-5">

Shortly after, the package from JLCPCB arrived! I was very well and tightly packed, and despite the choice of the cheapest shipping option, I had not encountered any problem. The package contained 5 halves, as you can only orders quantities which are equals to 5 or any of its multiples.
The gerber files is the same for both the halves, you just have to flip it.
<img src="https://res.cloudinary.com/marco-silvestri/image/upload/c_scale,q_70,w_700/v1657313643/silvestri-dot-cloud/assets/1657313281697_f3uv1w.jpg" alt="JLCPCB package" class="img-fluid rounded-lg mx-auto d-block pt-5 pb-5">

<img src="https://res.cloudinary.com/marco-silvestri/image/upload/c_scale,q_70,w_700/v1657313651/silvestri-dot-cloud/assets/1657313281672_pjkowo.jpg" alt="PCBs" class="img-fluid rounded-lg mx-auto d-block pb-5">

And finally also the parcel from AliExpress arrived! For the WS2812B leds I had some leftovers from a previous project: my intention is to use only one led per each side, as I want it to display the current layer.
<img src="https://res.cloudinary.com/marco-silvestri/image/upload/c_scale,q_70,w_700/v1657313629/silvestri-dot-cloud/assets/1657313281682_ur7xh0.jpg" alt="Components" class="img-fluid rounded-lg mx-auto d-block pt-5 pb-5">

This first part is over! Stay tuned for the step by step guide on how I am gonna build it ⚒