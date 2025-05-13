# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32 WiFi Scan

## Purpose
This example demonstrates how to use the WiFi library to scan available WiFi networks and print the results. 

## Supported Targets

Currently this example supports the following targets.

| Supported Targets | ESP32 | ESP32-S2 | ESP32-C3 | ESP32-S3 | ESP32-C6 |
| ----------------- | ----- | -------- | -------- | -------- | -------- |


## How to Install Arduino IDE

* How to install the Arduino IDE: [Install Arduino IDE](https://github.com/espressif/arduino-esp32/tree/master/docs/arduino-ide).

#### Using Arduino IDE

* Before Compile/Verify, select the correct board: `Tools -> Board`.
* Select the COM port: `Tools -> Port: xxx` where the `xxx` is the detected COM port.

#### Using Platform IO

* Select the COM port: `Devices` or setting the `upload_port` option on the `platformio.ini` file.

## Log Output
5 networks found
Nr | SSID                             | RSSI | CH | Encryption
 1 | MyOptimum 2b18bf                 |  -66 |  1 | WPA2
 2 | MyAltice 08e9e1_EXT              |  -80 |  1 | WPA2
 3 | MyAltice 08e9e1                  |  -80 |  1 | WPA2
 4 | myoptimumOf145                   |  -88 |  1 | WPA2+WPA3
 5 | Verizon_YJ66JC                   |  -93 | 11 | WPA2

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)


## Steps I followed
Installed Arduino IDE (latest version).

Added ESP32 board URL to File > Preferences > Additional Board Manager URLs: 
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Opened Boards Manager, searched for ESP32, and installed the package.

Connected ESP32-CAM using USB/FTDI adapter.

Opened example from File > Examples > WiFi > WiFiScan.

Opened Serial Monitor at 115200 baud to read the ESP32 IP address.


## Problems
No problems encountered during setup or upload.


## Final Report
The scan was successful, identifying multiple networks.

