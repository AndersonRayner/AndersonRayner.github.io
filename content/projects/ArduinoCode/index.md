---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Arduino Software"
summary: "A collection of Arduino drivers and utilities"
authors: []
tags: [code]
categories: []
date: 2020-05-09T18:56:00-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://andersonrayner.github.io/project/arduinocode/"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: "example"
---

A collection of Arduino drivers and software for random projects I've built over the years.
The quality and utility of them varies, but hopefully others will find them useful in the future.
Some of the code is written to be used with Platform I/O, but it should be easy enough to convert over to use the standard Arduino IDE.

Libraries
- [Heartbeat LED Class](https://github.com/AndersonRayner/arduino_heartbeat)
- [PID Controller Class](https://github.com/AndersonRayner/arduino_pid)
- [2-Pin Encoder Class](https://github.com/AndersonRayner/arduino_2pin_encoder)
- [MAVLINK-Arduino Interface Class](https://github.com/AndersonRayner/arduino_mavlink)

Drivers
- [Maxbotix I2C Sonar Driver](https://github.com/AndersonRayner/arduino_maxbotix_i2c)
- [AMT20 Absolute Encoder Driver](https://github.com/AndersonRayner/arduino_AMT20)
- [SprintIR-CO2 Sensor Driver](https://github.com/AndersonRayner/arduino_SprintIR-CO2-Sensor)
- [K30-CO2 Sensor Driver](https://github.com/AndersonRayner/arduino_K30-CO2-Sensor)
- [Pololu Simple Motor Controller G2 Arduino Driver](https://github.com/AndersonRayner/arduino_pololu_simple_motor_controller_g2)
- [Benewake LiDAR CAN Driver](https://github.com/AndersonRayner/arduino_Benewake_LIDAR_Library)
- [MAX1035 4-Channel ADC](https://github.com/AndersonRayner/MAX1035)

Debug Code
- [Debug Software for External Bluetooth Modules (HC-05)](https://github.com/AndersonRayner/arduino_bluetooth_tests)
