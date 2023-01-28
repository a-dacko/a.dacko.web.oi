---
title: Recent projects
---

## Master Thesis (curent project)
### Description
One way to see the human behavioral processes is through the dynamics of discrete states that switch over the course of time. Often times those states cannot be measured directly hence are latent (hidden). A probabilistic method that enables one to extract discrete latent states, based on one or several dependent variables, and model their dynamics over time is Hidden Markov Model (HMM).
![Example of Bipolar disorder modelled by HMM. (A) The Markov process of three latent states, describing Bipolar disorder. (B) Transition matrix of the HMM where diagonal entries represent self-transition probabilities and off diagonal entries representing transition probabilities between states, for example $$gamma_{23}$$ is probability of switching from Manic to Depressive state. (C) The HMM with hidden layer of states that follow the first-order Markov process and observable layer which consists of three observed dependent variables that are emitted at each point in time by state-specific emission distributions](/images/hmm.jpg)

To make the HMM the perfect match for intensive longitudinal behavioral data (ILD), the conventional HMM need to be extended to the multilevel framework such that we can model the observed sequences of multiple subjects simultaneously. The Multilevel Hidden markov models has been widely used in behavioral research but it comes wit some limitations. The HMM(and MHMM) assumes that the duration of each state is modeled by geometric distribution, which may not accurately reflect the true duration of each state. Additionally, the HMM(and MHMM) does not allow for different mean state duration since the most probable duration length is equal to 1. 
The Explicit-duration Hidden Markov model are able to address these limitations by explicitly modelling the duration of each state, allowing for a more accurate representation of the underlying dynamics of the behavioral data.


![Example of Bipolar disorder modelled by HSMM. (A) The first-order Semi-Markov process of three latent states, describing Bipolar disorder. (B) Transition matrix of the HSMM where diagonal self-transition entries equal to 0 and are not modelled within the transition matrix. Instead, the duration of each state is explicitly modelled using a dwell time distribution of choice (usually Log-Normal or Inverse-gamma distribution). The $$gamma_{12}$$ is probability of switching from Euthymic to Manic state. (C) The HSMM with hidden layer of states (following the first-order Semi-Markov process) with their durations explicitly defined. The observable layer, which consists of three observed dependent variables that are emitted at each point in time by state-specific emission distributions](/images/time-1.jpg) 

Although well suited for modeling behavioral processes, yet, there is too scarce information about how the model would fit into behavioral research. Therefore, given its potential in capturing the reflation of behavioral latent state duration, we hypothesis that the Multilevel Explicit-duration Hidden Markov Model (MEDHMM) would be preferable to the MHMM in the context of behavioral process modelling. In order to evaluate the hypothesis, we present the first, to our knowledge, simulation study comparing the MEDHMM with the MHMM. By simulating data from the MEDHMM and fitting it to both MEDHMM and MHMM using Bayesian estimation, we wish to inspect if more complex and computationally intensive MEDHMM can capture the true hidden state duration with greater accuracy to the MHMM. Also, we wish to evaluate if MEDHMM is capable of estimating other model-specific parameters with the same precision as the MHMM does. We test the models in various conditions mimicking the behavioral data. We vary three design levels: 1) mean dwell time since we expect the MEDHMM to be able to capture longer duration more accurately and short with a similar precision to MHMM, 2) the number of hidden states as the more states the larger complexity of the model, 3) sample size since in general the model inference depends on the length of the subject-specific time point series.
## Shiny app 
![The Data Science courses shiny app](/images/shiny_app.jpg) 
## Package development 
### [restriktor package](https://restriktor.org/) 
### [mHMMBayes package](https://github.com/emmekeaarts/mHMMbayes)

## Some data science projects I did
### Clustering 
### Deep Learning
### Suppervised Machine learning algorithms


