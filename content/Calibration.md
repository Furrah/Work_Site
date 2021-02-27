---
title: "Beam Current Transformer Calibration System"
date: 2021-02-24T18:21:08+01:00
tags: []
draft: false
image: "/Images/IMG_2655.jpg"
---

## Full system 
* FPGA based controller card 
* 2 x Analogue Precision Pulsed Current Source 
* PSU distribution card

<p align="center"> 
<img src="/Images/cal_front.jpg" alt="drawing" width="1000"/>
</p>
<br>

## Calibrator Controller 

* 4 layer board 
* 24 bit 4 MSPS sigma delta ADC 
* EEPROM 
* Voltage monitoring 
* 4 x Opto-coupled LEMO inputs 
* 2 x 10 GPIO with 3 pins dedicated to 3V3 for I2C etc.
* USB to QSPI bridge 

<p align="center"> 
<img src="/Images/controller.jpg" alt="drawing" width="1000"/>
</p>
<br>

## Analogue Precision Pulsed Current Source 

* 6 layer board 
* Precision current source - 12ppm stability to 3 standard deviations.
* Deviates by less than 100ppm over full pulse. 
* Internal current measurement system based on half bridge topology
* Adjustable precision reference voltage 
* EEPROM
* 12 bit nano DAC
* 4 x selectable outputs
<p align="center"> 
<img src="/Images/cal-anal-front.jpg" alt="drawing" width="1000"/>
</p>
<br>

<p align="center"> 
<img src="/Images/cal-anal-back.jpg" alt="drawing" width="1000"/>
</p>
<br>

## Testing Production

<p align="center"> 
<img src="/Images/cal_tower.jpg" alt="drawing" width="800"/>
</p>
<br>
