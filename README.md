# Vision Transformer (ViT) — CIFAR-10 🧠📦

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-red.svg)]()
[![Google Colab](https://img.shields.io/badge/Run%20on-Colab-yellow.svg)]()
[![Dataset](https://img.shields.io/badge/CIFAR10-Dataset-green.svg)]()
[![Status](https://img.shields.io/badge/Project-Complete-success.svg)]()

This project implements a **Vision Transformer (ViT)** from scratch in **PyTorch** and trains it on the **CIFAR-10** dataset as part of KIIT University coursework.

✅ Patch Embedding  
✅ Multi-Head Self-Attention  
✅ Transformer Encoder blocks  
✅ Roll-number-based hyperparameters  
✅ Attention map visualization  
✅ Runs on Google Colab  

---

## 📂 Project Structure

| File | Description |
|------|------------|
`ViT_22052412.ipynb` | Complete ViT implementation & training  
`Shubhi_Tiwari_ViT_Assignment.pdf` | Full report  
`PartC_Experiment_Analysis_22052412.pdf` | Experimental analysis (plots + CM + attention map)  
`README.md` | Documentation  

---

## 🧠 Dataset — CIFAR-10

| Images | Classes | Size |
|--------|--------|------|
60,000 | 10 | 32×32 RGB  

Official link: https://www.cs.toronto.edu/~kriz/cifar.html  
*(auto-downloads in notebook)*

---

## ▶️ Run on Google Colab

Open notebook here:

https://colab.research.google.com/drive/1-4KpXFHpwFT7PRpQUkrwIxZiBdYHlEvq#scrollTo=f13ad3fc
Runtime → Change runtime type → GPU

Run all cells ✅

---

## ⚙️ Optional: Local Setup

```bash
pip install torch torchvision numpy matplotlib scikit-learn tqdm jupyter
jupyter notebook
📊 Results (Demo Training)
Metric	Value
Train Accuracy	~52%
Val Accuracy	~38%
Epochs	1–3 (fast mode for assignment)

Full GPU training can reach ~80%+ accuracy
🔎 Key Output Visualizations

✅ Training curve

✅ Confusion Matrix

✅ Attention Heatmap

🎯 Roll-Number-Based Parameters
Hyperparameter	Value
Hidden dim	192
Heads	6 (adjusted to be divisible)
Patch size	8
Epochs	Demo: 1-3 (full: 12 planned)
👩‍🎓 Student Info

Name: Shubhi Tiwari
Roll No: 22052412
University: KIIT University
Course: B.Tech CSE
Instructor: Himanshu Ranjan Sir
⭐ Support

If you found this helpful, please ⭐ star the repository!


---

### ✅ Done  
Your README is clean, academic-ready, and GitHub-ready.

If you want, I can also give you:

- PPT slides 🎤
- Viva Q&A sheet 📄
- Final zip submission folder 📦

Just tell me 😊
