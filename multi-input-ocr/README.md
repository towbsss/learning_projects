# Multi-Input OCR Model with PyTorch

This project from DataCamp demonstrates how to build a multi-input neural network using PyTorch. The model is trained to classify scanned ID codes using both image data and categorical metadata (type information).

## The Model

- A dual-input model using:
  - Convolutional layers for 64x64 grayscale images
  - Fully connected layers for one-hot encoded type vectors
  - Merged features passed to a classifier
- Trained with `CrossEntropyLoss` and `Adam` optimizer
- Includes:
  - Training/validation split
  - Accuracy and loss tracking
  - Evaluation function and final model checkpoint

## Disclaimer

This project is for personal learning and demonstration purposes. It is based on a DataCamp project, and aside from the setup code, all code is written independently. The original dataset and helper utilities are not included to respect content ownership.

## Files Included

- `ocr_model_project.ipynb` – full code, documentation, and DataCamp instructor references
- `README.md` – this file
