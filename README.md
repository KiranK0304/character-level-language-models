
---

# Karpathy Zero to Hero: Neural Networks from Scratch 🧠🚀


Welcome to my repository containing implementations of **Andrej Karpathy's Neural Networks: Zero to Hero series**. This repo is a personal project where I follow along Karpathy’s videos to deeply understand neural networks by building them from the ground up in Python.

This repository is my implementation journey through **Andrej Karpathy’s “Neural Networks: Zero to Hero”** series. By building neural networks entirely from scratch in Python, I aim to deeply understand the mathematics and mechanics behind deep learning.
>>>>>>> a167464 (Saving local changes before pulling)

---

## 📂 Repository Structure

### `micrograd/` – Autograd Engine

A tiny, fully functional **autograd engine** with backpropagation from scratch, inspired by PyTorch.

* Implements a `Value` class supporting scalar computation graphs.
* Visualizes forward and backward passes in neural networks.
* Trains a basic MLP to classify tiny datasets.

---

### `makemore1/` – Bigram & Trigram Language Models

A **character-level name generator** using N-gram models.

* `bigram_model.ipynb`: Builds a simple bigram name model.
* `trigram_model.ipynb`: Adds context using trigrams.
* Based on counting and simple neural embeddings.

---

### `makemore2/` – Fully Connected MLP (Inspired by Bengio et al.)

This model evolves from n-grams to a **fully connected MLP**, treating character sequences as fixed-size context vectors.

* Uses PyTorch with **manual OOP class design**.
* Introduces embedding layers, linear layers, ReLU, and softmax.
* Inspired by the early works of Bengio et al. on neural language models.
* Shows significant improvement over N-gram models.

---

### `makemore3/` – Dilated CNN (Inspired by WaveNet)

An **advanced CNN-based character model** with dilation-style architecture.

* Rather than flattening context, it processes it **step by step through layers**.
* Mimics **WaveNet-style causal convolutions** for better sequence understanding.
* Shows how temporal features can be extracted without recurrence.
* Stronger generalization to name generation tasks.

---

## ⚙️ Getting Started

### Requirements

Make sure you have Python 3.x and the following libraries:

```bash
pip install numpy torch matplotlib jupyter
```

### Run the Notebooks

```bash
jupyter notebook
```

Open any of the notebooks inside each `makemore*/` or `micrograd/` folder and run them interactively.

---

## 🧠 What I Learned

> From understanding gradients and autograd to building language models with real architectural innovation, this repo reflects my growing intuition and skills in deep learning.


