# Deep Learning Project 2: Parameter-Efficient Fine-Tuning with LoRA

## Overview

This project explores parameter-efficient fine-tuning of transformer-based language models using Low-Rank Adaptation (LoRA). We adapt the RoBERTa-base model for the AG News classification task while significantly reducing the number of trainable parameters.

## Key Features

- Implementation of Low-Rank Adaptation (LoRA) with rank 8
- Fine-tuning of RoBERTa-base model
- AG News classification task
- Parameter-efficient approach (630,532 trainable parameters out of 125M total)
- Achieved test accuracy of 89.48%

## Technical Details

- Model: RoBERTa-base
- LoRA adapters inserted into query and value projection layers
- Input sequence length: 128 tokens
- Training duration: 3 epochs
- Parameter efficiency: Only 0.5% of total parameters are trainable

## Results

- Test Accuracy: 89.48%
- Trainable Parameters: 630,532

## Team Members

- Maneesh Kolli (mk9697)
- Srijan Yendluri (sy4417)
- Abhishek Agrawal (aa9360)
