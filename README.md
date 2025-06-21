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
- Source: [https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset]

---

## 💡 How to Use

```bash
# 1. Clone the repository
git clone https://github.com/your-username/EcoSort.git
cd EcoSort

# 2. Create a virtual environment and activate it
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# 3. Install the required dependencies
pip install -r requirements.txt

# 4. Add your trained model (e.g., model.h5) to the root directory
# Ensure the model path is correctly referenced in the code (app.py)

# 5. Run the application
python app.py
```

> 🌐 Visit `http://localhost:7860` in your browser to use the classifier.


🖼️ Sample UI
![image alt](https://github.com/RosheniSR/EcoSort/blob/8839923e64ff625f03fd38bde63e1987f740f1ea/Screenshot%202025-06-21%20160715.png)

📄 License

This project is open-source under the MIT License.


👨‍💻 Author

Rosheni S.R

Email: rosheniramesh@gmail.com

GitHub: @RosheniSR





