# Online vs. Offline Adaptive Domain Randomization Benchmark
##### Gabriele Tiboni, Karol Arndt, Giuseppe Averta, Ville Kyrki, Tatiana Tommasi.

This repository contains the code for the paper: "Online vs. Offline Adaptive Domain Randomization Benchmark" submitted to the 15th International Workshop on Human-Friendly Robotics, in June 2022.<!-- , in December 2021. -->

*Abstract:* Physics simulators have shown great promise for conveniently learning reinforcement learning policies in safe, unconstrained environments. However, transferring the acquired knowledge to the real world can be challenging due to the reality gap. To this end, several methods have been recently proposed to automatically tune simulator parameters with posterior distributions given real data, for use with domain randomization at training time. These approaches have been shown to work for various robotic tasks under different settings and assumptions. Nevertheless, existing literature lacks a thorough comparison of existing adaptive domain randomization methods with respect to transfer performance and real-data efficiency. In this work, we present an open benchmark for both offline and online methods (SimOpt, BayRn, DROID, DROPO), to shed light on which are most suitable for each setting and task at hand. We found that online methods are limited by the quality of the currently learned policy for the next iteration, while offline methods may sometimes fail when replaying trajectories in simulation with open-loop commands.

<img src="https://www.gabrieletiboni.com/assets/online_vs_offline_adr_compact.png" style="width: 80%; max-width: 800px; display: inline-block; margin: 0px auto; text-align: center;" />

Our release is **in progress**, you can track it below:

- [ ] MuJoCo Environments
- [ ] Methods
- [ ] Target Trajectory Data



## Cite us
If you use this repository, please consider citing
        
        @misc{tiboniadrbenchmark,
            title={Online vs. Offline Adaptive Domain Randomization Benchmark},
            author={Tiboni, Gabriele and Arndt, Karol and Averta, Giuseppe and Kyrki, Ville and Tommasi, Tatiana},
            year={2022},
            primaryClass={cs.RO},
            publisher={arXiv},
            doi={10.48550/ARXIV.2206.14661}
        }
