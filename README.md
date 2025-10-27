# 🩺 Diabetic Retinopathy Detection using Deep Learning

Welcome to the **Diabetic Retinopathy Detection** project!  
This repository presents a deep learning–based system that automatically classifies the **severity level of diabetic retinopathy** from retinal fundus images — enabling early detection and assisting ophthalmologists in diagnosis.

---

## 📂 Project Structure

### 🔍 1. **Image Preprocessing Module**
- Handles noise removal and contrast improvement.
- Steps include:
  - 🟢 **Green channel extraction**
  - ✨ **Contrast Limited Adaptive Histogram Equalization (CLAHE)**
  - ⚙️ **Image resizing and normalization**
- Enhances lesion visibility (microaneurysms, hemorrhages).

---

### 🧠 2. **Deep Learning Classifier**
- Based on **Convolutional Neural Networks (CNN)** and **EfficientNet-B0**.
- Trained on the **APTOS 2019 / Kaggle DR dataset**.
- Classifies fundus images into 5 stages:
   **0** — No DR  
   **1** — Mild  
   **2** — Moderate  
   **3** — Severe  
   **4** — Proliferative DR  

---

### 📊 3. **Evaluation & Visualization**
- Performance metrics:
   ✅ Accuracy  
   ✅ Precision, Recall, F1-Score  
   ✅ Confusion Matrix  
   ✅ ROC Curves  
- Grad-CAM visualization used to highlight disease-affected retinal regions.



## 🚀 Features

✅ Automated diabetic retinopathy grading  
✅ Enhanced image preprocessing for clarity  
✅ Explainable predictions using Grad-CAM  
✅ CNN & EfficientNet hybrid deep model  
✅ Intuitive Gradio-based web interface  

---

## 🛠️ How to Run

### 🔧 Installation

```bash
git clone https://github.com/yourusername/Diabetic_Retinopathy_Detection.git
cd Diabetic_Retinopathy_Detection
pip install -r requirements.txt
