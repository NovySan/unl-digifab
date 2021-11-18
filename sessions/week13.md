# Week 13 - More Sensors and Serial Communication

## Agenda
- Biomimicry Checkin
- Sensors and Serial Communication
  - [Temperature Sensor](#temperature-sensor)
  - [Ultrasonic Rangefinder](#ultrasonic-rangefinder)
  - Rangefinder to P5
- Discuss Final Project and Exhibition

## Temperature sensor

![image](https://user-images.githubusercontent.com/1598545/141343262-3c12cb66-e550-4696-81d9-30cc9c1ac033.png)

(image from [Adafruit](https://learn.adafruit.com/tmp36-temperature-sensor/using-a-temp-sensor))

- The [TMP 36GZ](http://www.us.diigiit.com/tmp36gz-temperature-sensor) is a temperature sensor.
- This is an active sensor, meaning we provide power to ground and 5V, and it outputs a voltage proportional to temperature.
  - Looking at the [datasheet](http://www.us.diigiit.com/download/TMP35-36-37.pdf), we see it is 10mV/degree Celsius. That means we can use the output voltage (read by analog in) to figure out what the temperature is.
- To convert from AnalogRead value to milli-volts: __Voltage at pin in milliVolts = (reading from ADC) * (5000/1024)__
- To convert from Volts to degree celsius: __Centigrade temperature = [(analog voltage in mV) - 500] / 10__
- Activity: 
  - Use AnalogReadSerial to figure out what the current temperature in the room is in Celsius.
  - Modify your code to convert Celsius to fahrenheit. 
  - Explore the dynamic behavior: how quickly does it change in response to breathing on it? In response to touching it? Can you get the temperature to go up, or go down?

## Ultrasonic Rangefinder

<img src="https://user-images.githubusercontent.com/1598545/142435895-e3024774-86f0-41b1-9914-a6e01e59d3fd.png" width=600px>

from https://create.arduino.cc/projecthub/abdularbi17/ultrasonic-sensor-hc-sr04-with-arduino-tutorial-327ff6

- [HC-SR04](https://www.sparkfun.com/products/15569) - [datasheet](https://www.sparkfun.com/products/15569)
- Code: [ping_hc_sr04.zip](../assets/ping_hc_sr04.zip)
- Graph it: __Tools->Serial Plotter__
![image](https://user-images.githubusercontent.com/1598545/142436732-25252eb5-682d-497d-9f52-df6584063f64.png)

<!--## Range Finder to Control p5 sketch

- `Serial.write()`
- `Serial.read()`
-->
## Homework
- [Even Thermostats](../exercises/ex12.md) Due December 2nd (2 weeks)

## Office Hours 
- Immediately after class. 
- or, contact me online

## Reference
- Detailed HC-SR04 tutorial with LEDs and Arduino https://www.instructables.com/Simple-Arduino-and-HC-SR04-Example/
