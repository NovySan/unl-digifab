# Week 10 - Digital and Analog IO

## Agenda
- Pre-class: ECE Capstone Visit
- Project 1 Critique
- Physical Computing
  - [Digital IO](#digital-io) and Voltage
  - [Analog Output](#analog-output)
  - [Analog Input](#analog-input)
- [Activities](#activities)
  - [Digital Output](#digital-output)
  - [Digital Input](#digital-input)
- [Homework](#homework)

## Review Code Basics
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

![Image](https://www.arduino.cc/wiki/static/73702ee121860fa04c7f6db5bc77183b/29007/circuit.png)

https://www.arduino.cc/en/Tutorial/BuiltInExamples/Button

- TODO
  - modify to be a toggle (and a variable that keeps track of on/off)
  - use the button input to call a function

## Analog Output

![Image](https://www.arduino.cc/wiki/static/079b1bab3758603a56c5d98e1f59a88e/29007/circuit.png)

https://www.arduino.cc/en/Tutorial/BuiltInExamples/Fade

- NOTE: this is a very similar circuit and wiring as [Digital Output](../week8.md#digital-output) from last time! 
  - the difference is that here we are using `analogWrite()` (reference)
  - and a different pin (one of the PWM capable pins)

- TODO: 
  - modify the speed at which it fades. (hint: change the `delay()` [ref](https://www.arduino.cc/reference/en/language/functions/time/delay/))

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

![image](https://user-images.githubusercontent.com/1598545/139250236-3dfac097-bcbe-4dad-920f-a23bd82b32a9.png)

![image](https://user-images.githubusercontent.com/1598545/139250292-c751c276-03f8-4714-a918-3b29955106b5.png)

from Sparkfun ([link](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law/resistance))

__Button__

