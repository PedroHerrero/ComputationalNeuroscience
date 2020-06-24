# Computational Neuroscience models

This repository contains a collection of methods in computational neuroscience to describe properies of neurons and neural networks with empashis in dynamics and Recurrent Neural Networks (RNNs). Each models is implemented from scratch and disected in a series of self-explanatory Jupyter Notebooks. The described models are:

## Leaky integrate-and-fire (LIF) model 
This model describes the membrane potential of a neuron as a resistor-capacitor. It was first introduced by [Lapicque in 1907](http://www.snv.jussieu.fr/brette/papers/Lap07.pdf)

## Kinetic model of a synapse
The model explores the communication between neurons the dynamics the process. It takes dynamic properties of channels and their interactions to asses their contribution to the electical state of the post-synaptic (receiving information) neuron.

## RNNs
The associate notebook describes a recurrent network model of orientation selectivity in primary visual cortex as described by [Ben-Yishai et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC42058/pdf/pnas01493-0220.pdf).

## RNN model for self-sustained activity
Neural networks represent information as particular states or activity patterns. A critical quesion in Neuroscience and Machine Learning is to understand how networks developed those representations and stable they are. This model ilustrates how a network with excitatory and inhibitory populations is able to generate a representation that is stable over time in the absence of stimulus drive and/or significant noise.

## Firing-rate model for decision making and working memory
This models describes how populations of recurrent networks with excitatory and inhibitory sub-networks can describe cognitive processes such as decision making and working memory
