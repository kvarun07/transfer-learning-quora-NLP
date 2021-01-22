# transfer-learning-NLP
This repository contains project on Transfer Learning for NLP with Tensorflow Hub that I made as a part of an online course on Coursera.

## Introduction
- Pre-trained models from TensorFlow Hub are used to perform text classification on the [Quora Insincere Questions](https://www.kaggle.com/c/quora-insincere-questions-classification/data) dataset.

- Questions that are 'insincere' have a non-neutral tone, are inflammatory, discriminatory and disparaging or based on false information. For detailed description, check [here](https://www.kaggle.com/c/quora-insincere-questions-classification/data).

- The dataset consists of:
  - `qid`: unique question identifier
  - `question_text`: Quora questions text
  - `target`: If questions are insincere, they are labelled as `target = 1`, otherwise `target = 0`.
  
