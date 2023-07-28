# DL-Project

# HotpotQA Question Answering Project

## Overview

This project focuses on using the HotpotQA dataset for question-answering tasks. We utilize two stages of BERT-based models to achieve our goal: the first model retrieves relevant paragraphs given a question, and the second model extracts related sentences from the retrieved paragraphs. The final output is evaluated using F1 score and exact match metrics.

## Dataset

The HotpotQA dataset is a popular question-answering dataset that contains questions, supporting paragraphs, and answer annotations. It includes both a training and a validation set, which we use to train and evaluate our models, respectively.

## Usage

1. **Data Preparation**: The HotpotQA dataset needs to be preprocessed before training.


2. **Training Stage 1 - Retrieval Model**: The first stage involves training a BERT-based model to retrieve relevant paragraphs for a given question.

3. **Training Stage 2 - Sentence Extraction Model**: The second stage consists of training another BERT-based model to extract sentences from the retrieved paragraphs.

4. **Evaluation**: After training both models, we can evaluate the final performance using F1 score and exact match metrics.

## Model Checkpoints

During the training process, the model checkpoints will be saved to the `../save/` directory by default. These checkpoints can be used for inference or continued training.

## Conclusion

This project demonstrates how to use the HotpotQA dataset for question-answering tasks. By training two BERT-based models, one for retrieval and another for sentence extraction, we aim to improve the accuracy of our final output. The evaluation metrics, F1 score, and exact match, provide insights into the model's performance.
