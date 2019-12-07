This is the readme file that explains the steps to run this project. 

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






