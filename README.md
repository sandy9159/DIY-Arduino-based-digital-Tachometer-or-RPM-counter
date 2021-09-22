# DIY-Arduino-based-digital-Tachometer-or-RPM-counter
![image](https://user-images.githubusercontent.com/19898602/134334331-50500088-c8fe-448f-851e-afa93af0accc.png)


Let see how to make Arduino based digital Tachometer.

Working principle :-

IR Sensor get penetrate by motion of motor shaft, signal are transfer from IR Senor module to Arduino.

This signal are processed in Arduino according to code loaded on it.

Then Arduino transfer signals to LCD Screen to display RPM

A tachometer is an instrument that comes in handy for all electrical engineers and DIYers who love to tinker around with motors and other rotating objects. 

It is a device that measures the speed of rotating objects such as a motor or a crankshaft in terms of the revolutions it makes in a minute, i.e. RPM. 

Today we’re going to make an easy-to-make and cost-effective digital tachometer for ourselves! We’re going to make this tachometer with the help of evive, an IR sensor, jumper wires, and some DIYing!

# COMPONENT REQUIRED

> 1) IR Sensor module :- http://amzn.to/2mOUVyw

> 2) LCD Screen :- http://amzn.to/2lxF1bp

> 3) Arduino Nano :- http://amzn.to/2lxF1bp

> 4) Zero PCB :- http://amzn.to/2lxF1bp

> 5) Header pins :- http://amzn.to/2lxF1bp

> 6) 9V Batter

![image](https://user-images.githubusercontent.com/19898602/134335366-b2b963a3-d20e-4371-8993-260f7d157ea7.png)![image](https://user-images.githubusercontent.com/19898602/134335394-30dee168-983f-4567-81dd-b2f571e68c26.png)
![image](https://user-images.githubusercontent.com/19898602/134335430-a0cc4162-bc6a-4c68-92b7-589d8e16d972.png)





# Electrical Circuit

![image](https://user-images.githubusercontent.com/19898602/134334835-13006e24-04c2-4844-9e5e-c0e1c7dfc71b.png)



Now after managing these components do this following connection for designing Digital Tachometer using IR Sensor with Arduino for measuring RPM

LCD Pins 1, 3 ,5 ,16 ——— GND


LCD Pins 2, 15————— VCC (+5V)


LCD Pin 4 —————— – Arduino pin D7


LCD Pin 6 —————— – Arduino pin D6


LCD Pin 11 ——————- Arduino pin D5


LCD Pin 12 ——————- Arduino pin D4


LCD Pin 13 ——————- Arduino pin D3


LCD Pin 14 ——————- Arduino pin D2


IR Sensor Module Pin -GND —— GND


IR Sensor Pin +VCC —— VCC


IR Sensor Pin OUT — Arduino Pin D9


Tact Switch one end ————- Arduino PinD12


Tact Switch another end ————-GND



# IR Sensor Module

An infrared sensor is an electronic instrument that is used to sense certain characteristics of its surroundings by either emitting and/or detecting infrared radiation. 

Infrared sensors are also capable of measuring the heat being emitted by an object and detecting motion.

The wavelength region which ranges from 0.75 to 3µm is known as the near-infrared region. 

The region between 3 and 6µm is known as the mid-infrared and infrared radiation which has a wavelength greater higher than 6µm is known as far-infrared.

![image](https://user-images.githubusercontent.com/19898602/134335288-86b69eeb-4ba6-4691-8e43-19e4ce69f62d.png)
![image](https://user-images.githubusercontent.com/19898602/134335310-c00add48-41c7-4d9a-b02e-d7f0f9edd393.png)


IR stands for infrared light, its non visible form of light. its wavelength is longer then visible light, so human eyes not able to see Infrared light.

Ir sensor module have two IR diode one is transmitting IR light and one is receiving IR light.

White surface reflect IR light and black surface absorb IR light.

When IR sensor module is powered on IR transmitter emit IR rays if any white object came in front of IR transmitter so IR rays reflect from that body and IR receiver receive this rays and generate a 5V digital output at output pin with the help of LM358 IC.

Range of IR sensor can adjust from 1K ohm pot available on board.

Now let we see how to build a digital Tachometer or RPM counter using IR sensor.



