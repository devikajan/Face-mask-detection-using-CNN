
#  Face Mask Detection using CNN

A Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images as **With Mask** or **Without Mask**.

##  Overview

This project implements an image classification model trained on the Face Mask Dataset from Kaggle. The model learns visual features from images and predicts whether a person is wearing a face mask.

##  Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-Learn

## 📂 Dataset

**Source:** Face Mask Dataset by Omkar Gurav

https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

| Class | Images |
|---------|---------:|
| With Mask | 3,725 |
| Without Mask | 3,828 |
| **Total** | **7,553** |

##  Workflow

```text
Dataset
   ↓
Image Preprocessing
   ↓
Train-Test Split
   ↓
CNN Model Development
   ↓
Model Training
   ↓
Prediction
   ↓
Evaluation
```

##  Image Preprocessing

- Resized images to 128 × 128 pixels
- Converted images to NumPy arrays
- Normalized pixel values
- Encoded labels
- Split data into training and testing datasets

##  Model Architecture

```text
Input Image
      ↓
Conv2D
      ↓
ReLU
      ↓
MaxPooling
      ↓
Flatten
      ↓
Dense Layer
      ↓
Softmax Output
```

##  Features

- Binary Image Classification
- CNN-based Deep Learning Model
- Image Preprocessing Pipeline
- Prediction on Unseen Images
- Model Evaluation using Accuracy and Loss

##  Project Structure

```text
Face-Mask-Detection/
│
├── Face_Mask_Detection.ipynb
├── README.md
├── requirements.txt
└── dataset/
    ├── with_mask/
    └── without_mask/
```

##  Run Locally

```bash
git clone https://github.com/your-username/face-mask-detection.git

cd face-mask-detection

pip install -r requirements.txt

jupyter notebook
```

Open:

```text
Face_Mask_Detection.ipynb
```

##  Results

The trained CNN model successfully classifies images into:

-  With Mask
-  Without Mask

##  References

- Face Mask Dataset: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset
- TensorFlow: https://www.tensorflow.org/
- Keras: https://keras.io/


---

⭐ If you found this project useful, consider giving it a star.
