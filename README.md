# Multiclass-Classification-with-Pins-Face-Dataset

This project demonstrates multiclass face recognition using Artificial Neural Networks (ANNs) in Keras. The notebooks provided focus on face cropping, data preparation, and model building for accurate classification of faces in the Pins Face Dataset.

## Dataset Description

The **Pins Face Dataset** is a collection of labeled images of faces, each organized by person (label). The dataset is commonly used for facial recognition tasks and is designed to train models to distinguish between multiple individuals based on facial features. It includes a variety of poses, lighting conditions, and facial expressions to improve model robustness.

## Project Structure

- **`crop_faces.ipynb`**: This notebook preprocesses the dataset by detecting faces and cropping them to focus on relevant features. It ensures that each input to the model is consistently prepared.
- **`bonus_7454.ipynb`**: In this notebook, we implement and train a multiclass ANN model to classify different individuals in the dataset. The goal is to achieve a target accuracy of 85% or higher.
- **`bonus_after_crop.ipynb`**: This notebook further refines the dataset after cropping and prepares it for model training and evaluation.

## Instructions for Running the Code

1. **Setup**: Clone the repository and ensure you have the necessary files and dependencies.
2. **Dataset Preparation**:
   - Download the Pins Face Dataset from the source.
   - Place the dataset in a directory accessible by the notebooks.
3. **Preprocess**:
   - Open `crop_faces.ipynb` and run the cells to crop the faces from the images. This process will prepare the dataset for training by standardizing image dimensions and focusing on facial regions.
4. **Train Model**:
   - Run `bonus_7454.ipynb` to initiate model training. This notebook configures and trains the ANN model with the processed dataset.
   - Use `bonus_after_crop.ipynb` to perform any final preprocessing and adjustments if needed.

## Dependencies and Installation Instructions

### Requirements
The following packages are required to run the notebooks:

- Python 3.x
- Keras
- TensorFlow
- OpenCV
- Numpy
- Matplotlib
- Jupyter Notebook

### Installation

 Make sure you have `res10_300x300_ssd_iter_140000.caffemodel` and `deploy.prototxt` files, as they are necessary for OpenCV's face detection model used in cropping faces.
