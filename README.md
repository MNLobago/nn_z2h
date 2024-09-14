### Open-source LLM PROJECT IN DEVELOPMENT

The goal of this project is to build a neural network that is capable enough to accomodate and train on locally trained data context from scratch.

This project is in progress of being built with these objectives in mind.

- create a repo of locally trained or curated data and train the network to be able to fine-tune appropriately.
- Serve as the african pathway to open-sourced AI model developemnt.

##### Project description

It started by mimicking PyTorch's API from a neuron unit level of 
``` y = mx+c ``` and was furthered into growing to the capacity of a BatchNorm1D driven RNN at its currents state. It is an absolute work in progress and open to contribution around relevant use cases.

#### TLDR;
The primary objective of this character-level language model is to train our network to be able to predict the next character correctly. 

Data-source: names.txt
micrograd: A walk around expresions and forward passes
makemore: Applying tokenization and embeddings
makemore3: Evaluation of activations and gradients of the network. (How it fires up and balances its scale while training)
makemore4 (Doing the hard thing): Backpropagation through the network to further understand how neural network works.
Makemore5: Building a wavenet of networks into an RNN/CNN structure.

See notes for further insights