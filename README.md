# Eye-disease-Classification-Using-Deep-Learning
👁️ Eye Disease Classification Using Deep Learning
This project is a complete deep learning-based web application built using Django and TensorFlow (MobileNetV2) that predicts common eye diseases from retinal fundus images.
The system identifies four classes of eye conditions:
Cataract
Diabetic Retinopathy
Glaucoma
Normal

It also offers medical advice such as precautionary measures, treatment suggestions, and recommended hospitals based on the prediction.

🧠 Project Objective
Early detection of eye diseases can prevent vision loss. This project aims to:

Develop a lightweight and accurate eye disease classifier using transfer learning.

Build a user-friendly web interface for easy image upload and diagnosis.

Provide actionable medical insights to patients for follow-up.

📸 Example Prediction Output
After uploading a fundus image, the app will display:

✅ Detected Disease
🎯 Confidence Score (e.g., 96.45%)
⚠️ Warning if model confidence is low
🏥 Hospital Recommendations
🥗 Precautionary Advice
💊 Suggested Treatments
🧱 Technologies Used
Layer	Tools / Libraries
Frontend	Django Templates, HTML, CSS
Backend	Django (Python), Gunicorn
Deep Learning	TensorFlow 2.19.0, Keras, MobileNetV2
Image Processing	Pillow, OpenCV
Visualization	Matplotlib
Deployment	Docker + Render Cloud Platform
                     # Model training script using MobileNetV2
