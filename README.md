# fire_security_alaram_with_control-
fire security alaram with controlling fan 

components required::
1. NodeMCU ESP8266
2. Micro USB Cable
3. Fire Sensor // IR Sensor 
4. Jumper Wires
5. Buzzer
6. Breadboard
7. LEDS
8. Power supply 9V battery
9. Fan 
10. Relay module

working::
Make the connections as given in the circuit diagram. Then upload the code in NodeMCU using
Arduino IDE . The fire sensor is connected at D1 pin to give the digital input to the NodeMCU and
Buzzer is connected at D2 pin to get digital output from the NodeMCU. Relay 2 channel is connected at D4 pin to get digital output from the NodeMCU. If fire is detected by the
fire sensor then it gives “0” and NodeMCU turns on the buzzer, fan attached to relay and sends notification to the mobile else it can send email to the attached mail address.

with ckt coonnections and pics attached 
