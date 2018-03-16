# Gesture-recognition-interface-for-remote-access-of-a-service-robot
Hand gesture controlled rover that lifts and moves objects.
The Hand Gesture Recognition is done on the Master Raspberrypi, and the rover movements are performed with the slave raspberrypi connected to it.
Wireless communication takes places between the two raspberry pi's over the WiFi.

Steps to execute:

1. Run controllingallmotors.py and receive.py as servers are ready to listen on two slave Raspberry pi's.
2. Run predictgest.py which reads gesture and multicasts index value corresponding to a pre-defined gesture.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=KWB5O_lDwE8
" target="_blank"><img src="http://img.youtube.com/vi/KWB5O_lDwE8/0.jpg" 
alt="Hand Gesture Controlled Service Bot" width="240" height="180" border="10" /></a>
