# Image Processing Project

This repository contains a collection of Jupyter Notebooks and sample images for exploring various image processing techniques using Python. The project covers adaptive noise reduction, image augmentation, morphology, restoration, noise addition, smoothing, and edge detection.

## Folder Structure

- `Dataset-images/`  
  Contains sample images used in the notebooks (e.g., `cat.png`, `IMG_2678.JPG`).

- `Notebooks/`  
  Contains Jupyter Notebooks organized by topic:
  - `Adaptive Noise Reduction/`
    - `Adaptive_noise_reduction.ipynb`: Adaptive noise reduction for salt and pepper noise.
  - `Image Augmentation, Morphology and Restoration/`
    - `Image augmentation, image morphology and image restoration.ipynb`: Techniques for augmenting images, applying morphological operations, and restoring images.
  - `Noise, Smoothing and Edge Detection/`
    - `Noise,_Smoothing_and_Edge_Detection.ipynb`: Methods for adding noise, smoothing images, and detecting edges.

## Notebooks Overview

### 1. Adaptive Noise Reduction
- **Notebook:** `Adaptive_noise_reduction.ipynb`
- **Description:** Implements an adaptive scheme to reduce salt and pepper noise in images using OpenCV and NumPy. Includes image reading, noise addition, and filtering techniques.

### 2. Image Augmentation, Morphology and Restoration
- **Notebook:** `Image augmentation, image morphology and image restoration.ipynb`
- **Description:** Demonstrates image resizing, augmentation (e.g., flipping, rotation), morphological operations (e.g., dilation, erosion), and restoration techniques.

### 3. Noise, Smoothing and Edge Detection
- **Notebook:** `Noise,_Smoothing_and_Edge_Detection.ipynb`
- **Description:** Covers adding different types of noise, applying smoothing filters (mean, median, Gaussian), and detecting edges using various algorithms.

## Dataset

Sample images are provided in the `Dataset-images/` folder. You can add your own images for experimentation.

## Requirements

- Python 3.x
- Jupyter Notebook
- OpenCV (`cv2`)
- NumPy
- Matplotlib

Install dependencies using pip:
```bash
pip install opencv-python numpy matplotlib
```

## How to Run

1. Clone or download this repository.
2. Open the desired notebook in Jupyter Notebook or JupyterLab.
3. Ensure the images in `Dataset-images/` are accessible to the notebooks.
4. Run the cells to see the results and experiment with the code.

## Credits

Developed for educational purposes to demonstrate fundamental image processing techniques in Python.

---
Feel free to contribute or use these notebooks for your own learning and projects!
