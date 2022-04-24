
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
