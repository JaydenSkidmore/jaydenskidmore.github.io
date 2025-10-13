---
layout: post
title: Battery Management System
description: A fully custom Battery Management System (BMS) I designed for the 2025 ANU Solar Racing iteration. Designed to monitor and maintain the 160V battery pack and all lithium ion cells present within it. Developed with cutting edge safety technology through the TI BQ796XX-Q1 chipset with safety, reliability, efficiency and cost at the forefront. Through this project I learned and tested years of circuit, PCB and microcontroller software design, with hand soldering and rigorous testing leading to a design I am incredibly proud of.


skills: 
  - High Voltage (300VDC) Design
  - Analog Signals
  - Analog Front-End Design
  - PCB Design and Implementation
  - Microcontrollers

main-image: /CMU.png
---

---
# Overview
The Battery Management System consists of a set of Cell Monitoring Units (CMU) and a Pack Monitoring Unit (PMU), mananged through a centralized Battery Management Unit (BMU).

<br>
---

## Cell Monitor
{% include image-gallery.html images="./Images/CMU/IsoCMU.png, ./Images/CMU/CMU_Render.png" height="200"%}
The Cell Monitor is responsible for measuring the voltages of each group of parallel cells within the battery, where each CMU is capable of monitoring 16 consecutive groups. Each Cell monitor is capable of measuring up to 6 temperature points external to the CMU, and two points across the balancing resistors. The cell monitors are equipped with passive cell balancing capabilities. More information can be found in the <a href="../../cell-monitor/index/">Cell Monitor</a> project page.

<br>
---

## Pack Monitor
{% include image-gallery.html images="./Images/PMU/Iso_PMU.png, ./Images/PMU/Render_PMU.png" height="200"%}

<br>
---

## Battery Management Unit
{% include image-gallery.html images="./Images/BMU/Iso_BMU.png, ./Images/BMU/Render_BMU.png" height="200"%}
---


