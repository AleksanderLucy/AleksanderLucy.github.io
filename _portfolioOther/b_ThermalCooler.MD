---
layout: single
title: "Thermoelectric Cooler"
excerpt: "Custom can cooler powered by thermoelectrics"
header:
  image: /assets/img/heatStackDiag.jpg
  teaser: /assets/img/heatStackDiag.jpg
gallery:
  - url: /assets/img/cooler1.jpg
    image_path: /assets/img/cooler1.jpg
    alt: "Cooler View 1"
  - url: /assets/img/cooler3.jpg
    image_path: assets/img/cooler3.jpg
    alt: "View Into the Cooler"
  - url: /assets/img/cooler2.jpg
    image_path: /assets/img/cooler2.jpg
    alt: "Cooler View 2"
---

## Purpose

* The purpose of this project was to design and prototype a thermoelectric-operated single-can beverage cooler. The device will hold a standard aluminum can and cool it down from room temperature.
* This design was meant to emphasise everyday use and a low cost of production.

## CAD Model
<iframe src="https://vanderbilt744.autodesk360.com/shares/public/SHd38bfQT1fb47330c9942c27ec9049f9ea0?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Design Features

* This design sought to incorporate easily available, off-the-shelf parts with a product that already exists to keep a drink cool: the coozie. As such, the structure of the device is focused on easily fitting with the coozie form factor and will match its size to be mounted directly underneath.
* It features a three-tiered stack where the top is directly glued to the bottom of the coozie, the middle provides support for the heat transfer system, and the bottom will house the battery to operate it.

![Image](/assets/img/heatStackDiag.jpg)

* The heat transfer stack comprises five components: a copper disk, the thermoelectric, a 60mm fan, and two heat sink fin arrays. 
  * The copper disk will be used to replace the typical foam bottom of the coozie, providing a vector for conductive heat transfer away from the can into the thermoelectric which will be affixed to its underside. 
  * The other side of the thermoelectric will contact one of the heat sink fin arrays, with its fins pointed down. The other heat sink fin array will be attached to the second tier platform of the enclosure with its fins up, sandwiching the fan between the pair. 
  * This will allow the fan to blow downwards, sucking air through the upside-down fin array and blowing it out through the bottom fin array. 
  * The fan and the thermoelectric can be powered by a 9 V battery, conveniently stowed in the bottom section of the enclosure.
* The 3d printed stack enclosure is made of FormLabs Black Resin which has a heat deflection temperature of 78 ℃ - well above expected operating temperatures for the thermoelectric.

![Image](/assets/img/coolerClose.jpg)

## Efficacy

To assess the effectiveness of the product, a full aluminum can was placed into the device at an initial temperature of 24.6 ℃. The device was powered on and every 60 seconds, the temperature of the can was measured. This was continued until the temperature of the can remained approximately unchanged. The results were plotted and are displayed in the figure below. The results show that the can temperature decreased very slightly and linearly with time. The decrease was at a rate of about 0.1335 ℃/min. The final temperature reached was 22.7 ℃, which is still above room temperature. This data demonstrated the ability of the device to only cool down the can to a small extent. An effective device would hopefully cool down the can to below 10℃.

![Image](/assets/img/hotCan.jpg)

To reassess the effectiveness of the can in a different sense, a can that was already cold was placed in the device and the temperature was measured over time. The data was collected over 15 minutes and is displayed in the figure below.

![Image](/assets/img/coolCan.jpg)

## Conclusions

While the device was designed to cool a can, it was not as effective as initially hoped for. A core element of the device’s construction was the inclusion of a coozie to envelope the can as it sits on the cooling pad; however, since the coozie serves as an insulator, a can that is warm and placed inside will be kept warm. This hinders the potential of the cooling pad to cool the can as it becomes the only source of heat relief. Furthermore, the device was designed with a focus on keeping a small size and portability, which limited the size of the heat sinks and fan that could be used. The fan does blow hot air out and there was a ~20℃ difference between the two heat sinks, but with less heat able to be drawn away from the thermoelectric, it was less effective. Finally, running this device off of a portable 9 V battery limits the strength of the fan which was truly intended to run on 12 V; as such, this device is perhaps best used to keep a drink cold out of the refrigerator or cooler.

{% include gallery caption="This is a sample gallery to go along with this case study." %}
