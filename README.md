# ULTRASONIC SENSOR INTERFACING
## AIM:
To measure the distance of the obstacle using ultrasonic sensor and display the value in LCD and serial monitor using Arduino UNO controller.
## Software required:
Arduino IDE </br>
Proteous
## PROCEDURE:
### Arduino IDE
Step1:Open the Arduino IDE </br>
Step2: Go to file and select new file option </br>
Step3:Type the program </br>
Step4:Go to file and select save option to save the program </br>
Step5:Go to sketch and select verify or compile options </br>
Step6:If no error Hex file will be generated in the temporary folder </br>
### Proteus
Step7:Open the Proteus software </br>
Step8:Go to file select new design and click ok button </br>
Step9:Select component mode and click pick devices from the library </br>
Step10:Type the component name in the keyword to select the components and click ok button </br>
Step11:Design the circuit as per the diagram </br>
Step12:Double click the Arduino controller and upload the hex file generated by Arduino IDE </br>
Step13:Click start button and check the output
## THEORY:
```
>>Ultrasonic Module HC-SR04 works on the principle of SONAR and RADAR system. It can be used to determine the distance of an object in the range of 2 cm – 400 cm.
>>The module has only 4 pins,
1.VCC
2.GND
3.Trig
4.Echo
>>When a pulse of 10µsec or more is given to the Trig pin, 8 pulses of 40 kHz are generated. After this, the Echo pin is made high by the control circuit in the module. Echo pin remains high till it gets echo signal of the transmitted pulses back.
>>The time for which the echo pin remains high, i.e. the width of the Echo pin gives the time taken for generated ultrasonic sound to travel to the object and back.
>>Using this time and the speed of sound in air, we can find the distance of the object using a simple formula for distance using speed and time.
For more information about ultrasonic module HC-SR04 and how to use it, refer the topic Ultrasonic Module HC-SR04 in the sensors and modules section.
```

## PROGRAM:
```
## CIRCUIT DIAGRAM:
## OUTPUT:
## RESULT:
Thus the distance of the obstacle is measured using ultrasonic sensor and display the value in LCD and serial monitor using Arduino UNO controller.
