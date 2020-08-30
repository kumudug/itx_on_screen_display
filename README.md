# itx_on_screen_display
OSD for a mini itx desktop using raspberry pi

![project img](pi_project.png)

## Purpose
The purpose of this project is to build a on screen display that can be mounted to a mini itx pc. 

## Features
1. Addressable RGB strip 
1.1 Will be used to display temperature, humidity inside the case
2. SPI OLED display
2.1 Used to display various stats 
2.2 Temperature (Gathered using a temperature sensor connected to raspberry pi
2.3 CPU, Mem, AIO temps gathered using a collectd service running on the pi
2.4 CPU, Mem usage gathered using a collectd service running on the pi

## Tech Stack
