# Cats and Dogs Classification Using Pretrained Xception Model

This repository contains a simple project that demonstrates how to build a binary classification model using the pre-trained Xception model. The task involves classifying images of cats and dogs.

## Features
- Uses the Xception model pre-trained on ImageNet.
- Implements image preprocessing and normalization.
- Fine-tunes the model by adding custom dense layers.
- Includes precision, recall, and binary accuracy metrics.
- Demonstrates the entire pipeline from loading data to evaluating the model.

---

## Dataset
The dataset used for this project is publicly available on Kaggle:
[Cats and Dogs for Classification](https://www.kaggle.com/dineshpiyasamara/cats-and-dogs-for-classification)

Ensure you download the dataset and place the train data folder and test data folder correctly in the notebook.

---

## Libraries Used
The project requires the following libraries:
- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib

### Installation
You can install the required libraries using pip:

```bash
pip install tensorflow numpy pandas matplotlib
