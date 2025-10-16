# Tutorial 1: Neural Rate Models
In this tutorial, we will simulate and study one of the simplest models of biological neuronal networks. Instead of modeling and simulating individual excitatory neurons (e.g., LIF models that you implemented yesterday), we will treat them as a single homogeneous population and approximate their dynamics using a single one-dimensional equation describing the evolution of their average spiking rate in time.

In this tutorial, we will learn how to build a firing rate model of a single population of excitatory neurons.

<br>

**Steps:**
- Write the equation for the firing rate dynamics of a 1D excitatory population.
- Visualize the response of the population as a function of parameters such as threshold level and gain, using the frequency-current (F-I) curve.
- Numerically simulate the dynamics of the excitatory population and find the fixed points of the system.

# Tutorial 2: Wilson-Cowan Model
In the previous tutorial, you became familiar with a neuronal network consisting of only an excitatory population. Here, we extend the approach we used to include both excitatory and inhibitory neuronal populations in our network. A simple, yet powerful model to study the dynamics of two interacting populations of excitatory and inhibitory neurons, is the so-called **Wilson-Cowan** rate model, which will be the subject of this tutorial.

The objectives of this tutorial are to:

- Write the **Wilson-Cowan** equations for the firing rate dynamics of a 2D system composed of an excitatory (E) and an inhibitory (I) population of neurons
- Simulate the dynamics of the system, i.e., Wilson-Cowan model.
- Plot the frequency-current (F-I) curves for both populations (i.e., E and I).
- Visualize and inspect the behavior of the system using **phase plane analysis**, **vector fields**, and **nullclines**.

Bonus steps:

- Find and plot the **fixed points** of the Wilson-Cowan model.
- Investigate the stability of the Wilson-Cowan model by linearizing its dynamics and examining the **Jacobian matrix**.
- Learn how the Wilson-Cowan model can reach an oscillatory state.

Bonus steps (applications):
- Visualize the behavior of an Inhibition-stabilized network.
- Simulate working memory using the Wilson-Cowan model.
