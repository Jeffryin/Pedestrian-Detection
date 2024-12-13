# Pedestrian-Detection
This was my senior design project utilizing the Nvidia Jetson Nano and Jetbot to integrate computer vision and mechatronics into one project as a whole. It consisted of training a model by taking images through the MIPS camera and then preprocessing the custom dataset before training and testing. The project worked by detecting a 'person' through the camera's vision and would stop in front of the 'person' whenever it was in the camera's POV.

# PROBLEM
The problem to this project was that when detecting a 'person' it was very inconsistent especially when the 'person' is in a complex background as the confidence level drops a lot when getting closer to the 'person.' This would become a problem if implemented to a real-life car as you would not want a self-driving car to continuosly drive towards a pedestrian.  To combat this problem, I plan to integrate large datasets vs a custom dataset of a 100+ images so that the model can better interpret when the camera sees a 'person'. With the larger dataset, I will need to revise a plan to preprocess this large amount of data to take out all the 'irrelavent' pieces of information so that the model is better trained. I will also devise a new plan on whether or not I need a new algorithm. 

# GOAL
My goal for this project since I've already demonstrated the first stage of it during my engineering showcase is to improve the accuracy when it sees a 'person' by testing the robot in very complex backgrounds and settings and seeing consistent results. 

# Model
