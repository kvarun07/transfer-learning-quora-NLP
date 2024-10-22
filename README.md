# transfer-learning-quora-NLP
This repository contains project on Transfer Learning for NLP with Tensorflow Hub that I made as a part of an online course on Coursera.

## Introduction
- Pre-trained models from TensorFlow Hub are used to perform text classification on the [Quora Insincere Questions](https://www.kaggle.com/c/quora-insincere-questions-classification/data) dataset. Transfer learning is performed to save training resources. It also helps to achieve model generalisation.

- Questions that are 'insincere' have a non-neutral tone, are inflammatory, discriminatory and disparaging or based on false information. For detailed description, check [here](https://www.kaggle.com/c/quora-insincere-questions-classification/data).

- The dataset consists of:
  - `qid`: unique question identifier
  - `question_text`: Quora questions text
  - `target`: If questions are insincere, they are labelled as `target = 1`, otherwise `target = 0`.
  
 ## Visualisation of model performance
- The performance metrics of model are visualised using `TensorBoard`.

- ***Accuracy curves***
![alt text](https://github.com/kvarun07/transfer-learning-NLP/blob/main/assets/model_accuracy_plot.png)

- ***Accuracy: TensorBoard***
![alt text](https://github.com/kvarun07/transfer-learning-NLP/blob/main/assets/epoch_accuracy_curves.png)

- ***Loss: TensorBoard***
![alt text](https://github.com/kvarun07/transfer-learning-NLP/blob/main/assets/epoch_loss_curves.png)

## Inference
- Highest accuracy is obtained when the model is trained with [Universal Sentence Encoder](https://tfhub.dev/google/universal-sentence-encoder-large/5) available on `TensorFlow Hub`.
