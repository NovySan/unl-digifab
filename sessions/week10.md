# Week 10 - Digital and Analog IO

## Agenda
- Pre-class: ECE Capstone Visit
- Project 1 Critique
- Physical Computing
  - Review: Blink and [Digital Output](..sessions/week8.md#digital-output) (last time)
  - [Digital Input](#digital-input)
  - [Analog Output](#analog-output)
  - [Analog Input](#analog-input)
- [Homework](#homework)

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
  - modify the speed at which it fades. (hint: change the `delay()`. see [the delay reference](https://www.arduino.cc/reference/en/language/functions/time/delay/))

## Analog Input

![Image](https://www.arduino.cc/wiki/static/7dbfb4b4c090ba1bc52c2a779822b8f9/29007/analoginoutserial1_bb.png)

https://www.arduino.cc/en/Tutorial/BuiltInExamples/AnalogInput

## Homework
- no homework

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

