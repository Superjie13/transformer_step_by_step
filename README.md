# Transformer is all you need (step by step) 

**中文教程**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Superjie13/transformer_step_by_step/blob/main/transformer_step_by_step.ipynb)

Note: This tutorial is written **in Chinese**. The English version can refer to [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html). 
- In the original blog post, you may not train the model on Multi30k dataset, cause the dataset could not be accessed. (you need to follow the dataset part in this tutorial to download and preprocess the dataset)

### Introduction
This is a step by step implementation of the Transformer model described in the paper [Attention is all you need](https://arxiv.org/abs/1706.03762) and inspired by the [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) blog post.

The goal of this project is to provide a simple and readable implementation of the Transformer model, and to provide a quick guide for researchers and ML practitioners to understand the model and its implementation. 

### Requirements
- Python 3.10
- PyTorch 1.10 + CUDA 11.3
- torchtext==0.3.0
- torchtext==0.12.0
- spacy==3.2.0
- altair==5.1.1
- GPUtil