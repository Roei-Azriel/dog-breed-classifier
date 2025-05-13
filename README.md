# Dog Breed Classifier

This project compares two deep learning models for classifying images of 70 dog breeds:

- A custom-built CNN model implemented from scratch
- A fine-tuned ResNet model based on transfer learning

The dataset was downloaded from Kaggle and preprocessed to fit both model architectures. Both models were trained and evaluated on the same dataset to enable performance comparison.

## Features
- Image preprocessing and augmentation
- Training with train/validation/test splits
- Accuracy and loss visualization
- Confusion matrix comparison
- Transfer learning with ResNet
- Performance benchmarking

## Structure
- `Model_dog_Our_CNN.ipynb` – Custom CNN model
- `Model_dog_resnet.ipynb` – ResNet-based model
- `Project_Report.ipynb` – Summary, evaluation, and comparison

## Requirements
- Python 3.x
- TensorFlow or PyTorch
- NumPy, Matplotlib, scikit-learn
- Kaggle API (to download the dataset)
