# SMS classifier

This project is aimed at building a classifier for SMS messages to automatically categorize them into predefined categories such as spam or ham (non-spam). The classifier utilizes machine learning techniques to learn from labeled SMS data and make predictions on unseen messages.

## Table of Contents

* Introduction
* Installation
* Usage
* Dataset
* Model Training
* Evaluation
* Contributing
* License
## Introduction

The SMS Classifier project is developed to assist in filtering and categorizing SMS messages into relevant categories automatically. With the increasing volume of SMS messages, particularly with the rise of spam messages, this classifier aims to streamline the process of segregating important messages from unwanted ones.

## Installation

To install and run this project locally, follow these steps:

Clone the repository:
```bash
git clone https://github.com/Prathamaryaaa/SMS_Classifier.git
```

Navigate to the project directory:
```bash
cd SMS-classifier
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Usage

To use the SMS Classifier:

1. Ensure you have installed all dependencies.
2. Prepare your SMS data or use the provided dataset.
3. Train the model using the provided training script or your custom implementation.
4. Evaluate the model's performance.
5. Utilize the trained model to classify new SMS messages.
## Dataset

The dataset used for training and testing the SMS Classifier is not included in this repository due to licensing restrictions. However, you can use your own dataset or find similar datasets online. Ensure your dataset is properly formatted with labeled categories (e.g., spam, ham).

## Model Training

The model training process involves preprocessing the text data, vectorizing it, and training a classification algorithm. You can find the implementation details in the train_model.py script.

To train the model, execute the following command:
```bash
python train_model.py
```
## Evaluation

Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the performance of the classifier. You can find the evaluation script in evaluate_model.py.

To evaluate the model, execute the following command:
```bash
python evaluate_model.py
```
## Contributing

Contributions to this project are welcome. Feel free to open issues, submit pull requests, or suggest new features.

## Contact

For any inquiries or suggestions, please contact pr12at34ham@gmail.com.
