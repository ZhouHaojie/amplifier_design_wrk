## Description

It is the Task of the workshop of lecture "Radio Frequency Electronics". The goal is to design, build and measure our own amplifier .

The final objective is to design a stable amplifier in Common Emitter topology with a center frequency of 2.4 GHz. The minimum requirements of final simulation has to fulfill are listed in table 1. Whether you want to focus on high gain or achieving a high bandwidth or low power consumption on top of that is up to you.

<img src="https://raw.githubusercontent.com/ZhouHaojie/Cloud/master/Photos/20201122190952.png" width="50%" height="50%" />

## Tools

Keysight’s Advanced Design System (ADS)

## Task 1 - Core Design

In the first task you have to make a decision on which transistor model you wish to use for your design, from BFP 520, BFP 540 and BFP 840 ESD.

We choose BFP 840 ESD, according to the datasheet,  It has a higher transition frequency($f_t$ = 80 GHz), so it is faster and could achieve a higher gain (about 26dB) at 2.4 GHz.

**schematic of  initial simulations with the transistor**

<img src="https://raw.githubusercontent.com/ZhouHaojie/Cloud/master/Photos/20201122191531.png" width="60%" height="60%" />

**DC-IV curve**

<img src="https://raw.githubusercontent.com/ZhouHaojie/Cloud/master/Photos/20201122191628.png" width="60%" height="60%" />

Operation point (Vbe = 0.845 V, Vce = 1.8 V, Ic = 10mA)

 

**Initial results for K-factor, MAG and S11, S21 in dB**

MAG at 2.4 GHz is about 25.584 dB and S21 is about 22.083 dB

S11 is -8.622dB at 2.4 GHz

<img src="https://raw.githubusercontent.com/ZhouHaojie/Cloud/master/Photos/20201122191736.png" width="60%" height="60%" />