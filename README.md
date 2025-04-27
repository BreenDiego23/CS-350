# CS 350 Portfolio Submission

This repository contains selected project artifacts from CS 350: Emerging Systems Architectures and Technologies. These projects demonstrate my ability to interface software with hardware components, manage real-time system behavior using state machines, and create maintainable, adaptable solutions.

## Project 1: Morse Code LED Controller (Milestone 3)

**Summary:**  
This project involved programming a Raspberry Pi to control two LEDs that blink Morse code signals ("SOS" and "OK") while using a 16x2 LCD display to show the active message. Button inputs allowed switching between messages, and the project required building a reliable state machine to control system behavior.

**What I did particularly well:**  
I created a clean and logical state machine that handled button presses smoothly without crashing the system, even under rapid input. I also made sure the timing for the LED blinks matched Morse code patterns accurately.

**Where I could improve:**  
I could improve the project by adding non-blocking delay techniques, such as threading or asynchronous programming, to make the system even more responsive.

**What tools and/or resources are you adding to your support network?:**  
I learned to use the GPIO Zero and RPi.GPIO Python libraries more effectively. I also added online resources like Raspberry Pi forums, Python official documentation, and GPIO programming tutorials to my toolkit for future projects.

**What skills from this project will be particularly transferable to other projects and/or coursework?:**  
Skills like building and organizing state machines, handling hardware inputs, debouncing buttons, and working with GPIO pins are all highly transferable to future embedded systems, IoT devices, and real-time control projects.

**How did you make this project maintainable, readable, and adaptable?:**  
I broke the code into well-defined functions, used meaningful variable names, added comments to describe key logic areas, and designed the state machine in a way that would make it easy to add more messages or devices if needed.

---

## Project 2: Thermostat State Machine (Final Project)

**Summary:**  
In this project, I created a smart thermostat simulation using a Raspberry Pi, a temperature and humidity sensor, and a 16x2 LCD screen. The program read real-time temperature data, displayed it to the user, and controlled red and blue LEDs to simulate heating or cooling based on predefined temperature thresholds. Button inputs allowed switching between Fahrenheit and Celsius displays.

**What I did particularly well:**  
I successfully integrated hardware components like the DHT11 sensor and LCD with a Python state machine that kept the system organized and predictable. I also made the user interface clear and informative through the LCD display.

**Where I could improve:**  
I could improve the thermostat's logic by dynamically adjusting the heating and cooling thresholds based on historical readings or environmental factors instead of using static threshold values.

**What tools and/or resources are you adding to your support network?:**  
I learned to use the Adafruit DHT sensor Python library and expanded my knowledge of LCD display wiring and programming. I also practiced troubleshooting hardware issues using Raspberry Pi community resources.

**What skills from this project will be particularly transferable to other projects and/or coursework?:**  
This project helped me strengthen my skills in sensor integration, real-time data handling, user feedback design, and developing scalable state machines — all valuable for embedded systems design, IoT development, and advanced programming work.

**How did you make this project maintainable, readable, and adaptable?:**  
I organized the code into clearly separated sections, wrote reusable functions, used comments to document my design decisions, and created flexible logic that could easily accommodate additional features like fan control or smartphone connectivity in future versions.

---
