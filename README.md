# RPi-LiveSignGestureRecognition
Sign Gestures have been helpful means of communication for differently abled people in terms of hearing and speaking.  
This project was to help people understand sign gestures by recognizing them using a CNN model with the help of the integration of a Pi Camera to Raspberry Pi along with a 16X2 LCD screen. 
Since the Raspberry Pi can only handle very less computation, we tried to make a TCP connection to a computationally capable device from the Raspberry Pi to get feed from the Pi Camera.  
After preprocessing the frames having the gestures, were sent to a much more computationally capable device that could run the trained CNN model using the frames.  
Then the appropriate gesture is recognized using the CNN model and was displayed on the 16X2 LCD Screen.   


