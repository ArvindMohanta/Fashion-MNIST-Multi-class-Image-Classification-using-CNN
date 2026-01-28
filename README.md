# Fashion-MNIST Multi-class Image Classification using CNN

This project implements **multi-class image classification** on the **Fashion-MNIST dataset** using a **Convolutional Neural Network (CNN)** in TensorFlow/Keras.  
Model performance is evaluated using a **confusion matrix**.

---

## 📌 Dataset
**Fashion-MNIST** is a dataset of grayscale clothing images, commonly used as a replacement for MNIST digits.

- Total images: 70,000
- Image size: 28 × 28
- Classes: 10
- Download size: ~30 MB
- Source: TensorFlow built-in dataset

### Class Labels
| Label | Class |
|------|------|
| 0 | T-shirt / Top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

---

## 🧠 Model Architecture
- Convolutional Layers (ReLU)
- Max Pooling
- Fully Connected Dense Layers
- Softmax Output Layer (10 classes)

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Evaluation
- Accuracy
- Multi-class Confusion Matrix (10 × 10)

The confusion matrix helps visualize correct and incorrect predictions across all classes.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Fashion-MNIST-Multiclass-Classification.git
