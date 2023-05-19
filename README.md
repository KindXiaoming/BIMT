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

With BIMT, neural networks are trained to be become more modular, e.g.,


