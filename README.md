# Model Finetuning Projects

Welcome to the Model Finetuning repository! This repository is dedicated to exploring, understanding, and implementing model fine-tuning across different architectures and domains.

## Structure

The repository is structured into isolated, self-contained sub-projects. Each sub-project focuses on a specific model, task, or fine-tuning library. We use Jupyter Notebooks for these sub-projects because they offer an excellent interactive environment to mix code, documentation, explanations, and outputs seamlessly.

### Current Projects
1. **[01_Text_Classification_DistilBERT](./01_Text_Classification_DistilBERT)**: Deep dive into standard full-model fine-tuning for text classification using Hugging Face's `transformers` library.
2. **[02_Llama3_Unsloth_Finetuning](./02_Llama3_Unsloth_Finetuning)**: Exploring Parameter-Efficient Fine-Tuning (PEFT) using LoRA and the highly optimized `Unsloth` framework for Llama-3 instruction tuning.

## What is Fine-Tuning?
Fine-tuning is the process of taking a pre-trained machine learning model (a model trained on a massive, general dataset) and further training it on a smaller, task-specific dataset. Instead of training a model from scratch—which requires vast amounts of data and compute—we leverage the general features the model has already learned to adapt it to our specific needs.

## Getting Started
Each sub-directory contains its own `README.md` and a heavily documented Jupyter Notebook that explains the "why" and "how" of every step.

To get started, navigate into one of the project folders, install the required dependencies (usually listed at the top of the notebook or in an `environment.yml` / `requirements.txt`), and run the cells interactively.
