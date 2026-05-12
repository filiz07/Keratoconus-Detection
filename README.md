# Keratoconus Detection

This project focuses on detecting **Keratoconus**, a progressive eye disease, using deep learning techniques.

## 📌 Project Overview

Keratoconus causes thinning of the cornea, leading to distorted vision. Early detection is critical for treatment.
This project uses a deep learning model to classify corneal images and identify potential keratoconus cases.

---

## 🧠 Model

* Deep Learning model (PyTorch)
* Trained for image classification
* Tracks:

  * Training loss & accuracy
  * Validation loss & accuracy

---

## 📊 Training Results

* Final Training Accuracy: ~95%
* Validation Accuracy: ~74%
* Best model saved as: `best_model.pth`

---

## 📁 Project Structure

```
Keratoconus-Detection/
│── Keratoconus_detection.ipynb
│── best_model.pth
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```
git clone https://github.com/filiz07/Keratoconus-Detection.git
```

2. Install dependencies:

```
pip install torch torchvision matplotlib
```

3. Open the notebook:

```
Keratoconus_detection.ipynb
```

---

## 📦 Dataset

The dataset used in this project is available on Kaggle:

👉 https://www.kaggle.com/datasets/elmehdi12/keratoconus-detection

The dataset contains corneal eye images used for keratoconus classification tasks.

Please download the dataset from Kaggle and update the dataset path in the notebook before running the project.


---

## ⚠️ Note

This project is for educational purposes only and should not be used for medical diagnosis.

---

## 👤 Author

* GitHub: https://github.com/filiz07
