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
