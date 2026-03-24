# 🌌 Galaxy Classifier using Deep Learning

## 📌 Overview

This project builds a **deep learning model** to classify galaxy images into different categories such as:

* Smooth
* Spiral
* Edge-on
* Irregular

It uses **Transfer Learning with MobileNetV2** to achieve efficient and accurate image classification.

---

## 🚀 Features

* Image classification using CNN
* Transfer learning with MobileNetV2
* Data preprocessing and augmentation
* Model evaluation (accuracy, confusion matrix)
* Grad-CAM visualization for model explainability
* Predict on custom galaxy images

---

## 🧠 Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas
* Matplotlib

---

## 📂 Project Structure

```
Galaxy-Classifier/
│
├── Galaxy_Classifier_2.ipynb   # Main notebook
├── galaxy_model_v1_final.h5    # Trained model
├── .gitignore
└── README.md
```

---

## ⚙️ How to Run

### 1. Clone the repository

```
git clone https://github.com/Varunsuryateja-cmd/Galaxy-Classifier.git
cd Galaxy-Classifier
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the notebook

Open:

```
Galaxy_Classifier_2.ipynb
```

---

## 📊 Model Details

* Model: MobileNetV2 (Transfer Learning)
* Input Size: 128x128
* Output: 4 Classes
* Activation: Softmax

---

## 🔍 Sample Prediction

The model predicts galaxy type with probabilities and can visualize attention using Grad-CAM.

---

## 📸 Results

* Achieves good classification accuracy on validation data
* Provides visual explanation of predictions

---

## 📌 Future Improvements

* Improve accuracy with more data
* Hyperparameter tuning
* Deploy as a web app
* Add real-time prediction interface

---

## 🤝 Contribution

Contributions are welcome. Feel free to fork and improve.

---

## 📜 License

This project is for educational purposes.
