# ESP32-S3 Pin Planner

An interactive static web tool for planning and tracking GPIO usage on ESP32-S3 development boards.

Designed originally to help allocate pins for embedded projects (CNC controllers, pendants, displays, keypads, encoders, etc.) and visually see what’s free, used, risky or reserved.

---

## 🌐 Live Demo

👉 https://festivejelly.github.io/ESP32PinPlanner/

(Will become active once GitHub Pages is enabled)

---

## ✨ Features

- Visual left/right header layout
- Click pins to mark as:
  - 🟢 Used  
  - 🟠 Caution (strap / USB / JTAG etc.)
  - 🔴 Reserved  
- Hover tooltips explaining risky pins
- Live lists of Used / Unused / Caution / Reserved
- Copy lists to clipboard
- Fully static (no backend required)
- Easy to extend via JSON board definitions later

---

## 🎯 Purpose

ESP32 boards have many multifunction pins and several that can cause boot or USB issues if reused incorrectly.  
This tool helps prevent:

- Accidental use of strapping pins  
- Conflicts with USB or JTAG  
- Losing track of GPIO allocation in larger projects  
- Trial-and-error wiring mistakes  

---

## 🔧 Future Ideas

- Multiple board profiles via JSON
- Peripheral-aware pin suggestions (I2C, SPI, UART, encoders)
- Conflict detection
- Save/load named pin configurations
- Export project pin maps

---

## 📜 License

MIT — free to use and modify.
