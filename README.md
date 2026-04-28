# Double JPEG Compression Detection Detection

This project implements a system to detect **single vs double JPEG compression** at the **8×8 block level**, based on the IEEE MLSP 2020 paper:

"Double JPEG Compression Detection for Distinguishable Blocks in Images Compressed with Same Quantization Matrix"

---

## 📌 Overview

Digital image forensics often requires detecting whether an image has been tampered with. One strong indicator is **double JPEG compression**.

This project:
- Works at **block level (8×8)**
- Uses **error analysis in spatial + frequency domain**
- Implements both:
  - MC-CNN model as the research paper
  - SVM baseline (scikit-learn) for baseline

---

## 🧠 Methodology

Each JPEG block is analyzed by:
1. Recompressing the block
2. Computing error images
3. Extracting spatial and DCT features

---

## 📂 Project Structure
(Put your datset here before running the code)
project/
│
├── data/
├── checkpoints/
├── plots/
├── best_models/
├── DIP_Group3.ipynb
├── requirements.txt
└── README.md

---

## ⚙️ Setup

pip install -r requirements.txt

---

## ▶️ Run

DIP_Group3.ipynb

---

## 📜 Reference

IEEE MLSP 2020 Paper



