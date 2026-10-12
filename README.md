# Starbie

A custom PCB project for a tiny interactive device that responds to movement.

---

## What exactly is it?

Starbie is a small interactive device built around the XIAO ESP32-C3. It uses a bunch of sensors and other components to make it actually do stuff.

Some of the things packed into it:

- Movement detection using the MPU6050.
- Temperature and humidity readings using the DHT11.
- An OLED display to show information.
- An RGB LED for visual feedback.
- Cherry MX switches for physical input.

## Why I built it

I wanted to make something cool with hardware and decided to try building my own custom PCB. I also wanted to learn more about how sensors, microcontrollers and firmware work together in an actual project.

Starbie is basically me experimenting with all of that in one board.

## The PCB Design

I designed the board using KiCad, with a custom shape and footprints for the components.

A look at the PCB layout.

![alt text](assests/image.png)

## Fabrication

The board is designed around the XIAO ESP32-C3, with connectors for the OLED and MPU6050 modules.

![alt text](assests\image copy.png)

## Firmware

The firmware will handle the sensor readings, display, RGB LED and button inputs.

Still working on getting everything together.

## Bill Of Materials

The main components are the XIAO ESP32-C3, DHT11, SSD1306 OLED, MPU6050, RGB LED, Cherry MX switches and the required resistors and connectors.

---

Still a work in progress. More soon.