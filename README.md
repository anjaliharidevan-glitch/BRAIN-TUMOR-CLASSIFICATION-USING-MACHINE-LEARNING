# 🧠 Brain Tumor MRI Classification Using Machine Learning

## 📌 Project Overview

This project focuses on classifying brain MRI images into four categories using Deep Learning and Convolutional Neural Networks (CNN). The model analyzes MRI images and predicts whether the image belongs to one of the following classes: **Glioma, Meningioma, Pituitary Tumor, or No Tumor**.

The project aims to demonstrate how machine learning techniques can be applied to medical image classification to support research in healthcare and medical image analysis.

## 🎯 Objectives

- Develop a deep learning model to classify brain MRI images.
- Preprocess and analyze MRI images for model training.
- Evaluate the model using performance metrics.
- Build a user-friendly web application for image upload and prediction.
- Demonstrate the potential application of AI in medical image analysis.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow, Keras
- **Image Processing:** OpenCV
- **Data Analysis:** NumPy, Pandas
- **Model Architecture:** Convolutional Neural Network (CNN)
- **Web Application:** Streamlit
- **Deployment / Public Access:** ngrok
- **Development Environment:** Google Colab

## 📂 Dataset

The dataset contains brain MRI images organized into four classes:

1. Glioma
2. Meningioma
3. Pituitary Tumor
4. No Tumor

The images are resized to **128 × 128 pixels** and normalized before being passed to the model.

## ⚙️ Project Workflow

1. **Data Collection:** Load the brain MRI image dataset.
2. **Data Preprocessing:** Resize images and normalize pixel values.
3. **Dataset Preparation:** Assign class labels and prepare training and testing data.
4. **Model Building:** Develop a CNN model for image classification.
5. **Model Training:** Train the model using labeled MRI images.
6. **Model Evaluation:** Evaluate performance using accuracy, precision, recall, F1-score, and a confusion matrix.
7. **Web Application:** Develop a Streamlit interface for uploading MRI images and displaying predictions.
8. **Deployment:** Use ngrok to make the application accessible through a public URL during the deployment session.

## 📊 Model Performance

The model achieved approximately **94% classification accuracy** on the evaluated test dataset in an earlier experiment.

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

*Note: Performance may vary depending on the dataset split, model configuration, and training process.*

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the Project Folder

```bash
cd YOUR-REPOSITORY
```

### 3. Install Dependencies

```bash
pip install tensorflow opencv-python numpy pandas streamlit
```

Install any additional libraries required by your notebook or application.

### 4. Run the Application

If your Streamlit application file is named `app.py`, run:

```bash
streamlit run app.py
```

If the project is provided as a Google Colab notebook, open the notebook in Google Colab and execute the cells in the required order.

## 📁 Suggested Repository Structure

```text
Brain-Tumor-MRI-Classification/
│
├── app.py
├── brain_tumor_classification.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
    └── prediction_demo.png
```

*Adjust the file names and folder structure to match your actual repository. Include a trained model file if your application requires it and the file is suitable for GitHub storage.*

## 💡 Key Features

- Multi-class classification of brain MRI images.
- Automated image preprocessing.
- CNN-based deep learning model.
- Performance evaluation using standard classification metrics.
- Interactive Streamlit application.
- MRI image upload and prediction display.

## 🔮 Future Enhancements

- Improve model generalization using data augmentation and hyperparameter tuning.
- Experiment with transfer learning architectures.
- Enhance
