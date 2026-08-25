# Image Processing using Python

This repository contains basic Image Processing programs implemented
using Python.

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- PIL (Pillow)

## 📌 Programs Included

### 1. Average Filtering

Average filtering is used to smooth an image and reduce noise.

Different kernel sizes are used to observe the effect of filtering:

- 3 × 3 Average Filter
- 5 × 5 Average Filter
- 7 × 7 Average Filter
- 11 × 11 Average Filter

### OpenCV Implementation

The OpenCV implementation uses:

```python
cv2.blur(img, (3, 3))
cv2.blur(img, (5, 5))
cv2.blur(img, (7, 7))
