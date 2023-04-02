---
title: "Microfluidic Devices"
excerpt: "Microfluidic device for homogenous mixing"
header:
  image: /assets/img/microfluid1.png
  teaser: /assets/img/microfluid1.png
gallery:
  - url: /assets/img/microfluid2.png
    image_path: /assets/img/microfluid2.png
    alt: "CAD Render 1"
  - url: /assets/img/plierv2.jpg
    image_path: assets/img/plierv2.jpg
    alt: "Build View 2"
  - url: /assets/img/plierv3.jpg
    image_path: /assets/img/plierv3.jpg
    alt: "CAD Render 2"
---

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee4b2ab1210fc7ad9?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## About

Microfluidic devices are tiny devices with small flow channels widely used in biomedical diagnostics, drug development, and the food and chemical industries. These devices are advantageous in many applications due to their high surface-to-volume ratio, but low Reynolds numbers in the channels eliminates turbulent mixing. To address this issue, microfluidic mixing schemes have been developed, achieving thorough and rapid mixing of multiple samples in microscale devices. The design of this device was an implementation of a passive mixing regime studied in *Microfluidic Mixing: A Review* by Lee *et al.* In this paper, a comprehensive view of different regimes was presented with efficiency statistics associated with each as well. Chosen for this device was a design studied by Mengeaud *et al.* with a 100 μm wide zigzag microchannel integrating a “Y” inlet junction, as seen in the figure below. In the study it was found that the most efficient mixing occurred when the ratio of the period of the zig zag to the width of the channel was 4 (S/W), at 98.6%.

This project sought to implement additive manufacturing techniques to create these microfluidic devices which require very fine details. Since the devices will be made out of polydimethylsiloxane, a widely used silicon-based organic polymer, which cannot be printed itself, casting is necessary. In order to create a mold with these fine details, the resolution of the 3d printer needs to be very high. As such, choosing what type of 3d printing technique will be used to print the part is very important; for this project vat photopolymerization, VPP, a stereolithography, SLA, technique was chosen. This process uses lasers to cure resin which is a mix of acrylates and epoxies, maximizing the laser’s ability to cure the resin while minimizing part shrinkage when the polymers crosslink. As important as the technique is the printer itself, and a Form 3 SLA primer from Form Labs was selected. This printer features a Light Processing Unit (LPU), which allows a single galvanometer to scan in two dimensions. With the LPU, the beam is always perpendicular to the film, thus there are no distortions at the edges of the bed. The LPU moves horizontally while the galvanometer directs and steers the laser vertically. The laser is redirected via a parabolic mirror ensuring that the laser is perpendicular to the film with a circular spot. The Form 3 printer with the Black v4 resin will allow for the following specifications:

* Laser Spot Size (i.e., Minimum Feature Size): 85 μm
* Minimum XY Resolution: 25 μm
* Minimum Z Resolution: 25 μm
* Build volume: (145 × 145 × 185) mm

{% include gallery caption="This is a sample gallery to go along with this case study." %}
