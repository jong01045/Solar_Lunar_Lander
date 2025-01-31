

# Lunar Lander Reinforcement Learning Project

## Overview

Welcome to the **Lunar Lander Reinforcement Learning Project**! This project is part of the CM50270: Reinforcement Learning course at the University of Bath. Our goal is to apply advanced reinforcement learning (RL) techniques to solve the **Lunar Lander** problem, where an agent must learn to safely land a spacecraft on the moon's surface. The problem is challenging due to its continuous state and action spaces, making it an ideal candidate for function-approximated RL methods.

In this project, we explore and implement various RL algorithms to train an agent that can successfully navigate the lunar environment, optimize fuel consumption, and achieve a safe landing. We evaluate the performance of our agent and compare it against baseline models to demonstrate the effectiveness of our approach.

## Problem Description

The **Lunar Lander** environment simulates a spacecraft attempting to land on the moon. The agent controls the spacecraft by firing engines to adjust its position, velocity, and orientation. The goal is to land the spacecraft safely within a designated landing zone while minimizing fuel consumption. The environment provides continuous state observations, including the spacecraft's position, velocity, angle, and angular velocity, and requires continuous actions to control the engines.

### Key Challenges:
- **Continuous State and Action Spaces:** The state space is high-dimensional, and the action space is continuous, making it unsuitable for tabular RL methods.
- **Sparse Rewards:** The agent receives rewards only when it lands successfully or crashes, making it difficult to learn optimal policies.
- **Fuel Optimization:** The agent must balance between achieving a safe landing and minimizing fuel usage.

## Methods

We implemented and evaluated several **function-approximated reinforcement learning algorithms** to solve the Lunar Lander problem. These include:

1. **Deep Q-Networks (DQN):** A value-based RL algorithm that uses a neural network to approximate the Q-value function.
2. **Proximal Policy Optimization (PPO):** A policy-gradient method that optimizes the policy directly while ensuring stable updates.
3. **Soft Actor-Critic (SAC):** An off-policy actor-critic algorithm that maximizes both the expected return and the policy's entropy, encouraging exploration.

We chose these methods because they are well-suited for environments with continuous state and action spaces, and they have shown promising results in similar control tasks.

## Results

Our trained agent achieved a high level of performance in the Lunar Lander environment. We evaluated the agent's learning progress by comparing its performance before and after training, and we included baselines such as random action selection and human-level performance for comparison. The results demonstrate that our agent successfully learned to land the spacecraft safely and efficiently.

### Key Metrics:
- **Success Rate:** Percentage of successful landings.
- **Fuel Consumption:** Average fuel used per landing.
- **Learning Curve:** Improvement in performance over training episodes.

For detailed results, please refer to the **Project Report** and the **Agent Performance Video** included in the powerpoint.


- **Project Report:** A detailed report outlining the problem definition, methods, results, and discussion.
- **Video Presentation:** A 4-minute video summarizing the project.
- **Agent Performance Video:** A video showing the agent's performance before and after training.
- **Source Code:** All code used to implement and evaluate the RL algorithms.
- **Group Contribution Form:** A form detailing each group member's contributions.

## Contributors

This project was completed by:
- [Jungho Park]
- [Bochen Zhao]
- [Ravikan Thanapanaphruekkul]
- [Sarat Smitinont]
- [Sarut Sunpawatr]

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this `README.md` file further to match your project's specific details and GitHub repository structure. This introduction provides a professional and engaging overview of your project, making it easy for others to understand and replicate your work.
