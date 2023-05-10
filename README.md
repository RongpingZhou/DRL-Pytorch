<div align=center>
<img src="https://github.com/XinJingHao/RL-Algorithms-by-Pytorch/blob/main/RL_PYTORCH.jpg" width=500 />
</div>

I found the current implementations of Reinforcement Learning Algorithms are somewhat complicated, which is hard to get start.

Here are some classical Reinforcement Learning Algorithms implemented by Pytorch. I tried to make them **clean, robust, and unified**, hoping to help you get start with RL quickly.

Now I have finished **Q-learning, DQN, DDQN, PPO discrete, PPO continuous, TD3, SAC Continuous, SAC Discrete, and Actor-Sharer-Learner (ASL)**. I will implement more in the future.

### [Q-learning:](https://github.com/XinJingHao/Q-learning)
<img src="https://github.com/XinJingHao/Q-learning/blob/main/result.svg" width=320>

### [DQN/DDQN on Classic Control:](https://github.com/XinJingHao/DQN-DDQN-Pytorch)
<img src="https://github.com/XinJingHao/DQN-DDQN-Pytorch/blob/main/IMGs/DQN_DDQN_result.png" width=700>


### [DQN/DDQN on Atari Game:](https://github.com/XinJingHao/DQN-DDQN-Atari-Pytorch)
Pong| Enduro
:-----------------------:|:-----------------------:|
<img src="https://github.com/XinJingHao/DQN-DDQN-Atari-Pytorch/raw/main/IMGs/Pong.png" width="320" height="200">| <img src="https://github.com/XinJingHao/DQN-DDQN-Atari-Pytorch/raw/main/IMGs/Enduro.png" width="320" height="200">

### [PPO Discrete:](https://github.com/XinJingHao/PPO-Discrete-Pytorch)
<img src="https://github.com/XinJingHao/PPO-Discrete-Pytorch/blob/main/result.jpg" width=700>

### [PPO Continuous:](https://github.com/XinJingHao/PPO-Continuous-Pytorch)
<img src="https://github.com/XinJingHao/PPO-Continuous-Pytorch/blob/main/ppo_result.jpg">

### [TD3:](https://github.com/XinJingHao/TD3-Pytorch)
<img src="https://github.com/XinJingHao/TD3-Pytorch/blob/main/images/TD3results.png" width=700>

### [SAC Continuous:](https://github.com/XinJingHao/SAC-Continuous-Pytorch)
<img src="https://github.com/XinJingHao/SAC-Continuous-Pytorch/blob/main/imgs/result.jpg" width=700>

### [SAC Discrete:](https://github.com/XinJingHao/SAC-Discrete-Pytorch)
<img src="https://github.com/XinJingHao/SAC-Discrete-Pytorch/blob/main/imgs/sacd_result.jpg" width=700>

### [Actor-Sharer-Learner (ASL):](https://github.com/XinJingHao/Actor-Sharer-Learner)
<div align="left">
<img width="70%" height="auto" src="https://github.com/XinJingHao/Images/blob/main/asl/ss_e.svg">
</div>


# References
DQN: Mnih V , Kavukcuoglu K , Silver D , et al. Playing Atari with Deep Reinforcement Learning[J]. Computer Science, 2013. 

Double DQN: Hasselt H V , Guez A , Silver D . Deep Reinforcement Learning with Double Q-learning[J]. Computer ence, 2015.

PPO: [Proximal Policy Optimization Algorithms](https://arxiv.org/pdf/1707.06347.pdf), [Emergence of Locomotion Behaviours in Rich Environments](https://arxiv.org/pdf/1707.02286.pdf) 

TD3: Fujimoto S , Hoof H V , Meger D . Addressing Function Approximation Error in Actor-Critic Methods[J]. 2018.

SAC: 

Haarnoja T, Zhou A, Abbeel P, et al. Soft actor-critic: Off-policy maximum entropy deep reinforcement learning with a stochastic actor[C]//International conference on machine learning. PMLR, 2018: 1861-1870.

[Soft Actor-Critic Algorithms and Applications](https://arxiv.org/pdf/1812.05905.pdf)

Christodoulou P. Soft actor-critic for discrete action settings[J]. arXiv preprint arXiv:1910.07207, 2019.


ASL: [Train a Real-world Local Path Planner in One Hour via Partially Decoupled Reinforcement Learning and Vectorized Diversity](https://arxiv.org/abs/2305.04180)

