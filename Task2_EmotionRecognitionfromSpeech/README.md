# 🎙️ Speech Emotion Recognition — CodeAlpha Machine Learning Internship (Task 2)

This project is part of the **CodeAlpha Machine Learning Internship**.  
The goal is to build a **Speech Emotion Recognition (SER)** model that classifies human emotions from voice recordings using deep learning techniques.

---

## 📁 Project Overview

The objective of this task is to **detect and classify emotions from speech audio** such as *Happy, Sad, Angry, Fearful, Disgust, Calm, Neutral,* and *Surprise*.  
The project involves **audio feature extraction (MFCCs)**, **data preprocessing**, **deep learning model training**, and **performance evaluation** using CNN and LSTM architectures.

---

## 🧠 Objectives

- Load and preprocess the TESS Speech Emotion Dataset  
- Extract audio features using **Mel-Frequency Cepstral Coefficients (MFCCs)**  
- Build and compare two models:
  - Convolutional Neural Network (**CNN**)
  - Long Short-Term Memory (**LSTM**)  
- Evaluate models on accuracy, confusion matrix, and classification report  
- Visualize training progress and emotion classification performance  

---

## 🧩 Dataset

**Dataset:** Toronto Emotional Speech Set (**TESS**)  
**Source:** [TESS Dataset — University of Toronto](https://tspace.library.utoronto.ca/handle/1807/24487)

**Structure:**
`TESS_Dataset/
│
├── Angry/
├── Disgust/
├── Fear/
├── Happy/
├── Neutral/
├── Pleasant_surprise/
└── Sad/`


Each folder contains multiple `.wav` files corresponding to that emotion.  

---

## ⚙️ Steps Performed

### 🪜 Step 1: Import Required Libraries
Installed and imported libraries:
```python
!pip install librosa soundfile tensorflow tqdm
-Used: librosa, numpy, pandas, matplotlib, tensorflow.keras, and sklearn.

## 📂 Step 2: Load & Extract Dataset
- Mounted Google Drive and extracted the TESS dataset:

**from google.colab import drive
drive.mount('/content/drive')**

## 📊 Visualizations

--Training vs Validation Accuracy graph

--Confusion Matrix heatmap

--Classification report (Precision, Recall, F1-score)

## 🧰 Technologies Used

--Python 3.10+

--Google Colab

--TensorFlow / Keras

--Librosa / SoundFile

--NumPy / Pandas / Matplotlib / Seaborn

--Scikit-learn


## 📜 Author

**👩‍💻 Khansa Urooj**  
CodeAlpha — Machine Learning Internship (Task 2: Emotion Recognition from speech)  
🔗 [GitHub Repository](https://github.com/khansaurooj/CodeAlpha_ML_Internship)

---


## 🧩 Next Steps (Future Work)

-- Add data augmentation for better generalization.

-- Deploy model as a real-time web app using Streamlit or Flask.

-- Experiment with pretrained audio embeddings (e.g., Wav2Vec 2.0).

-- Integrate with emotion-aware chatbots or call center systems.
