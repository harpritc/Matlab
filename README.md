# Matlab
Gesture based mouse controlling system using Matlab


Objective:

Main goal our project we is to control the mouse functions with help of colour recognition.A color pointer has been used for the object recognition and tracking. Left and the right click events of the mouse have been achieved by detecting the number of pointers on the image.

Motivation :

Our motivation to use mouse colour recognition technique to  control mouse functions is  to develop a more intuitive ,cheap and natural interface.  This creates an object tracking application to interact with the computer and develop a virtual human computer interaction device.

Proposed Approach:

In the object tracking application one of the main problems is object detection. Instead of finger tips, a color pointer has been used to make the object detection easy and fast. A circle blue sticker is used as a color pointer in this project. To simulate the click events of the mouse three fingers with three color pointers has been used. 

The basic algorithm is as follows
1.	 Set a pointer in the image.
2.	Detect the pointer using the defined color information.
3.	 Define the region and the center of the pointer and draw a bounding box around it.
4.	 Track the motion of the pointer.
5.	 Move the cursor according to the position of the center of the pointer.
6.	 Simulate the single and the double left click and the right click of the mouse.

