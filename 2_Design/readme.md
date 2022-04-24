
Block Diagram and Blocks explanation
• 3.1 BLOCK DIAGRAM
![image](https://user-images.githubusercontent.com/101462262/164988213-8483b3d8-ab9a-4de6-bd2b-a7155d87c10d.png)
3.2 SENSORS
• Temperature Sensor (Thermistor)
o This Thermistor is a resistor whose resistance is dependent on temperature here this 
change in resistance produces change in voltage, this voltage is taken as input to micro 
controller
• Light Intensity Sensor (LDR)
o This LDR(Light Dependent Resistor) is a resistor whose resistance is dependent on intensity 
of light here this change in resistance produces change in voltage, this voltage is taken as 
input to micro controller
• Door Open/Closed Sensor
o This is actually a micro switch in real world which will send data to micro controller about 
the door (opened/closed) in our simulation we just used a normal switch
• Master Switch
o This switch controls the Burglar alarm and other automations as unit when this switch is on 
(we ON it when we want alarm)
• Potentiometer (POT)
o This is basically used to take user input i.e. Temperature and Light Intensity
3.3 ACTUATORS
• FAN
o This is a fan which control the cooling of room by increasing/decreasing it's speed
• Actuator for drapes (Stepper motor)
o This is a motor who's direction and angle can be controlled which will inturn controls the 
DRAPES
• Relay
o Here we have used Relay to switch on and off the Burglar alarm system
• Light
o The lighting inside the room is controlled by this lights
• Display
o Here we have used (Hd44780-26) LCD display for displaying how much %of drapes are 
opened and how much %of lights are on
3.4 MICRO CONTROLLER AND MEMORY
• EEPROM
o Here this is actually inside the microcontroller
• Clock
o Here we are using internal clock of our micro controller
• Micro Controller
o This is the brain of the system here we use Atmega328 every computation is done inside 
this controller it converts analog to digital and maps certain values, it controls LCD display, 
it sends PWM signals to Fan and Stepper motor
3.5 SUBSYSTEM & OTHERS
• Burglar alarm
o This system consists of 555 Timer, some capacitors, resistors and a speaker connected in a 
specific way to make a buzzing sound
Motor Driver Unit
o This unit is different for both Drapes(we use Stepper motor driver i.e. ULN2804) and fan 
(we use motor driver L293183)
4 Architecture
• 4.1 Behavioral Diagram
– 4.1.1 High Level Flow chart Behavioral Diagram
![image](https://user-images.githubusercontent.com/101462262/164988796-97338700-31f3-4f7d-ae1f-2d5ba29683f7.png)

– 4.1.2 Low Level Flow chart Behavioural Diagram
![image](https://user-images.githubusercontent.com/101462262/164988902-c1e02eee-9523-41c4-90c2-5428d110e641.png)

• 4.2 Structural Diagram
– 4.2.1 High Level UML Use Case Structural Diagram
![image](https://user-images.githubusercontent.com/101462262/164988921-a44453f2-242b-4b4e-9187-cb7bdcec95f1.png)

– 4.2.2 Low Level UML Use Case Structural Diagram
![image](https://user-images.githubusercontent.com/101462262/164989012-1c6ead65-e713-440c-8843-e2fc5aed0638.png)

