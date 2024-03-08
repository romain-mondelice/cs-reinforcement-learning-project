# Reinforcement Learning Group Project - Super Mario Bros 2

## Team Members

- Romain MONDELICE
- Hanyun HU
- Olav DE CLERCK

## Date

February 18, 2024

## Abstract

The primary objective of this project is to design and implement a reinforcement learning agent that can successfully navigate and complete levels in Super Mario Bros 2. The agent aims to demonstrate proficiency in learning game mechanics, obstacle avoidance, enemy interaction, and level completion strategies.

## Introduction

Our group is collectively intrigued by the application of reinforcement learning in creating intelligent agents that can autonomously play video games. Driven by the ambition to develop an agent proficient in navigating the complexities of a sophisticated game, we have chosen Super Mario Bros 2 as our project focus.

## Method

### The gym-super-mario-bros Environment

The gym-super-mario-bros package is an open-source reinforcement learning environment, built on top of the OpenAI Gym interface, providing a standardized way of developing AI agents for Super Mario Bros. It abstracts the game into a series of states, actions, and rewards, allowing the agent to interact with the game purely through RL principles.

- **States:** The environment represents the game state as a snapshot of the current frame, which can be processed into a format suitable for the learning algorithm. This includes the position of Mario, enemies, obstacles, and other relevant environmental features.
- **Actions:** The agent can perform a series of discrete actions, such as moving left or right, jumping, and combinations of these movements, to navigate through the game world.
- **Rewards:** The reward system is designed to encourage progress through the game, with points awarded for advancing in the level, collecting items, defeating enemies, and completing levels.

### Learning Algorithm

The project will explore various reinforcement learning algorithms, such as Q-Learning, Deep Q-Networks (DQN), or more advanced techniques like Proximal Policy Optimization (PPO), to find the most effective strategy for this specific task. Key components include:

1. **Preprocessing and Feature Extraction:** Simplifying the game’s state representation to focus on relevant information, reducing the computational complexity.
2. **Network Architecture:** Designing a neural network architecture that can process state inputs and output a policy for selecting actions.
3. **Training and Optimization:** Training the agent through episodes of gameplay, using reward signals to adjust the policy towards optimal game-playing behavior.
4. **Evaluation:** Assessing the agent’s performance based on its ability to complete levels, its efficiency (time and steps taken), and its adaptability to new or unseen game scenarios.

## Complexity and Challenges

Developing an AI agent for Super Mario Bros presents a multifaceted challenge, characterized by the game’s dynamic environment, high-dimensional state space, and the need for adaptable and generalizable strategies. Key challenges include:

- Dynamic and unpredictable elements.
- Variety of levels.
- High-dimensional state space.
- Development of generalizable strategies.
- Optimization of reward structures.
- Technical and computational challenges.

## References

- Greg Brockman et al., OpenAI Gym. arXiv preprint arXiv:1606.01540, 2016.
- Niels Justesen et al., Illuminating generalization in deep reinforcement learning through procedural level generation. arXiv preprint arXiv:1806.10729, 2019.
- Christian Kauten, gym-super-mario-bros. https://github.com/Kautenja/gym-super-mario-bros, 2018.
- Volodymyr Mnih et al., Human-level control through deep reinforcement learning. Nature, 518(7540):529–533, 2015.
- Richard S. Sutton and Andrew G. Barto, Reinforcement Learning: An Introduction. MIT Press, 2 edition, 2018.
