---
title: "Smart Surveillance System"
description: "A smart surveillance system that could be used to recognize registered people on the system, detect how many people are there, or to monitor for suspicious or unknown people in a certain area."
dateString: April 2024 - September 2024
draft: false
tags: ["C++", "face-detection", "face-recognition", "OOP", "OpenCV"]
showToc: false
weight: 301
cover:
    image: "projects/smart-surveillance-system/smart-surveillance-system.png"
---

The system has been built in C++ using [OpenCV 4.9](https://github.com/opencv/opencv) along with a header-only library for the GUI called [cvui 2.7](https://github.com/Dovyski/cvui). It utilizes the [Viola–Jones](https://en.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework) algorithm for the facial detection. Additionally, it utilizes the [Eigenfaces](https://en.wikipedia.org/wiki/Eigenface) algorithm for facial recognition. The image processing runs on the CPU.

## Features

Some of the features currently implemented are: 

- Detecting faces.
- Recognizing registered faces.
- Information panel for keeping track of currently detected people in the frame.
- Options for enabling/disabling the webcam and the FPS counter.
- Adding people to the system.
- Removing people from the system.

## Project Link

For the complete project and details, check it out on [GitHub](https://github.com/kareem-ghazi/smart-surveillance-system)!