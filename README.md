# Hand Gesture Recognition

## Overview
This project focuses on recognizing hand gestures using OpenCV, Keras, and Convolutional Neural Networks (CNNs). The system captures live video feed, segments the hand region, and classifies gestures in real-time.

## Dataset
- **Link**: https://drive.google.com/drive/folders/17zMVpSzfA2U9wSv7y31JhcLUd2ZMHN1w?usp=drive_link
- **Description**: The dataset includes images of 6 different hand gestures.
- **Gesture Types**:
  - `BLANK`
  - `OK`
  - `THUMBSUP`
  - `THUMBSDOWN`
  - `PUNCH`
  - `HIGH-FIVE`

## Project Objective
- **Build a Real-Time Hand Gesture Recognition System**:
  - Capture live video feed using OpenCV.
  - Segment the hand region and preprocess the image.
  - Use a CNN model to classify hand gestures in real-time.

## Project Structure
- **File**: `cam_run.py`
  - Contains the main script for starting video capture, segmenting the hand region, and predicting gestures using the trained CNN model from the live camera feed.

- **File**: `train_gestures.ipynb`
  - Jupyter notebook for data loading, and training of a 2D Convolutional Neural Network (CNN) on the gesture dataset.

## Required Libraries
- Python 3.6.7
- OpenCV (`pip install opencv-python`)
- Matplotlib
- Keras
- scikit-learn

## How to Run the Project
1. Clone the repository.
2. Ensure you have all required libraries installed.
3. Prepare your dataset and place it in the `my_dataset` folder.
4. Train the CNN model using `train_gestures.ipynb`.
5. Run `cam_run.py` to start the real-time gesture recognition.

## Requirements
- Install necessary libraries using:

```bash
pip install opencv-python matplotlib keras scikit-learn
