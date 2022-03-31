# Arduino-LED-Controller

Uses your fingers to turn on 1-5 LEDs using your five fingers. 

Depending on the amount of fingers raised, that number of LEDs will be projected. 

The number of fingers read corresponding to the number of LEDs turned on will be displayed on the webcam (window).


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# In Depth Detail 

Using the landmarks given by mediapipe shown below, the camera uses these indicated numbers to recognize when finger(s) are lifted up. 

![HandLandmarks](https://user-images.githubusercontent.com/95951042/160973274-ee0d8b6c-b559-4152-b99a-a3934eedb0f8.png)

Then, we use the function imported from the other file named Controller.ipynb to turn on the same number of LEDs as the fingers raised
