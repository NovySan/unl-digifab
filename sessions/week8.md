# Week 8 - Microcontrollers and Digital I/O

## Agenda
- Check In
  - Show and Tell
  - Project 1 Check In
  - Fabrication Questions
- [Arduino Intro](#arduino-intro)
- [Code Basics](#code-basics)
- [Activities](#activities)
  - [Blink](#blink)
  - [Digital Input](#digital-input)
  - [Digital Output](#digital-output)
- [Homework](#homework)

## Arduino Intro
Arduino 1: Intro and Digital Input/Output. ([slides](https://docs.google.com/presentation/d/1MCeMUA2qPpZfLuKuGprEjDnPsyBjrhgGWWYNJiq0oLI/edit?usp=sharing))

## Code Basics
- `setup()` - runs once, like `setup()` in processing. [reference](https://www.arduino.cc/reference/en/language/structure/sketch/setup/)
- `loop()` - runs repeatedly, like `draw()` in processing. [reference](https://www.arduino.cc/reference/en/language/structure/sketch/loop/)
- `pinMode()` - tell the arduino whether to use a pin as an input, an output, or the other things it can do (more later on that). [reference](https://www.arduino.cc/reference/en/language/functions/digital-io/pinmode/)
- `digitalRead()` - reads the input on a digital pin. [reference](https://www.arduino.cc/reference/en/language/functions/digital-io/digitalread/)
- `digitalWrite()` - sets the output on a digital pin. [reference](https://www.arduino.cc/reference/en/language/functions/digital-io/digitalwrite/)

## Blink
The hello world of arduino. By default, the arduino will blink a built-in LED ("L"), next to the RX, TX, and POW lights.
- Schematic:
  - (no schematic needed, we will use the built in LED on the Arduino nano)
  - The built-in LED is attached internally to pin 13 on the arduino `LED_BUILTIN`. (see [constants](https://www.arduino.cc/reference/en/language/variables/constants/constants) in reference)
- Code: 
  - **File->Examples->01.Basics->Blink.ino**
- Behavior:
  - we will see the LED blinkin on for 1000 milliseconds, and then off for 1000 milliseconds.

### Delay and digitalWrite

Experiment with delays and digitalWrite

## Digital Output
Let's wire up our own LED attached to a different pin.
- Schematic
  - wire up an LED and resistor to a different pin on the arduino, say `D2`. 
  - we need one resistor (10k)
  - one LED (red?)
- Code
  - Make a copy of your Blink code from above. 
  - we need to change the line in `setup()` where the `pinMode()` is declared. Change `LED_BUILTIN` to the 

## Digital Input
- Schematic
- Code

## Homework
- Meaningful Signal

## Office Hours 
- Immediately after class. 
- or, contact me online
  
## Reference
__Arduino__

<img src="https://user-images.githubusercontent.com/1598545/137305695-2d5a0bbc-37c9-43ad-9d26-435b2782f24b.png" width=400>

__Breadboard__

<img src="https://user-images.githubusercontent.com/1598545/137305908-31ef631b-e085-44bf-b058-f9cb3bc7a368.png" width=400>

__LED__

![image](https://user-images.githubusercontent.com/1598545/137358952-3ea6684c-6ea3-4efb-8c69-6b9a4b2427d2.png)

__Resistor__

__Button__
