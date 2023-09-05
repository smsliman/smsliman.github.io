---
title: "Syringe Pump"
excerpt: "An ultra precise syringe pump for delivering medications or alcohol."
header:
  image: /assets/img/real.jpg
  teaser: /assets/img/real.jpg
gallery:
  - url: /assets/img/render.png
    image_path: assets/img/render.png
    alt: "placeholder image 1"
---

For my final project in my rapid prototyping, we were tasked with making a syringe pump that could deliver precise amounts of liquid. We constructed a linear acctuator from a mixture of off-the-shelf and custom 3D printed parts, then added an LED screen and additional buttons to provide information about the current state of the pump and control the motor in individual steps. 

Here are the off-the-shelf parts used:

| Part     |
|----------|
| Flanged Ball Bearing   |
| Lead Screw |
| Linear Rod   |
| Linear Bearing |
| Lock Collar for Lead Screw |
| Lock Collar Linear Rod |
| Thread Forming Screw |
| M3x10mm Bolt |
| M5 Tee Nut |
| M5x8mm Bolt |
| NEMA 17 Stepper Motor |
| Nut tr8x8 |
| V-Slot 20x40x350 |


Here are the custom parts used:

| Part |
|----------|
| Motor Mounting Plate   |
| Carriage |
| Supports   |


[Here is the code](https://github.com/theannachen/DFArduinoCode)


The pump is operated by moving the actuator back until a syringe is loaded, then moving it forward until the desired amount of liquid is delivered. The pump can be controlled in individual steps, or it can be set to run continuously until the syringe is empty. If provided the geometry of the syringe in the code, the pump can also deliver a precise amount at a specific flow rate.

{% include gallery caption="" %}
