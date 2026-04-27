# 🔵 Real-Time Circle Detection using OpenCV

This project detects circles in real time using a webcam and OpenCV.  
It uses the Hough Circle Transform to find circles and includes improvements such as noise reduction, contrast enhancement, parameter tuning, false circle rejection, stability across frames, FPS display, and screenshot saving.

---

## ✨ Features

- 🎥 Real-time circle detection using webcam
- 🔍 Hough Circle Transform
- ⚫ Grayscale conversion
- 🧹 Median blur for noise reduction
- 🌗 Histogram equalization for better contrast
- 🎛 Interactive trackbars for tuning parameters
- 🚫 Rejects false circles based on radius size
- 🔄 Tracks the most stable circle between frames
- 📍 Displays circle radius and center coordinates
- 🔢 Shows number of detected circles
- ⚡ Shows live FPS
- 💾 Press `s` to save a screenshot
- ❌ Press `q` to quit

---

## 📦 Requirements

Install the required libraries:

```bash
pip install opencv-python numpy
