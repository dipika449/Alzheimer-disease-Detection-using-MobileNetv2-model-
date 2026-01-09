# Alzheimer-disease-Detection-using-MobileNetv2-model

This project aims to detect Alzheimer's disease from MRI images
using MobileNETv2 model.

## Objectives
- Detect Alzheimer’s disease
- Classify MRI images
- Apply MobileNETv2 model


## Key Features
- MRI -based Alzheimer disease classification
- Image preprocessing and npormalization
- Model training, validation, and evaluation
- Accuracy and loss visualization
- Implemented using TensorFlow & keras
- 


## Dataset
-MRI brain images
-classes:
   - Mild Demented
   - Modarate Demented
   - Non-Demented

## Technology Used
- Programming Language: Python
- Platform: Google Colab
- Framework: TensonFlow, keras
- Libraries: NumPy, Matplotlib
- Model Type - convolutional Neural Network

## System Workflow
1. Mount Google Drive
2. Load MRI image dataset
3. Image preprocessing(resizing and normalization)
4. CNN model construction
5. Model training
6. Model evaluation
7. Visualization of accuracy and loss

## Model Architecture

The CNN architecture consists of:

- Convolutional layers
- Max Pooling layers
- Flatten layer
- Fully Connected (Dense) layers  
- Output layer with appropriate activation function  

## Experimental Results

- The model shows steady improve in traning and validation accuracy
- Training and validation loss decreases over epochs
- Results confirm the effective of CNN for Alzheimer’s disease detection from MRI images  

## Performance Visualization

- Training Accuracy vs Validation Accuracy
- Training Loss vs Validation loss
( visulized using Matplotlib)

## How to Run the Project

1. Open Google Colab
2. Upload Alzhimer.ipynb
3. Mount Google Drive
4.  Run all cells sequentially  

## Future Scope

- Multi-class classification for Alzheimer’s disease stages
- Use of Transfer Learning models such as VGG16, ResNet
- Performance improvement using larger datasets
- Deployment as a web or mobile application



