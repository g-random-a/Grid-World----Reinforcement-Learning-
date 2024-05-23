# Learning Grid World -- Reinforcement

This repository contains implementations of reinforcement learning algorithms applied to a grid world environment. The key algorithms included are Value Iteration, Policy Iteration, and Q-Learning. These notebooks serve as educational resources for understanding the fundamentals of reinforcement learning.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)

## Introduction

Reinforcement learning is a type of machine learning where agents learn to make decisions by taking actions in an environment to maximize cumulative rewards. This repository focuses on demonstrating three fundamental reinforcement learning algorithms:

1. **Value Iteration**: An iterative algorithm to compute the optimal policy by improving the value function.
2. **Policy Iteration**: Alternates between policy evaluation and policy improvement to find the optimal policy.
3. **Q-Learning**: A model-free algorithm that learns the value of actions directly without a model of the environment's dynamics.

## Setup

To run the notebooks, you will need Python and the following libraries installed:

- ``` numpy ```
- ``` matplotlib ```
- ``` jupyter ```

You can install these dependencies using pip:

   ``` pip install numpy matplotlib jupyter ```

## Usage

To explore and run the notebooks, follow these steps:

1. Clone the repository:

    ``` git clone https://github.com/yourusername/Learning-Grid-World-Reinforcement.git ```
    ``` cd Learning-Grid-World-Reinforcement ```

2. Start Jupyter Notebook:

    ``` jupyter notebook ```

3. Open the desired notebook (`Value_Iteration.ipynb`, `Policy_Iteration.ipynb`, or `QLearning.ipynb`) and run the cells to see the algorithms in action.

Alternatively, you can open the notebooks directly in Google Colab:

- [Value Iteration](https://colab.research.google.com/drive/1dPuzhaUrx5pVpfqkVDt-GPSecbjnp4LO#scrollTo=szS3M3OA7htr)
- [Policy Iteration](https://colab.research.google.com/drive/1GVI-JbmvALPYHjfhzHjsOjb1EKKPygvz#scrollTo=gmKH5XgM4vsz)
- [Q-Learning](https://colab.research.google.com/drive/1r0IvBlzotA52UpuFZ_o1-v36fmvNOaMz?usp=sharing#scrollTo=kEB1B5o12adx)

## File Descriptions

- **Value_Iteration.ipynb**: Contains the implementation and explanation of the Value Iteration algorithm applied to a grid world environment.
- **Policy_Iteration.ipynb**: Demonstrates the Policy Iteration algorithm with step-by-step explanations and visualizations.
- **QLearning.ipynb**: Covers the Q-Learning algorithm, a model-free reinforcement learning approach, with examples and code.
