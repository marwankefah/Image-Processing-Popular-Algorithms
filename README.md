
# Image Processing Assignments

Python codes for Image Processing Popular Assignments.


# Table of Contents
   * [What is this?](#what-is-this)
   * [Introduction](#Introduction)
      * [Introduction to Jupyter and Python](#Introduction-to-Jupyter-and-Python)
      * [HSV and Histogram](#HSV-and-Histogram)
   * [Smoothing and EdgeDetection](#Smoothing-and-EdgeDetection)
      * [Smoothing](#Smoothing)
      * [Edge Detection](#Edge-Detection)
   * [Morphology](#Morphology)
   * [Segmentation](#Segmentation)
      * [Simple Thresholding Techniques](#Simple-Thresholding-Techniques)
      * [Adaptive Thresholding Techniques](#Adaptive-Thresholding-Techniques)
   * [K means and Hough Transform](#K-means-and-Hough-Transform)
      * [K means](#K-means)
      * [Hough Transform](#Hough-Transform)
   * [Textures](#Textures)
  
# What is this?

This is a Python code collection of Image Processing algorithms.

# Introduction

## Introduction to Jupyter and Python
- Understanding the basics of Python, Jupyter, Skimage.
- Reading an image and then plot it.
- Indexing Numpy matrices
- HSV colormap.
- Function with positional or keyword arguments

Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Introduction%20to%20Jupyter%20%26%20Python%20(HSV%2CHistogram%20Lab)/Lab_1_std.ipynb)

## HSV and Histogram

- HSV colormap.
- Function with positional or keyword arguments
- Understand the effect of noise on images and how to produce it.
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Introduction%20to%20Jupyter%20%26%20Python%20(HSV%2CHistogram%20Lab)/Lab_1_std.ipynb)

![HSV](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/HSV.PNG)

# Smoothing and EdgeDetection
## Smoothing
Filtering:
- Read an image of your choice.
- Apply salt & pepper noise with density =0.05
- Apply median filtering algorithm using a mask of size 3*3
- Compare your results with python function Skimage.filters.median
- Apply Gaussian Filtering to the noisy image image with the following conditions:
- Lengths [3 3] [7 7] for sigma = 0.5.
- Sigma(s) 8 and 0.2 for length = [3 3].
- After understanding the effect of length and sigma. Choose the best combination that fits your image. Needs Justification.
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Smoothing%20%26%20EdgeDetection/lab4_part1_smoothing_STD/Lab_4_part1_STD.ipynb)

![Smoothing](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/Smoothing.PNG)

## Edge Detection
- Apply and notice the differences between edge detection techniques
- Understand the effect of different parameters used in edge detection techniques.
- Learn and implement “Sobel operator “and “LOG” edge detection techniques.
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Smoothing%20%26%20EdgeDetection/Lab4_part2_edge_detectionSTD/Lab_5_STD.ipynb)

![Edge](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/Edge%20Detection.PNG)

# Morphology
- Erosion / Dilation
- Case Study: Credit Card Number Extraction
- Skeletonization
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Morphology/lab5-STD.ipynb)

![Morph](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/Morph.PNG)

![MorphCreditCard](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/Morph_Credit_Card.PNG)

![Morph](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/Morph_Skelt.PNG)

# Segmentation
## Simple Thresholding Techniques
- Learn how to deal with pixel level values with minimum usage of already-implemented functions.
- Learn simple threshold technique(s).
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Segmentation/lab06-seg-part1/Lab_6_STD.ipynb)

![seg1](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/seg1.PNG)

## Adaptive Thresholding Techniques
- Learn adaptive thresholding technique
- histogram automatic thresholding technique
- Local adaptive thresholding technique
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Segmentation/lab06-seg-part2/Lab_7_STD.ipynb)

![seg2](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/seg2.PNG)

# K means and Hough Transform
## K means
- Apply the kmeans clustering algorithm to solve segmentation problems
- Use Ostu thresholding for segmentation .
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/K-means%20%26%20Hough%20Transform/Lab_8_STD.ipynb)

![kmeans](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/K-means.PNG)

## Hough Transform
- Extract lines using Hough transform.
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/K-means%20%26%20Hough%20Transform/Lab_8_STD.ipynb)

![Hogh](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/Hough%2CPNG.PNG)

# Textures
- Extract features from image samples of the jeans and cotton texture using GLCM.
- Differentiate between different textures.
- LBP histogram of a grayscale image
- Documentation: [Notebook](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/Textures/lab08_STD_texture.ipynb)

![textures1](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/textures1.PNG)
![textures1](https://github.com/marwankefah/Image-Processing-Assignments/blob/master/imgs/textures.PNG)
