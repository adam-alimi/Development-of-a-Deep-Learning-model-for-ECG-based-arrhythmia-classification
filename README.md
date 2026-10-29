# 🫀 ECG-Based Arrhythmia Classification with Deep Learning

## 📌 Overview
This project focuses on developing a **deep learning model** for classifying cardiac arrhythmias from ECG (electrocardiogram) signals.  
It combines **CNNs, Transformer encoders, and Wavelet transforms** to capture both spatial and temporal features of ECG signals.  
Goal: Support early detection of arrhythmias and assist doctors in decision-making.

---

## 📊 Dataset
- **Source**: MIT-BIH Arrhythmia Dataset (109,000+ samples)  
- **Classes**: 5 arrhythmia types  
- **Preprocessing**: Continuous Wavelet Transform (CWT), normalization, data augmentation, SMOTE  

---

## 🏗️ Model Architecture
- **Dual-branch architecture**:  
  - CNN layers → feature extraction  
  - Transformer encoders → sequential/temporal patterns  
- **Optimization**: Mixed precision training (AMP), early stopping, cross-validation
  
---

## 📈 Results
- **Accuracy**: 99.26%  
- **F1-score**: 90.25%  
- **Minority Class Recall**: +20% (via SMOTE + augmentation)  

📉 Performance visualization:  
- Confusion matrix  
- ROC curves  

---

## 🛠️ Technology Stack
- **AI/ML**: PyTorch, scikit-learn  
- **Deployment**: Flask/Flutter integration for demo app  
- **Tools**: Jupyter, Google Colab  

---

## 📚 Academic Contribution
- Demonstrated potential of **dual-branch deep learning** for medical signals.  
- Showcased integration of AI in **real-world healthcare contexts**.  

---

## 📄 License
MIT License – free for research and academic use.  

Developed by **Adam Alimi (INSAT, Tunisia)**.  

## 🙋‍♂️ About Me

I’m a computer engineering student at INSAT, passionate about deep learning, LLMs, and building AI-powered solutions. I focus on deploying intelligent models in real-world apps using Flutter and Firebase.

- 🔗 [LinkedIn](https://www.linkedin.com/in/adam-alimi/)
- 💻 [GitHub](https://github.com/adam-alimi)

