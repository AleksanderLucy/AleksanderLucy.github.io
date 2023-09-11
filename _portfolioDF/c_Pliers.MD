---
layout: single
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

## Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e4339a4635e84757e84?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Design

* This project utilized a dual-extrusion 3D printer so PLA and TPU-95A were selected as the ideal materials.
  * PLA is a material prized for its low cost and easy printing, and here it will be used to make up the rigid components of the pliers: the handles and the arms.
  * TPU is a plastic that is flexible making it ideal for joints or other parts with non rigid application.
  * TPU 95A was specifically chosen to be pliable enough to bend without too much application of force but still be rigid enough to maintain structural integrity.

* The design for these pliers went through three main iterations.
  * The initial version of the pliers used an x of TPU between the handles and the jaws to allow force transmission but proved too flimsy and directed the force poorly.
  * The next version was a more aesthetic focused joint of diamonds which directed the force better but had internal collisions from the points of the diamonds.
  * The final version was a 3x3 grid that was strong enough to be stable and directed the force properly to open and close the jaws.

### Print Settings

* The printer was set up with several general settings to keep both plastics at an acceptable temperature and prevent the extruders from moving too fast.
  * 60℃ bed temp, 25 mm/s max speed, 15 mm/s retraction speed
* Each extruder needed its own temperature setting to properly control the flow of each plastic.
  * PLA extruder: 215℃ ; TPU-95A extruder: 240℃
* To prevent contamination of the print form any leaky filament while an extruder is on standby, a wipe tower was employed purging remaining filament in the nozzle. 

{% include gallery caption="This is a sample gallery to go along with this case study." %}
