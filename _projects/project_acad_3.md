---
layout: page
title: buggy project
description: Engineering Design Project II
img: assets/img/acad_projects/buggy_proj.jpg
redirect:
importance: 3
category: academic
---


This is a Group Project and it is offered jointly by the department of Electronics and Communication Engineering and the department of Computer Science Engineering to the IInd year students of all branch.

The aim of this project is to create an autonomous vehicle that is under wireless supervisory control from a remote station (see Fig 1) and safely coexists with other trams. In effect, each group is required to design and implement a micro-simulation of the Lucas light rail system.

The project will introduce you to the challenge of electronic systems design & integration. The project is an example of ‘hardware and software co-design’ and the scale of the task is such that it will require teamwork as a co-ordinated effort. The vehicle (from now on called the “Buggy”) must meet a number of progressive design challenges:

**Bronze challenge**

*Single buggy capable of following main track twice in a clockwise direction under full supervisory control and obeying the “Rules” of the track.*

*Buggy must be capable of detecting an obstacle whilst following the track, coming to a temporary halt if it does.*
*It proceeds automatically when the obstacle is removed. The buggy must safely park in the parking bay after the two loops. No external end-user manual control input is permitted once the initial start is signalled.*

*Messages transmitted to control your buggy, and messages received from the buggy must be displayed onscreen for debug purposes.*
*You must also display onscreen the state of the track and buggy at each gantry STOP.*

**Silver challenge**
<!-- Two buggies on track going in opposite directions and following the “Rules” of
the track. -->

*The first buggy out of the parking lane goes in a clockwise direction until it reaches gantry 3. The second buggy then goes in an anticlockwise direction once around track and parks.*

*The first buggy then completes the loop and parks safely. Either buggy must be capable of detecting an obstacle and temporarily halting until the obstacle is removed.*

<!-- Both buggies under full supervisory control. No external end-user manual
control input is permitted once the initial start is signalled. Again, control
messages and state of the track and buggies must be displayed on screen. -->

**Gold challenge**

*The Gold challenge is the same as the Silver Challenge but at the start the Supervisor PC must ask the end-user how many loops of the track the two buggies should perform before parking safely.*

<!-- Therefore your code must be generalized. The buggies will perform the required
number of loops in opposite directions and park safely. Either buggy must be
capable of detecting an obstacle and temporarily halting until the obstacle is
removed.

Both buggies under full supervisory control. No external end-user manual control
input is permitted once the initial start is signalled. Again, control messages and
state of the track and buggies must be displayed on screen. -->

<!-- Electronic lab
Buggy equipped with
• Microcontroller (Arduino Uno)
• IR sensors (To detect path to be followed)
• Ultrasonic sensor (To detect any obstacle on the track)
• Receiver circuit (To receive signals from each gantry whenever passes through it)
• Wireless Serial communication devices (X-Bee module) (To send/receive signals between computer system and Buggy
• IR sensors (To send a unique pulse signal to the buggy receiver)
• Transmitter circuit (To transmit three unique waveforms of different pulse width to corresponding gantries)
• Computer system ( To simulate C# program for supervisory control) -->



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/acad_projects/buggy_1.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
      {% include figure.html path="assets/img/acad_projects/buggy_2.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
      {% include figure.html path="assets/img/acad_projects/buggy_proj.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
