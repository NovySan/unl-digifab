# Week 11 - Digital and Analog IO

## Agenda
- John Strough - DIY Animatronics and other work
  - Animatronic Eye Parts and Code: https://www.johnstrope.com/post/eyemech
- NEW PARTS
- Sensors and Serial Communication
  - [Analog with Serial](#analog-serial)
  - [Photoresistor](#photoresistor)
  - [Temperature Sensor](#temperature-sensor)
  - [Ultrasonic Rangefinder](#ultrasonic-rangefinder)
- NFT Workshop wth the McCoys

## Analog Serial

![Image](https://www.arduino.cc/wiki/static/7dbfb4b4c090ba1bc52c2a779822b8f9/29007/analoginoutserial1_bb.png)

https://www.arduino.cc/en/Tutorial/BuiltInExamples/AnalogInput

- Talk about Voltage, Current, and Resistance (Ohm's Law)
- Talk about using a multimeter. 
- Look at how a potentiometer (as voltage divider) changes voltages.
- How a changing voltage corresponds to an `analogRead()`

## Photoresistor

- photoresistor and voltage divider
- using multimeter to see how the resistance changes
- reading the photoresistor as a sensor
- Activity: Use the photoresistor to control the servo from last class, in place of the potentiometer
  1. Use the serial port to debug the range of analog values coming in from the photo-resistor/resistor voltage divider.
  2. Use map() to scale those analog values to zero -> 180 degrees (the full range of the servo)
  3. Interact with the photoresistor and see the motor move. 
- Extension: Instead of directly mapping sensor values to servo position, use the sensor values to trigger specific motions. For instance, have if statements that move it to different positions depending on how much light it sees.

## Temperature sensor

- TMP 36GZ ([link](http://www.us.diigiit.com/tmp36gz-temperature-sensor)) - [datasheet](http://www.us.diigiit.com/download/TMP35-36-37.pdf)
- Active sensor: connects to ground and 5V. The output is a voltage proportional to temperature.

## Ultrasonice Rangefinder

- [HC-SR04](https://www.sparkfun.com/products/15569) - [datasheet](https://www.sparkfun.com/products/15569)


## Homework
- [Even Thermostats](../exercises/ex12.md)

## Office Hours 
- Immediately after class. 
- or, contact me online

## Reference
- Detailed HC-SR04 tutorial with LEDs and Arduino https://www.instructables.com/Simple-Arduino-and-HC-SR04-Example/
- 
