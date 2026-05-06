# Automated EEG Signal-Based Sleep State Classification and Analysis

This project presents an automated approach for sleep stage classification using electroencephalogram (EEG) signals from the PhysioNet Sleep-EDF Expanded dataset.

---

## Authors
- **Christian Bammann** – Contributor of all data preprocessing, SVM/RF/CNN model development, experimentation, evalutation, and report/presentation preparation.

---

## Contents

| File                                                                                     | Description                                                 |
|------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| `figures`                                                                                | Folder containing visualization figures                      |
| `outputs`                                                                                | Folder containing metrics and plots for each model                            |
| `training`                                                                               | Folder containing all Python training notebooks                                |
| `report.pdf`                 | IEEE-style Report                                              |
| `README.md`                                                                              | Project Overview                                             |
| `requirements.txt`                                                                       | List of required dependencies                                            |

---

## Table I:  Overall Model Performance Comparison

| Model                               | Accuracy    | Balanced Accuracy   | Macro F1-Score                    | 
|-------------------------------------|-----------------------------|-----------------------------|-----------------------------|
| SVM              | 86.9%                      | 79.6%                      | 72.1%                       |
| RF       | 92.2%                       | 72.0%                       | 74.4%                       |
| 1D-CNN   | 93.0%                      | 83.3%                      | 79.9%                       |

---

## Table II:  Per-Class F1 Performance Comparison

| Model                               | Accuracy    | Balanced Accuracy   | Macro F1-Score                    | 
|-------------------------------------|-----------------------------|-----------------------------|-----------------------------|
| SVM              | 86.9%                      | 79.6%                      | 72.1%                       |
| RF       | 92.2%                       | 72.0%                       | 74.4%                       |
| 1D-CNN   | 93.0%                      | 83.3%                      | 79.9%                       |
