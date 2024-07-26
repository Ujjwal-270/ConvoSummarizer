# ConvoSummarizer

ConvoSummarizer is a machine learning project built to generate concise summaries of conversations using state-of-the-art language models.

## Objective

To provide accurate and succinct summaries of dialogues between a human and an AI agent.

## Data Source

Utilizes the Salesforce DialogStudio dataset for training and evaluation.

## Key Features

- **Preprocessing and Cleaning**: Preprocesses and cleans text data to remove irrelevant information.
- **Transformer-Based Model**: Uses a transformer-based language model, LLaMA-2, for natural language understanding and summarization.
- **LoRA (Low-Rank Adaptation)**: Employs LoRA for efficient model fine-tuning.
- **4-bit Quantization**: Supports 4-bit quantization for optimized model performance and reduced resource consumption.
- **Robust Training Pipeline**: Implements a robust training pipeline with customized training arguments for fine-tuning the model.
- **Real-Time Summary Generation**: Provides real-time summary generation for test conversations.

## Technology Used

- **PyTorch**
- **Transformers**
- **Datasets**
- **LoRA**
- **BitsAndBytes**
- **TensorBoard**

## Training and Evaluation

Includes detailed scripts for training, validation, and evaluation of the model, along with TensorBoard integration for monitoring.
