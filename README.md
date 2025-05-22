# Bank Fraud Clustering & Classification

## Tujuan Proyek

- 🔍 Mengelompokkan nasabah berdasarkan perilaku transaksi (Clustering).
- ⚠️ Memprediksi potensi kecurangan (fraud) dengan klasifikasi (Classification).

## 📂 Struktur Proyek
```
bank-fraud-clustering-classification/
├── model/
│ ├── decision_tree_model.h5 # Model klasifikasi Decision Tree
│ └── model_clustering.h5 # Model hasil clustering
├── data_clustering.csv # Dataset transaksi nasabah
├── [Clustering]_Submission_Akhir_BAIHAQI_ALZA.pdf # Laporan clustering
├── [Klasifikasi]_Submission_Akhir_BAIHAQI_ALZA.pdf # Laporan klasifikasi
```

## 🛠️ Tools & Library

- Python
- Scikit-learn
- TensorFlow / Keras (format model `.h5`)
- Pandas, Numpy, Matplotlib

## 🚀 Cara Menjalankan

```python
from keras.models import load_model

# Load model clustering
clustering_model = load_model('model/model_clustering.h5')

# Load model klasifikasi
classification_model = load_model('model/decision_tree_model.h5')
