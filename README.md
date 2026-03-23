# Brain Tumor Detection using CNN

## 📌 Project Overview
This project implements a Deep Learning model using Convolutional Neural Networks (CNN) to classify brain MRI images into two categories:
- Healthy
- Tumor

The model is trained using image data and evaluated using validation data.  
The trained model can also predict new unseen images.

This project demonstrates the use of Deep Learning in medical image classification.

## 🎯 Objective
- Build a CNN model for image classification
- Detect brain tumor from MRI images
- Evaluate model performance
- Predict new unseen images
- Save trained model for reuse

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL
- ImageDataGenerator


## 📂 Dataset
The dataset contains brain MRI images divided into two classes:
- Normal
- Tumor

Images are loaded using `flow_from_directory` and preprocessed using `ImageDataGenerator`.



## ⚙️ Model Architecture
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Sigmoid activation (Binary classification)

Input size: 128 × 128 × 3


## 🚀 Training
The model was trained using CNN with validation split.

Example output:

Validation Accuracy ≈ 94%


## 📊 Results
- Validation Accuracy: ~94%
- Model successfully predicts new unseen images
- Good performance on classification task


## 📈 Conclusion
A CNN-based deep learning model was successfully developed for brain tumor detection.

The model achieved high validation accuracy and was able to correctly classify new images.  
This project shows how deep learning can be used for medical image analysis.


## 🔮 Future Work
- Use larger dataset
- Apply Transfer Learning (VGG16, ResNet)
- Build web app using Flask / Streamlit
- Deploy model



## 👨‍💻 Author
Your Name
