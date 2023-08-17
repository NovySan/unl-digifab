# Week 13b - Actuators and Outputs

| [Wednesday](#wednesday) |

## Wednesday
Agenda 
- [Artist of the Day](#artist-of-the-day)
- More Sensors
  - ~[Temperature Sensor](#temperature-sensor)~
  - [Ultrasonic Rangefinder](#ultrasonic-rangefinder)
  - Rangefinder to P5
- [DC Motor](#dc-motor) and High Power
- [Homework](#homework)
- [Office Hours this Week](#office-hours)
- [Artist of the Day](#artist-of-the-day-2)
- [Relay](#relay)
- [Stepper Motor](#stepper-motor)
- [Homework](#homework)


### Artist of the Day
![image](https://user-images.githubusercontent.com/1598545/201956027-a0033407-8a2d-4167-91bc-a0a6dd38d518.png)

Amy Youngs

- [Rearming the Spineless Apuntia](https://hypernatural.com/portfolio/rearming-the-spineless-opuntia/)
- rest of portfolio: [https://hypernatural.com/art/](https://hypernatural.com/art/)

### Temperature sensor

![image](https://user-images.githubusercontent.com/1598545/141343262-3c12cb66-e550-4696-81d9-30cc9c1ac033.png)

(image from [Adafruit](https://learn.adafruit.com/tmp36-temperature-sensor/using-a-temp-sensor))

- The [TMP 36GZ](http://www.us.diigiit.com/tmp36gz-temperature-sensor) is a temperature sensor.
- This is an active sensor, meaning we provide power to ground and 5V, and it outputs a voltage proportional to temperature.
  - Looking at the [datasheet](http://www.us.diigiit.com/download/TMP35-36-37.pdf), we see it is 10mV/degree Celsius. That means we can use the output voltage (read by analog in) to figure out what the temperature is.
- To convert from AnalogRead value to milli-volts: __Voltage at pin in milliVolts = (reading from ADC) * (5000/1024)__
- To convert from milliVolts to degree celsius: __Centigrade temperature = [(analog voltage in mV) - 500] / 10__
- Activity: 
  - Use AnalogReadSerial to figure out what the current temperature in the room is in Celsius.
  - Modify your code to convert Celsius to fahrenheit. 
  - Explore the dynamic behavior: how quickly does it change in response to breathing on it? In response to touching it? Can you get the temperature to go up, or go down?

### Ultrasonic Rangefinder

<img width="800" alt="image" src="https://user-images.githubusercontent.com/1598545/201957013-f666732a-57be-410c-85c1-76aa5d606797.png">

See this file from the ELEGOO examples: [l10 ultrasonic sensor.pdf](https://github.com/roberttwomey/unl-digifab/files/10013826/l10.ultrasonic.sensor.pdf)

And this code: [Lesson 10 Ultrasonic Sensor Module.zip](https://github.com/roberttwomey/unl-digifab/files/10013847/Lesson.10.Ultrasonic.Sensor.Module.zip)

### Bonus Artist: Garnet Hertz



<!--

<img src="https://user-images.githubusercontent.com/1598545/142435895-e3024774-86f0-41b1-9914-a6e01e59d3fd.png" width=600px>

from https://create.arduino.cc/projecthub/abdularbi17/ultrasonic-sensor-hc-sr04-with-arduino-tutorial-327ff6

- [HC-SR04](https://www.sparkfun.com/products/15569) - [datasheet](https://www.sparkfun.com/products/15569)
- Code: [ping_hc_sr04.zip](../assets/ping_hc_sr04.zip)
- Graph it: __Tools->Serial Plotter__
![image](https://user-images.githubusercontent.com/1598545/142436732-25252eb5-682d-497d-9f52-df6584063f64.png)

-->

<!--## Range Finder to Control p5 sketch

- `Serial.write()`
- `Serial.read()`
-->

### DC Motor

<img width="800" alt="image" src="https://user-images.githubusercontent.com/1598545/201957155-f1e5e081-5967-4d14-8664-c4820943d348.png">

See this file from the ELEGOO examples: [l21 dc motor.pdf](https://github.com/roberttwomey/unl-digifab/files/10013811/l21.dc.motor.pdf)

And this code: [Lesson 21 DC Motors.zip](https://github.com/roberttwomey/unl-digifab/files/10013843/Lesson.21.DC.Motors.zip)


## Office Hours 
Discord or by appointment



### Artist of the Day 2

![image](https://user-images.githubusercontent.com/1598545/202450393-95dcd465-afec-471d-b35c-89b1e6bf95fa.png)

Garnet Hertz

- Cockroach Bot [http://www.conceptlab.com/roachbot/](http://www.conceptlab.com/roachbot/)

### Relay

<img width="800" alt="image" src="https://user-images.githubusercontent.com/1598545/202452995-d084949b-fb19-455f-ac36-3a27b9632fcc.png">


See this file from the ELEGOO examples: [l22 relay.pdf](https://github.com/roberttwomey/unl-digifab/files/10031660/l22.relay.pdf)
 
And this code: [Lesson 22 Relay.zip](https://github.com/roberttwomey/unl-digifab/files/10031666/Lesson.22.Relay.zip)

### Stepper Motor

<img width="800" alt="image" src="https://user-images.githubusercontent.com/1598545/202453114-ee4b9e7f-306f-411b-b49b-834e013e4514.png">

See this file from the ELEGOO examples: [l23 stepper.pdf](https://github.com/roberttwomey/unl-digifab/files/10031617/l23.stepper.pdf)

And this code: [Lesson 23 Stepper Motor.zip](https://github.com/roberttwomey/unl-digifab/files/10031668/Lesson.23.Stepper.Motor.zip)

### Homework

Write a proposal for the final project. Due Monday morning 11/27 for one-on-one meetings. [https://canvas.unl.edu/courses/158902/assignments/1521886](https://canvas.unl.edu/courses/158902/assignments/1521886)

## Reference
- Detailed HC-SR04 tutorial with LEDs and Arduino https://www.instructables.com/Simple-Arduino-and-HC-SR04-Example/
