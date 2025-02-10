# Hand Gesture Recognition

## Overview
This project develops a hand gesture recognition model that accurately identifies and classifies different hand gestures from image or video data. The model enables intuitive human-computer interaction and gesture-based control systems.

## Dataset
The dataset used for training the model is available on Kaggle:
[Leap Gesture Recognition Dataset](https://www.kaggle.com/gti-upm/leapgestrecog)

## Model Architecture
The model is based on **ResNet50**, a deep convolutional neural network known for its strong feature extraction capabilities.

### Key Features:
- Achieved **97.87% accuracy** on the dataset.
- Used **transfer learning** with ResNet50 for efficient training.
- Applied **data augmentation** to enhance model generalization.
- Implemented **real-time prediction capability**.

## Installation & Setup
To run the project, ensure you have the following dependencies installed:
```bash
pip install tensorflow keras numpy matplotlib opencv-python
```

## Training the Model
Run the following script to train the model:
```bash
python train.py
```

## Inference & Real-Time Gesture Recognition
To use the trained model for real-time predictions:
```bash
python predict.py
```

## Results
- **Validation Accuracy:** 97.77%
- **Test Accuracy:** 97.87%.
