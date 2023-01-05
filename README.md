# Online vs. Offline Adaptive Domain Randomization Benchmark

[Paper](https://arxiv.org/abs/2206.14661) / [Website](https://gabrieletiboni.github.io/adr-benchmark/) / [Video](https://gabrieletiboni.github.io/adr-benchmark/)

##### Gabriele Tiboni, Karol Arndt, Giuseppe Averta, Ville Kyrki, Tatiana Tommasi.

This repository contains the code for the paper "Online vs. Offline Adaptive Domain Randomization Benchmark", published in the Springer Proceedings in Advanced Robotics 2022.

*Abstract:* Physics simulators have shown great promise for conveniently learning reinforcement learning policies in safe, unconstrained environments. However, transferring the acquired knowledge to the real world can be challenging due to the reality gap. To this end, several methods have been recently proposed to automatically tune simulator parameters with posterior distributions given real data, for use with domain randomization at training time. These approaches have been shown to work for various robotic tasks under different settings and assumptions. Nevertheless, existing literature lacks a thorough comparison of existing adaptive domain randomization methods with respect to transfer performance and real-data efficiency. In this work, we present an open benchmark for both offline and online methods (SimOpt, BayRn, DROID, DROPO), to shed light on which are most suitable for each setting and task at hand. We found that online methods are limited by the quality of the currently learned policy for the next iteration, while offline methods may sometimes fail when replaying trajectories in simulation with open-loop commands. [Watch video](https://gabrieletiboni.github.io/adr-benchmark/)

<img src="https://www.gabrieletiboni.com/assets/online_vs_offline_adr_compact.png" style="width: 90%; max-width: 900px;" />

Our release is **under construction**, you can track its progress below:

- [ ] MuJoCo Environments
- [ ] Methods
- [ ] Target Trajectory Data



## Cite us
If you use this repository, please consider citing
```
@InProceedings{tiboniadrbenchmark,
    author="Tiboni, Gabriele and Arndt, Karol and Averta, Giuseppe and Kyrki, Ville and Tommasi, Tatiana",
    editor="Borja, Pablo and Della Santina, Cosimo and Peternel, Luka and Torta, Elena",
    title="Online vs. Offline Adaptive Domain Randomization Benchmark",
    booktitle="Human-Friendly Robotics 2022",
    year="2023",
    publisher="Springer International Publishing",
    address="Cham",
    pages="158--173",
    isbn="978-3-031-22731-8"
}
```
