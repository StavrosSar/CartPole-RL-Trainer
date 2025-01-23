# **CartPole-v1 Reinforcement Learning with Tree-Based Models**

This project trains and evaluates various tree-based machine learning models to solve the CartPole-v1 environment from OpenAI Gym. The goal is to balance the pole on the cart as long as possible by predicting the optimal actions based on observations.

---

## **Overview**

In this project:
- A memory of episodes is collected by randomly sampling actions in the CartPole-v1 environment.
- **Tree-based models** such as ExtraTreesRegressor, AdaBoostRegressor, and RandomForestRegressor are trained to predict combined rewards based on observations.
- These models are evaluated for their performance in guiding the agent to maximize rewards.

---

## **Key Features**

- **Data Collection**: Random sampling to gather observation, action, and reward data.
- **Training**: Tree-based models trained on features and a reward-combination target (`comb_reward`).
- **Evaluation**: Models predict optimal actions for 100 episodes, and their average rewards are compared.

---
