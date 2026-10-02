# aurdino-p-1
traffic light 
# Arduino Traffic Light System 🚦

A simple traffic light built with Arduino Uno and 3 LEDs.

## What it does
Red (2s) → Green (2s) → Yellow (1s), repeating forever.
Only one LED is ON at a time.

## Components
- Arduino Uno
- 3 LEDs (red, yellow, green)
- 3 x 220 Ω resistors
- Breadboard + jumper wires

## Pin connections
| LED    | Arduino Pin |
|--------|-------------|
| Red    | 2          |
| Yellow | 3          |
| Green  | 4         |

Each LED's long leg goes via a 220 Ω resistor to the pin, short leg to GND.

## Code
See `traffic_light.ino`


## What I learned
- Using pinMode(), digitalWrite(), delay()
- Why LEDs need current-limiting resistors
