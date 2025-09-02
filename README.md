# Feature Tracking with OpenCV (Beginner Demos)

This repository contains beginner-friendly demos of **corner detection** and **optical flow tracking** using OpenCV and Python.  
It is part of my learning journey into **Computer Vision** and **Visual-Inertial Navigation Systems (VINS)**.

---

## 🚀 Features
- **Shi–Tomasi Corner Detection** (`cv2.goodFeaturesToTrack`)
- **Lucas–Kanade Optical Flow** (`cv2.calcOpticalFlowPyrLK`)
- Three runnable demos:
  1. **Corner Detection on Uploaded Image**  
     Upload an image (e.g., building facade) and detect feature corners.  
  2. **Synthetic Checkerboard Tracking**  
     Generate a moving checkerboard and track features across frames.  
  3. **Shifted Real Image Tracking**  
     Download a real image, synthetically shift it, and track features.

---

## 📂 Repository Structure
feature-tracking-opencv-demos/
```
│── README.md             # Project description and usage
│── requirements.txt      # Python dependencies
│── corner_detection.py   # Demo 1: Corner detection on uploaded image
│── checkerboard_flow.py  # Demo 2: Optical flow on synthetic checkerboard
│── shifted_image_flow.py # Demo 3: Optical flow on shifted real image
```
## 🔧 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/adyasha95/feature-tracking-opencv-demos.git
cd feature-tracking-opencv-demos
pip install -r requirements.txt
