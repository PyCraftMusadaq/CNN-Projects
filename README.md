# CNN Projects: Parkinson's Disease Image Classification

This project focuses on classifying Parkinson's disease images using a Convolutional Neural Network (CNN) model.

## Complete Pipeline Overview

This repository contains the complete code, starting from downloading the dataset in Google Colab to preprocessing, scaling, and model building using CNN. Below is an outline of the workflow:

1. **Dataset Preparation**:  
   - Download the dataset and preprocess it, including scaling the images for optimal performance.
   
2. **Model Development**:  
   - Build and train the CNN model.  
   - Address the imbalanced dataset by truncating the majority class to create a balanced dataset, as training on large datasets requires substantial GPU and RAM resources.

3. **Model Evaluation**:  
   - Evaluate the model to ensure it performs well for the given scenario.

4. **Pipeline Creation**:  
   - Develop a simple pipeline that processes input images from users and predicts the classification.

We are in the process of integrating this model into a web application. The website link will be shared here once it becomes operational.

## How to Use

1. Clone this repository to your local machine.
2. Ensure you have Python and the required dependencies installed:
   - TensorFlow
   - OpenCV
   - NumPy
3. Run the code to start the pipeline.

## Notes

- The dataset used in this project is small and required adjustments to handle its imbalance. Future versions will explore larger datasets and improved resources.
- This project demonstrates a working prototype and can be expanded with further optimizations.

Thank you for exploring this project! Stay tuned for updates.
