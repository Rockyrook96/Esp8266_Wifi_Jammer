# Esp8266_Wifi_Jammer
"An open-source ESP8266 Deauther project for testing Wi-Fi network security against deauthentication attacks. For educational and ethical pen-testing purposes only."

# Installation!

1 Download the desired bin file from this link[ Download here.](https://github.com/SpacehuhnTech/esp8266_deauther/releases)      
2 Flash the bin file onto the nodemcu using Nodemcu-flasher.

# ESP8266 Wi-Fi Deauther
GitHub Repository Documentation & Setup Guide

# Overview

The ESP8266 Deauther allows cybersecurity researchers and network administrators to perform
authorized penetration testing on 2.4 GHz Wi-Fi networks. By taking advantage of unencrypted
management frames in standard 802.11 networks, this tool can simulate disassociation and
deauthentication attacks to test client stability and Protected Management Frames (PMF)
configuration

# Key Features

* Deauth Attack: Transmit disassociation frames to selected clients or networks to test
disconnection behavior.
* Beacon Attack: Generate custom Wi-Fi access point beacons for network traffic testing.
* Probe Request Attack: Send probe requests to test client-side AP detection mechanisms.
* Web Interface: Built-in web server interface accessible directly from any browser for simple
management.

# Hardware & System Requirements

* Hardware NodeMCU v2 / v3 (ESP8266-12E) Development Board
* Connection Micro-USB Cable (Data transfer capable)
* Software Arduino IDE (v1.8.x or later)
* Core ESP8266 Board Package for Arduino

  # Installation & Flashing Guide

1. Open Arduino IDE and navigate to File > Preferences.
2. Add the ESP8266 board manager URL:
           https://arduino.esp8266.com/stable/package_esp8266com_index.json
3. Open Tools > Board > Boards Manager, search for esp8266, and click Install.
4. Select board: Tools > Board > ESP8266 Boards > NodeMCU 1.0 (ESP-12E Module).
5. Connect your NodeMCU board, select the correct Port, and click Upload.

# Usage Instructions

1. Power on the ESP8266 module via USB.
2. Connect to the Wi-Fi AP created by the device (Default SSID: pwned / Password: deauther).
3. Open a browser and navigate to http://192.168.4.1 to access the web panel.
4. Perform a scan, select target access points or clients, and execute required testing modules

# Legal & Ethical Disclaimer

 Warning: This project is created strictly for educational, research, and authorized penetration testing
purposes. Executing deauthentication attacks on wireless networks without explicit prior permission from
the network owner is illegal in most jurisdictions. The author assumes no responsibility for unauthorized
or illegal use of this software
   
