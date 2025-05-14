# 🔒 Deep Learning Project 3 – Jailbreaking Deep Models

This project explores adversarial robustness in deep image classifiers by implementing and evaluating adversarial attacks on a pretrained ResNet-34 model using ImageNet-1K subset data.

## 📂 Contents

- `main.ipynb`: Complete implementation of all 5 tasks
- `DeepLearningProject3_Report.pdf`: Final AAAI-style report (with tables, plots, and visuals)
- `TestDataSet.zip`: Input test images (100-class ImageNet subset)
- `DeepLearningProject3_Report.pdf`: Final project writeup
- `.DS_Store`: Auto-generated system file (can be ignored)

---

## 🧪 Tasks Overview

| Task | Description |
|------|-------------|
| **Task 1** | Baseline accuracy evaluation on clean ImageNet images |
| **Task 2** | FGSM attack on full image with $\ell_\infty$ constraint |
| **Task 3** | Stronger iterative attacks: I-FGSM and PGD |
| **Task 4** | Patch-constrained attacks (32×32 region only) |
| **Task 5** | Transferability analysis to DenseNet-121 |

---

## 📊 Key Results

- **Baseline Accuracy (ResNet-34)**:  
  - Top-1: 76.00%  
  - Top-5: 94.20%

- **Best Attack (PGD)**:  
  - Top-1 Accuracy: **0.20%**  
  - Top-5 Accuracy: **14.20%**

- **Transfer to DenseNet-121 (PGD)**:  
  - Top-1 drops to **65.00%**  
  - Patch PGD drops to **59.80%**

- 🔁 Results include full plots comparing:
  - Attack strength (FGSM, PGD, Patch)
  - Transferability across architectures

---

## 📷 Visualizations

- 🔎 Adversarial examples (FGSM, PGD, Patch)
- 📉 Accuracy drop bar charts
- 🔁 Transferability line plots

---

## 💡 Lessons Learned

- Even imperceptible pixel-level changes can collapse model predictions.
- Iterative and patch attacks outperform vanilla FGSM.
- Transferability makes black-box attacks viable.

---

## 👩‍💻 Authors

- **Anushka Garg**
- **Nishant Sharma**
- **Rahul Mallidi** 
