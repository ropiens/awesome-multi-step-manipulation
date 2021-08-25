# Awesome-multi-step-manipulation

>  Inspired by the [awesome](https://github.com/sindresorhus/awesome) list and [awesome-long-horizon-goal-reaching](https://github.com/Mehooz/awesome-long-horizon-goal-reaching).

Reading list by [Junyeob Baek](https://github.com/CUN-bjy) , with help from [Haegu Lee](https://github.com/benthebear93). 

This repository is one of project deliverables for [project-sandwich-man](https://github.com/ropiens/project-sandwich-man), which project is especially focused on hierarchical stacking blocks. If you see papers missing from the list, please send me an email or a pull request.



## Table of Contents

- [Awesome-block-stacking-manipulation](#awesome-block-stacking-manipulation)
  * [Table of Contents](#table-of-contents)
  * [Core Area](#core-area)
    + [Approach from TAMP](#approach-from-tamp)
    + [Approach from Hierarchical RL](#approach-from-hierarchical-rl)
    + [Multi-step Manipulation](#multi-step-manipulation)
    + [Multi-goal Task Approach](#multi-goal-task-approach)
    + [Approach from Relational RL](#approach-from-relational-rl)
    + [Good Environment to Start](#good-environment-to-start)
    + [Further More](#further-more)

</br>

## Core Area

### Approach from TAMP

- [Classical TAMP vs Learning-based TAMP](http://web.mit.edu/caelan/www/presentations/6.881_TAMP.pdf)
- [Classical TAMP](https://www.ics.uci.edu/~kkask/Fall-2014%20CS271/slides/09-planning.pdf)



### Approach from Hierarchical RL

- [nikhilbarhate99/Hierarchical-Actor-Critic-HAC-PyTorch](https://github.com/nikhilbarhate99/Hierarchical-Actor-Critic-HAC-PyTorch)
- [Hierarchical Deep Reinforcement Learning (HDQN)](https://bluediary8.tistory.com/4)
- [Learning Multi-Level Hierarchies with Hindsight(HAC)](https://arxiv.org/abs/1712.00948)
- [Introduce to HRL](http://khanrc.github.io/RL-Hierarchy.html) 
- [Meta-Learning shared Hierarchy(MLSH)](https://openai.com/blog/learning-a-hierarchy)
- [Article : The Promise of Hierarchical Reinforcement Learning](https://thegradient.pub/the-promise-of-hierarchical-reinforcement-learning)


### Multi-step Manipulation
(for long-horizon tasks)

- [A Long Horizon Planning Framework for Manipulating Rigid Pointcloud Objects](https://anthonysimeonov.github.io/rpo-planning-framework/)
  - its manipulation skills from [here](https://sci-hub.se/https://ieeexplore.ieee.org/abstract/document/9196976)
- [Hierarchical Reinforcement Learning with Universal Policies for Multi-Step Robotic Manipulation](https://ieeexplore.ieee.org/abstract/document/9366328), [video](https://www.youtube.com/watch?v=n_wQuf4r0qk)
- [Planning for Multi-Stage Forceful Manipulation](https://arxiv.org/abs/2101.02679)


### Multi-goal Task Approach

- [Hindsight Experience Replay](https://arxiv.org/abs/1707.01495)
- [CURIOUS: Intrinsically Motivated Modular Multi-Goal Reinforcement Learning](https://arxiv.org/pdf/1810.06284.pdf)



### Approach from Relational RL

- [Towards Practical Multi-Object Manipulation using Relational Reinforcement Learning](https://richardrl.github.io/relational-rl/)



### Good Environment to Start

-  [IanYangChina/pybullet_multigoal_gym](https://github.com/IanYangChina/pybullet_multigoal_gym), paper : https://arxiv.org/pdf/2105.05985.pdf
-  [qgallouedec/panda-gym](https://github.com/qgallouedec/panda-gym) -> pre-trained model on [rl-baselines3-zoo](https://github.com/DLR-RM/rl-baselines3-zoo)

---

### Further More

- [IKEA Furniture Assembly Environment for Long-Horizon Complex Manipulation Tasks](https://arxiv.org/pdf/1911.07246.pdf), (https://clvrai.github.io/furniture)
- [Learning to guide task and motion planning using score-space representation](https://journals.sagepub.com/doi/pdf/10.1177/0278364919848837)
- [Self-play for goal discovery in robotics manipulation](https://robotics-self-play.github.io/)
- [Transporter Network: Rearranging the Visual World for Robotic Manipulation](https://transporternets.github.io/)
- [CAVIN: Dynamics Learning with Cascaded Variational Inference for Multi-Step Manipulation](http://pair.stanford.edu/cavin/)
- [Neural Task Programming: Learning to Generalize Across Hierarchical Tasks](https://stanfordvl.github.io/ntp/)
