# Simulation of Self Driving Car

- A self-driving car is a type of vehicle that does not need a person to operate it. 
- Instead, it uses advanced sensory technology like lidar, sonar, GPS, radar, or odometry and inertial measurements to identify environmental changes and adapt to restore safe speed or distance. 
- Self Driving Cars mostly aim to achieve road safety as human error is the cause of 90% of road accidents and less traffic on the road among other things.

# Overview of Project
- Use the simulator to collect data via front,left and right camera frames and steering angles of good driving behaviour on a track.
- For game we only took one camera frame into consideration and created a custom dataset which consisted the images and the keyboard actions.
- Used AlexNet for game and NVIDIA architecture with TensorFlow as backend that predicts steering angles from images.
- Train the model.
- Test the model in Autonomous Mode.

# Basic Pipeline for development of self driving car model
- Finding Region of Interest
- Lane Finding
- Vehicle detection and vehicle tracking
- Behaviour Cloning

# Tech Stack Used :
- Game : NFS
- Simulator : Udacity’s open sourced simulator 
- Neural Network Architecture used : AlexNet , NVIDIA architecture for autonomous driving
- Frameworks : Tensorflow 
 
# Some part of the code was taken by sentdex's implementation of Python plays GTAV 
