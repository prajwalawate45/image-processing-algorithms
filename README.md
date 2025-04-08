# 🧠 Image Processing Algorithms with OpenCV

This repository contains implementations of key computer vision algorithms using Python and OpenCV. The focus is on detecting features, matching keypoints between images, and identifying corners in real-world scenarios.

## 📌 Project Objectives

- Implement SIFT to detect and match features between two images.
- Use RANSAC to eliminate outlier keypoint matches and fit a transformation model.
- Apply the Harris Corner Detector to find corners in a grayscale image.
- Visualize all outputs clearly alongside original images.

---

## 📷 Algorithms Implemented

### 🔍 1. **SIFT (Scale-Invariant Feature Transform)**
- Detects and describes local features in images.
- Matches keypoints between two input images.
- Useful for object recognition and tracking.

### 🧹 2. **RANSAC (Random Sample Consensus)**
- Filters incorrect keypoint matches from SIFT.
- Computes a homography matrix for geometric alignment.
- Great for panorama stitching or image alignment.

### 🏠 3. **Harris Corner Detector**
- Detects corners in grayscale images.
- Corners are important in structure tracking and SLAM applications.

---

## 🛠️ Tech Stack

- Python 🐍
- OpenCV 🖼️
- NumPy ➕
- Matplotlib 📊
- Jupyter Notebook 📓
