# MNIST Digit Classification using Bidirectional LSTM

## 📌 Overview
This project applies a Bidirectional LSTM to classify handwritten digits from the MNIST dataset, demonstrating how RNNs can process sequential pixel data for image recognition.

## 📂 Dataset
- **Name**: MNIST  
- **Size**: 70,000 grayscale images (28×28 pixels)  
- **Classes**: 10 digits (0–9)  
- **Split**: 60,000 training + 10,000 test images  

## ⚙️ Tech Stack
- **Language**: Python  
- **Libraries**: TensorFlow/Keras, NumPy, Matplotlib  

## 🚀 Project Workflow
1. Load and preprocess MNIST dataset  
2. Build Bidirectional LSTM model  
3. Train with Adam optimizer  
4. Plot accuracy and loss curves  
5. Evaluate on test data  

## 📊 Results
- Training vs validation accuracy/loss plots  
- Final test accuracy reported  

## 🛠️ Installation & Usage
```bash
git clone <repo-url>
cd <repo-name>
pip install -r requirements.txt
python main.py
