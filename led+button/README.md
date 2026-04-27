# LED Push Button PCB

## Overview

This project is a simple PCB circuit that lights up an LED when a push button is pressed. It is designed for educational purposes, prototyping, and basic electronics testing.

## Features

- **LED Indicator:** Lights up when the button is pressed.
- **Push Button:** Momentary tactile switch for user input.
- **Current Limiting Resistor:** Protects the LED from excessive current.
- **Power Input:** Operates from a +5V power supply.

## Schematic Description

- **LED:** Connected in series with a resistor and push button.
- **Resistor (R1):** 1kΩ, limits current to the LED.
- **Push Button (SW1):** 6x6mm tactile switch, closes the circuit when pressed.
- **Power:** +5V and GND are used as power rails.

## Components

| Reference | Value   | Description           |
|-----------|---------|-----------------------|
| LED1      | LED     | Red LED (0603 SMD)    |
| R1        | 1kΩ     | Resistor (0603 SMD)   |
| SW1       | Button  | Tactile Switch 6x6mm  |
| +5V       |         | Power Supply          |
| GND       |         | Ground                |

## How It Works

- When the push button is **not pressed**, the circuit is open and the LED is off.
- When the push button is **pressed**, the circuit closes, allowing current to flow from +5V through the resistor and LED to GND, lighting up the LED.

## Usage

1. Connect the PCB to a +5V power supply.
2. Press the push button to light up the LED.
3. Release the button to turn off the LED.

## Design Files

- Schematic: `SCH_led+button_2026-04-27.json`
- PCB Layout: `PCB_PCB_led+button_2026-04-27.json`

## Assembly Notes

- Ensure correct orientation of the LED (anode to +5V, cathode to GND).
- Use SMD components as specified for compact layout.
- Double-check button pinout before soldering.

## License

This project is open-source and free to use for educational and personal purposes.

---
