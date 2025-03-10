# Infyma Hackathon - We3Bears   

Welcome to our project for the **Infyma Hackathon**! 🚀  
We are **Team We3Bears** – a passionate group of developers working on an AI-powered classification system.  

## 👥 Team Members  
- **Moawiz**  
- **Areeba**  
- **Sarim**  

---  

## 📌 Project Overview  
This project implements a **multi-model classification system** using deep learning techniques.  
We trained standalone models (**ViT**, **DenseNet201**) and an **ensemble model**, which provided superior performance in terms of **accuracy, precision, recall, and F1-score**.  

An interactive **Gradio** interface is included for easy inference and visualization of predictions along with **Grad-CAM interpretability**.  

---  

## 🚀 Installation & Setup  

### 1️⃣ Install Dependencies  
Make sure you have Python installed, then run:  

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Gradio Inference Demo  
Start the interactive inference tool with:  

```bash
python ./notebooks/app.py
```

This will launch a web-based UI where you can upload images and view classification results.  

---  

## 📊 Model Comparison  

| Model          | Accuracy  | F1 Score  | Precision  | Recall   | Inference Speed (ms) |
|---------------|:--------:|:--------:|:---------:|:-------:|:-------------------:|
| **ViT**       | 0.742    | 0.742    | 0.745     | 0.742   | 3900.0              |
| **DenseNet201** | 0.755   | 0.753    | 0.752     | 0.755   | **2500.0**         |
| **Ensemble**   | **0.828** | **0.829** | **0.83**  | **0.828** | 2900.0 |

✅ **The ensemble model achieved the best accuracy, precision, recall, and F1-score.**  
✅ **DenseNet201 had the fastest inference speed.**  

---  

## 📌 Features  
✔️ **Multi-model classification** (ViT, DenseNet201, and an ensemble model)  
✔️ **Real-time inference using Gradio**  
✔️ **Grad-CAM visualization for explainability**  
✔️ **Hyperparameter tuning for optimal performance**  
✔️ **Early stopping, dropout, and batch normalization**  

---  

## 📜 Conclusion  
Our **ensemble model** provided the best overall performance, while **DenseNet201 was the fastest in inference**.  
This project showcases the power of combining multiple deep-learning models for improved accuracy and robustness.  
