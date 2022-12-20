# PGD-attack-for-randomized-smoothing
Attacking randomized smoothing aims to find the perturbation that fools the following noising and voting operations of randomized smoothing most.

Implementations including L2 and Linf are based on the idea of [Provably Robust Deep Learning via Adversarially Trained Smoothed Classifiers](https://arxiv.org/abs/1906.04584).

This code is based on these resources:
1. [smoothing-adversarial](https://github.com/Hadisalman/smoothing-adversarial)
2. [torchattacks](https://github.com/Harry24k/adversarial-attacks-pytorch)

Note: Applying EOT startegy for PGD attack when inference involving randomness, but why?

It becomes a two-stage stochastic prohramming problem, and the solution is Sample Average Approximation (SAA).

# Requirements
- torchattacks
