This is the readme file that explains the steps to run this project. 

In this project, we trained an Artificial learning agent which interacts with an environment with specific state which has a set of actions it can perform. Each state has many actions associated with it and each action leads to either a positive or negative consequence. If it’s positive, we’re reinforced to take that action again, and vice versa. The goal of the agent is to maximize its rewards for each state action pair.

In this project we used the concept of Q-Learning, it allows machines (known as agents) to learn by experimentation.  In Q-Learning, we use these rewards to update Q-Values that tell us how good/desirable a certain state is. In Deep Q-Learning, instead of storing Q-Values, we instead use a Deep Neural Network which allows us to approximate Q-Values, given our state as input. Next time our agent moves through our environment, it will use the Deep Q-Network to generate Q-Values for each action, and take the action with the highest Q-Value.


Enhancements:
Experimented with various neural network architectures and the results shows that  layered architecture with 128-128-64-64-32-3 neurons performed better when compared to other set of architectures. Tuned Neural network parameters by experimenting with different combinations of activations and weight initializers. Changed the Sonar arms from 3 to 5 to increase the range of vicinity of the learning agent so that the learning curve of the agent will be improved. Also, changed the dynamic objects from 1 to 2 and static objects from 3 to 5. 


This project is about obstacle detectection for autonomous cars.We used Python 3 to implement this project. It uses Python3, Pygame, Pymunk, Keras and Theanos. It employes a Q-learning (unsupervised) algorithm to learn how to move an object around a screen (drive itself) without running into obstacles.

This version of the code attempts to simulate the use of sensors to get us a step closer to being able to use this in the real world.

The Steps to run in subject:

1. Open the repository
2. After opening the repository we need install certain libraries, these libraries can be installed through command "pip install #library_name. The list of libraries that we need to install are:

      1. keras
      2. numpy
      3. random
      4. csv
      5. os.path
      6. timeit
      7.  matplotlib.pyplot
      8. tensorflow


Once the above libraries are installed, we need to run the python files in the below order:

       1. learning.py - This python file has the code that trains the agent so that it can learn based on the rewards and
                        penalties. This file generates a model that the agent used in real time scenario,

        2. playing.py - After training the agent now we need to test the agent in a real time environment so for this we
                        need to run this file.
                        
                        
 References:
 https://blog.coast.ai/using-reinforcement-learning-in-python-to-teach-a-virtual-car-to-avoid-obstacles-6e782cc7d4c6
 https://github.com/harvitronix/reinforcement-learning-car






