# PPO_From_Scratch

Proximal Policy Optimization, or PPO, is a policy gradient method for reinforcement learning. The motivation was to have an algorithm with the data efficiency and reliable performance of TRPO, while using only first-order optimization.

In 2017, Schulman et al. introduced Proximal Policy Optimization (PPO), building on the TRPO foundations.


Proximal policy optimization (PPO) is the state-of the-art most effective model-free reinforcement learning algorithm. Its powerful policy search ability allows an agent to find the optimal policy by trial and error but leads to high computation and low data-efficiency.

Implementing an architecture from scratch is the best way to understand it, and it's a good habit. We have already done it for a value-based method with Q-Learning and a Policy-based method with Reinforce.

So, to be able to code it, we're going to use two resources:

A tutorial made by Costa Huang. Costa is behind CleanRL, a Deep Reinforcement Learning library that provides high-quality single-file implementation with research-friendly features.
In addition to the tutorial, to go deeper, you can read the 13 core implementation details: https://iclr-blog-track.github.io/2022/03/25/ppo-implementation-details/
Then, to test its robustness, we're going to train it in 2 different classical environments:

Cartpole-v1
LunarLander-v2
