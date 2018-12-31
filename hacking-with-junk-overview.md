# 2016 Hacking Course Ideas
    
## Course Names

- Coding the physical world.
- Computing with junk
- Tangible/digital bits

## Overview

This course will introduce students to the process of product
development afforded by the new generation of single-board computers
and prototyping boards that have become available. _mention IoT, Edge here_. 
Students will design a smart hardware device using a single-board computers (Raspberry Pi),
Arduino microcontrollers, sensors, and servos as the computing core of
their designs. They will create prototypes of their devices in
**maker-space style labs**, where they will rapidly sketch in hardware
using upcycled cardboard and other scavenged materials. Their designs
will bring computing power to bear on everyday problems like fitness,
health, home-automation, and emphasise the power of the maker to
create new forms of artistic expression and entertainment.

*Maybe make more of the "junk" aspect?*
*Maybe not make more of "junk" aspect---how would this fit into the learning outcomes?*

## Educational Outcomes

- Produce designs for physical computing devices including sensors,
  actuators, and internet connectivity.
- Produce software for microcontrollers and single-board Linux
  computers to control their device and connect to web-based services.
- Produce basic circuits to connect sensors and actuators to
  microcontrollers using breadboards or prototyping hardware.
- Explore ML inference and data science in low-power/real-time environments.
- Produce physical prototypes of devices using upcycled materials.
- Iteratively evaluate and refine prototype devices through a
user-centred design process.

## ACM/IEEE Bodies of Knowledge

### Core

- Systems (integrating hardware, software, network connectivity)
- Software Engineering (requirements gathering, stakeholder
  engagement, continuous evaluation & delivery)

### Electives

- HCI/New Interactive Technologies
- HCI/Design-oriented HCI
- HCI/Mixed, Augmented & Virtual Reality
- PBD/Mobile Platforms
- PBD/Cloud  (maybe spin up an AWS EC2 instance to talk to)

## Course Outline

_do this_


## Inspirational Project Ideas

- Controllers and Computing
    - [OneHand 20% Chording Keyboard](http://deskthority.net/workshop-f7/onehand-20-keyboard-t6617-120.html)
    - [Arduino Controlled Apple 1 Replica Computer](http://dave.cheney.net/2014/12/26/make-your-own-apple-1-replica)
- Health
    - [Multi-sensor data recorder](https://hackaday.io/project/1395-open-source-science-tricorder)
- Fitness
    - [Jacket/backpack-mounted LED display for cyclists/runners](http://www.wired.com/2010/09/cyclists-backpack-shows-led-turn-signals/)
- Art
    - [Button Grid Music Controller](http://flipmu.com/work/arduinome/)
    - [Programmable Effects Pedal](http://hackaday.com/2012/11/30/guitar-foot-controller-uses-dsp-for-audio-effects/)
    - [Hackable Digital Synthesiser](https://ccrma.stanford.edu/~eberdahl/Papers/NIME2014EmbeddedAcousticInstruments.pdf)
    - [Sound and Light Trail Makers](https://hackaday.io/project/157-center-flee)
- Bikes
- Environment
    - [Raspberry Pi night-vision camera](http://www.mcmelectronics.com/product/RASPBERRY-PI-/28-18030)
    - [Raspberry Pi baby monitor](https://www.raspberrypi.org/products/camera-module/)
- Fun
    - [Portable Games Console](https://youtu.be/zrEj1aQRbpw)
    - [Cuddly Companion Robot](http://www.nickstedman.com/art/adb.html)
- Home Automation
    - [Home RGB Lighting System]()

## Hardware kits

Each student should have a kit available for experiments in labs and
product designs.

### Raspberry Pi

Pros         | Cons
-------------|-------------------
Cheap        | high power
Well-known   | no wifi
audio onboard| no ethernet on Model A
video onboard| tricky to deal with GPIO
USB onboard  |no bluetooth
lots of GPIO |
lots of accessories |
available in large quantitites |

Test budget for one student:

- RPi 3B+ kit 100AUD

need some kind of multi-parts experimentation kit.

- Actuators: go with servos (connect straight to GPIO), not special HATs
- Sensors, need some arduinos, or ADCs on breakout boards, cheap on AliExpress/DFRobot
- Interfacing with PIR sensors etc, can we have a sponsor or commercial partner help with a big kit of sensors?
- What kind of boards to get? RPis are awesome, but so is coding straight on hardware on ESP32. Is there an ARM competitor with WiFi and bluetooth that could be good? For this course, should it be board-agnostic, or focussed on a single system?
- Good to include some ML ideas. Realistic in terms of real-world use, but also helps to make a case for research-led research.
