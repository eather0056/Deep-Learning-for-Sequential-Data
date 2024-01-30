# Deep Learning for Sequential Data

Welcome to the "Deep Learning for Sequential Data" repository! This project represents an in-depth exploration of deep learning techniques for handling sequential data, conducted as part of the coursework at the University de Toulon under the guidance of Professor Santiago.

## Problem 1: RNNs on the Parity Task

### Introduction
In this section, we address the "parity task" using Recurrent Neural Networks (RNNs). The goal is to predict a binary indicator based on variable-sized sequences of bits, where the indicator is 0 if the sequence contains an even number of ones and 1 otherwise. This task is conceptually similar to learning the XOR function at each time step.

### Tasks
- Implement a vanilla RNN in PyTorch to solve the parity task.
- Apply a Mean Squared Error (MSE) loss function to train the RNN in two modes: (1) applying the loss at each time step, and (2) applying the loss only at the last time step.
- Analyze the impact of hyperparameters such as `full_supervision`, `max_grad_norm`, and `seq_len` on the training dynamics.
- Implement the LSTM cell and evaluate its performance on the parity task.
- Compare the training of the vanilla RNN and LSTM in long sequences without full supervision.

## Problem 2: GPT (Generative Pre-trained Transformer)

### Introduction
In this section, we delve into the implementation of the GPT architecture (Generative Pre-trained Transformer), a model designed for next-token prediction, commonly used in state-of-the-art AI systems like ChatGPT.

### Tasks
- Implement a transformer decoder block, including the forward pass of Multihead Attention and the attention block.
- Create positional encodings to inject information about the position of elements in the sequence.
- Implement causal self-attention to prevent tokens from attending to future tokens.
- Train a GPT model to generate Harry Potter text based on the first four books.
- Define tokenization methods for encoding text as integers, including character tokenization and subword tokenization using SentencePiece.
- Assess the English language skills of the trained GPT model through spelling and grammar tests.
- Explore the impact of subword tokenization on the model's performance in the grammar test.

## Google Colab Link
You can access and run this project in Google Colab using the following link: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zUusMfl24zTQSACCYjme3oY8mDfH99oO#scrollTo=OgKtz93lLxNe)

## Usage
To get started, clone this repository to your local machine:

```bash
git clone https://github.com/eather0056/Deep-Learning-for-Sequential-Data.git
cd Deep-Learning-for-Sequential-Data
```

Feel free to explore the provided code, experiment with different configurations, and gain insights into deep learning for sequential data.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```
