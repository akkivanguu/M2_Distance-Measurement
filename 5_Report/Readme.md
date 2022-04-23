### Folder Structure
| Folder | Description |
| ----- | ----- |
|0_Abstract|about project|
| 1_Requirements | Documents detailing requirements and  research |
| 2_Design | Documents specifying design details |
| 3_Implementation | All code and documentation |
| 4_TestCases | Documents with test plans and procedures |
| 5_Report | Documentation of the whole Project |
| 6_Output | Output of the Project |
## Abstract
The Ultrasonic Module HC-SR04 operates with the SONAR principle and the RADAR system.
The HC-SR-04 module has an ultrasonic transmitter, receiver, and control circuit on a single board.
The module has only 4 pins, Vcc, Gnd, Trig, and Echo.
When a pulse of 10µsec or more is given a Trig PIN, 8 pulses of 40 kHz are generated. After this, the Echo PIN is made at the top by the module control circuit.
The echo pin remains high until it receives an echo signal for the pulses transmitted backwards.
The time when the echo pin remains high, i.e. the width of the Echo pin gives the time taken by the generated ultrasonic sound to move towards the object and back.
By using this time and the speed of sound in the air, we can determine the distance of an object using a simple distance formula using speed and time.
For more information on the ultrasonic HC-SR04 module and how it is used, see the article Ultrasonic HC-SR04 Module in the Sensors and Modules section.

## Requirements
## Introduction
In this project, we are going to interface Ultrasonic sensor HC-SR04 with Atmega328 and LCD Display. The ultrasonic sensor is used to measure the distance. It acts as a Sonar. It sends an ultrasonic wave of a certain frequency that comes back after hitting the object and calculates the time traveled by it. This distance measurement system can be widely used as range meters and as proximity detectors in
industries. The hardware part of ultrasonic sensor is interfaced with atmega328.
## Research
- The Ultrasonic Sensor sends out a high-frequency sound pulse and then times how long it takes for the echo of the sound to reflect back. The sensor has 2 openings on its front. One opening transmits ultrasonic waves, (like a tiny speaker), the other receives them, (like a tiny microphone).

- The speed of sound is approximately 341 meters (1100 feet) per second in air. The ultrasonic sensor uses this information along with the time difference between sending and receiving the sound pulse to determine the distance to an object.
## Features
- Highly accurate – Because of the way they work, Ultrasonic sensors are highly accurate and can be used to detect very small alterations in position. They can also measure the thickness of an object as well as the depth of the parallel surface.
- Detect a range of materials – Ultrasonic position sensors can detect and measure objects irrespective of their surface.
- ultrasonic sensors is that they can easily interface with a microcontroller and they are not dangerous to operate.
- Ultrasonic sensors generate high frequency sound waves and evaluate the echo which is received back by the sensor.
- Sensors calculate the time interval between sending the signal and receiving the echo to determine the distance to an object. The microcontroller is used to generate 40 kHz sound pulse.

## SWOT Analysis
### Strengths
*   It has sensing capability to sense all the material types.
*   This sensor is not affected due to atmospheric dust, rain, snow etc.
*   It can work in any adverse conditions.
*   It has higher sensing distance (in centimeters and inches) compare to inductive/capacitive proximity sensor types.
*   It provides good readings in sensing large sized objects with hard surfaces.
### Weaknesses
*   It is very sensitive to variation in the temperature.
*   It has more difficulties in reading reflections from soft, curved, thin and small objects.
### Opportunities
*   They have greater accuracy than many other methods at measuring thickness and distance to a parallel surface.
*   Their high frequency, sensitivity, and penetrating power make it easy to detect external or deep objects.
### Threats
*   Limited testing distance
*   Inaccurate readings
*   Inflexible scanning methods
### 4W's and 1'H 
*   Who :The importance of the project is calculating accurate distance from any obstacle that we want to measure. Ultrasonic sensors are used primarily as proximity sensors. They can be found in automobile self-parking technology and anti-collision safety systems.
*   What :As the name indicates, ultrasonic sensors measure distance by using ultrasonic waves. The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. Ultrasonic Sensors measure the distance to the target by measuring the time between the emission and reception.
*   When :Ultrasonic sensors can measure the distance to a wide range of objects regardless of shape, color or surface texture. They are also able to measure an approaching or receding object. By using “non-contact” ultrasonic sensors, distances can be measured without damage to the object.
*   Where :The device can be used in many different fields and categories like distance calculation in construction field, robots, car sensor to avoid obstacles and many other applications.
*   How :Ultrasonic sensors are useful for measuring distances. Ultrasonic waves are transmitted and whenever these strike an obstacle and return back in the from of an echo. Difference of outgoing sound and returning echo gives us the distance.
*   


  ## Behavioral Diagram
  
  ## Flow Chart
  ![flow](https://user-images.githubusercontent.com/101030179/164615413-661b0281-2694-40ce-8f43-85edb1a6849b.png)

## Block Diagram
1. ![block](https://user-images.githubusercontent.com/101030179/164615603-c2e0c1a8-9673-4d35-b488-388eea8b10fa.png)
2. ![Block 2](https://user-images.githubusercontent.com/101030179/164616494-40cba547-8114-4788-bb42-8bbe0c4187ef.png)

## Structural Diagram

![Structural diagram](https://user-images.githubusercontent.com/101030179/164615966-1aa4e7b1-0c5e-4116-bb22-7b75ecfc7bde.png)

## Circuit Diagram
![Screenshot (38)](https://user-images.githubusercontent.com/101030179/164713695-ba76860d-1285-414f-b6be-6eb25389e87b.png)




## Challenges Faced and How Was It Overcome

| No. | Challenge | Solution
|-----|-----------|--------
|1.| installation of  doxygen documention| use youtube videos and stackoverflow information 
|2. | Had challenges in workflows  |  use wiki page and example of workflow in provided github repository by GEA

## Learning Resources
1.Github
2.GeeksforGeeks
3.For makefile - https://github.com/riuandg5/learn-makefile
4.For problems during coding , iuse stackoverflow platform for solution.
