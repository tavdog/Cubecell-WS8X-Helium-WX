
# Helium WS85 WX

<img width="834" alt="Screenshot 2025-03-19 at 4 53 52 PM" src="https://github.com/user-attachments/assets/ae234304-c6d3-4232-9f90-df9a4d58c139" />

## Overview  
This repository contains a **basic example** of a **WisBlock/Helium** embedded project using **PlatformIO** as the development environment instead of the Arduino IDE.  

This project joins the **Helium network** and periodically transmits **weather (WX) data** from a **WS85/WS80 serial output** to the **Helium network**.  

The build setup is based on the heltec Cubecell
and the code is based on https://github.com/helium/longfi-platformio/tree/master/RAKWireless-WisBlock/examples/LoRaWan_OTAA

### Hardware
The only hardware required is:
* Heltec Cubecell
* WS85 Weather station from Ecowitt (follow this hackaday article for how to modify the station to enable serial output [WS85 Mod](https://hackaday.io/project/196990-meshtastic-ultrasonic-anemometer-wx-station) )
* A Harbor Breeze solar led lamp https://hackaday.io/project/194509-harbor-breeze-mesh-node-hack

#### Antenna Type/location
The transmit antenna can left inside the solar enclosure out secured outside for slightly better range. 
<img width="541" alt="Screenshot 2025-03-19 at 4 50 39 PM" src="https://github.com/user-attachments/assets/bd7be7ab-d512-480e-9969-85c8ac52fb5f" />


