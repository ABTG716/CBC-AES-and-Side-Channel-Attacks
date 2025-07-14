# AES-128-algorithm
# 🔐 CBC-AES and Side-Channel Attacks

This repository explores the inner workings of AES encryption in CBC (Cipher Block Chaining) mode, including a full implementation of AES from scratch, and an analysis of its vulnerability to side-channel attacks—particularly power analysis techniques like Correlation Power Analysis (CPA).

---

## 📌 Project Overview

The goal of this project is twofold:

1. **Implement AES from scratch** in Python (including SubBytes, ShiftRows, MixColumns, and Key Expansion).
2. **Demonstrate a side-channel attack** (specifically CPA) by analysing power traces and recovering key information based on leakage.

This project serves as both a cryptographic engineering and side-channel attack analysis exercise.

---

## 🛠️ What Was Implemented

- ✅ AES-128 encryption (from scratch, in Python)
- ✅ CBC mode block chaining logic
- ✅ Power model using Hamming weights
- ✅ Correlation Power Analysis (CPA)
- ✅ Key byte hypothesis and recovery
- ✅ Detailed visualisation of side-channel leakage and correlation

> 📎 Note: All code and the Jupyter Notebook were created by the contributor. Some additional boilerplate (e.g., trace generation or provided dataset) was supplied by the instructor.

---

## 🧠 Key Concepts

- AES S-box, key expansion, and rounds  
- CBC mode padding and chaining  
- Leakage modelling using Hamming weight  
- Statistical analysis using Pearson correlation  
- Side-channel resistance and cryptanalysis  

---

## 📈 Visualisations

The notebook includes:
- Sample power traces  
- Hamming weight analysis  
- Correlation vs. key byte plots  
- Recovered key comparison  

---

## ⚙️ Requirements

You’ll need the following Python packages:

```bash
pip install numpy pandas matplotlib scikit-learn

