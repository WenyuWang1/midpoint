# midpoint
# Code
Up to now we have done:
1. Assembled the the robotic arm; 
2. Replaced raspberry Pi 4 with RP2040 to drive the servo motors;
3. Control the servo motors through driver board
4. Capture image through  pico4ML

The code is uploaded in the code file.

# Media

## Materials

### Adeept 5-DOF Robotic Arm

![arm](https://user-images.githubusercontent.com/113371324/205537644-73a3e00c-cbaf-4ed0-82db-e12f961bdeeb.jpg)

### Pico4ML

![pico](https://user-images.githubusercontent.com/113371324/205538015-8ecde5f9-b235-44c3-beb2-3dbb6b988308.jpg)

### Qt Py Rp2040



## Design

### Motor Connection

![motor](https://user-images.githubusercontent.com/113371324/205538771-e7845161-a172-4315-8071-3c792a1a6a70.jpg)

### Qt Py Rp2040 Connection


### Pico4ML Connection


## Troubleshooting



## Demos




## Diagram
![6](https://user-images.githubusercontent.com/113371324/205553511-d88c2dc2-4b17-4cee-9a5e-95b3d1dd9fb5.png)



## Problem to be addressed
1. Due to the poor precision of the servo motors, it is hard for us to realize autonomously grasping

2. Hard for us to figure out the mathematics behind the robotics forward and inverse kinematics due to the poor control precision

3. The library of  raspberry Pi 4 is different from RP2040 series, thus I cannot import RPI.GPIO directly, which may influence the application of joystick

4. How to communicate between pico4ML and Qt Py RP2040 as we designed to transfer control signal from the pico4ML to RP2040 while i2c seems not available
