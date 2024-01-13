# GCRL-Survey
This Repository is aimed to summary how many GCRL algorithms use goal distribution in training

# GCRL-Collection

This repo relates to the survey paper <[Goal-Conditioned Reinforcement Learning: Problems and Solutions](https://arxiv.org/abs/2201.08299)>. We collects widely used benchmark environments and conclude a series of research works for goal-conditioned reinforcement learning (GCRL).

## Summary of collected algorithms

| Approach                                                                                                                                                                                                                                                                                                                                           | Resolved Goal Type | Sub-Goal | Relabel | Optimization |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:------------------:|:--------:|:-------:|:------------:|
| [UVFA](http://proceedings.mlr.press/v37/schaul15.pdf)                                                                                                                                                                                                                                                                                              | Vector/Image       |          |         | ✅            |
| [HER](https://proceedings.neurips.cc/paper/2017/file/453fadbd8a1a3af50a9df4df899537b5-Paper.pdf)                                                                                                                                                                                                                                                   | Vector/Image       |          | ✅       |              |
| [Laplacian Representation Learning](https://arxiv.org/pdf/1810.04586.pdf)                                                                                                                                                                                                                                                                          | Vector/Image       |          |         | ✅            |
| [SR](https://proceedings.neurips.cc/paper/2019/file/64c26b2a2dcf068c49894bd07e0e6389-Paper.pdf)                                                                                                                                                                                                                                                    | Vector/Image       |          |         | ✅            |
| [DDL](https://arxiv.org/pdf/1907.08225.pdf)                                                                                                                                                                                                                                                                                                        | Vector/Image       | ✅        |         | ✅            |
| [SoRB](https://proceedings.neurips.cc/paper/2019/file/5c48ff18e0a47baaf81d8b8ea51eec92-Paper.pdf)                                                                                                                                                                                                                                                  | Vector/Image       | ✅        |         |              |
| [Skew-Fit](https://arxiv.org/pdf/1903.03698.pdf)                                                                                                                                                                                                                                                                                                   | Vector             | ✅        |         |              |
| [HER with Demonstrations](https://arxiv.org/pdf/1709.10089.pdf)                                                                                                                                                                                                                                                                                    | Vector             |          |         | ✅            |
| [GoalGAN](http://proceedings.mlr.press/v80/florensa18a/florensa18a.pdf)                                                                                                                                                                                                                                                                            | Vector             | ✅        |         |              |
| [Sub-goal Discovery](https://proceedings.neurips.cc/paper/2019/file/6f518c31f6baa365f55c38d11cc349d1-Paper.pdf)                                                                                                                                                                                                                                    | Vector             | ✅        |         |              |
| [HGG](https://proceedings.neurips.cc/paper/2019/file/57db7d68d5335b52d5153a4e01adaa6b-Paper.pdf)                                                                                                                                                                                                                                                   | Vector             | ✅        |         |              |
| [CHER](https://proceedings.neurips.cc/paper/2019/file/83715fd4755b33f9c3958e1a9ee221e1-Paper.pdf)                                                                                                                                                                                                                                                  | Vector             |          | ✅       |              |
| [G-HER](https://www.sciencedirect.com/science/article/pii/S0925231219308495)                                                                                                                                                                                                                                                                       | Vector             |          | ✅       |              |
| [Hindsight Planner](https://ifaamas.org/Proceedings/aamas2020/pdfs/p690.pdf)                                                                                                                                                                                                                                                                       | Vector             | ✅        |         |              |
| [GDP](https://www.researchgate.net/profile/Diego-Faria-2/publication/344237429_Goal_Density-based_Hindsight_Experience_Prioritization_for_Multi-Goal_Robot_Manipulation_Reinforcement_Learning/links/5f5f4d904585154dbbd03279/Goal-Density-based-Hindsight-Experience-Prioritization-for-Multi-Goal-Robot-Manipulation-Reinforcement-Learning.pdf) | Vector             |          | ✅       |              |
| [VDS](https://proceedings.neurips.cc/paper/2020/file/566f0ea4f6c2e947f36795c8f58ba901-Paper.pdf)                                                                                                                                                                                                                                                   | Vector             | ✅        |         |              |
| [MEGA](http://proceedings.mlr.press/v119/pitis20a/pitis20a.pdf)                                                                                                                                                                                                                                                                                    | Vector             | ✅        | ✅       |              |
| [PlanGAN](https://proceedings.neurips.cc/paper/2020/file/6101903146e4bbf4999c449d78441606-Paper.pdf)                                                                                                                                                                                                                                               | Vector             |          |         | ✅            |
| [AIM](https://proceedings.neurips.cc/paper/2021/file/486c0401c56bf7ec2daa9eba58907da9-Paper.pdf)                                                                                                                                                                                                                                                   | Vector             |          |         | ✅            |
| [I-HER](https://arxiv.org/pdf/2110.02414.pdf)                                                                                                                                                                                                                                                                                                      | Vector             |          |         | ✅            |
| [GCSL](https://arxiv.org/pdf/1912.06088.pdf)                                                                                                                                                                                                                                                                                                       | Vector             |          |         | ✅            |
| [MapGo](https://arxiv.org/pdf/2105.06350.pdf)                                                                                                                                                                                                                                                                                                      | Vector             |          | ✅       | ✅            |
| [L3P](http://proceedings.mlr.press/v139/zhang21x/zhang21x.pdf)                                                                                                                                                                                                                                                                                     | Vector             |          |         | ✅            |
| [RIG](https://proceedings.neurips.cc/paper/2018/file/7ec69dd44416c46745f6edd947b470cd-Paper.pdf)                                                                                                                                                                                                                                                   | Image              | ✅        |         |              |
| [DISCERN](https://arxiv.org/pdf/1811.11359.pdf)                                                                                                                                                                                                                                                                                                    | Image              | ✅        |         |              |
| [HVF](https://arxiv.org/pdf/1909.05829.pdf)                                                                                                                                                                                                                                                                                                        | Image              | ✅        |         |              |
| [AMIGo](https://arxiv.org/pdf/2006.12122.pdf)                                                                                                                                                                                                                                                                                                      | Image              | ✅        |         |              |
| [GAP](http://proceedings.mlr.press/v119/nair20a/nair20a.pdf)                                                                                                                                                                                                                                                                                       | Image              |          |         | ✅            |
| [LEXA](https://arxiv.org/pdf/2110.09514.pdf)                                                                                                                                                                                                                                                                                                       | Image              |          |         | ✅            |

## Widely used benchmark environments.

Update: Most of these environments has been integrated in [Gymnasium-Robotics](https://robotics.farama.org/).

Note almost all environments support various kinds of goal structures, i.e., vector, image, language, etc.

| Environment                                                                         | Benchmark Type        | Common Used Goal Structure | Description                                                                |
| ----------------------------------------------------------------------------------- | --------------------- | -------------------------- | -------------------------------------------------------------------------- |
| [FetchReach](https://github.com/Farama-Foundation/Gym-Robotics)                     | Gym Robotics/Mujoco   | Vector/Image               | A robotic arm reaches a target position                                    |
| [FetchPush](https://github.com/Farama-Foundation/Gym-Robotics)                      | Gym Robotics/Mujoco   | Vector/Image               | A robotic arm pushes a block to a target position                          |
| [FetchPickAndPlace](https://github.com/Farama-Foundation/Gym-Robotics)              | Gym Robotics/Mujoco   | Vector/Image               | A robotic arm first picks up the block then places it to a target position |
| [FetchSlide](https://github.com/Farama-Foundation/Gym-Robotics)                     | Gym Robotics/Mujoco   | Vector/Image               | A robotic arm slides a buck to a goal position                             |
| [HandManipulateBlock](https://github.com/Farama-Foundation/Gym-Robotics)            | Gym Robotics/Mujoco   | Vector/Image               | Orient a block using a robot hand                                          |
| [HandManipulateEgg](https://github.com/Farama-Foundation/Gym-Robotics)              | Gym Robotics/Mujoco   | Vector/Image               | Orient an egg using a robot hand                                           |
| [HandManipulatePen](https://github.com/Farama-Foundation/Gym-Robotics)              | Gym Robotics/Mujoco   | Vector/Image               | Orient a pen using a robot hand                                            |
| [HalfCheetah](https://github.com/vitchyr/multiworld)                                | Mujoco                | Vector/Image               | Make a 2D cheetah robot run and keep a specific speed                      |
| [AntLocomotion/Ant Maze](https://sites.google.com/view/goalgeneration4rl)           | Mujoco                | Vector                     | Make a 3D four-legged robot walk to a target position                      |
| [Sawyer](https://github.com/vitchyr/multiworld)                                     | Mujoco                | Vector                     | A sawyer robot reaches a target position                                   |
| [Reacher](https://github.com/vitchyr/multiworld)                                    | Mujoco                | Vector/Image               | A reacher robot reaches a target position                                  |
| [N-D Mass](https://sites.google.com/view/goalgeneration4rl)                         | Mujoco                | Vector                     | A ball reaches a target position                                           |
| [DoorOpening](https://github.com/suraj-nair-1/goal_aware_prediction)                | Mujoco                | Image                      | A sawyer robot opens a door by latching onto the handle                    |
| [Dy-Reaching](https://github.com/mengf1/DHER)                                       | Mujoco                | Image                      | A robotic arm reaches a target position moving along a straight line       |
| [Dy-Circling](https://github.com/mengf1/DHER)                                       | Mujoco                | Image                      | A robotic arm reaches a target position moving along a circle              |
| [Dy-Pushing](https://github.com/mengf1/DHER)                                        | Mujoco                | Image                      | A robotic arm moves the box to a moving target position                    |
| [Dy-Pouring](https://github.com/mengf1/DHER)                                        | Mujoco                | Image                      | A robotic arm grips the can and pours the water into a cup                 |
| [WaterMaze](https://github.com/deepmind/lab)                                        | DeepMind Lab          | Image                      | Get to a target position described by an image                             |
| [Seaquest](https://github.com/mgbellemare/Arcade-Learning-Environment)              | Atari                 | Image                      | Get to a target position described by an image                             |
| [Montezuma’s Revenge](https://github.com/mgbellemare/Arcade-Learning-Environment)   | Atari                 | Image                      | Get to a target position described by an image                             |
| [Reacher](https://github.com/deepmind/dm_control/tree/main/dm_control/suite)        | DeepMind Control Suit | Image                      | A two-link planar reacher poses an aimed shape                             |
| [Manipulator](https://github.com/deepmind/dm_control/tree/main/dm_control/suite)    | DeepMind Control Suit | Image                      | A 3-DoF finger robot rotates the body into a target orientation            |
| [Finger](https://github.com/google-research/google-research/tree/master/c_learning) | DeepMind Control Suit | Image                      | A planar manipulator brings an object in a target location                 |
| [Place Object in Tray](https://sites.google.com/view/val-rl)                        | PyBullet              | Image                      | A robotic arm puts toys into a tray                                        |
| [Opening Drawer](https://sites.google.com/view/val-rl)                              | PyBullet              | Image                      | A robotic arm opens the drawer                                             |
| [PickandPlace](https://sites.google.com/view/val-rl)                                | PyBullet              | Image                      | A robotic arm first picks up the block then places it to a target position |
| [Five Object Manipulation](https://github.com/google-research/clevr_robot_env)      | CLEVR-Robot/Mujoco    | Image/Language             | A point mass agent arranges, orders and sorts 5 fixed objects              |
| [Diverse Object Manipulation](https://github.com/google-research/clevr_robot_env)   | CLEVR-Robot/Mujoco    | Image/Language             | A point mass agent orders objects in different shapes and colors           |
| [Playground](https://github.com/flowersteam/playground_env)                         | Playground            | Image/Language             | A 2D hand moves and grasps/releases different objects                      |
| [VizDoom](https://github.com/mwydmuch/ViZDoom)                                      | ViZDoom               | Image/Language             | AI bots reach specific place in the first person shooter 3D game Doom      |
