# Copley_Driver
This repository contains the Copley driver for controlling Copley amplifiers.
# Copley Servo Driver Setup Procedure Overview

## Reference Websites
1. Drive manual website
    DC Driver：
    - AEV Series: [AEV-180V-10A](https://copleycontrols.com/en/products/aev-180-10/) 
    - Accenlent Series: [BE2-90V-6A](https://copleycontrols.com/en/products/be2-090-06/) (Dual Axis)
    
    AC Driver：
    - Xenus Series：[XEL-230V-18A](https://copleycontrols.com/en/products/xel-230-18/)
2. Drive software configuration manual website
    - [CME User Guide](https://copleycontrols.com/wp-content/uploads/2018/02/CME-User-Guide.pdf)
    - [CANopen Programmer’s Manual](https://copleycontrols.com/wp-content/uploads/2018/02/CANopen-Programmers-Manual.pdf)

## Installation
To install the Copley application CME, follow these step:
[Download link](https://copleycontrols.com/wp-content/uploads/2018/02/CME2_Ver_8.0.zip)
<img width="548" alt="image" src="https://user-images.githubusercontent.com/125642743/226841490-1c68d04f-14ae-4175-9a81-c5543f9011c1.png">

## EtherCAT/TwinCat3 Setup
1. Download the EtherCAT ESI file on the [Copley ESI file generator website](http://embeddedintelligence.com/esi/)
2. Select the firmware file according to your driver model
3. Copy the **".\esi.zip\flat\(driver_name.xml)"** file to the path **".\TwinCAT\3.1\Config\Io\EtherCAT"**


## Hardware Setup
### DC Driver Setup
### AC Driver Setup
### MTO/STO Setup 




### TwinCat3 control/Status word Configuration
<img width="592" alt="image" src="https://user-images.githubusercontent.com/125642743/225541670-3c806367-0273-4b0c-b88c-8c2d0bfa8a1d.png">


## UV Bipolar Current Control
---
UV 设置


