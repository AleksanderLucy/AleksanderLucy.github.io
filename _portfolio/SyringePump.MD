---
title: "Syringe Pump"
excerpt: "This custom syringe pump can deliver precise flows _"
header:
  image: /assets/img/pump1.jpeg
  teaser: /assets/img/pump1.jpeg
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

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# 
# Operation Code


# Operating Instructions

The interface system should be intuitive, and the controls were designed with this idea in mind. To set the flow rate - in mL per min - adjust the variable called flow_rate to the desired flow rate in the first line of the Arduino code under the //Global variables section. Next, set the variable is_twenty to true or false depending on whether the 20 ml syringe is being used. The black button on the side of the box controls the state of the syringe pump. If the latching button is pressed, the pump pauses. If the button is unlocked the pump resumes. When running, the syringe will move at the set rate until it is out of liquid and stops. An LED on the side of the enclosure serves as a visual reference for the syringe’s operational state: green - actively running, yellow - paused, red - out of liquid. Manual adjustments, if necessary, can be made using the white button to rotate the screw clockwise or the blue button to rotate the screw counterclockwise. Note that the pump must be paused or off to activate these manual rotation buttons.

{% include gallery caption="This is a sample gallery to go along with this case study." %}
