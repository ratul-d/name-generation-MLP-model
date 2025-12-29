# name-generation-MLP-model

## Overview

This project implements a character-level Multi-Layer Perceptron (MLP) trained to generate names. The model learns from a dataset of names by mapping fixed-length character contexts to the probability distribution of the next character. Using learned character embeddings, a hidden layer with a tanh activation, and a softmax output layer, the model can sample new, previously unseen names.

---

## Project Structure

```
MLP-model/
├── understanding_process.ipynb
├── final_model.ipynb
└── names.txt                               # training dataset
```
---

## Acknowledgement

This project follows [**Andrej Karpathy’s** tutorial](https://youtu.be/TCH_1BHY58I?si=BeEc1anvJ5ysptFH)  on building and training language models from scratch.

---