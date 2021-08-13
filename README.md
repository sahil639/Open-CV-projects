# Open-CV-projects

Concepts used in this project:

## 1.Image thresholding 
  The simplest thresholding methods replace each pixel in an image with a black pixel if the image intensity {\displaystyle I_{i,j}}I_{{i,j}} is less than some fixed constant T (that is, {\displaystyle I_{i,j}<T}I_{{i,j}}<T), or a white pixel if the image intensity is greater than that constant. In the example image on the right, this results in the dark tree becoming completely black, and the white snow becoming completely white.
   to learn more about image thresholding in OpenCV got to: https://docs.opencv.org/4.5.1/d7/d4d/tutorial_py_thresholding.html

## 2.Image masking
   Image masking is a process of graphics software like Photoshop to hide some portions of an image and to reveal some portions. It is a non-destructive process of image editing. Most of the time it enables you to adjust and tweak the mask later if necessary. Very often, it is an efficient and more creative way of image manipulation services.

## 3.Space Conversion 
  to learn more about space/color coversion in OpenCV got to:https://docs.opencv.org/4.5.2/df/d9d/tutorial_py_colorspaces.html

## 4.Video input 
   How to get a video input from your laptop camera here : https://www.geeksforgeeks.org/python-opencv-capture-video-from-camera/

System Requirements: Python 3 , OpenCV, Numpy installed.

..* Steps to run this program:
Keep the PC camera stable and ensure that there frame is empty or void of the object that is going to be targeted for masking
Run the python script in your preferred IDE, I used jupyter notebook.

3. Couple of windows will pop up: The first window consists of sliders for Hue, Saturation, Value of colour of sheet, the second displaying live video output.

4. Adjust the HSV values for the color of the object that you want to use as an object to hide yourself in its color range.

5. Play around with different objects and use thenm as your invisibility cloak

6. Star this repo for future OpenCV projects!!!💯✨
