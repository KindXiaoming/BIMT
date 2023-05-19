# Brain-inspired Modular Training (BIMT)
This is the code repo for the paper: ["# Seeing is Believing: Brain-Inspired Modular Training for Mechanistic Interpretability"](https://arxiv.org/abs/2305.08746). We introduce Brain-Inspired Modular Training (BIMT), a method for making neural networks more modular and interpretable. Inspired by brains, BIMT embeds neurons in a geometric space and augments the loss function with a cost proportional to the length of each neuron connection. We demonstrate that BIMT discovers useful modular neural networks for many simple tasks, revealing compositional structures in symbolic formulas, interpretable decision boundaries and features for classification, and mathematical structure in algorithmic datasets. 

The examples used in this paper are relatively small-scale. We make our codes as minimal as possible: each example is self-consistent, kept in a single jupyter notebook. Each example is runnable on a single CPU (e.g., Mac M1) usually in minutes, in hours at most.

|Examples| Figure in [paper](https://arxiv.org/abs/2305.08746) | Notebook |
|--|--|--|
|Symbolic Formulas|Figure 3| symbolic_formulas_3.1|
|Two Moon | Figure 4 | two_moon_3.2 |
|Modular Addition | Figure 5 | modular_addition_3.3 |
|Permutation S4 | Figure 6 | permutation_S4_3.3 |
|In-context linear reg | Figure 7 | incontext_3.4 |
| MNIST | Figure 8 | mnist_3.5 |

With BIMT, neural networks are trained to be become more modular and interpretable, e.g.,

Two moon classification:

https://github.com/KindXiaoming/BIMT/assets/23551623/420e8323-220d-4371-98c8-ab8e88108d05

Modular addition:

https://github.com/KindXiaoming/BIMT/assets/23551623/4fdcee5e-14d9-4239-8707-5e03c42215b4

Permutation group S4:

https://github.com/KindXiaoming/BIMT/assets/23551623/906ca5c4-54b4-45ab-b749-5c0d29972de4

Symbolic formulas:

https://github.com/KindXiaoming/BIMT/assets/23551623/8d7825d1-7a96-41d0-9b7c-defffb30c610

https://github.com/KindXiaoming/BIMT/assets/23551623/37c92b9e-43b4-43cf-815f-ac35814b8cf7

https://github.com/KindXiaoming/BIMT/assets/23551623/98bf50c7-ae80-413a-bda3-118d2960722a




