# Build INstructions: Temperature Sensor(DS18b20)
## Introduction
The project which I decide to work on is the Temperature Sensor. The motive of this project is to detect the Temperature at various sites. The reason why I chose this project is because I felt like it met all my capabilities. It is an individual project so I worked on it alone but for the software I got two partners Ravneet Singh and Bojan. 

## System Diagram
My temperature sensor will sense the temperature and with the help of raspberry pi it will show the readings of the temperature on the computer screen. You can also use LCD display to show the readings of the temperature.
![alt text](https://github.com/GaGanGr3wal/My-Project/blob/master/SystemDiagram.PNG)

## Budget
The main components which are required for my project are a raspberry pi, a temperature sensor(DS18B20), jumper wires(male to female). In addition, if you want to show the temperature readings on an LCD you will have to add potentiometers and an LCD display in your budget. These all components are available on Amazon, so you can easily get them. Some other components you will need to make this project are breadboard and a resistor. You can get these components from your parts kit.

![alt text](https://github.com/GaGanGr3wal/My-Project/blob/master/budget11.PNG)

If you want to show the readings of temperature on LCD display your budget will increase a bit. 

![alt text](https://github.com/GaGanGr3wal/My-Project/blob/master/budget111.PNG)

## Time Commitment
The project began with ordering the parts/components which are required for the project. All the components used in this project are available on Amazon. Once ordered, it took about a week and a half to arrived. After the parts arrived, I started to setup my raspberry pi and its components. It tooks about 1 hour to setup. Then I started implementing the code by which my temperature sensor will sense the temperature and displays the readings of the tmeperature on the computer screen. It tooks about 1 hour because I had to change lot of things in the code. And to complete the whole project it tooks about 3 hours to complete it. At last, I designed a 3d printed case for my project and it took about 1 day to get printed.

## Mechanical Assembly 
The assembly of my project is very simple. Firstly, put SD card into the pi and set it up. Attach temperature sensor to raspberry pi with the help of breadboard, 4.7k ohm resistor and jumper wires as shown in the picture and follow the steps given below.

#1 - Connect GPIO GND [Pin 6] on the Pi to the negative rail on the breadboard and connect GPIO 3.3V [Pin 1] on the Pi to the Positive rail on the breadboard.<br>
#2 - Plug the DS18B20+ into your breadboard, ensuring that all three pins are in different rows. Familiarise yourself with the pin layout, as it’s quite easy to hook it up backwards!<br>
#3 -  Connect DS18B20+ GND [Pin 1] to the negative rail of the breadboard.<br>
#4 -  Connect DS18B20+ VDD [Pin 3] to the positive rail of the breadboard.<br>
#5 -  Place your 4.7kΩ resistor between DS18B20+ DQ [Pin 2] and a free row on your breadboard.<br>
#6 - Connect that free end of the 4.7kΩ resistor to the positive rail of the breadboard.<br>
#7 -   Finally, connect DS18B20+ DQ [Pin 2] to GPIO 4 [Pin 7] with a jumper wire.<br>

![alt text](https://github.com/GaGanGr3wal/My-Project/blob/master/DS18B20-rpi-setup-3.JPG)

## Unit Testing


## Production Testing 
The production testing is very easy. First, run the temperature sensor program temp.py and heat the sesnor with the help of your hands and by blowing air from your mouth on the sensor. In addition, heat the temperature sensor with the help of a lighter so that you can see the changing temperature readings quickly on the screen.

