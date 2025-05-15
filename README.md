# Age Detection with Deep Learning

## Project Overview

This project focused on building a deep learning model to estimate a person’s age based on facial images. The objective was to explore how computer vision techniques can support age verification processes in retail settings. Using a convolutional neural network (CNN) with a ResNet50 backbone, the model predicts a customer's age and can be used to flag potentially underage individuals for further review.

## Objectives

- Explore facial image data and assess quality, distribution, and biases
- Build a regression model using convolutional neural networks
- Apply data augmentation and regularization to improve generalization
- Evaluate model performance using appropriate metrics (MAE)

## Tools & Technologies

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, pandas
- Matplotlib, Seaborn
- Pretrained ResNet50 model (ImageNet)

## Approach

- Loaded and preprocessed facial image data with OpenCV
- Resized images and normalized pixel values
- Split dataset into training and validation sets
- Fine-tuned a ResNet50-based CNN model
- Used Mean Absolute Error (MAE) to evaluate predictions

## Key Results

- The model achieved a validation MAE of approximately 7.6 years
- Data augmentation helped improve model robustness against lighting and expression variability
- Results indicate potential for supporting — but not replacing — manual age verification processes

## Limitations and Future Improvements

- The model was limited by label distribution skew and lack of demographic variety
- Future versions could incorporate metadata (e.g., gender, region) for better accuracy
- Model could be deployed in a Streamlit interface or integrated into a retail kiosk application

