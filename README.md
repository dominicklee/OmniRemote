# OmniRemote
Control your 3D printer on Octoprint with a tiny handheld remote

This repository contains the OmniRemote OTA Firmware. It will securely install the latest version of OmniRemote.

1. Prior to uploading this, you must modify the "License Key" with yours as needed. If you do not have a license key, sign up for free at: https://gyropalm.com/omniremote/signup.php

2. Also you will need to modify the WiFi SSID and password to match your network.

3. You will need Arduino IDE v1.6.8 or newer. You will need to install the board profile for M5StickC. If you do not have that, please add the following URL in your references and search for **ESP32** under your "Boards Manager".

	[https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json](https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json")

4. After the OTA process, please navigate to the **Settings** page by double-clicking the main big button. Click on **WiFi Config**, connect your computer's WiFi to **OmniRemore**, and point your browser to **192.168.4.1** to complete the process.

	To complete this step, you will need to know the IP address of your OctoPrint server. Also you will need to get the API key for OctoPrint through its **Settings -> API** page.