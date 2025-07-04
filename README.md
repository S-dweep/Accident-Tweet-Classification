# 🚦 A Hybrid CNN-LSTM Approach for Accident Tweet Classification

This repository contains the Official Documentation File (ODF) and supporting materials for our research paper titled:

**"A Hybrid CNN - LSTM Approach for Accident Tweet Classification"**,  
**Published in:** *International Research Journal of Multidisciplinary Studies (IRJMS)*

## 📄 Overview

With the explosion of real-time information on Twitter, this study leverages the power of deep learning to detect and classify accident-related tweets. We propose a **hybrid CNN-LSTM model** capable of capturing both local textual patterns and long-term sequential dependencies. Our approach surpasses traditional NLP models in accuracy and reliability for this classification task.


## 🎯 Objectives

- To classify tweets into:
  - 🚨 Traffic Accident Tweet (`1`)
  - 🚗 Traffic Information Tweet (`2`)
  - 🚫 Non-Traffic Tweet (`0`)
- To build a hybrid deep learning model optimized for short, noisy social media text.
- To compare performance against classical ML models: Logistic Regression, Naive Bayes, SVM, and Random Forest.


## 📊 Results

We evaluated the performance of our model against standard NLP classifiers. Below is a snapshot of how models compared:

| Model              | Accuracy | Precision | Recall | F1 Score | Loss  |
|-------------------|----------|-----------|--------|----------|-------|
| **CNN-LSTM (Hybrid)** | **97%**   | **98%**     | **96%**  | **96%**    | 0.23  |
| Logistic Regression | 97%      | 97%        | 96%     | 96%       | 0.18  |
| SVM               | 97%      | 97%        | 96%     | 97%       | 0.66  |
| Random Forest     | 95%      | 96%        | 94%     | 95%       | 0.17  |
| Naive Bayes       | 88%      | 89%        | 77%     | 78%       | 0.27  |

### 🔍 Confusion Matrix Highlights

- **CNN-LSTM** correctly predicted most **non-traffic tweets (Class 0)**.
- Minor confusion between accident vs. traffic info tweets (Class 1 vs. 2).
- Naive Bayes and RF models struggled with nuanced tweet semantics.

### 🔎 Real Examples

| Tweet                                                                 | Classification         |
|-----------------------------------------------------------------------|-------------------------|
| "Minor injuries reported after crash at Gayosa Street."              | 🚨 Traffic Accident (1) |
| "UPDATE: Rt. 33 reopened near Commerce Circle. Detour lifted."       | 🚗 Traffic Info (2)     |
| "I no longer have the energy for meaningless friendships."           | 🚫 Non-Traffic (0)      |

---

## 📂 Repository Contents

- `A Hybrid CNN - LSTM Approach for Accident Tweet Classification` — Published IRJMS paper.
- `Code/cnn_lstm.ipynb` — Model training code.
- `Code/stat_model.ipynb` — Model training code.
- `data/` — Cleaned and labeled tweet dataset.
- `README.md` — This documentation file.

---

## 📄 Read the Full Paper

[👉 Download "A Hybrid CNN-LSTM Approach for Accident Tweet Classification"](./A%20Hybrid%20CNN%20-%20LSTM%20Approach%20for%20Accident%20Tweet%20Classification.pdf)



## 🤝 Acknowledgements

Thanks to Narula Institute of Technology for their support and to the open-source community for enabling impactful research.

## ⚠️ Disclaimer

This project is for academic purposes only. All tweet content is anonymized and handled ethically, in compliance with Twitter’s data policy.