# SA-MahaBERT

SA-MahaBERT (Sentiment Analysis using MahaBERT) is a transformer-based sentiment classification project built by fine-tuning the MahaBERT language model on a custom sentiment dataset. The project demonstrates the complete NLP pipeline, including data preprocessing, model training, evaluation, and sentiment prediction.

## Features

* Sentiment classification using MahaBERT
* Fine-tuned transformer model
* Data preprocessing and tokenization
* Model evaluation using standard metrics
* Inference on custom user inputs
* Google Colab training workflow

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Pandas
* NumPy
* Scikit-learn
* Google Colab

## Project Goal

The objective of SA-MahaBERT is to leverage transformer-based language models for accurate sentiment analysis and provide an end-to-end workflow that can be extended to real-world NLP applications.

## Model Weights

Model hosted on Hugging Face:
https://huggingface.co/mahesh611/SA-MahaBERT


## Dataset

The dataset consists of Marathi news headlines annotated with sentiment labels (positive, negative, neutral).
The dataset was derived from the L3Cube-MahaNews corpus and further processed for sentiment analysis by introducing sentiment annotations.
Training, validation, and test splits are generated programmatically during experimentation using stratified sampling.

## License
The dataset included in this repository is derived from the L3Cube-MahaNews dataset and is distributed under the CC BY-NC-SA 4.0 license. See LICENSE_DATASET.md for details.
