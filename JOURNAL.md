---
title: "Tadpole FPV Drone"
author: "Logan Peterson"
description: "A small FPV drone that has a custom cost effective transmitter PCB."
created_at: "2025-06-06"
---

# June 6th: Drone Parts Selected + Work On Transmitter Electronics

I looked around at some images prior to starting this project and decided I wanted my drone to have a smaller form factor, similar to a APEX 2" drone.

That inspiration frame looks like this:
![APEX 2" Drone](./images/droneframeinspiration.png)

After looking around at some other builds of this form factor, I found some similar parts that I could use and created a parts list in this google doc:
> https://docs.google.com/document/d/1UYxp3Jcj_MZBELJUi8HEg_IUyJKEcsd3nflhL_p9VP8/edit?usp=sharing

![FPV Drone Parts List](./images/FPVDroneHardwareTable01.png)

Finding good parts on AliExpress was more tedious then I expected as the prices seemed to keep changing, but I think I have a good completed list for the drone that should work well together.

I also worked to figure out how I could control the drone with a custom transmitter PCB.
I found that the flight controller I selected would work with ExpressLRS, which is an open source radio link protocol that would work with an ESP32 based transmitter. By pairing the ESP32 with an appropriate LoRa module I found, I should be able to create a custom transmitter PCB that can control the drone.

![FPV Transmitter Hardware Table (WIP)](./images/FPVTransmitterHardwareTable01.png)

(The Transmitter Electronics list is still a work in progress)

**Total time spent: 4.5h**

