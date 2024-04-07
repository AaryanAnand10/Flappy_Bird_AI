# Flappy Bird AI
An implementation of a Flappy Bird AI using reinforcement learning in Python. This project uses a Q-learning algorithm to train the AI to play the game.

# Working 
This program is an implementation of the game Flappy Bird using the Pygame library in Python. Additionally, it uses the NEAT (NeuroEvolution of Augmenting Topologies) library to train a neural network to play the game. The goal is to have the neural network learn how to control the bird in the game to navigate through pipes and achieve the highest score possible.

The main components of the program include:

Bird class: represents the flappy bird with attributes such as position, velocity, rotation, and image. It has methods to move and jump the bird.
Pipe class: represents the pipes that the bird must navigate through with attributes such as position, height, and image. It has methods to move and check for collisions with the bird.
Base class: represents the ground that the bird is flying above with attributes such as position, velocity, and image. It has a method to move the ground.
Game window: the Pygame window where all the graphics are displayed.
NEAT integration: the program uses the NEAT library to train a neural network to control the bird. The eval_genomes function runs the simulation of the current population of birds and sets their fitness based on the distance they reach in the game.
The program has a main loop that runs the game and updates the graphics on the screen. The user can control the bird by pressing the space bar to make it jump. The neural network is trained by running the simulation multiple times with different populations of birds and selecting the fittest individuals to reproduce and mutate. The best neural network can be saved to a file for later use.

# Q Learning Algorithm 
Q-learning is a type of reinforcement learning algorithm that aims to learn the optimal action to take at each state of an environment to maximize the cumulative reward. It is a value-based algorithm, meaning that it learns the value of each action at each state, which is represented by the Q-value. The Q-value is updated iteratively based on the observed rewards and the maximum Q-value of the next state. The algorithm continues to update the Q-values until it converges to the optimal policy.
  

![Alt text]("https://cdn-media-1.freecodecamp.org/images/s39aVodqNAKMTcwuMFlyPSy76kzAmU5idMzk")
<img align="right" alt="GIF" src="https://cdn-media-1.freecodecamp.org/images/s39aVodqNAKMTcwuMFlyPSy76kzAmU5idMzk" width="500" height="320" style="border-radius:50%" />



