# Smart-Dustbin-Using-Arduino
Automatic lid opening and closing method is used in smart dustbin and microcontroller  programming is done in the system. A simple but useful project called smart dustbin  using arduino is designed and developed here. 

To complete our project, we 
require some software as well as some hardware.  
Required : 
1. ARDUINO UNO.  
2. ULTRASONIC SENSOR.  
3. SERVO MOTOR.  
4. 9V BATTERY. 
5. DUSTBIN. 
6. JUMPER WIRES.
<img width="463" height="267" alt="image" src="https://github.com/user-attachments/assets/89530cd4-df2e-4c8d-9a2a-9c08cbff00d2" />



CIRCUIT DIAGRAM:  

The circuit diagram of smart dustbin is shown in given below. 

The ultrasonic sensor echo pin and trigger pin is connected to pin digital pin D7 
and D8. The +Vcc pin is connected to +5V supply and GND pin is connected to 
ground pin of arduino Uno board. The control (PWM) pin of servo motor is 
connected to digital pin D9 of arduino. Hence, servo motor is used to open the cap 
of dustbin. For this project and components used, the preset level of distance 
between dustbin and hand is fixed to 40 cm. 

Distance (in cm) = (duration/2) / 29.1 

<img width="542" height="507" alt="image" src="https://github.com/user-attachments/assets/ab98fda8-13c4-4374-8d84-bb6fd9b65e10" />    

BLOCK DESCRIPTION: 

After wiring and attaching all the devices and setting up to the Smart Dustbin, now 
observe all the important setup whether they are well connected or something missed. 
After connection set up now next step is to submit/upload code in Arduino and supply 
power to the circuit. When system is powered ON, Arduino keeps monitoring for any 
things that come near the sensor at give range. When Ultrasonic sensor detect any 
object for example like hand or others, here Arduino calculates its distance and if it 
less than a certain predefines value than servo motor get activate first and with the 
support of the extended arm of the lid. Lid will open for a given time than it will 
automatically close.

<img width="868" height="624" alt="image" src="https://github.com/user-attachments/assets/5d713bfe-3738-41cc-89bb-1457cec2081b" />

CONCLUSION: 

Here we are going to make an evolution changes toward cleanliness. The combination 
of intelligent waste monitoring and trash compaction technologies, smart dustbins are 
better and shoulders above traditional garbage dustbin. It is equipped with smart 
devices like sensor, Arduino etc. Lid of the dustbin will automatically open when an 
object comes near to the dustbin and after certain time period it will close the lid. For 
social it will help toward health and hygiene, for business for we try to make it 
affordable to many as many possible. 

REFERENCE: 

Youtube: https://youtu.be/9yrP1CZN3Ds?si=JO7Wef3PaloO-Jam 
