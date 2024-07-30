# Feature Extraction Techniques for Image Analysis

This repository provides a collection of feature extraction techniques implemented in Python, designed for various image analysis tasks such as classification, object detection, and image retrieval. The techniques include traditional methods as well as deep learning-based features.

## Overview

The following feature extraction techniques are implemented:

1. **Color Histogram**: Captures the distribution of colors in an image.
2. **Edge Detection (Canny)**: Detects edges within an image, useful for capturing structural features.
3. **Local Binary Pattern (LBP)**: A texture descriptor that captures local patterns in grayscale images.
4. **Contour Detection**: Identifies and extracts contours from an image, useful for shape analysis.
5. **Keypoint Detection (ORB)**: Detects and describes keypoints in an image, useful for image matching and retrieval.
6. **Deep Learning Features (ResNet)**: Extracts high-level features using a pre-trained ResNet model.

## Getting Started

### Prerequisites

To run the code in this repository, you need to have the following Python libraries installed:

- `opencv-python`
- `numpy`
- `scikit-image`
- `matplotlib`
- `torch`
- `torchvision`
- `Pillow`

You can install these dependencies using pip:

```bash
pip install opencv-python numpy scikit-image matplotlib torch torchvision Pillow
