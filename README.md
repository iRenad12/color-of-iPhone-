# color-of-iPhone-
Identifying the color of the iPhone 
iPhone 14 Color Recognition using Teachable Machine & Google Colab

This project uses a machine learning model trained with Google's Teachable Machine to recognize the color of an iPhone 14. The model was exported and used in a Google Colab notebook.

🧠 Project Overview
The goal of this project is to automatically detect whether an iPhone 14 shown to the camera is Purple or White (Starlight) using a custom-trained image classification model.


🛠 Tools & Technologies
Teachable Machine – For training the image classification model
Google Colab – For testing and running the model in Python
TensorFlow / Keras – For loading and running the model
OpenCV – For image input and display
Webcam or Uploaded Images – To input images of the iPhone.


🧪 How It Works
A dataset was created with images of iPhone 14 in Purple and White.
The model was trained using Teachable Machine's Image Project.
The trained model was exported and integrated into a Google Colab notebook.
The notebook processes images from a webcam or file upload and predicts the iPhone's color.


▶️ Usage
Open the iPhone14_Color_Recognition.ipynb notebook in Google Colab.
Upload or capture an image of the iPhone 14.
The model will predict the color: Purple or White.
📁 Project Files
iPhone14_Color_Recognition.ipynb – Google Colab notebook for running predictions
model/ – Exported model files from Teachable Machine
sample_images/ – Optional folder for test images
