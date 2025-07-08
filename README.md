# First-Arduino-Code
This Arduino sketch controls an LED connected to pin 13, creating a specific blinking pattern. The code is designed to run on an Arduino board (e.g., Arduino Uno) and uses the built-in LED for simplicity.
Functionality
- In the `setup()` function:
  - Pin 13 is configured as an output to control the LED.
- In the `loop()` function:
  - The LED to blink three times with a pattern: ON for  milliseconds and OFF for 500ms each time.
  - Followed by three longer blinks: ON for 100ms and OFF for 1000ms each time.
  - This sequence repeats indefinitely, creating a rhythmic blinking effect.

Hardware Requirements
- **Arduino Board**: Any Arduino with a digital pin 13 (e.g., Arduino Uno, Nano).
- **LED**: Uses the built-in LED on pin 13 (no external components required).

Usage
- Upload the sketch to your Arduino board using the Arduino IDE.
- The LED on pin 13 will start blinking in the described pattern immediately.

Notes
- The timing of the blinks is controlled by `delay()` functions, which pause the program for specified durations (in milliseconds).
- If using an external LED, connect it to pin 13 with a current-limiting resistor (e.g., 220Ω) and ground.

This description provides a clear overview of what the code does, the hardware needed, and how to use it, making it accessible to others viewing your GitHub repository. If you want to add more details 
