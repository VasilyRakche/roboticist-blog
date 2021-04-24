---
title: Handling Driver
description: How to not get into trouble
date: 2021-04-22
slug: handling-driver
image: pexels-matheus-bertelli-4558403.jpg
categories:
    - PCB
tags: [
    "BLDC controller"
]
---

## Cautions
 - Power supply must be able to sink-in current, if cant must design [Shunt Regulators](https://www.pololu.com/category/249/shunt-regulators)  
 - Pre-charge circuit must be used, more intuition about it: [How the pre-charge works, some intuituion](https://cotronics.nl/ger-series-contactors-in-electric-vehicles/) 
 - Do not connect ground pins of the CAN connector between Motor Drives 
 - Isolation of grounds is desired between the computer and Controller. In case of controll with TTY, possible solution: [CAN Board Connecting MCUs to CAN](https://www.amazon.com/gp/product/B00KM6XMXO)
 - Some internal settings in Firmware are calculated on Power-on. Restart when new settings applied

More information: [Motor Drive Documentation](https://docs.google.com/document/d/1dzNVzblz6mqB3eZVEMyi2MtSngALHdgpTaDJIW_BpS4/edit)  
 
 ## Useful links
 [External research on MIT controllor by Bart](https://docs.google.com/document/d/1QIEI6IdHOcW4N1cRyucb33io4LriNYafIMs1sjLfTQU/edit)
 