# Karpathy Zero to Hero: Neural Networks from Scratch 🧠🚀

Welcome to my repository containing implementations of **Andrej Karpathy's Neural Networks: Zero to Hero series**. This repo is a personal project where I follow along Karpathy’s videos to deeply understand neural networks by building them from the ground up in Python.

---

## 📂 Repository Structure

This repository contains two main projects corresponding to different parts of the series:

### 1. `micrograd/`  
A minimalistic **autograd engine** inspired by PyTorch’s core principles, implemented from scratch in Python.

- Contains the notebook `micrograd.ipynb` which walks through:
  - Building the core `Value` class that supports automatic differentiation.
  - Implementing backpropagation manually.
  - Demonstrating simple examples of training neural networks.
- This project is perfect for understanding how gradients flow and how neural nets learn.




### 2. `makemore/`  
A character-level neural network trained to generate names, built step-by-step from bigram models to trigram and beyond.

- Includes Jupyter notebooks:
  - `bigram.ipynb`: Implements a bigram language model to generate names.
  - `trigram.ipynb`: An extended trigram model developed as an exercise to improve prediction quality.
- Also contains the `names.txt` file — the dataset of names used for training.
- This project introduces language modeling and sequential data concepts using neural networks.

---



## ⚙️ How to Use

### Prerequisites

Make sure you have Python 3.x installed, along with the following libraries:

- numpy
- torch
- matplotlib
- jupyter (if you want to run notebooks interactively)

You can install these with:

```bash
pip install numpy torch matplotlib jupyter
