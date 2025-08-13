# 🩺 Eye Disease Classification Using Deep Learning

A Django-based web application that analyzes retinal images and detects common eye diseases using a deep learning model trained on ophthalmic datasets.
The system classifies uploaded images into four categories:

Cataract 👁️ – Clouding of the eye’s natural lens leading to blurry vision.

Normal Eye ✅ – Healthy retina without signs of disease.

Glaucoma 🌀 – Damage to the optic nerve often caused by high eye pressure.

Diabetic Retinopathy 🩸 – Retina damage caused by complications of diabetes.

The application leverages a Convolutional Neural Network (CNN) to process and classify the images with high accuracy. Users can upload retinal images through the web interface, and the model instantly provides predictions along with confidence scores.

This system aims to:

Assist ophthalmologists in quick screening and diagnosis.
Enable early detection to prevent irreversible vision loss.

Provide accessible eye health check-ups even in remote areas.
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
**Demo:**
[![Watch the video](https://github.com/Purnimaannam/Eye-disease-Classification-Using-Deep-Learning/blob/main/Screen%20Recording%202025-08-11%20150838.mp4)


