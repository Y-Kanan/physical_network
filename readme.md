# DR_RNN in Tensorflow

Tensorflow implementation of [DR-RNN: A deep residual recurrent neural network for model reduction](https://arxiv.org/abs/1709.00939).

# Result
Reproduced result of Fig.2 from [the paper](https://arxiv.org/abs/1709.00939)
![dist2](./assets/problem1_dist2.png)

![dist3](./assets/problem1_dist3.png)

# Todo
- extrapolation in time
- larger time step
- scalability with y
- include mapping from x to y
- compute sensitivity w.r.t x for control purpose
- adding external loading and see if it is predictable given observation in y
- partial observed
- Direct Acyclic Graph and Bayesian