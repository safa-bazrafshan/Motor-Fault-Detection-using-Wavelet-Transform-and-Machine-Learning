# Motor Fault Detection using Wavelet Transform and Machine Learning

This project demonstrates how to classify motor faults using synthetic signals, wavelet-based feature extraction, and machine learning.

## 🔧 Tools & Technologies

- Python
- NumPy, Matplotlib, PyWavelets, Pandas
- Scikit-learn (ML model training)
- Wavelet Transform (feature extraction)
- Signal Simulation (synthetic)

---

## 📁 Project Structure

motor_fault_wavelet_ml/ ├── src/ │   ├── step1_generate_signal.py        # Simulates synthetic normal and faulty signals │   ├── step2_wavelet_features.py       # Applies DWT and extracts features (energy, entropy) │   ├── step3_create_dataset.py         # Builds dataset from multiple signals │   ├── step4_train_model.py            # Trains and evaluates ML model (RandomForest) ├── motor_wavelet_dataset.csv           # Final dataset with labels ├── results/                            # Contains all plots & figures

---

## 🧪 Results

- Achieved 100% accuracy on binary classification (Normal vs Faulty)
- Used DWT (db4) to extract multi-level energy and entropy
- Visualized signals, wavelet coefficients, and confusion matrix

<p align="center">
  <img src="results/step4_confusion_matrix.png" alt="Confusion Matrix" width="300"/>
</p>

---

## 📌 Conclusion

This simple workflow showed the power of wavelet-based features in classifying motor faults with high accuracy using classical ML models.

---

## 🚀 Future Work

- Replace synthetic signals with real-world motor data (current or vibration)
- Add multiple fault types and multi-class classification
- Explore deep learning models (CNN, LSTM) for feature learning
- Real-time fault detection deployment

---

## 👤 Author

Safa Bazrafshan  
📧 safa.bazrafshan@gmail.com

---

## 📄 License

This project is open-source and free to use.
