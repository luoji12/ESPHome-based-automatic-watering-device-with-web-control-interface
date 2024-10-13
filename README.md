# ESPhome-based-automatic-irrigation-unit-with-web-interface

Project Overview
This project provides an ESPHome-based automatic irrigation system with a web control interface, allowing users to manage plant watering remotely. The system can automatically water plants based on soil moisture readings, and also supports manual and scheduled control.

Features
ESPHome Integration: Manage the firmware and device through ESPHome.
Automatic Irrigation: Automatically water plants based on soil moisture sensor readings.
Web Control Interface: User-friendly web interface for manual control and real-time monitoring.
Remote Monitoring: Check soil moisture levels and manage irrigation through the web interface.
Hardware Requirements
ESP32/ESP8266 board
Soil moisture sensor
Water pump and water supply system
Power supply
Installation Steps
Hardware Setup: Connect the soil moisture sensor, water pump, and other components to the ESP32/ESP8266 board following the hardware diagram.
ESPHome Configuration: Download the YAML configuration file provided in the repository and upload it to the ESP device using the ESPHome tool.
Web Control: Once configured, access the web control interface via the device’s IP address to manage watering.
Usage Instructions
Install ESPHome.
Clone this repository:
git clone https://github.com/luoji13/ESPHome-based-automatic-watering-device-with-web-control-interface
Edit the YAML configuration file as needed and upload it to your device:
esphome run your_config.yaml
Access the web control interface by entering the device’s IP address in a browser.
Notes
Ensure the device is connected to a stable WiFi network.
Periodically calibrate the soil moisture sensor to maintain accuracy.
Place the water pump in a sufficient water source to avoid dry running and potential damage.
License
This project is open-source under the MIT License, allowing free modification and distribution.
