## Abstract
The Ultrasonic Module HC-SR04 operates with the SONAR principle and the RADAR system.
The HC-SR-04 module has an ultrasonic transmitter, receiver, and control circuit on a single board.
The module has only 4 pins, Vcc, Gnd, Trig, and Echo.
When a pulse of 10µsec or more is given a Trig PIN, 8 pulses of 40 kHz are generated. After this, the Echo PIN is made at the top by the module control circuit.
The echo pin remains high until it receives an echo signal for the pulses transmitted backwards.
The time when the echo pin remains high, i.e. the width of the Echo pin gives the time taken by the generated ultrasonic sound to move towards the object and back.
By using this time and the speed of sound in the air, we can determine the distance of an object using a simple distance formula using speed and time.
For more information on the ultrasonic HC-SR04 module and how it is used, see the article Ultrasonic HC-SR04 Module in the Sensors and Modules section.
