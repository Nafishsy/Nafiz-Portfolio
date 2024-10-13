---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Fire Detection and Alert System"
summary: "This Arduino-based project detects fire using LM35 temperature and MQ-2 smoke sensors. It sends SMS alerts with GPS coordinates via a GSM module, activates alarms, and displays real-time status on an LCD screen."
authors: []
tags: [Arduino, ES, Fire Detection, IoT]
categories: []
date: 2022-12-01

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/Nafishsy/Fire-Detection-and-Alert-System"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### Features:
- Detects fire based on temperature and smoke levels.
- Alerts through visual indicators (LEDs) and an audible alarm (speaker).
- Sends SMS alerts with GPS location to pre-configured phone numbers.
- Displays real-time status on an LCD.
- Servo motor control for additional physical responses (e.g., unlocking emergency exits).

### Components:
- Arduino (UNO or similar)
- LM35 temperature sensor
- MQ-2 smoke sensor
- Servo motor
- 16x2 LCD display
- GPS module (TinyGPS library used)
- GSM module for SMS alerts
- LED indicators (Red, Yellow)
- Buzzer/Speaker
- Relay module
- Jumper wires
- Breadboard or custom PCB
