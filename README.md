# Landmark Detection using VGG19

## Project Overview

This project implements a Landmark Classification system using a Convolutional Neural Network based on the VGG19 architecture.

The model predicts the landmark ID from an input image using transfer learning.

---

## Features

- Google Landmark Dataset
- Image preprocessing
- Random image visualization
- Label Encoding
- Train-Test Split
- VGG19 Transfer Learning
- Batch-wise Training
- Landmark Prediction
- Model Saving

---

## Dataset

Dataset Used:
Google Landmark Recognition Dataset

Files Required

- train.csv
- images/

Dataset Link:

https://s3.amazonaws.com/google-landmark/train/images_000.tar

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Model Architecture

Input Image

↓

Resize (224×224)

↓

VGG19 (Pretrained)

↓

Flatten

↓

Dense Layer

↓

Dropout

↓

Softmax

↓

Predicted Landmark ID

---

## Workflow

1. Import Libraries
2. Load Dataset
3. Display Random Images
4. Image Preprocessing
5. Label Encoding
6. Train-Test Split
7. Build VGG19 Model
8. Train Model
9. Evaluate Model
10. Predict Landmark
11. Save Model

---

## Installation

```bash
git clone https://github.com/yourusername/Landmark-Detection-VGG19.git

cd Landmark-Detection-VGG19

pip install -r requirements.txt
```

---

## Run

Open

```
Landmark_Detection.ipynb
```

Run all cells sequentially.

---

## Future Improvements

- Fine-tune VGG19 layers
- Increase dataset size
- Add Top-5 Accuracy
- Model Deployment using Flask/Streamlit
- Mobile App Integration

---

## Author

**Krishnendu Das**

B.Tech Artificial Intelligence & Machine Learning

Aditya University
