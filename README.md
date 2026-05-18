# LEGO Image Converter

A computer vision project that captures real-world images and converts them into LEGO-style mosaics using image processing techniques.

## Overview

This project uses OpenCV-based image processing to transform live camera images into LEGO-style renderings. The pipeline supports grayscale LEGO mosaics, color LEGO mosaics, constrained color palettes, edge enhancement, and multi-brick merging.

## Features

- Live camera image capture in Google Colab
- Grayscale LEGO rendering using black, gray, and white bricks
- Color LEGO mosaic generation using a custom LEGO color palette
- Gaussian blur for noise reduction
- Canny edge detection for preserving facial/object contours
- RGB color quantization using closest-palette matching
- Saturation boosting to improve color vibrancy
- Multi-brick merging with 1x1, 1x2, 2x2, and 2x4 bricks
- Brick usage statistics and summary

## Technologies Used

- Python
- OpenCV
- NumPy
- Google Colab
- Image Processing
- Computer Vision

## Report

The full assignment report is included here:

[Assignment Report](Assignment1_Report_25142309x_PATEL_Diya.pdf)

## What I Learned

This project helped me understand image quantization, edge detection, color palette mapping, noise reduction, and the trade-off between visual detail and constrained LEGO-style rendering.
