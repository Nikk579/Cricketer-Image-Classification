# Cricket Image Classification Project

This repository contains the code and documentation for a Cricket Image Classification project using machine learning classifiers. The project aims to classify cricket images into different categories based on the cricketers present in the images.

## Overview

The project involves several key steps:

1. **Data Collection:**
   - The dataset consists of cricket images featuring various cricketers.
   - Images were collected using Fatkun batch image downloader

2. **Data Preprocessing:**
   - Ensuring uniform image sizes and formats.
   - Augmenting the dataset to increase its diversity.

3. **Data Cleaning:**
   - Removing irrelevant or duplicate images.
   - Standardizing labels for consistency.
   - if the image of cricketer dosen't have clear face and two eyes then it will be discarded and other remains .

4. **Feature Engineering:**
   - Extracting relevant features from images.
   - Utilizing techniques like wavelet transformations for better feature representation.

5. **Model Planning:**
   - Choosing appropriate machine learning classifiers for image classification.
   - Considering limitations like a small dataset and exploring strategies to overcome them.

6. **Model Building:**
   - Building machine learning models using selected classifiers.
   - Fine-tuning models to enhance performance.

7. **Hyperparameter Tuning:**
   - Optimizing model hyperparameters for better accuracy.
   - Using techniques like Grid Search CV.

8. **Model Evaluation:**
   - Evaluating models using appropriate metrics.
   - Understanding the limitations and challenges faced.

9. **Data Visualization:**
   - Visualizing key insights from the dataset.
   - Creating plots and graphs to illustrate performance.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Nikk579/Cricketer-Image-Classification.git
   cd cricket-image-classification

  Open and run the Jupyter notebooks in the notebooks directory to follow the step-by-step process.

  Explore the data directory for the dataset.

## Results
Due to the small size of the dataset, the model may not perform optimally. Additional data collection and more sophisticated techniques may be required for better accuracy.

Feel free to contribute, provide suggestions, or raise issues to improve the project.

Note: Ensure you have the required dependencies installed before running the notebooks.

## Dependencies
Python 3.x
Jupyter Notebooks
scikit-learn
OpenCV
NumPy
Matplotlib
Seaborn

Install the dependencies using:
pip install -r requirements.txt

