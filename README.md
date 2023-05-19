# Brain-inspired Modular Training (BIMT)
This is the code repo for the paper: ["Seeing is Believing: Brain-Inspired Modular Training for Mechanistic Interpretability"](https://arxiv.org/abs/2305.08746). We introduce Brain-Inspired Modular Training (BIMT), a method for making neural networks more modular and interpretable. Inspired by brains, BIMT embeds neurons in a geometric space and augments the loss function with a cost proportional to the length of each neuron connection. We demonstrate that BIMT discovers useful modular neural networks for many simple tasks, revealing compositional structures in symbolic formulas, interpretable decision boundaries and features for classification, and mathematical structure in algorithmic datasets. 

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

Two Moon:

https://github.com/KindXiaoming/BIMT/assets/23551623/f3c8b32d-72de-4fba-9209-430037709546

Modular addition:

https://github.com/KindXiaoming/BIMT/assets/23551623/a9fddbb2-481b-482a-976e-6a5234f48881

Permutation group S4:

https://github.com/KindXiaoming/BIMT/assets/23551623/588b8368-94c4-43ae-a29c-5248ab765a61


Symbolic formulas:

https://github.com/KindXiaoming/BIMT/assets/23551623/0abda470-60a8-46a4-9e61-5775fce49d9a

https://github.com/KindXiaoming/BIMT/assets/23551623/f5640f41-619a-4e71-a2b3-2ef738f423e3

https://github.com/KindXiaoming/BIMT/assets/23551623/39c2f3fb-1ec9-4849-b588-fee2054bb6e5

