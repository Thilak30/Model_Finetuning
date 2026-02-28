# Text Classification with DistilBERT

This project demonstrates how to fine-tune a pre-trained Transformer model on a custom text classification dataset using the Hugging Face `transformers` library.

## Why DistilBERT?
For our first exploration into fine-tuning, `DistilBERT` is an excellent choice:
- **Efficiency**: It is a distilled (compressed) version of BERT. It retains ~97% of BERT's language understanding capabilities but is 40% smaller and 60% faster.
- **Accessibility**: Because it requires less compute memory, it is much easier to fine-tune on personal laptops or single GPUs.
- **Baselines**: It establishes a strong baseline for Natural Language Processing (NLP) tasks like Sentiment Analysis or Topic Classification.

## Project Contents
- `DistilBERT_Finetuning.ipynb`: The primary interactive notebook containing rich explanations on tokenization, dataset preparation, metric evaluation, and the `Trainer` API.

## How to use
Open the Jupyter notebook. Everything from package uninstallation/installation to training and inference is contained within the notebook cells.
