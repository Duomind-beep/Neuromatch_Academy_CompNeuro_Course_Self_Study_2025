# Intro

## Overview

Today you will learn about Hidden Markov Models (HMMs), which allow us to infer things in the world from a stream of data. Tutorials will continue our two running examples that help provide intuition: fishing (for a binary latent state) and tracking astrocat (for a gaussian latent state). In both examples, we've set up interactive visualizations to provide intuition, and then you will recreate the key inferences step by step. For the binary case, we start with a simple version where the latent state doesn't change, then we'll allow the latent state to change over time. There's plenty of bonus material, but your core learning objective is to understand and implement an algorithm to infer a changing hidden state from observations.

The HMM combines ideas from the linear dynamics lessons (which used Markov models) with inferences described in the Bayes day (which used Hidden variables). It also connects directly to later lessons in Optimal Control and Reinforcement Learning, which often use the HMM to guide actions.

The HMM is a pervasive model in neuroscience. It is used for data analysis, like inferring neural activity from fluorescence images. It is also a foundational model for what the brain should compute, as it interprets the physical world that is observed only through its senses.

## Prerequisites

In the content today, you will be using concepts from probability and statistics such as:

- Gaussian distributions (see [here](https://compneuro.neuromatch.io/tutorials/W0D5_Statistics/student/W0D5_Tutorial1.html#section-3-1-gaussian-distribution))

- likelihood functions (see [here](https://compneuro.neuromatch.io/tutorials/W0D5_Statistics/student/W0D5_Tutorial2.html#section-2-1-likelihoods))
- Markov processes (see [here](https://compneuro.neuromatch.io/tutorials/W0D5_Statistics/student/W0D5_Tutorial2.html#section-1-2-markov-chains) and [here](https://compneuro.neuromatch.io/tutorials/W2D2_LinearSystems/student/W2D2_Tutorial2.html))

Video available at https://youtube.com/watch?v=bJIAWgycuVU
