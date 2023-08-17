# Week 12b - Wednesday - Arduino Analog

| [Wednesday](#wednesday) |

## Wednesday

Agenda

- [Artist of the Day](#artist-of-the-day)
- [Arduino Refresher](#arduino-refresher)
- Physical Computing
  - [Analog Output](#analog-output)
  - [Analog Input](#analog-input)
  - [Servo Sweep](#servo-sweep)
  - [Servo Knob](#servo-knob)
- [Homework](#homework-2)

### Artist of the Day

<img src="https://user-images.githubusercontent.com/1598545/199747061-8090f82e-6b9d-4d82-b17d-0b3633036b4b.png" width="600">

Marguerite Humeau

- [The Rebirth of Prehistoric Creatures](https://we-make-money-not-art.com/back_here_below_formidable/)
- [making of video](https://www.dezeen.com/2012/07/11/proposal-for-resuscitating-prehistoric-creatures-marguerite-humeau/)

### Arduino Refresher

- Install the arduino software on your computer: [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)
- Explore the Basic Blink example: 
  - <img width="400" alt="image" src="https://user-images.githubusercontent.com/1598545/199736888-13783e7a-c5d5-49d6-abb2-d90e79e5cd69.png">
 

### Analog Input

![Image](https://www.arduino.cc/wiki/static/7dbfb4b4c090ba1bc52c2a779822b8f9/29007/analoginoutserial1_bb.png)

https://www.arduino.cc/en/Tutorial/BuiltInExamples/AnalogInput

- Talk about Voltage, Current, and Resistance (Ohm's Law)
- Talk about using a multimeter. 
- Look at how a potentiometer (as voltage divider) changes voltages.
- How a changing voltage corresponds to an `analogRead()`

### Servo Sweep

- Install the Servo library:
-  
  - **Tools** -> **Manage Libraries**:
  -  
    - <img width="300" alt="image" src="https://user-images.githubusercontent.com/1598545/199737681-24316f67-162c-4575-b1e5-931186a644c5.png"> 
  - Search for **Servo**. Click **Install**:
    - <img width="400" alt="image" src="https://user-images.githubusercontent.com/1598545/199737612-735b282d-016f-4162-897a-6d06e2802555.png">
  - Select the "Sweep" example: 
    - <img width="400" alt="image" src="https://user-images.githubusercontent.com/1598545/199741588-8e8a7d49-9f1a-4bff-a5db-9fd8c0d67384.png">

![image](https://user-images.githubusercontent.com/1598545/140386249-6cd37d02-87af-4730-b97e-e04a0f0afb11.png)

![Image](https://www.arduino.cc/wiki/static/dcca996e7af6025b856c4907c3ffa235/01e7c/sweep_schem.png)

https://www.arduino.cc/en/Tutorial/LibraryExamples/Sweep

- How to read a schematic
- Pulse Width Modulation
  - (`analogWrite()`!)
  - more on PWM [Secrets of Arduino PWM](https://www.arduino.cc/en/Tutorial/SecretsOfArduinoPWM)

### Servo Knob
- Under **Examples** -> **Servo**, select the **Knob** example: 
  - <img width="300" alt="image" src="https://user-images.githubusercontent.com/1598545/199742032-4d5e6b1f-d340-47ff-93bb-e52343f48ed6.png">

![Image](https://www.arduino.cc/wiki/static/32db11499efe2d9c9ee451f7996e42a2/e85cb/knob_bb.png)

![Image](https://www.arduino.cc/wiki/static/b0be5a84f8d4dd59d63cf0c102102fa6/b06ae/knob_schem.png)

- Reading the schematic.
- Use the servo to control two knobs. 

### Homework
Finish _Making Things Move_. (Due Monday). Be ready to demo on Monday.

## Reference
- [TK]
