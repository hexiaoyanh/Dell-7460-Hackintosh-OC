# Change log

> 目前 OC 版本: `0.6.4`
> 系统版本: `macOS Big Sur(20C5061b)`

## 2020-12-11

- Change `csr-active-config`
- 添加`AirPortBrcm4360_Injector.kext`并限制最高内核`19.99.99`

## 2020-12-08

- 更新`OC`至`0.6.4`
- 更新`AirportBrcmFixup`至`2.1.2`
- 更新`AppleALC`至`1.5.5`
- 更新`HibernationFixup`至`1.3.8`
- 更新`Lilu`至`1.5.0`
- 更新`VirtualSMC`至`1.1.9`
- 更新`VoodooInput`至`1.0.9`
- 更新`VoodooPSController`至`2.1.9`
- 更新`WhateverGreen`至`1.4.5`

## 2020-12-7

- 更新`RealtekRTL8111`至`2.4.0d5`
- 删除`ProcessorType`以解决`CPU`型号识别错误的问题

## 2020-11-16

- 回滚`VoodooI2C`驱动至`2.4.4`版本,解决开不了机的问题

## 2020-11-15

- 删除`OC/Kexts`文件夹下没有使用的`VoodooI2C`驱动
