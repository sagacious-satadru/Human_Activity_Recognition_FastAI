# Human Activity Recognition using Deep Learning

This repository contains a Jupyter Notebook that demonstrates the creation of a deep learning model for human activity recognition. The model is built using the PyTorch and FastAI libraries and is capable of classifying various types of human activities based on input images.

## Notebook Overview

The notebook is designed to guide you through the process of:

1. Setting up the necessary environment and libraries for the project.
2. Collecting and preparing the dataset of human activity images.
3. Training a deep learning model using the FastAI library.
4. Saving and exporting the trained model for future use.
5. Making predictions on new images and displaying the results.

## Prerequisites

- Python (>= 3.9)
- Jupyter Notebook or Jupyter Lab
- FastAI library
- PyTorch library
- Matplotlib library
- ipywidgets library

## Notebook Contents

1. **Environment Setup**: Installing required libraries and setting up the FastAI environment for the project.
2. **Data Collection**: Collecting images of different human activities using Bing Image Search.
3. **Data Preprocessing**: Organizing the collected images into labeled directories and verifying image quality.
4. **Data Loading**: Creating data loaders using FastAI's `DataBlock` to load and preprocess the dataset.
5. **Model Training**: Building and training a deep learning model using transfer learning with the ResNet18 architecture.
6. **Model Evaluation**: Visualizing the model's performance using a confusion matrix and top loss analysis.
7. **Model Export**: Saving the trained model using both FastAI and PyTorch formats for future use.
8. **Real-time Prediction**: Creating an interactive interface to upload images and obtain real-time predictions.

## How to Use

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook (`Human_Activity_Recognition.ipynb`) using Jupyter Notebook or Jupyter Lab.
4. Follow the notebook cells sequentially, executing them one by one to understand and replicate the process.
5. Upload your own human activity images using the interactive widget and observe the model's predictions.


### The notebook is a part of the final project done for Celebal Summer Internship 2023 - by Satadru Bhowmik (CSI ID:  CT-CSI23/DS0492)

---

**Note:** This readme has been written to provide a general overview. Please refer to the actual notebook for detailed code explanations, step-by-step instructions, and code execution.
