# Image Processing Lab Assignments

## Overview
This repository contains six lab assignments related to Image Processing using OpenCV, Matplotlib, NumPy, and Pandas. Each assignment is implemented in a separate Jupyter Notebook (`.ipynb`) file.

## Prerequisites
Ensure you have the following libraries installed before running the notebooks:

```bash
pip install opencv-python matplotlib numpy pandas jupyter
```

Alternatively, you can install the required packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Lab Assignments
Each lab focuses on different aspects of image processing:

### 📌 **Lab 1: Introduction to Image Processing**
- Image Creation and Image Display
- Accessing Image Properties
- Color Space Conversion
- Sampling and Quantization
- Basic Image Manipulation ( resize, crop, rotate, flip, annotate )
- Pixel Neighborhood Analysis ( connectivity, distance measure )


### 📌 **Lab 2: Image Transformations**
- Image resizing, cropping, and aspect ratio preservation
- Image rotation and flipping
- Image annotation (drawing lines, shapes, and text)

### 📌 **Lab 3: Image Enhancement and Filtering**
- Applying different filters: Blur, Gaussian, Median, and Bilateral filtering
- Image thresholding (Binary, Adaptive, Otsu's method)
- Histogram equalization for contrast enhancement

### 📌 **Lab 4: Edge Detection and Contour Analysis**
- Applying Sobel, Prewitt, and Canny edge detection
- Finding and drawing contours
- Convex hull and bounding boxes

### 📌 **Lab 5: Morphological Operations**
- Dilation, erosion, opening, and closing operations
- Morphological gradient and top-hat transformation
- Removing noise from binary images

### 📌 **Lab 6: Image Segmentation and Object Detection**
- Thresholding and region-based segmentation
- Watershed algorithm for separating objects
- Object detection using contour properties

## How to Run the Notebooks
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/image-processing-labs.git
   cd image-processing-labs
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and run each lab notebook (Lab1.ipynb, Lab2.ipynb, etc.)

## Folder Structure
```
📂 image-processing-labs/
├── 📜 Lab1.ipynb  # Introduction to Image Processing
├── 📜 Lab2.ipynb  # Image Transformations
├── 📜 Lab3.ipynb  # Image Enhancement and Filtering
├── 📜 Lab4.ipynb  # Edge Detection and Contour Analysis
├── 📜 Lab5.ipynb  # Morphological Operations
├── 📜 Lab6.ipynb  # Image Segmentation and Object Detection
├── 📜 requirements.txt  # Required dependencies
├── 📜 README.md  # Project documentation
└── 📂 images/  # Sample images for processing
```

## Contributions
Feel free to contribute by improving code or adding more assignments.

## License
This project is open-source and available under the [MIT License](LICENSE).

---
🚀 **Happy Coding!**

