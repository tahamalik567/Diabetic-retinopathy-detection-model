# Fundus Image Classification for Diabetic Retinopathy

## Overview
This repository contains code for training a deep learning model to classify fundus images into five classes of Diabetic Retinopathy (DR): no-DR, mild, moderate, severe, and PDR (Proliferative Diabetic Retinopathy). The model architecture used is EfficientNet with a custom dense layer consisting of 2040 neurons.

## Dataset
The model was trained using a private preprocessed dataset of fundus images. The dataset consists of images labeled with one of the five DR classes. It's important to note that the classes were balanced to ensure unbiased learning.

## Model Architecture
The model architecture employed in this project is EfficientNet, which is known for its effectiveness in handling image data efficiently. Additionally, a custom dense layer with 2040 neurons was added on top of the EfficientNet base for fine-tuning and classification.

## Results
The model achieved excellent results in classifying fundus images into the five DR classes. Performance metrics such as accuracy, precision, recall, and F1-score were computed and found to be satisfactory.

## Usage
To train the model:
1. Clone this repository.
2. Preprocess your fundus image dataset (ensure it is formatted correctly and labeled).
3. Adjust the configurations in the training script if necessary.
4. Run the training script.

## Requirements
- Python 3.x
- TensorFlow
- EfficientNet
- Other dependencies 

## Future Work
- Fine-tuning the model on larger datasets for even better performance.
- Exploring other deep learning architectures and techniques for comparison.
- Building a web or mobile application for practical deployment of the model in real-world scenarios.

