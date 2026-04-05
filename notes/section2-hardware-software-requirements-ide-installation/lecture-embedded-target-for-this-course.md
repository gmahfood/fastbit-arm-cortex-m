# Lecture
# Embedded Target Used in this Course

**Date** 4 Apr 2026

---

## Key Concepts

### In this course, the STM32F407VGT6 MCU based discovery board is used as the target. I purchased the "EC Buying STM32F407VET6 Development Board" from Amazon to follow along as closely as possible.
[EC Buying STM32F407VET6 Core Board System Board Main Frequency 168M 512K ROM 192K RAM STM32 Development Board 74 IO 3.3V 500mA Lite Version STM32F407 Board](https://www.amazon.com/dp/B0F28NF9ZG?ref=ppx_yo2ov_dt_b_fed_asin_title)

---

## Notes

![[stm32-nucleo-board.jpeg|299]]

- The STM32F407VGT6 is an ARM Cortex-M4 (Processor) based microcontroller with a maximum clock speed of 168 MHz, 512 KB of flash memory, and 192 KB of RAM. 
- It has a wide range of peripherals, including GPIO, USART, SPI, I2C, ADC, DAC, timers, and more.
	- The board includes an onboard **ST-LINK/V2-A** debugger/programmer, which allows for easy programming and debugging of the microcontroller (Important feature). 
	- It also has a USB interface for power and communication, as well as a variety of headers for connecting external components and sensors.
	- Plenty of IO pins or also called external interfacing headers (IO headers)
- 8 megahertz (MHz) crystal oscillator to supply clock to the microcontroller.
- When installing STM32CubeIDE the driver for this programmer and debugger will be installed automatically. 
	- If need be the the drivers can be downloaded from ST's website
- Will need to procure a USB type A to Mini Type B cable, in my case a USB C to USB C. 



---

## Code Snippets
```c
// paste any important code here
```

---

## Questions / Things to Revisit

- [ ] Where to connect USB, in the lecture there were two ports and the one with some buttons next to the USB port were not used in the course.
- [ ] How does my STM32 compare to this older model?

---

## Summary

### The course uses the STM32F407VGT6 Discovery board as its target hardware. It's an ARM Cortex-M4 running at up to 168 MHz with 512 KB of flash and 192 KB of RAM, packed with peripherals including GPIO, USART, SPI, I2C, ADC, DAC, and timers. The board includes an onboard ST-LINK/V2-A debugger that installs automatically with STM32CubeIDE, making programming and debugging straightforward. I purchased a compatible Amazon alternative and will need a USB-C to USB-A cable to connect it.

