---
layout: page
title: Pyranometer Board
description: PCB that interfaces a Pyranometer with a laptop
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
        {% include figure.liquid loading="eager" path="assets/img/Pyranometer.jpg" title="example image" class="img-fluid rounded z-depth-1" style="max-width: 50%;" %}
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

Key features of the project include:

-Pyranometer Integration: I connected the pyranometer to the PCB to measure the intensity of sunlight. The sensor converts light intensity into a voltage, which can be read and processed by the system.

-PCB Design: I designed the custom PCB to connect with the pyranometer, ensuring that the layout was optimized for signal integrity and ease of integration with other components in the system.

-Data Processing: The system collects and processes the voltage readings from the pyranometer, which are then fed to a computer for further analysis. This allows users to monitor sunlight intensity over time.

-Power and Signal Integrity: Focused on ensuring stable power distribution and minimizing noise in the signal path to ensure accurate readings from the pyranometer.

Through this project, I developed several key skills:

-PCB Design: Gained experience designing PCBs for sensor integration, focusing on layout, power routing, and signal integrity.
Sensor Integration: Improved my understanding of sensor interfacing, particularly in converting raw sensor data into a usable format for analysis.

-Analog Signal Processing: Learned how to handle analog sensor outputs and convert them into digital values for further processing and visualization.

-Embedded Systems: Enhanced my ability to integrate hardware components with software to build a functional system for real-world applications.

This project provided a great opportunity to apply sensor integration and PCB design skills, and helped deepen my knowledge of data acquisition systems and environmental monitoring.


