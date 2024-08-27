# 💤 Drowsiness Detection using Custom Dataset

## Overview

This project demonstrates how to create and use a custom dataset for detecting drowsiness in real-time using a YOLOv5 model. The dataset consists of images labeled as either "awake" or "drowsy," which are used to train the model for real-time detection.

## Dataset 📁

### 1. Data Collection 📷

The dataset is composed of images captured via a webcam, labeled as either `awake` or `drowsy`. Each category includes 20 images.

#### Labels:
- **😴 drowsy**: Images of individuals exhibiting signs of drowsiness.
- **😃 awake**: Images of individuals in an alert state.

### 2. Directory Structure 🗂️

The images are stored in the following directory structure:

```data/ 
└── images/
 ├── awake.XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX.jpg 
 └── drowsy.XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX.jpg
 ```

- Images are saved with unique identifiers to avoid filename conflicts.

## Training 🛠️

### 1. Setting Up the Environment ⚙️

Ensure all necessary dependencies are installed, including `torch`, `cv2`, and `matplotlib`.

### 2. Data Collection Script ✏️

Use a script to collect images for the dataset, categorizing them into `awake` and `drowsy` labels.

### 3. Training the Model 🧠

Train the YOLOv5 model on the custom dataset using a specified training command.

### 4. Loading the Trained Model 📦

After training, load the custom-trained model for real-time drowsiness detection.

### 5. Real-Time Detection 🎥

Deploy the trained model to detect drowsiness in real-time using a webcam.

## Conclusion ✅

This project demonstrates the process of creating a custom dataset, training a YOLOv5 model, and deploying it for real-time drowsiness detection. The methodology can be adapted for other object detection tasks or expanded for improved performance.

