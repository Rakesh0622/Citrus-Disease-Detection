# 🍃 Citrus Leaf Disease Detection Using Deep Learning

## 📌 Project Overview

Citrus Leaf Disease Detection is a deep learning-based application designed to automatically identify and classify diseases in citrus leaves using image processing and Convolutional Neural Networks (CNN).

The system analyzes uploaded leaf images and predicts whether the leaf is affected by **Black Spot, Canker, Greening, or is Healthy**. It aims to support early disease identification, reduce manual inspection efforts, and help improve agricultural productivity.

## 🎯 Objectives

- Automate the detection of citrus leaf diseases using deep learning.
- Classify citrus leaves into multiple disease categories.
- Provide accurate and efficient disease predictions from leaf images.
- Support early identification to minimize potential crop losses.

## 🔍 Disease Categories

The model identifies the following four classes:

| Disease | Description |
|---|---|
| Black Spot | Fungal disease causing dark spots on citrus leaves and fruits. |
| Canker | Bacterial disease characterized by raised, brown lesions. |
| Greening | Disease associated with yellowing and irregular leaf discoloration. |
| Healthy | Citrus leaves without visible disease symptoms. |

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **Model Architecture:** Convolutional Neural Network (CNN)
- **Image Processing:** Image resizing and normalization
- **Data Augmentation:** Image transformations for improved model generalization
- **Backend:** Flask
- **Frontend:** HTML, CSS
- **Development Environment:** Jupyter Notebook / Python IDE

## ⚙️ Project Workflow

1. **Dataset Collection:** Collect citrus leaf images belonging to different disease categories.
2. **Image Preprocessing:** Resize and normalize images to prepare them for model training.
3. **Data Augmentation:** Apply transformations to improve dataset diversity.
4. **Model Training:** Train a CNN model to learn disease-specific visual patterns.
5. **Model Evaluation:** Evaluate performance using accuracy, loss, and confusion matrix.
6. **Disease Prediction:** Upload a citrus leaf image through the Flask web application to obtain the predicted class.

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/polaternez/citrus-diseases-detection.git
```

### 2. Navigate to the Project Directory

```bash
cd citrus-diseases-detection
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment:

**Windows:**
```bash
.venv\Scripts\activate
```

**Linux / macOS:**
```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install tensorflow flask numpy pillow matplotlib scikit-learn
```

If a `requirements.txt` file is available, install dependencies using:

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

Open your browser and navigate to:

```text
http://127.0.0.1:5000/
```

Upload a citrus leaf image to view the predicted disease category.

## 📊 Model Evaluation

The CNN model is evaluated using:

- Training and validation accuracy.
- Training and validation loss.
- Confusion matrix.
- Classification performance across all four categories.

These metrics help assess the model's ability to distinguish between different citrus leaf conditions.

## 🌱 Applications

- Early identification of citrus leaf diseases.
- Agricultural disease monitoring.
- Smart farming and precision agriculture.
- Supporting farmers in making timely crop-management decisions.

## 🔮 Future Enhancements

- Deploy the application on a cloud platform.
- Improve prediction accuracy using advanced deep learning architectures.
- Develop a mobile-friendly interface.
- Extend the model to support additional citrus diseases.
- Optimize the model for faster predictions on resource-constrained devices.

## 👨‍💻 Contributors

Developed as an academic project by:

- Shreya S
- Rakesh K N
- Preethi H K
- Shaan S
- Divya H T

**Department of Information Science and Engineering**  
Malnad College of Engineering, Hassan, Karnataka.

## 📄 License

This project is intended for educational and research purposes.
