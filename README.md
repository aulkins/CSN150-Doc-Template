# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32 Introduction

## Purpose
Set up the ESP32-CAM and Arduino IDE environment. Execute both the WiFiScanner and CameraWebServer sketches to verify wireless connectivity and camera functionality. 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Video 1: 
Arduino Setup for ESP32: ESP32 Install Guide

##### Other Link: 
Video Guide: YouTube – ESP32-CAM Setup


## Steps I followed
Installed Arduino IDE (latest version).

Added ESP32 board URL to File > Preferences > Additional Board Manager URLs:
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Opened Boards Manager, searched for ESP32, and installed the package.

Connected ESP32-CAM using USB/FTDI adapter.

Selected board: AI Thinker ESP32-CAM under Tools > Board.

Opened CameraWebServer example from File > Examples > ESP32 > Camera > CameraWebServer.

Entered WiFi credentials (ssid, password) in the code.

Verified that CAMERA_MODEL_AI_THINKER was uncommented.

Uploaded the sketch.

Opened Serial Monitor at 115200 baud to read the ESP32 IP address.

Entered the IP address in a browser — the camera stream loaded successfully.

## Problems
No problems encountered during setup or upload.


## Final Report
Arduino IDE and ESP32-CAM were set up without any issues.
