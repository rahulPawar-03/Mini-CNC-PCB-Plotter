# Mini CNC PCB Plotter Using Arduino Uno

This project demonstrates the design and development of a low-cost, portable, and compact CNC PCB plotter using Arduino Uno. The plotter is capable of engraving custom-designed printed circuit boards (PCBs) and also supports functionalities such as sketching, laser engraving, and wood carving.

The system integrates stepper motors salvaged from DVD/CD drives, a CNC shield, and A4988 drivers to move across the X, Y, and Z axes with precision. The software stack includes Inkscape for converting images to G-code, and GRBL firmware to control the motion of the machine.

## 🔧 Features

* Compact and affordable CNC plotter
* 3-axis control (X, Y, Z)
* Printing area of 4x4 cm
* G-code interpretation via GRBL
* Inkscape integration for design-to-G-code conversion
* Supports multiple tools: pen, laser, engraving bit
* Designed with sustainability (reused components) and education in mind

## 🎯 Objectives

* Design and fabricate a low-cost CNC PCB plotter for personal and educational use
* Enable in-house PCB prototyping to avoid costly fabrication services
* Provide flexibility to adapt the machine for multiple fabrication tasks

## 🧰 Hardware Used

* Arduino Uno
* CNC Shield
* A4988 Stepper Motor Drivers
* Stepper Motors (from CD/DVD drives)
* 12V DC Motor
* Servo Motor
* Jumper Wires and PCB base

## 💻 Software Used

* Arduino IDE (for firmware)
* Inkscape (for vector to G-code conversion)
* GRBL Firmware
* GRBL Controller/Universal G-code Sender

## 📐 System Design

The system takes a user-supplied vector image, converts it to G-code using Inkscape, and sends it to the Arduino-controlled machine. GRBL interprets G-code and controls the motion across X, Y, and Z axes to engrave or draw the design on the surface.

## 📈 Advantages

* Cost-effective and reliable
* Easy to assemble and maintain
* Suitable for students, hobbyists, and small-scale manufacturers
* Portable and user-friendly

## ⚠️ Limitations

* Small work area (4x4 cm)
* Limited material compatibility
* Basic automation level

## 🔮 Future Scope

* Wireless (Bluetooth/WiFi) control
* Integration with cloud-based G-code generation
* Expandable workspace
* Auto soldering and PCB component planting
