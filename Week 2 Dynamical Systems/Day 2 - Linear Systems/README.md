# Objectives
In Linear Systems, you will cover a lot of the really foundational knowledge on dynamical systems that you will use throughout the rest of the course, including a brief dive into stochastic systems which will underlie the next module. 

# Tutorial 1: Linear Dynamical Systems
The focus will be on **linear dynamics** and studying dynamical systems as a deterministic process.
* Explore and understand the behavior of such systems where $x$ is a single variable
* Consider cases where $\mathbf{x}$ is a state vector representing two variables.

# Tutorial 2: Markov Processes
### Tutorial Objectives
For Tutorial 2, we will look at **probabilistic** dynamical systems
* Understand Markov processes and history dependence.
* Explore the behavior of a two-state telegraph process and understand how its equilibrium distribution is dependent on its parameters.

# Tutorial 3: Combining determinism and stochasticity
### Tutorial Objectives
This tutorial will build on our knowledge and gain some intuition for how deterministic and stochastic processes can both be a part of a dynamical system by:
* Simulating random walks
* Investigating the mean and variance of a Ornstein-Uhlenbeck (OU) process
* Quantifying the OU process's behavior at equilibrium.

# Tutorial 4: Autoregressive models
### Tutorial Objectives

The goal of this tutorial is to use the modeling tools and intuitions developed in the previous few tutorials and use them to _fit data_. The concept is to flip the previous tutorial -- instead of generating synthetic data points from a known underlying process, what if we are given data points measured in time and have to learn the underlying process?

This tutorial is in two sections.

**Section 1** walks through using regression of data to solve for the coefficient of an OU process from Tutorial 3. Next, **Section 2** generalizes this auto-regression framework to high-order autoregressive models, and we will try to fit data from monkeys at typewriters.
