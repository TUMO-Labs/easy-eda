# Booster (33V → 5V) — Components

This README summarizes components from `BOM_booster_2026-05-04.csv`.
-
## Purpose

This booster converts the ESP32's 3.3V supply to a stable 5V rail required by the PMS5003 particulate sensor, allowing the sensor to operate while the ESP32 remains at 3.3V. It can also provide 5V to other peripherals that require it.

- **SS14** (Designator: `D1`) — Footprint: `SMA_L4.2-W2.6-LS5.0-RD_1` — Quantity: 1 — Supplier: LCSC (C2480) — https://item.szlcsc.com/datasheet/SS14/2857.html
- **ESP32-DEVKITC** (Designator: `ESP32`) — Footprint: `BULETM-SMD_ESP32-DEVKITC` — Quantity: 1 — Manufacturer: ESPRESSIF — Supplier: LCSC (C571180) — https://www.espressif.com.cn/zh-hans/products/devkits/esp32-devkitc
- **22uH Inductor** (Designator: `L1`) — Footprint: `IND-SMD_CYN5040-22UH` — Quantity: 1 — Supplier: LCSC (C2879700) — https://atta.szlcsc.com/upload/public/pdf/source/20250110/15C5F1CEE9A0C0D0826AFF692DB87906.pdf
- **PMS5003 header** (Designator: `PMS5003`) — Footprint: `HDR-F-2.54_1X8` — Quantity: 1 — Supplier: LCSC (C225505)
- **12uF capacitors** (Designators: `U1, U2`) — Footprint: `CAP-TH_L41.5-W24.0-P37.50-D1.2` — Quantity: 2 — Manufacturer part: `B32776T5126K000` (TDK) — Supplier: LCSC (C3785054) — https://www.tdk-electronics.tdk.com/inf/20/20/db/fc_2009/MKP_B32774_778.pdf
- **ME2108A50PG (regulator)** (Designator: unspecified) — Footprint: `SOT-89-3_L4.5-W2.5-P1.50-LS4.2-BR` — Quantity: 1 — Supplier: LCSC (C236798) — https://item.szlcsc.com/421845.html

Notes:
- Parts and supplier part numbers were taken from the BOM file. Use the designators when populating the PCB or ordering.
- Verify footprints and footprints' mounting style before ordering.


![alt text](<Screenshot 2026-05-04 at 00.36.18.png>)