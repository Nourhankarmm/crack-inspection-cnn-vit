# 🛣️ Pavement Crack Classification using CNNs & Vision Transformers

A binary image classification project to automatically detect the presence of cracks in road/pavement surfaces using deep learning. This work compares classical CNNs with Vision Transformers (ViT) for improved accuracy.

---

## 🚀 Project Overview

Manual inspection of cracks in pavements is time-consuming and prone to errors. This project automates the process using AI models trained to classify whether an image contains a crack (`positive`) or not (`negative`).

---

## 🧠 Models Used

| Model           | Type              | Description                       |
|----------------|-------------------|-----------------------------------|
| CNN (Custom)   | Convolutional NN  | Simple and fast classifier        |
| ViT (Vision Transformer) | Transformer-based | High accuracy with more data       |

---

## 📁 Dataset Structure

<pre>
dataset/
├── positive/       # Images that contain visible cracks
└── negative/       # Images with no cracks
</pre>

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/oluwaseunad/concrete-and-pavement-crack-images)

---

## 🏗️ Project Structure

<pre>
├── models/
│   ├── cnn_classifier.py       # CNN-based model
│   └── vit_classifier.py       # Vision Transformer-based model
│
├── dataset/
│   ├── positive/
│   └── negative/
│
├── notebooks/
│   └── crack_classification.ipynb
│
├── assets/
│   ├── img1.jpg                # Positive example
│   └── img2.jpg                # Negative example
│
├── requirements.txt
└── README.md
</pre>

---

## 🧪 Sample Predictions

| Sample Image        | Model Prediction     |
|---------------------|----------------------|
| ![](assets/img1.jpg) | Crack Detected ✅     |
| ![](assets/img2.jpg) | No Crack ❌           |

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## ⚙️ Installation

git clone https://github.com/Nourhankarmm/crack-classification-cnn-vit.git
cd crack-classification-cnn-vit

---

## 🛠️ Tech Stack

Python
TensorFlow / PyTorch
Vision Transformers
OpenCV
Matplotlib, NumPy

---

## ⭐ Acknowledgements

HuggingFace Vision Transformer resources
