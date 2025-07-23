
# Question Answering System using Transformer Models

This project is a Question Answering (QA) system that leverages transformer-based models to provide answers to user-input questions based on a given context. The system utilizes Hugging Face's Transformers library and a pre-trained model to identify the most probable answer span in a given context.

## Features

- Utilizes transformer models (like BERT or DistilBERT) for QA tasks.
- Accepts a passage (context) and a question from the user.
- Outputs the most probable answer using the transformer model.

## How it Works

1. Load a pre-trained Question Answering model from Hugging Face.
2. Tokenize the context and question.
3. Use the model to compute the answer span.
4. Display the extracted answer.

## Installation

```bash
pip install transformers torch
```

## Usage

```bash
python app.py
```

You will be prompted to enter a context and a question. The model will then predict the answer based on the input.

## Example

**Context:** "The capital of France is Paris."  
**Question:** "What is the capital of France?"  
**Answer:** "Paris"

## Requirements

- Python 3.x
- transformers
- torch

## Acknowledgements

- [Hugging Face Transformers](https://huggingface.co/transformers/)
