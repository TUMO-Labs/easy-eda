# LED Push Button PCB for Arduino UNO R3

## Overview

This project is a simple PCB circuit designed to light up an LED when a push button is pressed. The board is powered by an Arduino UNO (or compatible) via the +5V and GND pins.

## Features

- **LED Indicator:** Lights up only when the button is pressed.
- **Push Button:** Momentary tactile switch for user input.
- **Current Limiting Resistor:** Protects the LED from excessive current.
- **Arduino Power Input:** Uses +5V and GND from Arduino UNO header.

## Schematic Description

- **LED** and **resistor** are connected in series.
- **Push button** is placed in series with the LED and resistor, so pressing the button completes the circuit.
- **Power** is supplied from Arduino UNO header (+5V and GND).

## Components

| Reference | Value   | Description           |
|-----------|---------|-----------------------|
| LED1      | LED     | Red LED (0603 SMD)    |
| R1        | 1kΩ     | Resistor (0603 SMD)   |
| SW1       | Button  | Tactile Switch 6x6mm  |
| P1        | UNO_R3  | Arduino UNO header    |

## How It Works

- When the push button is **not pressed**, the circuit is open and the LED is off.
- When the push button is **pressed**, the circuit closes, allowing current to flow from +5V through the resistor and LED to GND, lighting up the LED.

## Usage

1. Connect the PCB to the Arduino UNO header (matching +5V and GND).
2. Press the push button to light up the LED.
3. Release the button to turn off the LED.

## Design Files

- Schematic: `SCH_led+button_2026-04-28.json`
- PCB Layout: `PCB_PCB_led+button_2_2026-04-28.json`

## Assembly Notes

- Ensure correct orientation of the LED (anode to +5V, cathode to GND).
- Use SMD components as specified for compact layout.
- Double-check button pinout before soldering.

## License

This project is open-source and free to use for educational and personal purposes.
