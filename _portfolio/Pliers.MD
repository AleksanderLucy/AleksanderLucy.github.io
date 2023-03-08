---
title: "Multi-material Pliers"
excerpt: "Print-in-place pliers made from PLA and TPU"
header:
  image: /assets/img/plier-banner.png
  teaser: /assets/img/plier-banner.png
gallery:
  - url: /assets/img/plierv1.jpg
    image_path: /assets/img/plierv1.jpg
    alt: "CAD Render 1"
  - url: /assets/img/plierv2.jpg
    image_path: assets/img/plierv2.jpg
    alt: "Build View 2"
  - url: /assets/img/plierv3.jpg
    image_path: /assets/img/plierv3.jpg
    alt: "CAD Render 2"
---

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e4339a4635e84757e84?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## About

This project sought to implement several different principles used in additive manufacturing but primarily focused on the print-in-place philosophy and the use of multiple materials in a single print job. To explain the print-in-place philosophy is as simple as reading it out; 3D printing complicated designs with multiple components or a need for actuation can often be a long, sometime arduous, process with multiple printers and stages necessary to create all of the components, but if something is designed to be print-in-place, all components can be completed in one print job. Utilizing print-in-place design decreases the number of resources necessary to produce said design (primarily through fewer printers) and can shorten print times without needing to take components off of the print bed and be actively waiting for each component to finish. Multi-material printing is also just like it sounds, 3D printing with different types of plastics. Different plastic filaments have different material properties which can be beneficial when creating a design, but can make printing more difficult. One of the more common ways, and the one used for this project, to do multi-material printing is to use a 3D printer with multiple, independent extruders so that each can run at the necessary settings for a successful print. 

In this project, a pair of pliers that could be printed in place and actuated, was designed using two materials, PLA and TPU-95A. PLA is a material prized for its low cost and easy printing, and here it will be used to make up the rigid components of the pliers: the handles and the arms. TPU is a plastic that is flexible making it ideal for joints or other parts with non rigid application. The TPU used in this project is the 95A variant specifically since it is pliable enough to bend without too much force application but it is still rigid enough to maintain structural integrity. Like normal pliers, these are actuated by squeezing the handles to close the arms and jaws; the flexible TPU center joint allows for the handles closing to translate a force to the arms. To retain this joint within the PLA appendages a dovetail joint is utilized, preventing the parts from being pulled from one another.

## Print Settings

Since this is a print using multiple materials, there are some settings that can be common across the printer and some that will need to be specific to each extruder based on the individual material properties.

### General:
60℃ bed temp, 25 mm/s max speed, 15 mm/s retraction speed

### Filament Temperatures:
PLA extruder: 215℃ ; TPU-95A extruder: 240℃

{% include gallery caption="This is a sample gallery to go along with this case study." %}
