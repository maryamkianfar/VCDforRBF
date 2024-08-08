# VCDforRBF
This repository contains my Master Thesis. 

# TL;DR
In my thesis, I proofed that the Vapnik-Chervonenkis dimension (VCD) for concatenated functions \( f \circ g \), where both \( f \) and \( g \) have image in the real numbers, can be calculated by multiplying the VCD of f by the number of intervals, on which g is monotonous.

# Additional Content


- The thesis gives a wide range of methods for easier calculation of VCD.
- A full proof of the generalization bound of Vapnik is provided, which bounds the overfitting error of a set of functions from above by the VCD of that set.
- The same bound is also proven using the Rademacher complexity, leading to a sharper bound.

Also, the same bound is proofed by the Rademacher complexity. Again the Rademacher complexity can be bound from above by the VCD, which concludes in a sharper bound. 

# Further Work

It is also possible to obtain generalization bounds by conditional mutual information, which can also again be expressed via the VCD. For more details, please refer to [this paper](https://arxiv.org/pdf/2005.08044.pdf).
