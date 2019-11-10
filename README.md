# Raah Darshni
![](https://img.shields.io/badge/python-3.6.2-brightgreen.svg)
<br>

Hardware and software implementation of obstacle detection for visually impaired people. This software allows the interaction of hardware to detect collision and then guide users accordingly to a correct direction.

## Idea
The main idea behind the project is to help blind people. We’ve observed that they are always dependent on other people to help them find their way. With Raah Darshini, we aim to help these people become independent. Raah Darshini can detect obstacles in the person’s way and hence guide them accordingly. 
We use audio cues to guide the person to the correct or obstacle free path. In further development we intend to use a physical device that would correct the path in certain circumstances.
The project incorporates computer vision, machine learning and an IP camera for software implementation. Whereas for hardware the project uses adrino, ATMEGA-162, Ultrasound sensor. With the sensors, it combines the data from software with hardware to get more accurate results. Moreover this device is put on a 'Walkinng Stick', and wirelessly connected to a mobile device for processing. Audio cues and rotator is used to provide direction results.


## Implementation

We detect the obstacle and after detecting the object, navigation path are given to the user. For being economical we use a camera feature instead of relying on acquired help like guide dogs.
We’ve used the Single Shot Detector (SSD) which provides a good balance between speed and accuracy since the project would work on real-time implementation. The COCO dataset is used for the objects.
The code is written in python and tensorflow is used as machine learning backend. An IP camera is used to get live feed and process the result. This result is further compared and fed to a python file that takes in sensor data and processes the data. This result is then compared to threshold values and audio cues are provided.

## Business Strategy
#### 1
Initially we’ll launch a mobile application that would inquire no cost. This would provide an early assessment of our target audience and the scope of the application.

#### 2
Our main product highlights would be the highly economical use of devices which altogether reduces the cost as compared to when being made by analog devices which would require high maintenance. 

#### 3
After an initial assessment and market research we would launch our second and third products into the market which would be “Immersive Glasses” and a highly productive walking stick.

#### 4
Our main product assessment and recognition would be by these devices whose services would be billed quarterly.




