# 🔧 Motor Fault Detection using Wavelet Transform & Machine Learning

This project demonstrates how wavelet transform and classical machine learning models can be used for early fault detection in electric motor signals. The goal is to extract robust time-frequency features and classify motor conditions (normal vs. faulty) from synthetic signals.

---

## 📌 Project Overview

- **Signal Simulation**: Synthetic time-domain signals are generated to represent both healthy and faulty motor behaviors.
- **Wavelet Feature Extraction**: Energy and entropy values are extracted from wavelet decomposition levels.
- **Classification**: A Random Forest classifier is trained to distinguish between signal types.
- **Noise Handling**: The robustness of the method is evaluated on noisy signals as well.

---

## ✅ Completed Steps

### 🟢 Step 1 – Basic Signal Processing & Feature Extraction
- Created synthetic signals (normal vs. faulty)
- Applied `pywt` to extract wavelet features (Energy, Entropy)
- Trained and evaluated a classifier (RandomForest)
- Achieved **100% accuracy** on the simple dataset  
- 📊 Confusion matrix and plots included  
- 📄 Report: [`Step1_Report.pdf`](figures/Step1_Report.pdf)

### 🟢 Step 2 – Noisy Signal Handling
- Added Gaussian noise to both signal types
- Extracted wavelet features from noisy signals
- Observed feature differences under noise
- Model retained **100% accuracy** even on noisy data  
- 📊 Confusion matrix, signal plots
- 📄 Report: [`Step2_Report.pdf`](figures/Step2_Report.pdf)

---


## 🚀 How to Run

1. Clone the repository  
2. Set up a virtual environment and install dependencies:

```bash
pip install -r requirements.txt

3.python src/step1_generate_signal.py
python src/step2_wavelet_features.py
...

 ___

🛠️ Tools & Libraries

Python 3.10+

NumPy

PyWavelets (pywt)

Scikit-learn

Matplotlib / Seaborn

Pandas



---

✍️ Author

Safa Bazrafshan
📧 safa.bazrafshan@gmail.com

