# Week 12 - Light Sensor and Servo

## Agenda
- John Strough - DIY Animatronics and other work
  - Animatronic Eye Parts and Code: https://www.johnstrope.com/post/eyemech
- NEW PARTS
- Sensors and Serial Communication
  - [Analog with Serial](#analog-serial)
  - [Photoresistor](#photoresistor)
- NFT Workshop wth the McCoys

## Analog Serial


![Image](https://www.arduino.cc/wiki/static/7dbfb4b4c090ba1bc52c2a779822b8f9/29007/analoginoutserial1_bb.png)

https://docs.arduino.cc/built-in-examples/basics/AnalogReadSerial

- From last class, we should still have our potentiometer hooked up into Analog Input 0 (A0) on the arduino. 
- Load the AnalogReadSerial sketch (Examples->01.Basics->AnalogReadSerial) to the arduino. 
- Open the serial monitor:
  - ![image](https://user-images.githubusercontent.com/1598545/141345025-13b9fced-5f45-4f7b-892e-936678a94808.png)
  - Look at how moving the potentiometer changes the value of analogRead(). 
- Activity: Use [`map()`](https://www.arduino.cc/reference/en/language/functions/math/map/) to scale those analog values to 0-255, and use that to fade a jumbo LED (`analogWrite()`)
- We can use `serial.write()` to communicate with p5, or processing, or maxMSP or any other program that can read from a serial port.

## Photoresistor

![Image](https://www.arduino.cc/wiki/static/bb8d0c184836ed4f8cabf71c3dc07ce9/29007/PhotoCellA0.png)

https://www.arduino.cc/en/Tutorial/BuiltInExamples/AnalogInput


- Use a multimeter to see how the resistance changes with the photoresistor. 
  - (this does not need a circuit. connect the red lead to one side of the photoresister, and the black lead to the other)
- We can put a photoresistor in series with a resistor to make a voltage divider. This is similar to how a potentiometer works. As the resistance of the photoresistor changes (the light changes), the output voltage will change.
- Hook up the circuit in the picture above with a resistor, photoresistor, and wires to ground, 5V, and A0.
- Use AnalogReadSerial from the section above, and use the serial port monitor to see what the range of output voltages is.
- Activity: Use the photoresistor to control the servo from last class, in place of the potentiometer
  1. Use the serial port to debug the range of analog values coming in from the photo-resistor/resistor voltage divider.
  2. Use [`map()`](https://www.arduino.cc/reference/en/language/functions/math/map/) to scale those analog values to 0 -> 180 degrees (the full range of the servo)
  3. Interact with the photoresistor and see the motor move. 
- Extension: Instead of directly mapping sensor values to servo position, use the sensor values to trigger specific motions. For instance, have if statements that move it to different positions depending on how much light it sees.

## Homework
- <!--[Even Thermostats](../exercises/ex12.md)-->

## Office Hours 
- Immediately after class. 
- or, contact me online

## Reference
