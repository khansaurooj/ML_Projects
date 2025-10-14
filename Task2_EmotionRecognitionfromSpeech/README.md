# 🎙️ Speech Emotion Recognition (SER) — CodeAlpha Machine Learning Internship (Task 2)

This repository contains the implementation for **Task 2** of the [CodeAlpha Machine Learning Internship](https://github.com/khansaurooj/CodeAlpha_ML_Internship).  
The objective is to build a robust **Speech Emotion Recognition (SER)** system capable of classifying human emotions from voice recordings using state-of-the-art deep learning architectures.

---

## 📁 Project Overview

The aim of this project is to **detect and classify emotions** in speech audio, specifically: *Angry, Disgust, Fear, Happy, Neutral, Pleasant Surprise,* and *Sad*.  
Key components include:

- **Audio Feature Extraction:** Leveraging Mel-Frequency Cepstral Coefficients (**MFCCs**)  
- **Data Preprocessing:** Cleaning and transforming raw audio data  
- **Model Training:** Building and comparing Convolutional Neural Networks (**CNN**) and Long Short-Term Memory (**LSTM**) models  
- **Evaluation & Visualization:** Assessing model performance using accuracy metrics, confusion matrices, and classification reports

---

## 🧠 Objectives

- Load and preprocess the TESS Speech Emotion Dataset
- Extract audio features using **MFCCs**
- Implement and compare two deep learning models:
  - **Convolutional Neural Network (CNN)**
  - **Long Short-Term Memory (LSTM)**
- Evaluate models using:
  - Accuracy scores
  - Confusion matrix analysis
  - Classification reports (Precision, Recall, F1-score)
- Visualize training process and classification outcomes

---

## 🧩 Dataset

**Dataset:** [Toronto Emotional Speech Set (TESS)](https://tspace.library.utoronto.ca/handle/1807/24487)  
**Structure:**
```
TESS_Dataset/
│
├── Angry/
├── Disgust/
├── Fear/
├── Happy/
├── Neutral/
├── Pleasant_surprise/
└── Sad/
```
Each subdirectory contains `.wav` files labeled by emotion.

---

## ⚙️ Steps Performed

### 1. Import Required Libraries
- Installed: `librosa`, `soundfile`, `tensorflow`, `tqdm`
- Used: `librosa`, `numpy`, `pandas`, `matplotlib`, `tensorflow.keras`, `sklearn`

### 2. Load & Extract Dataset
- Mounted Google Drive for dataset access
- Loaded and parsed audio samples

### 3. Feature Engineering
- Extracted **MFCC** features from audio clips

### 4. Model Development
- Built and trained both **CNN** and **LSTM** architectures
- Compared performances

### 5. Model Evaluation & Visualization
- Plotted training vs. validation accuracy
- Generated confusion matrix heatmaps
- Produced detailed classification reports

---

## 📊 Visualizations

- **Training vs Validation Accuracy**: Tracking model learning progress
- **Confusion Matrix**: Visualizing prediction accuracy for each emotion
- **Classification Report**: Presenting metrics like Precision, Recall, and F1-score per class

---

## 🧰 Technologies Used

- **Python 3.10+**
- **Google Colab**
- **TensorFlow / Keras**
- **Librosa / SoundFile**
- **NumPy / Pandas / Matplotlib / Seaborn**
- **Scikit-learn**

---

## 👩‍💻 Author

**Khansa Urooj**  
CodeAlpha — Machine Learning Internship (Task 2: Speech Emotion Recognition)  
🔗 [GitHub Repository](https://github.com/khansaurooj/CodeAlpha_ML_Internship)

---

## 🚀 Future Work

- Integrate **data augmentation** techniques to improve model generalization
- **Deploy** as a real-time web application using Streamlit or Flask
- Experiment with **pretrained audio embeddings** (e.g., Wav2Vec 2.0)
- Extend to **emotion-aware chatbots** or call center systems

---

> For questions or suggestions, please open an issue or contact the author via GitHub.
