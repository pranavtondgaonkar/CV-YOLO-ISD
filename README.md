# CV-YOLO-ISD

## Problem Statement

To Develop a detection system that uses computer vision and machine learning to monitor, track, and enforce employees/workers to wear safety gear. 

## Proposed Solution
This app will develop an Industry Safety Detection (ISD) designed and modeled to take a real-time image of the personnel as input and determine whether or not the five gears - helmet, gloves, jacket, goggles, and footwear - are worn before entering the workplace, as well as record the procedures. The app is developed in the following steps:
1. Data Collection: [Kaggle]((https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection))
2. Preprocess the data for training
3. Train a YOLOv7 model to perform object detection in images
4. Create a web app using Flask
5. Deploy on AWS cloud

## How to Run the Code locally

1. **Setup**: Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the Application**: Execute the main application file:
   ```bash
   python app.py
   ```
