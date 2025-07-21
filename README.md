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

