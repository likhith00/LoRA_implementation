# LoRA_implementation

This repository is an implementation of finetuning of Bert Variatant using LoRA (Low Rank Adaption).This implementation is tailored specifically for binary classification task.

# Libraries
numpy
torch
transformers
huggingface-hub
peft
datasets
evaluate
pandas

# Dataset

IMDB truncated dataset by <a href="https://huggingface.co/datasets/shawhin/imdb-truncated" target="_blank">shawhin/imdb-truncated</a>

| No.of rows    | Dataset size |
| ------------- |:------------:|
| 2000          | 1.69MB       |

# Implementation

LoRA_finetuning.ipynb was executed on <a href = "https://colab.research.google.com/">google colab</a> as colab provides T4 GPU for free.

To implement this process on your PC, follow the below steps:

1. clone the repository using ```git clone https://github.com/likhith00/LoRA_implementation.git```
2. install the requirements.txt using ```pip install -r requirements.txt```\
3. Now, execute all the cells. After training, make sure to mention your huggingface id to push the model in your repository.

# References:

GitHub Repository: <a href = "https://towardsdatascience.com/fine-tuning-large-language-models-llms-23473d763b91">Finetuning Large Language models(LLMS)</a> by Shaw Talebi