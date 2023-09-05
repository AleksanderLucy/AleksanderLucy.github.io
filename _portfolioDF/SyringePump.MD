---
layout: single
title: "Syringe Pump"
excerpt: "Custom syringe pump delivering precise flows at any given flow rate"
header:
  image: /assets/img/pump3.png
  teaser: /assets/img/pump3.png
gallery:
  - url: /assets/img/pump_render1.png
    image_path: /assets/img/pump_render1.png
    alt: "CAD Render 1"
  - url: /assets/img/pump2.jpeg
    image_path: assets/img/pump2.jpeg
    alt: "Build View 2"
  - url: /assets/img/pump_render2.png
    image_path: /assets/img/pump_render2.png
    alt: "CAD Render 2"
---

## Purpose

* Syringe pumps are devices commonly used to administer fluids over a set period of time or at a set rate.
  * They can be used for any number of applications but are most often seen in medicinal practice to administer medicine.
* Motor driven syringe pumps operate on a fairly simple design, but many commerical products can be very expensive.
  * This project sought to create an inexpensive version with off the shelf parts and additive manufacturing.

## CAD Model
<iframe src="https://a360.co/3QIlW1A?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Design Features

* The syringe plunger moves via a Nema 17 stepper motor driving a 2mm pitch lead screw; The lead screw's rotation actuates the lead screw nut on it linearly, moving the 3D-printed plunger holder forwards and backwards. The addition of a linear rod and bearing maintains axial alignment of the compontents during these moves.


* Syringes of both a 20 mL capacity and 5 mL capacity can be used and interchanged without fasteners. 

## Operating Instructions

The interface system should be intuitive, and the controls were designed with this idea in mind. To set the flow rate - in mL per min - adjust the variable called flow_rate to the desired flow rate in the first line of the Arduino code under the //Global variables section. Next, set the variable is_twenty to true or false depending on whether the 20 ml syringe is being used. The black button on the side of the box controls the state of the syringe pump. If the latching button is pressed, the pump pauses. If the button is unlocked the pump resumes. When running, the syringe will move at the set rate until it is out of liquid and stops. An LED on the side of the enclosure serves as a visual reference for the syringe’s operational state: green - actively running, yellow - paused, red - out of liquid. Manual adjustments, if necessary, can be made using the white button to rotate the screw clockwise or the blue button to rotate the screw counterclockwise. Note that the pump must be paused or off to activate these manual rotation buttons.

## Operation Code

The aforemantioned code that is the only part the user needs to modify:
```c++
// GLobal Vars

float flow_rate = 5; //mL/min
bool is_twenty = false;
```

{% include gallery caption="This is a sample gallery to go along with this case study." %}
