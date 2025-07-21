# myprojects
# Feature Detection on Microscopy Images with OpenCV

This project demonstrates and compares four keypoint detection algorithms—SIFT, ORB, BRISK, and AKAZE—applied to a stained microscopy image of blood cells. Using Python, OpenCV, and Matplotlib, the project extracts keypoints, visualizes them, and evaluates descriptor outputs to understand how each algorithm responds to texture-rich biological structures.

## Notebook

The full implementation is available in the file `featuredetection_microscopy_opencv.ipynb`.

## Overview

This project covers:
- Grayscale conversion of a microscopy image
- Keypoint detection and descriptor computation using SIFT, ORB, BRISK, and AKAZE
- Visualization of keypoints using OpenCV and Matplotlib
- Printing descriptor shapes and keypoint counts for comparative analysis
- Explanation of how each algorithm detects specific features such as corners, blobs, or textures

## Technologies Used

- Python  
- OpenCV  
- Matplotlib  
- Google Colab

## Applications

This analysis can be applied in:
- Biomedical imaging and diagnostics
- Computer vision education and algorithm benchmarking
- Feature tracking in texture-dense environments

## Image Description

The input is a stained microscopic image of blood cells. These images contain distinct edges, circular shapes, and internal textures, making them ideal candidates for visual feature analysis. Each algorithm detects different aspects of this structure, which is then visualized and quantified.

## Author

Created by Harshitha Reddy Gudati  
Graduate student specializing in computer vision, image processing, and algorithm explainability

# Comprehensive Image Preprocessing Pipeline for Computer Vision

This repository contains a modular image preprocessing pipeline designed to prepare and enhance input data for various computer vision tasks. Implemented in Python using OpenCV and supporting libraries, the pipeline includes twenty commonly used techniques for image normalization, feature boosting, and transformation—all essential for improving model accuracy and interpretability in real-world applications.

## Overview

The pipeline is organized for flexibility and experimentation. Each preprocessing method can be applied independently or as part of a sequential workflow. The implementations are documented with code explanations, visual outputs, and practical use cases.

## Included Techniques

The preprocessing steps in this collection include:

- Image resizing
- Grayscale conversion
- Histogram equalization
- Blurring: Gaussian and Median
- Denoising
- Adaptive thresholding
- Edge detection: Canny and Sobel
- Erosion and dilation
- Image padding
- Image masking
- Rotation and flipping
- Normalization
- HSV and RGB conversion
- Image cropping
- Contour detection
- Noise simulation
- Image sharpening
- Contrast adjustment
- Image augmentation

## Technologies Used

- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- Google Colab  

## Applications

This pipeline supports preprocessing for tasks such as:
- Image classification and segmentation
- Feature extraction and object detection
- Biomedical image analysis
- Model training preparation and data augmentation

## Project Structure

Each technique is implemented and documented in individual notebooks or code files. Descriptions are provided for every step, with input/output comparisons and notes on parameter selection where applicable.

## Author

Created by Harshitha Reddy Gudati  
Master's-level researcher exploring feature engineering, image analysis, and algorithm explainability in computer vision.
