# ♻️ EcoSort – Deep Learning-Based E-Waste Image Classifier

EcoSort is a deep learning-powered web application that classifies electronic waste (e-waste) images into various categories such as Battery, Mobile, Keyboard, and more. This tool leverages convolutional neural networks (CNNs) and image preprocessing to enable intelligent and sustainable e-waste management.

---

## 🌍 Purpose

To enhance sustainability by automating the classification of e-waste using AI-based image recognition, supporting recycling initiatives and efficient waste segregation systems.

---

## 🚀 Features

- 📸 Upload or drag-and-drop e-waste images  
- 🤖 Real-time classification using a pre-trained deep learning model  
- 🧠 Trained on diverse classes like: `Battery`, `Keyboard`, `Mobile`, `Printer`, etc.  
- 🌐 User-friendly Gradio web interface  
- 💻 Works locally or can be deployed on platforms like Hugging Face or Streamlit Cloud

---

## 🧠 Model Details

- **Architecture:** TensorFlow/Keras EfficientNet or Custom CNN  
- **Input Size:** 224x224  
- **Optimizer:** Adam  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Evaluation Metrics:** Accuracy  
- **Callbacks:** EarlyStopping for overfitting control

---

## 📁 Dataset

- The model is trained on a custom dataset consisting of labeled images from 10+ e-waste categories.
- Source: [Kaggle / Custom Collected]

---

## 💡 How to Use

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/EcoSort.git
   cd EcoSort

2. Create a virtual environment & install requirements

python -m venv venv
source venv/bin/activate        # For Linux/macOS
venv\Scripts\activate           # For Windows

3. Install required dependencies
pip install -r requirements.txt

