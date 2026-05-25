# 😶 Live Face Blur - Python Edition
Real-time face detection and blurring using `OpenCV` and `Haar Cascade` classifiers.

## 🎮 Description
This is a simple implementation of a live face blur tool, built entirely in Python using OpenCV. The program accesses your webcam in real time and automatically detects and blurs any faces it finds. The project features:

* Real-time webcam face detection
* Automatic Gaussian blur applied to detected faces
* Lightweight and minimal dependencies
* Clean and readable code structure
* Simple one-key exit control

Great for learning computer vision fundamentals and OpenCV basics in Python.

---

## 🚀 Getting Started

### Prerequisites

* Python 3.7 or later
* pip
* A working webcam

### Install Dependencies

```bash
pip install opencv-python
```

### Run the Program

1. Clone the repository:

```bash
git clone https://github.com/IoannisKassios/Face_Blur.git
cd Face_Blur
```

2. Run the script:

```bash
python main.py
```

3. Press **`Q`** to quit the window.

---

## 🧠 Concepts Used

* **OpenCV** for real-time video capture and image processing
* **Haar Cascade Classifier** for frontal face detection
* **Gaussian Blur** for privacy masking of detected faces
* **Region of Interest (ROI)** manipulation on video frames
* Basic **computer vision** pipeline (capture → detect → process → display)

---

## 🙌 Acknowledgments

Inspired by privacy-focused computer vision demos and OpenCV tutorials. A great starter project for anyone learning:
* Computer vision with Python
* Real-time video processing
* Face detection techniques

---
