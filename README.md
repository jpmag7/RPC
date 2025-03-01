# RPC - Relevant Precedence Compression

The primary goal of this work is to create a very small language model (SLM) with fewer than 5 million parameters that can generate reasonable text completions. Unlike traditional methods that use a neural network to predict the next token distribution, RPC employs a neural network to compress the prompt into a vector. This vector is then used to search for the next token in a vector database.

[DATASET](https://www.kaggle.com/datasets/pedrocas15/rpc-dataset)

![architecture](https://github.com/user-attachments/assets/5c7223cc-a731-4bc2-bc87-507c651215d2)

