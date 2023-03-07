# Attention is All You Need: Implementing the Transformer in PyTorch

NOTE: Project is still in development


This project is an implementation of the transformer model introduced in the research paper "Attention is All You Need".
Research paper link: https://arxiv.org/pdf/1706.03762.pdf


In this project, the transformer model is implemented in PyTorch and train it on the WMT'14 English-German translation task.


The transformer model replaces traditional recurrent neural networks (RNNs) with a self-attention mechanism that allows the model to weigh the importance of different parts of the input sequence. This leads to better performance on tasks that require modeling long-range dependencies, such as machine translation.

Our implementation of the transformer model uses PyTorch and leverages its built-in support for multi-head attention and positional encoding. The Adam optimizer is used with a custom learning rate schedule to train the model.