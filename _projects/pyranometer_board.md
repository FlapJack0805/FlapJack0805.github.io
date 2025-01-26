---
layout: page
title: Pyranometer Board
description:
img: assets/img/Final Pyranometer board PCB.png
importance: 2
category: Hardware
giscus_comments: false
---

The Pyranometer Board was a project that forced me to 
combine the things I've learned from both hardware and 
software engineering. I was required to design a PCB that 
could interace a pyranometer with a Laptop. I also made 
a program that published all of the data the board was 
recieving to a another program that would then organize 
the information for the Solar Car's race crew to use in 
the middle of the race.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pyranometer.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Photo of Pyranometer
</div>

Our pyranometer had only two analog output cords to connect to. Because of this I had to use a two pin connector to input data, and a USB-C as the output.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Final Pyranometer board PCB.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Soldered Pyranometer Board.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Partially Soldered PCB and Altium PCB Layout
</div>

After finishing up the Board I had to make sure my program worked with it. I had already written the code and conducted unit testing to make sure it worked but I had to make sure it interfaced with my PCB correctly. Everything worked and all I had to do was calibrate it to get correct results.


