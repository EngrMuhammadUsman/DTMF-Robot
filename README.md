# DTMF-Robot
Signals &amp; Systems project - the robot is work on the basis of the DTMF signal that is generated through mobile keys. 

The DTMF robot is controlled by a mobile phone that makes a call to the mobile phone attached to the robot. If any button is pressed,a tone corresponding to the button pressed is heard at the other end of the call. This tone is called **‘dual-tone multiple-frequency’ (DTMF)** tone. 
The robot perceives this DTMF tone with the help of the phone stacked in the robot. The received tone is processed by the ATmega16 microcontroller with the help of DTMF decoder HT9170.The decoder decodes the DTMF tone into its equivalent binary digit and this binary number is sent to the microcontroller.The microcontroller is preprogrammed to take a decision for any given input and outputs its decision to motor drivers in order to drive the motors for forward or backward motion or a turn. The mobile that makes a call to the mobile phone stacked in the robot acts as a remote. So this simple robotic project does not require the construction of receiver and transmitter units. 


 
