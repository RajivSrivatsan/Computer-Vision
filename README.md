# Moving-Object-Detection
#1 Computer vision project

A technique used in Computer Vision and Image processing to detect if there are any moving objects in the frame

Libraries used:
OpenCV
cv2, imutils, time

Functions to perform:
1.Resizing an image - imutils.resize(img) 
Resizing the image to a specific frame

2.Grayscale conversion - cv2.cvtColor(img, COLOR_BGR2GRAY)
Changing the image to grayscale image
3.Gaussian Blur - cv2.GaussianBlur(img, (kernel), 0)
Converting a image to blurred image
4.Threshold - cv2.threshold(img, threshold, maxvalueofthreshold, binarytype)
5.To draw a rectangle - cv2.rectangle(img, startpoint, endpoint, color, thicknes)
6.To put a text in image - cv2.putText(img, text, (10,20), FONT, COLOR, Thickness)
7.To add contours to image - cv2.findContours(img, ContourRetrievalMode, ContourApproximationMethod)
8.Reading camera feed - cv2.Videocapture(0)

9.Image Difference - cv2.absDiff(src, img)

Process:
We will compare camera feed with the background image and display as Normal if there is no movement and if there are any movements it will display Movement detection.

