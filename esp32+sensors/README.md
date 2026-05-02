# ESP32 + Sensors — Components

This README lists components taken from `BOM_esp32+sensors_2026-05-02.csv`.

- **BME280** (Designator: `BME280`) — Footprint: `HDR-F-2.54_1X4` — Quantity: 1 — Supplier: LCSC (C225501)
- **ESP32-DEVKITC** (Designator: `ESP32`) — Footprint: `BULETM-SMD_ESP32-DEVKITC` — Quantity: 1 — Manufacturer: ESPRESSIF(乐鑫) — Supplier: LCSC (C571180) — https://www.espressif.com.cn/zh-hans/products/devkits/esp32-devkitc
- **PMS5003** (Designator: `PMS5003`) — Footprint: `HDR-F-2.54_1X8` — Quantity: 1 — Supplier: LCSC (C225505)
- **SD card header** (Designator: `SDCARD`) — Footprint: `HDR-F-2.54_1X6` — Quantity: 1 — Supplier: LCSC (C40877)

Notes:
- Source and part numbers come from the project's BOM file.
- Use the designators above when populating the PCB or ordering parts.
This project is a modular environmental monitoring station based on the ESP32 DevKitC.
It measures air quality using the PMS5003 (UART) and BME280 (I2C) sensors, and stores data on a MicroSD card (SPI).