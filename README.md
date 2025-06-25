# 📡 LDPC Coding and Decoding for 5G NR (Base Graph 2)

This repository contains a **MATLAB** implementation of **Low-Density Parity-Check (LDPC)** coding and decoding based on the **5G New Radio (NR)** standard, specifically using **Base Graph 2 (BG2)**. The project includes encoding, Min-Sum algorithm-based belief propagation decoding, and simulation-driven performance analysis.

---

## 🚀 Features

- ✅ LDPC encoding for 5G NR Base Graph 2  
- ✅ Min-Sum decoding with adjustable maximum iterations  
- ✅ Performance simulation across various SNR (Eb/No) values  
- ✅ Visualization of Bit Error Rate (BER) and decoding convergence  
- ✅ Comparison with the theoretical Shannon limit  

---

## 🧠 Theory

**LDPC codes** are forward error correction codes used in modern communication systems, including **5G NR**, to achieve high data reliability with low redundancy.  
**Base Graph 2 (BG2)** is designed for smaller block sizes and low-latency applications.  
Decoding is done using the **Min-Sum Algorithm**, a simplified and computationally efficient approximation of the Belief Propagation algorithm.

---

## 📊 Outputs

The simulation produces the following plots:
- 📉 **BER vs. Eb/No**
- 🔁 **Average number of decoding iterations vs. Eb/No**
- ✅ **Success rate of decoding vs. number of iterations**

---

## 🛠️ Requirements

- MATLAB **R2021a** or later
- `ParityCheck_BG2.mat` file (included in this repository)

---

> Made with using MATLAB
