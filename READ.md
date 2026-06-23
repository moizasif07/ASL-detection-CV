# ASL Alphabet Recognition using CNN and PyTorch

## Overview
This project uses a Convolutional Neural Network (CNN) built with PyTorch to recognize American Sign Language (ASL) alphabet gestures from images.

The model is trained on an ASL alphabet dataset and can perform both offline image classification and real-time webcam-based gesture recognition.

## Features
- ASL alphabet classification
- CNN architecture using PyTorch
- Training and validation pipeline
- Saved trained model support
- Real-time webcam inference

## Dataset
Dataset contains images of ASL alphabet hand gestures organized into class folders.

Training Data:
- ASL_alphabet_train/

Testing Data:
- ASL_alphabet_test/

## Model
- Framework: PyTorch
- Architecture: Convolutional Neural Network (CNN)
- Loss Function: CrossEntropyLoss
- Optimizer: Adam

## Results
The trained model is saved as:

asl_cnn_model.pth

## Running the Project

### Install Dependencies

pip install torch torchvision opencv-python numpy matplotlib scikit-learn

### Train Model

Run:
ASL_CNN_PyTorch_TrainVal.ipynb

### Test Model

Run:
ASL_CNN_PyTorch.ipynb

### Real-Time Prediction

Run:
realtime_app.ipynb

## Future Improvements
- Data augmentation
- Transfer learning
- Improved real-time accuracy
- Deployment as a web application

## Author
Your Name