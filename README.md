# OmniRemote
Control your 3D printer on Octoprint with a tiny handheld remote

This repository contains the OmniRemote OTA Firmware. It will securely install the latest version of OmniRemote.

## Installation ##

1. Prior to uploading this, you must modify the "License Key" with yours as needed. If you do not have a license key, sign up for free at: https://gyropalm.com/omniremote/signup.php

2. Also you will need to modify the WiFi SSID and password to match your network.

3. You will need Arduino IDE v1.6.8 or newer to upload this firmware. You will need to install the board profile for M5StickC. If you do not have that, please add the following URL in your references and search for **ESP32** under your "Boards Manager".

	[https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json](https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json")

	Once you have the board and COM port selected, upload your final code.

4. After the OTA process, please navigate to the **Settings** page by double-clicking the main big button. Click on **WiFi Config**, connect your computer's WiFi to **OmniRemote**, and point your browser to **192.168.4.1** to complete the process.

	To complete this step, you will need to know the IP address of your OctoPrint server. Also you will need to get the API key for OctoPrint through its **Settings -> API** page.

## Usage ##

- Double-click the **main button** to switch between pages
- Single press the **main button** to select an item from the menu
- Single press the **right-button** to scroll down the menu
- Double-click the **right-button** to scroll up the menu