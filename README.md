# Thunder Pack

<img src="https://cdn.hackaday.io/images/5175201571795557825.JPG" alt="ThunderPack Board" width="500" />

A kick-ass microcontroller board with everything you need in a compact package that fits in your pocket. Integrated battery, power management system, Arm microcontroller, USB bootloader, 4 high-power PWM outputs, and 12 GPIOs.

Why? After years of wiring together portable LED controllers that all consisted of a lithum batter, charge controller, power switch, and an arduino nano (or similar), I wanted something better. I always found those versions to be janky and fragile -- not to mention concerned that damaging the pouch cell battery might make it explode! This board has everything I need with room to expand.

* [Overview](https://github.com/jgillick/ThunderPack/wiki/)
* [Getting started](https://github.com/jgillick/ThunderPack/wiki/Getting-Started)
* [Pins & functions](https://github.com/jgillick/ThunderPack/wiki/Pinout-Details)
* [History & build log](https://hackaday.io/project/161054-lit-fist)

## Features

* Ultra-low-power 32-bit microcontroller ([STM32L072xx](https://www.st.com/resource/en/datasheet/stm32l072v8.pdf))
* Integrated high-capacity 18650 lithium battery
* 4 high-current PWM outputs (2.3A per channel!) with an LED on each for debugging.
* 12 GPIOs, USART, I2C, SPI, USB
* 6k EEPROM
* USB bootloader
* Tactile on/off switch
* Tactile user button with built-in debounce circuit
* Breadboard friendly
* Durable [AF](https://www.urbandictionary.com/define.php?term=af)! (Put a tube of heat shrink around it for a super easy case, if you'd like.)

<img src="./images/breadboard.jpg" alt="On the breadboard" width="400" />

_Breadboard friendly_

## Board & Pinout

<img src="./images/pinout.svg" alt="Pinout diagram" />

[See the full list of pins and details.](https://github.com/jgillick/ThunderPack/wiki/Pinout-Details)
