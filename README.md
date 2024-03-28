We add some experiments to illustrate the behavior of IPA and the Principal's epsilon greedy algorithm proposed in Dogan et al., Repeated Principal-Agent Games with Unobserved Agent Rewards and Perfect-Knowledge Agents, compared to the UCB baseline.

On the captions, T is the horizon, K refers to the number of available actions, rewards_0_1 means that the rewards are considered in [0,1] and m is the experimental parameter that needs to be chosen in the Principal's epsilon greedy algorithm. The number of episodes/epochs defines the number of times each algorithm is run for T iterations. The curves represent the average and standard deviation accross all different episodes.

List of the experiments:

- vector $\theta$: [0.44 0.48 0.59 0.00 0.28 0.27 0.63 0.45 0.17 0.5  0.14 0.24 0.03 0.34 0.33 0.78 0.69 0.69 0.88 0.37 0.52 0.08 0.22 0.76 0.48 0.99 0.16 0.86 0.08 0.27 0.47 0.37 0.11 0.18 0.5  0.43 0.52 0.72 0.3  0.24 0.81 0.23 0.74 0.87 0.34 0.48 0.68 0.73 0.38 0.63]; vector $s$: [0.39 0.3  0.02 0.89 0.78 0.46 0.72 0.8  0.33 0.2  0.85 0.79 0.08 0.15 0.85 0.63 0.38 0.11 0.23 0.42 0.05 0.08 0.31 0.18 0.38 0.58 0.31 0.24 0.98 0.19 0.29 0.6  0.   0.32 0.81 0.   0.72 0.4  0.5  0.95 0.98 0.17 0.02 0.46 0.81 0.36 0.59 0.99 0.18 0.44]; T=40000, K=50, m=2000, 30 episodes.

- vector $\theta$: [0.5  0.2  0.95 0.86 0.18 0.57 0.06 0.75 0.73 0.28 0.07 0.03 0.36 0.14 0.26 0.58 0.79 0.85 0.06 0.34 0.   0.13 0.88 0.97 0.4  0.75 0.72 0.84 0.2  0.54 0.23 0.57 0.6  0.74 0.24 0.79 0.14 0.71 0.58 0.01 0.91 0.03 0.82 0.87 0.76 0.04 0.68 0.41 0.79 0.88 0.01 0.47 0.5  0.67 0.17 0.42 0.67 0.48 0.06 0.21 0.6  0.65 0.43 0.01 0.63 0.46 0.04 0.38 0.47 0.95
 0.37 0.85 0.18 0.81 0.44 0.48 0.75 0.58 0.97 0.43 0.81 0.56 0.41 0.63 0.52 0.31 0.62 0.89 0.26 0.1  0.7  0.46 0.22 0.14 0.81 0.12 0.1  0.92  0.79 0.13], vector $s$: [0.3  0.93 0.03 0.32 0.58 0.07 0.13 0.61 0.45 0.42 0.21 0.81 0.44 0.18 0.26 0.24 0.34 0.8  0.31 0.07 0.82 0.07 0.68 0.31 0.15 0.55 0.45 0.21 0.77 0.03 0.38 0.83 0.83 0.64 0.94 0.61 0.55 0.28 0.41 0.17 0.97 0.15 0.37 0.26 0.65 0.78 0.51 0.53 0.51 0.73 0.65 0.98 0.04 0.69 0.64 0.76 0.84 0.54 0.3  0.6  0.15 0.51 0.35 0.07 0.02 0.3  0.5  0.62 0.12 0.51 0.14 0.37 0.91 0.11 0.57 0.28 0.39 0.83 0.22 0.86 0.74 0.85 0.79 1.0 0.87 0.3  0.46 0.42 0.05 0.52 0.64 0.45 0.8  0.51 0.04 0.95 1.00 0.69 0.4  0.38]; T=40000, K=100, m=5000, 30 episodes.

- another experiment with the same vectors $s$ and $\theta$, T=100000, m=300.

- an experiment with T=40000, m=100: linear behavior of the Principal's $\epsilon$-greedy algorithm and the same vectors $s$ and $\theta$ as in the paper.
