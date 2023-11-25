# Automated-traffic-system
A model of a utopian traffic system was designed using Arduino as the microcontroller, LDR, LM393 sound detection sensor module and HW-201 1R sensor.
Sensors used: HW-201 infrared (IR) sensor, Light Dependent Resistors (LDRs), LM393 Sound detection sensor module. 
Actuators used:  Servomotors, 7-segment displays, LEDs.
Power Source: AC, 12V DC supply.
2 IR sensors are used in each of the 4 lanes to detect vehicle congestion.   

Servomotors are used to block or open the lanes depending on the IR sensor readings.

LDRs are used to conserve energy by switching the street lights on only when the resistance is high and light intensity is low.
3 LEDs are used as the traffic lights for the 4 lanes. 

The sound sensor is used as a High Pass Filter (HPF). It detects sound intensity of the siren blares from ambulances / police cars (high priority situations) via its microphone and sends it into an LM393 operational amplifier. When the sound level exceeds the threshold, that lane is prioritized and other lanes go to RED. 

7-segment display is used to display the timer.
