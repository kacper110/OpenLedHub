# OpenLedHub
Open source led controller based on the rp2350 with an esp32
Note:if you are reading this line, that means this is not even in a working beta

Hello, this is my led controller based on the new rp2350B chip. It has emmc pads for storing effects, you can also use an sd card instead of the emmc by ignoring the emmc pads and soldering an sd card slot to the sd pads, the emmc is bga153. the features include:

Mobile app(WIP) that uses bluetooth or wifi to communicate with the controller's onboard esp32
dual channel neopixels
RS485 for custom addons or DMX
8 line level audio input channels
Fully customizable led effects
USB-C for easy programming of both the rp2350 and esp32
ch340 or ft232 usb uart for the esp32 programming
onboard usb hub-one cable to program both mcu's!
up to 16 pwm led channels(depends on how many mosfets are populated)
