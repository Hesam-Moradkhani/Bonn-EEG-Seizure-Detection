# Bonn-EEG-Seizure-Detection
This project focuses on the classification of EEG signals for epileptic seizure detection using the Bonn University dataset. The pipeline includes signal preprocessing, feature extraction using Discrete Wavelet Transform (DWT), and classification using traditional machine learning models (SVM and Naive Bayes classifier)   

**Dataset**
Bonn University EEG dataset
Five subsets: A, B, C, D, E
Binary classification tasks:
- A vs E
- B vs E
- C vs E
- D vs E
- ABCD vs E


**Methodology**

1. **Data Preprocessing**
- Loading EEG signals from .txt files
- Labeling classes
- Organizing dataset for binary classification

 
2. **Feature Extraction**
Using Discrete Wavelet Transform (DWT):
- Mean
- Standard Deviation
- Energy
- Shannon Entropy

3. **Classification** 
- Support Vector Machine (SVM)
- Naive Bayes


4. **Prediction/ Evaluation** 
- Train/Test Split (80/20)
- 10-Fold Cross Validation


5. **Evaluation Metrics**
- Confusion Matrix
- Accuracy 


6. **Results**

**Train/Test Split (80/20)**
- Accuracy(A-E): 100.0 %
- Accuracy(B-E): 97.5 %
- Accuracy(C-E): 100.0 %
- Accuracy(D-E): 97.5 %
- Accuracy(ABCD-E): 95.0 %

**10-Fold Cross Validation**
- Accuracy(A-E): 100.0 %
- Accuracy(B-E): 99.5 %
- Accuracy(C-E): 98.5 %
- Accuracy(D-E): 90 %
- Accuracy(ABCD-E): 95.8 %
