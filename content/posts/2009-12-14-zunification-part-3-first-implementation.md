---
layout: post
title: "Zunification part 3: First implementation"
date: 2009-12-14T10:07:00-08:00
author: Paolo
comments: true
categories: []
tags: []
---
It turns out that option 2 and 4 (Soundgate CORE and homebrew AUX in) are not mutually exclusive at all. So this puts the final plan at this: enable the AUX input and use a Soundgate CORE and a REMCORE (wired remote control) to charge and control the device.

Good, let’s do it.



#### 1. Upgrading the firmware



First thing first, you need to update the firmware in the RNS-E to at least 250 (260 is the latest North American release as of December 2009). This can be done by purchasing a NA Maps 2009 DVD from an Audi dealership or find someone who has it and update the unit with it. Once you’ve done that, you can use your old maps with no problems.



#### 2. Recoding the unit



While the firmware upgrade activated the AUX input, it did not enable it. You need to use a special tool and enter a secret code to do that. The special tool is a combination of a cable and some software that can be obtained at [http://www.ross-tech.com/](http://www.ross-tech.com/) for some money. In alternative, you can ask your friendly dealer for a two minute procedure and they usually do it for free.

The software part requires to recode the RNS-E to 0xxxx5x or 0xxxx6x and reboot the RNS-E.

<a href="/blog/images/image1.png">![image](/blog/images/image1-300x213.png)</a>

&nbsp;

At this point, the AUX input should be visible in the sources available under CD/TV.



#### 3. Building the input cable



Ok, the unit is ready now and we “only” have to build the necessary hardware to connect the Zune. The first piece to build is the audio input cable: you can find the parts at any Audi dealership for less than $15. You’ll need:



*   The 32 pin AV connector that goes on the RNS-E (1J0 972 977 G)
*   2x replacement female wires for the 32 pins AV connector (000 979 009)

Cut the wires in half and plug them in the connector as such:



*   **Ground** -&gt; pin 21 on Gray plug RNS-E
*   **Right** -&gt; pin 6 on Gray plug RNS-E
*   **Left** –&gt; pin 22 on Gray plug RNS-E

Now solder the wires to a couple of female RCA connectors and you’ll get something like this:

<a href="/blog/images/20091208Zunification0091.jpg">![20091208Zunification009](/blog/images/20091208Zunification0091.jpg)</a>

That’s all that’s needed now to listen to your Zune in your fancy Audi. Connect a RCA to 3.5mm jack cable and fish it out of sight, plug it into the headphone jack of the Zune and you’re done.

In the next post we’ll see how to spruce this up with a remote control!
