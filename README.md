# Image Processing Toolkit

A comprehensive **Image Processing Toolkit** developed in Google Colab, providing a variety of image processing, feature extraction, object detection, and machine learning techniques for analyzing images.  

> **Note:** GitHub may not render Colab notebooks properly if outputs are large. **Best practice:** download the repository and open the notebook in **Google Colab** for full functionality and visualization.

---

## Features

### 1. Basic Image Processing
- Grayscale conversion
- Histogram equalization
- Gaussian blur for smoothing and noise reduction
- Image sharpening for edge enhancement
- Edge detection using **Sobel** and **Canny**

### 2. Advanced Image Processing
- Morphological operations: erosion, dilation, opening, closing
- Thresholding: simple & **Otsu's**
- Color space conversions: **HSV**, **LAB**
- Fourier Transform analysis for frequency-domain understanding

### 3. Feature Extraction
- SIFT & ORB keypoints and descriptors
- HOG (Histogram of Oriented Gradients) features

### 4. Object Detection
- Feature matching with SIFT + FLANN
- Template matching
- Homography-based bounding box detection

### 5. Machine Learning Integration
- Pre-trained **ResNet50** model for image classification

### 6. User Interface
- Web-based UI using **Gradio**
- Tabbed interface for image processing, detection, and classification

### 7. Code Organization & Visualization
- All functions consolidated for reusability
- Enhanced visualizations for feature matching, histograms, and outputs

---

## Repository Structure

```text
ImageProcessingToolkit/
├── Image_Processing_Toolkit.ipynb   # Main Colab notebook
├── results/                         # Sample results and processed images
│   ├── grayscale.png
│   ├── histograms.png
│   └── ... (other output images)
├── README.md                         # This file
```
---

## How to Use

1. Clone or download the repository.
2. Open `Image_Processing_Toolkit.ipynb` in **Google Colab**.
3. Run all cells to explore the toolkit and interact with the **Gradio** interface.

> ⚠️ Opening the notebook directly on GitHub may not render outputs properly. Using **Colab** ensures full functionality.

---

## License

This project is released under the **MIT License**.
