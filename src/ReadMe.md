!--READ ME--!

folder structure

src
--handgesture
  --datacollection.py
  --dataset.py
  --traingest.py
  --predictgest.py  
--controllingallmotors.py
--receive.py

predictgest.py in the folder handGesture, takes the input from webcam, does image preprocessing, and then predicts the gesture using the CNN Model. 
It takes hand gesture as an input and returns the index of the most probable gesture read.

controllingallmotors.py takes in the index value as the parameter passed by the code above and runs the rover as specified 
in the code.

receive.py takes in the index value as the parameter passed by the code above and runs the bulb to switch on/off.


