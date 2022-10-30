# TPS63070
**TPS63070 DCDC** 低功耗高效电池稳压方案  
**TPS63070 Buck-Boost** Converter  

 <img src="/Img/Top.png" width = "300" alt="TopView" align=center /> 
 <img src="/Img/Bottom.png" width = "300" alt="BottomView" align=center />

🌏[**简体中文**](##概述)     🌎[**English**](##Overview)


## 概述

基于**TPS63070**降压-升压转换器的一种低功率高效锂电池稳压器解决方案
适用于 那些 输入电压可能高于或低于输出电压的应用。在升压或降压模式下,输出电流可高达 2A。
此降压-升压转换器基于一个固定频率、脉宽调制 (PWM)控制器，此控制器通过使用同步整流来获得最高效率。
在低负载电流情况下，此转换器进入省电模式以在宽负载电流范围内保持高效率。

## 性能

• 输入电压范围：2.0V 至 16V  
• 输出电压范围：2.5V 至 9V （本开源设置为3.3V）  
• 效率高达 95%  
• 脉宽调制 (PWM) 模式下的直流精度为 +/-1%  
• 脉频调制 (PFM) 模式下的直流精度为 +3%/-1%  
• 降压模式下的输出电流为 2A  
• 升压模式下的输出电流为 2A  
（VIN = 4V；Vout = 5V）  
• 器件静态电流典型值：50μA  

## 主控芯片

**TPS63070** 2.5mm x 3mm QFN封装 ➡ [Datasheet](/Doc/Datasheet/)

## 硬件电路

**TPS63070** DCDC 低功耗高效电池稳压方案 ➡ [OSHWHub](https://oshwhub.com/c7h10n2/TPS63070)

## Overview

A low power, high efficiency lithium battery regulator solution based on the TPS63070 buck-boost converter
It is suitable for applications where the input voltage may be higher or lower than the output voltage. The output current can be up to 2A in boost or buck mode.
This buck-boost converter is based on a fixed frequency, pulse width modulated (PWM) controller that uses synchronous rectification to achieve maximum efficiency.
At low load currents, the converter enters power saving mode to maintain high efficiency over a wide load current range.

## Performance

- Input voltage range: 2.0V to 16V  
- Output voltage range: 2.5V to 9V (3.3V for this open source setting)  
- Up to 95% efficiency  
- DC accuracy of +/-1% in pulse width modulation (PWM) mode  
- DC accuracy of +3%/-1% in pulse frequency modulation (PFM) mode  
- Output current of 2A in buck mode  
- Output current in boost mode is 2A  
(VIN = 4V; Vout = 5V)  
- Device quiescent current typical value: 50μA  

## Control Chip

TPS63070 2.5mm x 3mm QFN package ➡ [Datasheet](/Doc/Datasheet/)

## Hardware Circuit

TPS63070 DCDC Low Power Efficient Battery Regulator Solution ➡ [OSHWHub](https://oshwhub.com/c7h10n2/TPS63070)


