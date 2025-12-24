# Smart Traffic Light System

## Overview
This project aims to address traffic congestion challenges in India by implementing an AI-based Smart Traffic Light System. The system uses computer-vision techniques — particularly object detection with YOLOv5 — along with IoT components (Arduino UNO + LEDs) to dynamically control traffic signals based on real-time vehicle density.

The objective is to intelligently redirect traffic flow depending on the number of vehicles present in each lane, with future enhancements planned for identifying emergency vehicles such as ambulances.
## Features
-Real-time vehicle detection using YOLOv5
-Tracking algorithm to monitor vehicle movement
-Automated traffic-signal switching based on traffic density
-Arduino-based LED traffic-light control
-Two-lane adaptive traffic monitoring
-Designed for highly congested urban roads

## Project Highlights
-Developed as an applied AI + IoT project
-Focused on solving real-world traffic congestion problems
-Demonstrates practical integration of Machine Learning & embedded systems
-Built using Python, OpenCV, PyTorch & Arduino hardware

## How It Works
1.A camera continuously captures live traffic footage
2.YOLOv5 detects vehicles present in the frame
3.A tracking algorithm assigns IDs and counts vehicles
4.Traffic density per lane is calculated
5.Arduino LEDs simulate traffic-signal switching
6.Green-light duration is dynamically adjusted
7.This results in smarter signal timing instead of fixed-interval cycles.

## Usage
1.Install required Python dependencies such as OpenCV, NumPy & PyTorch
2.Connect Arduino UNO & LEDs for traffic-light simulation
3.Run the Python script: python smart_traffic_light.py
4.Watch the real-time AI-based traffic-control output

## Technology Stack

Python
YOLOv5
OpenCV
PyTorch
NumPy
Arduino UNO

## Future Enhancements
Automatic detection & priority handling for ambulances 🚑
Multi-lane expansion
Real-world deployment testing
Cloud-based monitoring dashboard


## Acknowledgments
Special thanks to my institute and faculty for guidance and support in exploring AI-based smart-city applications.



## Developer
Shravan Kumar
---

Feel free to modify the content as needed.