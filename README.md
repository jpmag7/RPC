# RPC - Relevant Precedence Compression

The primary goal of this work is to create a very small language model (SLM) with fewer than 5 million parameters that can generate reasonable text completions. Unlike traditional methods that use a neural network to predict the next token distribution, RPC employs a neural network to compress the prompt into a vector. This vector is then used to search for the next token in a vector database.

![image](https://github.com/user-attachments/assets/25545d99-fcce-4239-92b0-706dea52d0df)
