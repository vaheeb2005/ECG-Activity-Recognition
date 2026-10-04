# Analyzing ECG Signal with Different State of Human Activity

## 📌 Internship Project

This project focuses on analyzing Electrocardiogram (ECG) signals and identifying different states of human physical activity using ECG signal processing and Machine Learning techniques.

The system classifies ECG signals into three activity states:

- 🧘 Rest
- 🚶 Walking
- 🏃 Running

---

## 👨‍🎓 Student Details

**Name:** Sadiq Vaheeb Shaik  
**Roll Number:** 23691A32C4  
**Branch:** Computer Science and Engineering (Data Science)  
**College:** Madanapalle Institute of Technology & Science  
**Academic Year:** 2025–2026

---

## 🎯 Project Objective

The main objective of this project is to analyze ECG signals and extract meaningful physiological features that can be used to identify a person's physical activity state.

The project demonstrates how heart rate, RR intervals, R-peaks and other ECG characteristics can be used with Machine Learning algorithms for activity classification.

---

## 🧠 Methodology

The project follows the following pipeline:

```text
ECG Signal
     ↓
Data Acquisition
     ↓
Signal Preprocessing
     ↓
ECG Filtering
     ↓
R-Peak Detection
     ↓
Feature Extraction
     ↓
Feature Dataset
     ↓
Train/Test Split
     ↓
Machine Learning
     ↓
Model Evaluation
     ↓
Activity Prediction
```

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- SciPy
- Matplotlib
- Scikit-learn
- NeuroKit2
- BioSPPy

---

## 📊 Activities Classified

| Activity | Description |
|---|---|
| Rest | ECG characteristics during a resting state |
| Walking | ECG characteristics during walking |
| Running | ECG characteristics during running |

---

## 🔬 ECG Features Extracted

The following features are extracted from the ECG signals:

- Mean Heart Rate
- Standard Deviation of Heart Rate
- Mean RR Interval
- Standard Deviation of RR Interval
- R-Peak Count
- Signal Mean
- Signal Standard Deviation
- Signal Minimum
- Signal Maximum

---

## 🤖 Machine Learning Models

Three Machine Learning algorithms were implemented and compared:

### 1. Logistic Regression

Used as a baseline classification algorithm.

### 2. Decision Tree

Used to classify activity states based on extracted ECG features.

### 3. Random Forest

Used as the final classification model because of its ability to handle multiple features and provide feature importance.

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The model performance was compared to identify the most suitable classifier for ECG activity recognition.

---

## 📁 Project Structure

```text
ECG-Activity-Recognition/
│
├── ECG_Activity_Recognition_Sadiq_Vaheeb.ipynb
│
├── ECG_Activity_Feature_Dataset.csv
│
├── README.md
│
└── screenshots/
    ├── 01_ecg_generation.png
    ├── 02_raw_ecg.png
    ├── 03_preprocessed_ecg.png
    ├── 04_rpeak_detection.png
    ├── 05_feature_dataset.png
    ├── 06_model_comparison.png
    ├── 07_classification_report.png
    ├── 08_confusion_matrix.png
    └── 09_final_prediction.png
```

---

## 💻 How to Run the Project

### Step 1 — Open Google Colab

Open the project notebook in Google Colab.

### Step 2 — Install Required Libraries

Run:

```python
!pip install neurokit2 biosppy heartpy
```

### Step 3 — Import Libraries

Run the library import cells provided in the notebook.

### Step 4 — Generate ECG Signals

The project generates ECG signals representing:

- Rest
- Walking
- Running

### Step 5 — Preprocess ECG

The ECG signals are cleaned using ECG signal-processing techniques.

### Step 6 — Extract Features

Important ECG characteristics such as heart rate, RR intervals and R-peaks are extracted.

### Step 7 — Train Machine Learning Models

The extracted features are used to train:

- Logistic Regression
- Decision Tree
- Random Forest

### Step 8 — Evaluate Models

The models are evaluated using accuracy, classification reports and a confusion matrix.

### Step 9 — Predict Activity

A test ECG signal is provided to the trained model to predict the corresponding activity state.

---

## 📷 Project Screenshots

The `screenshots` folder contains evidence of the project implementation and results, including:

- ECG signal generation
- Raw ECG visualization
- ECG preprocessing
- R-peak detection
- Feature extraction
- Machine Learning model comparison
- Classification report
- Confusion matrix
- Final activity prediction

---

## 📌 Results

The developed system demonstrates that ECG signals contain useful patterns for distinguishing different physical activity states.

The extracted ECG features are used to train Machine Learning models capable of classifying:

```text
Rest
  ↓
Walk
  ↓
Run
```

The final Random Forest model is used for activity prediction.

---

## 🚀 Future Scope

The project can be further improved by:

- Using real-world ECG datasets
- Collecting ECG signals from wearable devices
- Adding more physical activities
- Implementing Deep Learning models such as 1D CNN
- Developing real-time ECG activity recognition
- Integrating the model with wearable health-monitoring systems
- Deploying the system as a web or mobile application

---

## 📚 Conclusion

This project demonstrates an end-to-end ECG signal processing and Machine Learning pipeline for recognizing different physical activity states.

The system performs ECG preprocessing, R-peak detection, feature extraction, Machine Learning model training and activity prediction.

The project provides a foundation for future healthcare, fitness-monitoring and wearable-device applications.

---

## 👨‍💻 Author

**Sadiq Vaheeb Shaik**  
B.Tech — Computer Science and Engineering (Data Science)  
Madanapalle Institute of Technology & Science

---

## ⭐ Project Status

**Completed — Internship Project**
