# 🎨 Air Canvas - OpenCV Virtual Painter

A real-time Computer Vision application built using **Python** and **OpenCV** that allows users to draw digitally on screen by moving a colored object (like a blue cap or marker) in front of their webcam.

---

## 📌 Features

- **Object Tracking:** Real-time color tracking in the **HSV color space** using contour detection.
- **Dynamic Palette:** Easily switch between 7 vibrant colors (Blue, Green, Red, Yellow, Orange, Purple, Cyan).
- **Virtual Eraser:** Switch to Eraser mode to clean specific parts of your drawing.
- **Screen Clear:** Quick action box to clear the entire canvas instantaneously.
- **Dynamic UI:** Automatically adjusts palette layout based on the number of configured colors.

---

## 🛠 Tech Stack

- **Language:** Python 3.x
- **Libraries:** 
  - `opencv-python` (Image processing & computer vision)
  - `numpy` (Matrix operations & canvas generation)

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed on your system. Install the required dependencies using pip:

```bash
pip install opencv-python numpy
