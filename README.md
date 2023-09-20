# LLM-finetunes
Python colab notebooks testing finetuning scripts on small language models 

## 1. GPT-neo-125M-finetune.ipynb
This notebook shows my attempt at finetuning a small LLM model on a basic alpaca dataset based on instruction format. I've reduced the no. of training data to only 1000 in this run, to go through a full run in a short time.

All the code was run on Colab notebooks using T4 GPU environment.
## 2. Code_Alpaca_Lora_on_self_generated_data .ipynb
This notebook tries to reproduce the code-alpaca model that specializes in generating code outputs. It's trained on Llama 7B v2 in a colab T4 gpu environment. 

check the final model Lora at : [https://huggingface.co/sandeshrajx/code-alpaca-100](https://huggingface.co/sandeshrajx/code-alpaca-100)
