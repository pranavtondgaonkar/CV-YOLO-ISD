# CV-YOLO-ISD

## Problem Statement

Considering the hazardous nature of work in various industries and the increase in neglect of safety standards. Organizations and Governments have implemented rules and guidelines for the labours working in these sectors (Construction, Mining, Heavy Metal industries, etc.) to decrease the probability of injury and accidents.
This app detects the safety gear worn by the workers to recognize if the safety standards are followed.

## Solution

This app will use computer vision and machine learning to detect and force the workers to wear the necessary protection gear while entering the workspace. The model will take a real-time image and determine if 5 objects (Helmet, Gloves, Jacket, Goggles, footwear) are detected in the image. If those are absent a prohibition alarm will be triggered.

The CV-YOLO-ISD project leverages the YOLO (You Only Look Once) model to perform object detection in images. The application is built using Flask and provides endpoints for training the model and performing object detection on input images.

- **Training**: The application has a training pipeline in place, which can be triggered via the `/train` endpoint. This pipeline is designed to train the YOLO model on a dataset of images.

- **Prediction**: The `/predict` endpoint allows users to input an image and receive the processed image with detected objects highlighted.

## How to Run the Code

1. **Setup**: Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the Application**: Execute the main application file:
   ```bash
   pip install -r requirements.txt
   ```
