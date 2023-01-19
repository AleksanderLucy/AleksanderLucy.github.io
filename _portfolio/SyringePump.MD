---
title: "Syringe Pump"
excerpt: "This custom syringe pump can deliver precise flows _"
header:
  image: /assets/img/pump1.jpeg
  teaser: /assets/img/pump1.jpeg
gallery:
  - url: /assets/img/Cyber-Scooter-1.jpg
    image_path: assets/img/Cyber-Scooter-1.jpg
    alt: "placeholder image 1"
  - url: /assets/img/Cyber-Scooter-2.jpg
    image_path: assets/img/Cyber-Scooter-2.jpg
    alt: "placeholder image 2"
  - url: /assets/img/Cyber-Scooter-3.jpg
    image_path: assets/img/Cyber-Scooter-3.jpg
    alt: "placeholder image 3"
---

##Operating Instructions

The interface system should be intuitive, and the controls were designed with this idea in mind. To set the flow rate - in mL per min - adjust the variable called flow_rate to the desired flow rate in the first line of the Arduino code under the //Global variables section. Next, set the variable is_twenty to true or false depending on whether the 20 ml syringe is being used. The black button on the side of the box controls the state of the syringe pump. If the latching button is pressed, the pump pauses. If the button is unlocked the pump resumes. When running, the syringe will move at the set rate until it is out of liquid and stops. An LED on the side of the enclosure serves as a visual reference for the syringe’s operational state: green - actively running, yellow - paused, red - out of liquid. Manual adjustments, if necessary, can be made using the white button to rotate the screw clockwise or the blue button to rotate the screw counterclockwise. Note that the pump must be paused or off to activate these manual rotation buttons.

{% include gallery caption="This is a sample gallery to go along with this case study." %}
