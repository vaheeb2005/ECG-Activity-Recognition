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
