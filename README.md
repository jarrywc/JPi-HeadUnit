# JPi-HeadUnit
Implementing computer vision for person &amp; animal detection using HDMI capture card (webcam compatible) &amp; coral tpu on B-Key &amp; Carplay on Raspberry Pi 5

# Features

## Touchscreen with Raspbian OS

### Software
**Description**
Provides an interface for user to control & use the connected phone, music, temperature, & rear camera.

**Requirements**
- Python 3.9 (Compatibility needed for Tensorflow Lite with Coral AI)
- Raspbian OS (based on )

### Parts

**Electronic**

*Compute*
- Single Board Computer
  - [Raspberry Pi 4 (8gb)](https://www.raspberrypi.com/products/raspberry-pi-4/)

*Output Vision*
- Display - [waveshare 10.4inch](https://www.waveshare.com/10.4hp-capqled.htm)

*Steering Wheel Control*
- [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/)

Repo: [JPiPico-Car-AC-Control](https://github.com/jarrywc/JPiPico-Car-AC-Control)

**Mounts & Fixtures**


**Cables & Wiring**


### Resources

## Rear Camera Object Recognition
### Software
**Description**
Using wide angle camera in rear of vehicle to detect safety conditions



### Electronic Parts

**Compute**
- AI Compute
  - [USB Coral Accelerator](https://coral.ai/products/accelerator/)

**Input Vision**
- High FPS Wide Angle Camera (120 Degree, 90 FPS, Global Shutter) [ELP High Speed Wide Angle Global Shutter USB Camera Module](https://www.amazon.com/dp/B0C3C2YVK9?ref=ppx_yo2ov_dt_b_product_details&th=1)

**Audio**
- Audio Digital Analog Converter - [Raspberry Pi HiFi DAC Pro Hat ES9038Q2M Audio Card PCM DSD Lossless High Resolution Digital-to-Analog Converter Adapter](https://www.inno-maker.com/product/hifi-dac-pro/)


### Resources


## Temperature

**A/C Control**
- [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/)
- Transistor 

Repo: [JPiPico-Car-AC-Control](https://github.com/jarrywc/JPiPico-Car-AC-Control)

**Front Seats Temperature Control**
- [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/)
- 3.3V Relay

## Phone Connectivity -> Carplay & Android Auto
- Carlinkit [CarlinKit CarPlay Dongle only for Car with Android Head Unit System 4.4.0+](https://www.amazon.com/gp/product/B09ZQJXWVW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)
- Lightning Cable or USB-C Cable

# Tools & Equipment