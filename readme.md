## SDCA
This code helps in getting the steering angle of self driving car. The inspiraion is taken from [Udacity Self driving car](https://github.com/udacity/CarND-Behavioral-Cloning-P3) module as well [End to End Learning for Self-Driving Cars](https://devblogs.nvidia.com/deep-learning-self-driving-cars/) module from NVIDIA



### Code Requirements
You can install Conda for python which resolves all the dependencies for machine learning.

##### pip install requirements.txt

### Description
An autonomous car is a vehicle that can guide itself without human conduction. This kind of vehicle has become a concrete reality and may pave the way for future systems where computers take over the art of driving. An autonomous car is also known as a driverless car, robot car, self-driving car or autonomous vehicle.Autonomous cars combine a variety oftechniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage


## SDCA V2 (NVIDIA Dataset based on real world)

### Dataset
Download the dataset at [here](https://github.com/SullyChen/driving-datasets) and extract into the repository folder

### Python  Implementation

1) Network Used- Convolutional Network
2) Inspiration - End to End Learning for Self-Driving Cars by Nvidia

If you face any problem, kindly raise an issue

### Procedure

1) First, run `LoadData_V2.py` which will get dataset from folder and store it in a pickle file after preprocessing.
2) Now you need to have the data, run `Train_pilot.py` which will load data from pickle. After this, the training process begins.
3) For testing it on the video, run `SDCA.py`


