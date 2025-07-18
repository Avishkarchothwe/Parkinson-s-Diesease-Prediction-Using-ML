# Parkinson's Disease Detection

This project implements a machine learning model to detect Parkinson's disease using biomedical voice measurements. It leverages Python, data preprocessing techniques, and classification algorithms to predict whether a patient has Parkinson's disease based on given features.

---

## 📌 Project Overview
Parkinson's disease is a progressive nervous system disorder that affects movement. Early detection is crucial for better treatment and care. This project uses supervised machine learning algorithms to classify patients as **Parkinson's Positive** or **Negative** based on voice-related features.

---

## 📂 Dataset
The dataset contains various biomedical voice measurements from patients with and without Parkinson's disease.

- **Source**: UCI Machine Learning Repository (Parkinson's Dataset)
- **Features**:
  - Name: Patient Identifier
  - MDVP:Fo(Hz) – Average vocal fundamental frequency
  - MDVP:Fhi(Hz) – Maximum vocal fundamental frequency
  - MDVP:Flo(Hz) – Minimum vocal fundamental frequency
  - MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP – Several measures of variation in fundamental frequency
  - MDVP:Shimmer, Shimmer(dB), APQ3, APQ5, APQ, Shimmer:DDA – Several measures of variation in amplitude
  - NHR, HNR – Two measures of ratio of noise to tonal components in the voice
  - **status**: Target variable (1 = Parkinson’s, 0 = Healthy)

---

## ⚙️ Requirements
Install the following Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
