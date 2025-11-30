# DHAdam-Optimizer
This is the repo for the project done as part of the course 'Computational Methods and Optimization' in Monsoon 2025, by Lavanya Gupta, Rushil Gargash, Sartajdeep Singh, Shreya Khanna [L1P2]

DH-Adam is a novel adaptive optimizer that uses two gradient horizons (fast + slow) and blends them based on a confidence score derived from their disagreement. Inspired by the two-pointer doubly linked list technique, as the group members learned in their data structures course, this helps avoid plateaus and improves stability in noisy or high-curvature optimization.

Benchmarks on quadratic functions, Rosenbrock, and MNIST show competitive and robust convergence compared to common optimizers.