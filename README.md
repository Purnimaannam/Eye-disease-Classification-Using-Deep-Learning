# 🩺 Eye Disease Classification Using Deep Learning

A Django-based web application that detects eye diseases from retinal images using a deep learning model.  
This version focuses on **Cataract detection , Normal eye** **Glaucoma** , **Diabetic Retinopathy**.

---

## 📌 Features
- Upload retinal images directly from browser.
- Deep learning inference using TensorFlow/Keras model.
- Multi Class classification: **Normal Eye** / **Cataract Detected**.
- Displays confidence score alongside prediction.
- Web interface built with Django for easy interaction.


---

## 📖 Background
Eye diseases are a major cause of preventable blindness worldwide.  
Automated detection using deep learning can:
- Reduce diagnostic time.
- Assist ophthalmologists in preliminary screening.
- Increase access to healthcare in underserved areas.

This project implements a **Convolutional Neural Network (CNN)** to analyze retinal images and classify them into categories based on patterns learned from a labeled dataset.

---

## 🧠 Model Training
- **Framework:** TensorFlow/Keras
- **Dataset:** Preprocessed retinal images resized to **224x224**.
- **Preprocessing:** Normalization to [0,1] pixel range.
- **Architecture:** Custom CNN / Transfer Learning (e.g., MobileNet, EfficientNet).
- **Training Environment:** GPU-enabled Colab / Local machine.
- **Loss Function:** Binary Crossentropy.
- **Optimizer:** Adam.

---

## 🛠 Tech Stack
**Frontend:**
- HTML5 / CSS3
- Django Templates

**Backend:**
- Django (Python)
- TensorFlow/Keras for inference

**Deployment:**
- Render Web Service
- Gunicorn as production server

---


