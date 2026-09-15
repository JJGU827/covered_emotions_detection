# Covered Emotions Detection

A computer vision and machine learning project developed during the **NSLC Artificial Intelligence Summer Program at UC Berkeley in Summer 2025**.

The project explores emotion recognition from facial features, with a focus on identifying emotions when parts of the face are obstructed or covered.

## Overview

Facial emotion recognition models can have difficulty making accurate predictions when important facial features are hidden. This project explores how image processing and machine learning can be used to classify emotions from facial images, including images with partial facial obstruction.

The project includes tools for preparing facial-image datasets, processing images for model training, and storing trained models.

## Features

- Facial image preprocessing for machine learning
- Support for partially obstructed facial images
- Image conversion to grayscale
- Automatic image resizing
- Conversion of image data into numerical arrays
- Dataset preparation and CSV export
- Machine learning model training and storage

## Technologies

- **Python**
- **NumPy**
- **pandas**
- **Pillow (PIL)**
- Machine Learning / Computer Vision

## Image Processing Pipeline

The preprocessing pipeline prepares images for use by the emotion-detection model.

Images are:

1. Loaded from the dataset
2. Converted to grayscale
3. Resized to a consistent resolution
4. Converted into NumPy arrays
5. Flattened into numerical feature vectors
6. Exported into CSV format for further processing and model training

The current preprocessing implementation supports `.png`, `.jpg`, and `.jpeg` images and can be configured for different image resolutions.

## Repository Structure

```text
covered_emotions_detection/
├── datasets/          # Image datasets used by the project
├── models/            # Model-related code and resources
├── trained_models/    # Trained model files
├── data_prep.py       # Image preprocessing and dataset preparation
└── main.py            # Main project entry point
