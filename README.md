# 🔢 Supervised Object Counting using Deep Learning

This two-part project demonstrates a supervised approach to object counting in images using deep learning. The task is to predict the number of objects (e.g., people, cars, etc.) in an image rather than performing pixel-wise detection or segmentation. This is useful in scenarios where object localization is difficult due to crowding, occlusion, or low resolution.

---

## 🧪 Project Structure

### 📘 Part 1: Data Preprocessing & Baseline Model
- Loaded and explored the counting dataset (e.g., crowd images or synthetic object scenes)
- Applied image transformations and normalized inputs
- Defined the counting problem as a **regression task**
- Built a **simple CNN-based baseline model**
- Trained and evaluated the model using MAE (Mean Absolute Error)

### 📙 Part 2: Model Improvement & Evaluation
- Implemented **advanced architectures** (e.g., ResNet-based or deeper CNNs)
- Applied data augmentation techniques
- Introduced **regularization** and learning rate schedules
- Compared baseline and improved model performance
- Visualized predictions vs. ground-truth counts

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- OpenCV (for image loading and processing)

---

## 🚀 How to Run

1. Install dependencies:  
   pip install tensorflow opencv-python matplotlib numpy
