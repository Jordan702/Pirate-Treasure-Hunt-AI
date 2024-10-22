# Pirate-Treasure-Hunt-AI
CS-370 Final Project
Project Overview:
This project, titled "Pirate Intelligent Agent: Treasure Hunt Game," applies reinforcement learning (specifically deep Q-learning) to train an agent to navigate a maze and find treasure. The pirate intelligent agent learns how to avoid obstacles, explore the maze, and optimize its path toward the treasure. The goal is to demonstrate the application of AI to solve pathfinding problems within game environments.

Work Completed:
Code Provided:
The base environment, including the maze layout and the framework for defining the agent's state and actions, was pre-supplied. The project also came with an initial version of the Q-learning algorithm structure.

Code Created by Me:
I developed the following:

Custom reward functions to guide the agent toward the treasure and penalize it for running into obstacles.
The deep Q-learning model, implemented using TensorFlow, which includes tuning hyperparameters such as learning rate, gamma, epsilon, and decay strategies.
A replay buffer to allow the agent to learn from past experiences efficiently.
Visualizations to track the agent’s learning progress and decision-making.
Learning and Connection to Computer Science:
What Do Computer Scientists Do? Computer scientists create solutions to real-world problems using algorithms, data structures, and software. In this project, reinforcement learning is used to solve a game-based problem, but the approach can be adapted for other applications like robotics, navigation, and autonomous systems.

How Do I Approach a Problem as a Computer Scientist? The problem was broken down into smaller pieces: first, designing the environment and state-action space for the agent, then implementing a reward system that guided the agent toward optimal behavior, and finally improving the model’s performance through experimentation with different learning algorithms and neural networks. Critical thinking, iteration, and debugging were key aspects of this process.

Ethical Responsibilities: When developing AI systems, it’s important to ensure fairness, transparency, and privacy. Although this is a game-based project, in real-world applications of reinforcement learning, these systems must be designed to avoid biases and unfair advantages. Additionally, privacy concerns arise when AI interacts with sensitive data, such as user behavior in games or other applications. Future iterations of the project could include logging agent decisions to improve transparency.

Reflection on the Project:
Application of Reinforcement Learning:
The use of deep Q-learning allowed the agent to learn through exploration and feedback (rewards and penalties). The integration of neural networks to approximate the agent’s action-value function significantly enhanced its ability to generalize and adapt to new situations in the maze.

Challenges Faced:
One of the biggest hurdles was balancing exploration and exploitation for the agent. Tuning hyperparameters like epsilon and gamma required several iterations to find the optimal setup that allowed the agent to learn efficiently without getting stuck in suboptimal paths.

Outcome:
The agent successfully learned to navigate the maze, demonstrating the power of reinforcement learning in solving complex problems. The project serves as a practical showcase of how AI can be applied in game environments and beyond.
