![1_xIho0iQQPs5SyrCHvw55SA](https://user-images.githubusercontent.com/132823058/236677602-a0d45cdc-7760-4011-b450-8ff51f5ce4d4.gif)
![1_xIho0iQQPs5SyrCHvw55SA](https://user-images.githubusercontent.com/132823058/236677587-0877ff9a-1f8e-4068-9e07-f1d496d8ca34.gif)
# harry_clock-python

How it works
*This technique is opposite to the Green Screening. In green screening, we remove background but here we will remove the foreground frame.

*Capture and store the background frame
*Detect the defined color using color detection and segmentation algorithm.
*Segment out the defined colored part by generating a mask.
*Generate the final augmented output to create a magical effect. [ output.avi ]



You need the following libraries
import cv2
import time
import numpy as np




H : Hue
Hue is the colour portion of the model, expressed as a number from 0 to 360 degrees:

*Red falls between 0 and 60 degrees.
*Yellow falls between 61 and 120 degrees.
*Green falls between 121–180 degrees.
*Cyan falls between 181–240 degrees.
*Blue falls between 241–300 degrees.
*Magenta falls between 301–360 degrees.
