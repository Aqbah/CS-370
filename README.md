# Pirate Intelligent Agent – Deep Q-Learning Project

## Overview

This repository contains my implementation of a **Pirate Intelligent Agent** developed as part of a reinforcement learning project. The goal of the project was to design and train a non-player character (NPC) pirate that could successfully navigate a maze and reach a treasure before a human player. This artifact demonstrates my ability to apply **reinforcement learning**, **neural networks**, and **algorithmic problem-solving** techniques to a realistic AI pathfinding problem.

The primary artifact included in this repository is a Jupyter Notebook that implements a **Deep Q-Learning (DQN)** algorithm using TensorFlow and Keras.

---

## Project Description and Contributions

For this project, I was provided with starter code that defined the game environment and supporting infrastructure. This included:

- A `TreasureMaze` environment that modeled the maze, rewards, penalties, and game rules  
- A `GameExperience` class that handled experience replay for reinforcement learning  
- A pre-defined neural network architecture used for approximating Q-values  

My responsibility was to design and implement the **Q-training algorithm** that enables the pirate agent to learn optimal navigation strategies. I created the full deep Q-learning training loop, which included:

- Implementing epsilon-greedy exploration and exploitation logic  
- Managing experience replay and batch training  
- Training a neural network to approximate Q-values  
- Integrating a target network to stabilize learning  
- Validating the trained model using a completion check to ensure the agent could reach the treasure from every valid starting position  

Through iterative training and evaluation, the pirate agent successfully learned an optimal path through the maze and consistently reached the treasure.

---

## Connection to the Field of Computer Science

### What Do Computer Scientists Do and Why Does It Matter?

Computer scientists design, analyze, and improve computational systems that solve real-world problems. This project reflects how computer science concepts—such as algorithms, data structures, and machine learning—are used to build intelligent systems capable of learning and adapting over time. Reinforcement learning techniques like deep Q-learning are widely used in robotics, game development, autonomous systems, and decision-making software, making these skills directly applicable to industry challenges.

---

### How I Approach Problems as a Computer Scientist

I approach problems by breaking them down into smaller, manageable components and designing solutions iteratively. In this project, I analyzed the environment, defined clear success criteria, and incrementally built a learning system that could improve through feedback. I relied on debugging, experimentation, and validation to ensure that the solution was not only functional but also robust and generalizable. This structured, analytical approach is central to how I solve problems as a computer scientist.

---

### Ethical Responsibilities to Users and Organizations

As a computer scientist, I have a responsibility to create systems that are reliable, transparent, and aligned with user expectations. In intelligent systems, this includes ensuring predictable behavior, avoiding unintended bias, and validating that automated decisions perform as intended. From an organizational perspective, ethical responsibilities also include writing maintainable code, following best practices, and ensuring that AI systems are tested thoroughly before deployment. This project reinforced the importance of validating learning outcomes and ensuring consistent behavior across all scenarios.

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- Reinforcement Learning (Deep Q-Learning)  
- Jupyter Notebook  

---

## Portfolio Note

This project serves as a portfolio artifact demonstrating my understanding of **artificial intelligence**, **reinforcement learning**, and **neural network–based decision systems**, and reflects my growth in applying theoretical concepts to practical implementations.
