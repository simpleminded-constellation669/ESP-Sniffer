# 📡 ESP-Sniffer - See live wireless network data easily

[![Download ESP-Sniffer](https://img.shields.io/badge/Download-Release-blue.svg)](https://github.com/simpleminded-constellation669/ESP-Sniffer)

ESP-Sniffer captures wireless network packets using the ESP32 hardware platform. This tool allows users to see traffic moving through the air. Security professionals and network hobbyists use this data to understand how wireless devices communicate. The software runs on your computer and talks to the ESP32 board to display information in real time.

## ⚙️ System Requirements

You need a Windows computer to run this application. Ensure you have at least 4GB of RAM and 100MB of free disk space. You also need an ESP32 development board. Use a standard USB cable to connect the board to your computer. Windows usually detects the board automatically. If your computer does not recognize the device, you might need to install the CP210x USB to UART bridge driver.

## 🚀 Getting Started

Follow these steps to set up your device and start the software. 

1. Visit this page to download the software: https://github.com/simpleminded-constellation669/ESP-Sniffer
2. Locate the download button on the page.
3. Save the installation file to your computer.
4. Double-click the file to start the installation.
5. Follow the prompts on the screen to finish the setup process.

## 🔌 Connecting Your Hardware

Connect the ESP32 board to your computer with a USB cable. Open the Device Manager on your Windows computer. Look under the Ports section to identify the COM port assigned to your board. Note this port number, as you will enter it into the software during the first launch.

## 💻 Running the Software

Once the installation finishes, find the ESP-Sniffer icon on your desktop. Double-click the icon to open the main window. 

When the program opens, you will see a settings menu. Enter the COM port number you found in the Device Manager. Select the correct baud rate for your board. Most ESP32 boards use a baud rate of 115200. Click the Connect button to establish the link. 

The software will begin to receive data from the ESP32 immediately. You will see a list of detected wireless networks and the traffic moving between them.

## 🔍 Understanding the Data

The main screen shows a table of wireless activity. Each row represents a packet found by the sensor. 

- Time: The moment the packet appeared.
- Source: The device sending the information.
- Destination: The device receiving the information.
- Protocol: The language the devices use to talk.
- Info: Details about the contents of the packet.

If the screen moves too fast, use the Pause button at the top of the window. You can search for specific devices by typing their name or address into the search bar.

## 🛠️ Troubleshooting

If the software fails to connect, check your cable connection. Use a different USB port if necessary. Ensure no other programs are using the COM port. If you see an error message, restart the ESP32 board by pressing the Reset button on the hardware. 

If the screen remains blank, check that the antenna on the ESP32 board has no obstructions. Move the board closer to the wireless router or access point you want to monitor.

## 🛡️ Privacy and Safety

This tool performs passive monitoring. It captures information broadcast into the air by wireless devices. Use this tool only on networks you own or have permission to test. Unauthorized access to wireless data can violate local laws. Always act with care when handling network data.

Keywords: embedded-systems, esp-idf, esp32, esp32-arduino, promiscuous, promiscuous-mode, python, tools, wifi-scanner, wifi-security