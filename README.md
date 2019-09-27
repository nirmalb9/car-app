# Car App

## Lane Detection


### Single Frame Lane Detection

I utilized the hough transform method from the cv2 library to detect common intersection points in different bins with a couple of different image manipulations to draw strong detected edges as they appeared in a single frame. 

The initial image:
![Test Image](singleFrameLaneDetection/test_image.jpg)


The result:
![Result Image](singleFrameLaneDetection/result.png)


### Continuous Lane Detection with stream

You can extend a lot of what you do with single frame lane detection to a continous set of frames if you process each frame at some discrete millisecond interval. 
There are a fair amount of tutorials online that followed the Hough Transform method using the CV library that helped implement the hough transform method for each of those frames.

Overlayed result:
![Result Video](continuousLaneDetection/output.mp4)
