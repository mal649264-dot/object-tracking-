# object-tracking-
# Blue Object Tracking using OpenCV

A simple Computer Vision project built with Python and OpenCV to detect and track blue objects in a video using the HSV color space.

---

## 📽️ Demo / Output

<!-- Drag and drop your video or GIF directly here on GitHub -->
https://github.com/mal649264/object-tracking-/assets/output.mp4

---

## 📌 How It Works

The code processes the video in **3 simple steps**:

1. **Color Conversion:** Converts video frames from BGR to HSV color space for accurate color detection.
2. **Color Masking:** Isolates the blue color range to filter out all other background colors.
3. **Contour Tracking:** Finds the largest blue object in each frame and draws a dynamic bounding box around it.

---

## 🛠️ How to Run

### 1. Install Dependencies
Make sure you have `opencv-python` and `numpy` installed:
```bash
pip install opencv-python numpy
