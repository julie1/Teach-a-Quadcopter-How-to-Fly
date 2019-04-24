# Teach a Quadcopter How to Fly

This project is one of the requirements for Udacity's machine learning nanodegree.
The goal was to use a reinforcement learning algorithm to teach a quadcopter drone
to perform a task with minimal error.  The task I gave to the drone was to take off
from the ground at zero initial velocity obtaining a hovering position with x, y, and
z coordinates respectively 10, 10, and 20.  I used the Keras DDPG actor-critic deep learning
code provided by Udacity with some modifications and I adjusted various parameters to optimize
my results.  The Quadcopter_Project.html contins my results.  I found that adding batch normalization,
droput, or lowering the default learning rate in the DDPG model did not improve my result.  However,
adding some regularization 
