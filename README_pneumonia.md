# 🫁 Automated Pneumonia Detection using Deep Learning

A deep learning project that classifies chest X-ray images as **pneumonia-positive or negative** using a Convolutional Neural Network (CNN), achieving **97.80% validation accuracy**.

---

## 📌 Project Overview

Pneumonia is one of the leading causes of death worldwide, and early detection is critical. This project automates the detection of pneumonia from chest X-ray images using CNNs, transfer learning, and data augmentation — reducing the dependency on manual diagnosis and supporting clinical decision-making.

---

## 🎯 Results

| Metric | Score |
|--------|-------|
| Validation Accuracy | **97.80%** |
| Model Type | CNN with Transfer Learning |
| Dataset | Kaggle Chest X-Ray Images |

---

## 🗂️ Dataset

- **Source:** [Kaggle – Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- **Classes:** `NORMAL` / `PNEUMONIA`
- **Split:** Train / Validation / Test

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| Python | Core programming language |
| TensorFlow / Keras | Model building and training |
| NumPy | Numerical operations |
| Matplotlib | Visualisation and plotting |

---

## 🏗️ Project Structure

```
pneumonia-detection/
│
├── data/
│   ├── train/
│   ├── val/
│   └── test/
│
├── notebooks/
│   └── pneumonia_detection.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   └── evaluate.py
│
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. **Data Preprocessing** — Images resized, normalised, and split into train/val/test sets
2. **Data Augmentation** — Rotation, flipping, and zoom applied to improve generalisation
3. **Model Architecture** — CNN with transfer learning backbone
4. **Training** — Model trained with early stopping and learning rate scheduling
5. **Evaluation** — Validated on held-out test set; results visualised with confusion matrix and accuracy/loss curves

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install tensorflow numpy matplotlib
```

### Run the notebook
```bash
jupyter notebook notebooks/pneumonia_detection.ipynb
```

---

## 📊 Sample Output

The model outputs a binary classification:
- `0` → Normal
- `1` → Pneumonia

Confidence scores are provided alongside predictions to support clinical interpretation.

---

## 📚 Learnings

- Implemented transfer learning to overcome limited dataset size
- Applied data augmentation to reduce overfitting on medical imaging data
- Translated model outputs into actionable insights for clinical screening contexts

---

## 👩‍💻 Author

**Sanshita Yelina Ekka**
[LinkedIn](https://linkedin.com/in/sanshita-yelina-ekka) • [GitHub](https://github.com/Sanshitayelina08)

---

> *Academic project — Mount Carmel College, Bengaluru (2024)*
