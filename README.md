# GCRL-Survey
This Repository is aimed to summary how many GCRL algorithms use goal distribution in training

## Summary of collected algorithms

| Approach                                                                                                                                                                                                                                                                                                                                           | Resolved Goal Type | Sub-Goal | Relabel | Optimization | Use Env Goal Distribution in training |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:------------------:|:--------:|:-------:|:------------:|:------------:|
| [UVFA](http://proceedings.mlr.press/v37/schaul15.pdf)                                                                                                                                                                                                                                                                                              | Vector/Image       |          |         | ✅            | ✅ 1           |
| [HER](https://proceedings.neurips.cc/paper/2017/file/453fadbd8a1a3af50a9df4df899537b5-Paper.pdf)                                                                                                                                                                                                                                                   | Vector/Image       |          | ✅       |              | ✅ 1           |
| [Laplacian Representation Learning](https://arxiv.org/pdf/1810.04586.pdf)                                                                                                                                                                                                                                                                          | Vector/Image       |          |         | ✅            | ✅  1          |
| [SR](https://proceedings.neurips.cc/paper/2019/file/64c26b2a2dcf068c49894bd07e0e6389-Paper.pdf)                                                                                                                                                                                                                                                    | Vector/Image       |          |         | ✅            | ✅  1          |
| [DDL](https://arxiv.org/pdf/1907.08225.pdf)                                                                                                                                                                                                                                                                                                        | Vector/Image       | ✅        |         | ✅            |             |
| [SoRB](https://proceedings.neurips.cc/paper/2019/file/5c48ff18e0a47baaf81d8b8ea51eec92-Paper.pdf)                                                                                                                                                                                                                                                  | Vector/Image       | ✅        |         |              | ✅   1        |
| [Skew-Fit](https://arxiv.org/pdf/1903.03698.pdf)                                                                                                                                                                                                                                                                                                   | Vector             | ✅        |         |              |             |
| [HER with Demonstrations](https://arxiv.org/pdf/1709.10089.pdf)                                                                                                                                                                                                                                                                                    | Vector             |          |         | ✅            | ✅  demon          |
| [GoalGAN](http://proceedings.mlr.press/v80/florensa18a/florensa18a.pdf)                                                                                                                                                                                                                                                                            | Vector             | ✅        |         |              |     GAN        |
| [Sub-goal Discovery](https://proceedings.neurips.cc/paper/2019/file/6f518c31f6baa365f55c38d11cc349d1-Paper.pdf)                                                                                                                                                                                                                                    | Vector             | ✅        |         |              | ✅  expert          |
| [HGG](https://proceedings.neurips.cc/paper/2019/file/57db7d68d5335b52d5153a4e01adaa6b-Paper.pdf)                                                                                                                                                                                                                                                   | Vector             | ✅        |         |              | ✅    1        |
| [CHER](https://proceedings.neurips.cc/paper/2019/file/83715fd4755b33f9c3958e1a9ee221e1-Paper.pdf)                                                                                                                                                                                                                                                  | Vector             |          | ✅       |              | ✅   1         |
| [G-HER](https://www.sciencedirect.com/science/article/pii/S0925231219308495)                                                                                                                                                                                                                                                                       | Vector             |          | ✅       |              | ✅  1          |
| [Hindsight Planner](https://ifaamas.org/Proceedings/aamas2020/pdfs/p690.pdf)                                                                                                                                                                                                                                                                       | Vector             | ✅        |         |              | ✅ 1           |
| [GDP](https://www.researchgate.net/profile/Diego-Faria-2/publication/344237429_Goal_Density-based_Hindsight_Experience_Prioritization_for_Multi-Goal_Robot_Manipulation_Reinforcement_Learning/links/5f5f4d904585154dbbd03279/Goal-Density-based-Hindsight-Experience-Prioritization-for-Multi-Goal-Robot-Manipulation-Reinforcement-Learning.pdf) | Vector             |          | ✅       |              | ✅   1         |
| [VDS](https://proceedings.neurips.cc/paper/2020/file/566f0ea4f6c2e947f36795c8f58ba901-Paper.pdf)                                                                                                                                                                                                                                                   | Vector             | ✅        |         |              | ✅ 1 *           |
| [MEGA](http://proceedings.mlr.press/v119/pitis20a/pitis20a.pdf)                                                                                                                                                                                                                                                                                    | Vector             | ✅        | ✅       |              | ✅  pick with < α          |
| [PlanGAN](https://proceedings.neurips.cc/paper/2020/file/6101903146e4bbf4999c449d78441606-Paper.pdf)                                                                                                                                                                                                                                               | Vector             |          |         | ✅            | ✅ 1           |
| [AIM](https://proceedings.neurips.cc/paper/2021/file/486c0401c56bf7ec2daa9eba58907da9-Paper.pdf)                                                                                                                                                                                                                                                   | Vector             |          |         | ✅            | ✅ 1           |
| [I-HER](https://arxiv.org/pdf/2110.02414.pdf)                                                                                                                                                                                                                                                                                                      | Vector             |          |         | ✅            | ✅  1 same with her          |
| [GCSL](https://arxiv.org/pdf/1912.06088.pdf)                                                                                                                                                                                                                                                                                                       | Vector             |          |         | ✅            | ✅  1        |
| [MapGo](https://arxiv.org/pdf/2105.06350.pdf)                                                                                                                                                                                                                                                                                                      | Vector             |          | ✅       | ✅            | ✅  1          |
| [L3P](http://proceedings.mlr.press/v139/zhang21x/zhang21x.pdf)                                                                                                                                                                                                                                                                                     | Vector             |          |         | ✅            | ✅  1          |
| [RIG](https://proceedings.neurips.cc/paper/2018/file/7ec69dd44416c46745f6edd947b470cd-Paper.pdf)                                                                                                                                                                                                                                                   | Image              | ✅        |         |              | ✅            |
| [DISCERN](https://arxiv.org/pdf/1811.11359.pdf)                                                                                                                                                                                                                                                                                                    | Image              | ✅        |         |              | ✅            |
| [HVF](https://arxiv.org/pdf/1909.05829.pdf)                                                                                                                                                                                                                                                                                                        | Image              | ✅        |         |              | ✅            |
| [AMIGo](https://arxiv.org/pdf/2006.12122.pdf)                                                                                                                                                                                                                                                                                                      | Image              | ✅        |         |              | ✅            |
| [GAP](http://proceedings.mlr.press/v119/nair20a/nair20a.pdf)                                                                                                                                                                                                                                                                                       | Image              |          |         | ✅            | ✅            |
| [LEXA](https://arxiv.org/pdf/2110.09514.pdf)                                                                                                                                                                                                                                                                                                       | Image              |          |         | ✅            | ✅            |
