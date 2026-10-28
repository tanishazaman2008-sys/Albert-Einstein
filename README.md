**OBSTACLE AVOING ROBOT CAR**


**TEAM:**
Albert_&_Einstein


This robot uses an ultrasonic sensor to detect obstacles and automatically changes direction to avoid collision

**Project by:**

-Tanisha Zaman Tonny

-Saba Tasneem

-Maisha Ahmed Roza

**Contribution:**

-CODING: Saba Tasneem

-WIRING: Maisha Ahmed Roza

-ASSEMBLING PARTS: Tanisha Zaman Tonny


**Setup Instructions:**



1. Base Assembly

Assemble the base of the car by attaching the DC gear motors to the edges.
Secure the motors firmly with hot glue to prevent vibrations .

2. Component Placement 

Mount the SG90 servo motor at the front to allow the ultrasonic sensor to scan for obstacles.
Place the Arduino Uno, L298N motor driver, Buck Converter, breadboard, ON/OFF switch, and battery holder onto the base using hot glue.

3. Wiring Connections

Motor Driver: Connect the right-side motors to OUT1/OUT2 and the left-side motors to OUT3/OUT4.

Power: Connect the battery holder through the switch to the motor driver's 12V input. Connect the driver's 5V output to the Arduino VIN pin and breadboard power rails.

Sensors & Driver: Connect the ultrasonic sensor (Echo to pin 2, Trig to pin 3), the servo (signal to pin 5), and the motor driver inputs to pins 6-11 on the Arduino.


4. Coding & Calibration 

Load the primary obstacle avoidance code  which uses the ultrasonic sensor to measure distances and trigger avoidance maneuvers.

  Calibration Tip: If the robot turns too sharply, adjust the delay values in the turnLeft and turnRight functions within your code 


🛠**Components Used:**

• Arduino Uno

• L298N Motor Driver

• HC-SR04 Ultrasonic Sensor

• SG90 Servo Motor

• Buck Converter

• Breadboard

• 6x 18650 Batteries

• 2x Battery Holder

• ON/OFF Switch

DIAGRAM: https://acrobat.adobe.com/id/urn:aaid:sc:AP:4b5d0b07-2752-4cb8-a7df-fb8a70658779

YOUTUBE VIDEO LINK: https://www.youtube.com/watch?v=Vpk5PH6QexA


**Dc gear motor has an upper hand over ac gear motor as it allows a steady current and thereby a constancy on the desired speed. We wished to keep the robot easy to make and on a rudimentary level so Arduino uno was chosen over the complexities of other microcontroller like ESP32.**
