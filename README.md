<div align="center">

# Machine Learning — AI Development B10

Kumpulan implementasi Machine Learning yang dikerjakan selama mengikuti program **AI Development B10** di **Infinite Learning**, mencakup Supervised Learning (Regression & Classification), Unsupervised Learning (Clustering), dan Deep Learning.

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)](https://keras.io/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)]()

</div>

---

## Table of Contents

- [About](#about)
- [Author](#author)
- [Tech Stack](#tech-stack)
- [Daftar Tugas](#daftar-tugas)
  - [Tugas 9 — Linear Regression](#tugas-9--linear-regression)
  - [Tugas 10 — Decision Tree Classification](#tugas-10--decision-tree-classification)
  - [Tugas 11 — Clustering Algorithms](#tugas-11--clustering-algorithms)
  - [Tugas 12 — Deep Learning (MLP & CNN)](#tugas-12--deep-learning-mlp--cnn)
- [Struktur Repository](#struktur-repository)
- [Cara Menjalankan](#cara-menjalankan)
- [Workflow Pengerjaan](#workflow-pengerjaan)
- [Lisensi](#lisensi)

---

## About

Repository ini berisi penugasan mandiri yang dikerjakan untuk memenuhi syarat program AI Development B10 di Infinite Learning. Fokus utamanya adalah implementasi berbagai algoritma Machine Learning, mulai dari yang klasik seperti Linear Regression dan Decision Tree, sampai algoritma unsupervised seperti Clustering dan Deep Learning dengan TensorFlow/Keras.

Setiap tugas dikerjakan secara end-to-end mencakup data collection, preprocessing, EDA, training model, evaluasi, dan analisis hasil. Tujuan akhirnya adalah membangun pemahaman mendalam tentang berbagai pendekatan ML dan kapan harus menggunakan masing-masing.

---

## Author

**Firman Fadilah**

- Role: Design Researcher & Scrum Master, Tim Kaca Digital Nusantara (KDN)
- Program: AI Development B10 — Infinite Learning
- Capstone Project: [Pangan Pintar](#) — Platform prediksi harga pangan strategis Indonesia berbasis AI

---

## Tech Stack

| Kategori | Tools |
|---|---|
| **Language** | Python 3.x |
| **Environment** | Jupyter Notebook (Google Colab dengan GPU T4) |
| **Classical ML** | scikit-learn (Linear Regression, Decision Tree, KMeans, DBSCAN, Agglomerative) |
| **Deep Learning** | TensorFlow, Keras |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Model Persistence** | Joblib |
| **Version Control** | Git, GitHub |

---

## Daftar Tugas

### Tugas 9 — Linear Regression

Membangun model **Linear Regression** untuk memprediksi konsumsi energi bangunan (Energy Consumption) berdasarkan karakteristik bangunan dan kondisi lingkungannya.

**Algoritma:** Linear Regression (Supervised Learning - Regression)

**Dataset:** [Energy Consumption Dataset](https://www.kaggle.com/datasets/govindaramsriram/energy-consumption-dataset-linear-regression)

**Cakupan:**
- Problem identification
- Data preprocessing (one-hot encoding, StandardScaler)
- EDA dengan visualisasi univariat, bivariat, dan korelasi
- Model training dan evaluasi (MAE, RMSE, R²)
- Save model dan scaler menggunakan joblib
- Prediksi pada data baru

**File:** [`Tugas-9-Linear-Regression/Tugas_9_ML_FirmanFadilah.ipynb`](./Tugas-9-Linear-Regression/Tugas_9_ML_FirmanFadilah.ipynb)

---

### Tugas 10 — Decision Tree Classification

Klasifikasi spesies bunga **Iris** menggunakan algoritma **Decision Tree**, dilengkapi dengan visualisasi pohon keputusan dan analisis cara kerjanya.

**Algoritma:** Decision Tree Classifier (Supervised Learning - Classification)

**Dataset:** Iris Dataset (built-in di scikit-learn)

**Cakupan:**
- EDA dengan pairplot
- Split data training & testing
- Model training Decision Tree
- Evaluasi: accuracy, classification report, confusion matrix
- Visualisasi struktur Decision Tree
- Prediksi data baru dengan multiple samples
- Analisis overfitting dan algoritma serupa

**File:** [`Tugas-10-Decision-Tree/Tugas_10_ML_FirmanFadilah.ipynb`](./Tugas-10-Decision-Tree/Tugas_10_ML_FirmanFadilah.ipynb)

---

### Tugas 11 — Clustering Algorithms

Segmentasi pelanggan mall menggunakan tiga algoritma clustering berbeda dan membandingkan hasilnya untuk menentukan pendekatan terbaik.

**Algoritma:** KMeans, DBSCAN, Agglomerative Clustering (Unsupervised Learning - Clustering)

**Dataset:** [Mall Customers](https://gist.githubusercontent.com/pravalliyaram/5c05f43d2351249927b8a3f3cc3e5ecf/raw/Mall_Customers.csv)

**Cakupan:**
- Pemilihan fitur untuk clustering
- StandardScaler preprocessing
- Implementasi KMeans dengan k=5
- Implementasi DBSCAN dengan eps=0.6, min_samples=5
- Implementasi Agglomerative dengan 5 cluster
- Evaluasi dengan Silhouette Score
- Perbandingan visual ketiga algoritma
- Analisis naratif untuk rekomendasi algoritma terbaik

**File:** [`Tugas-11-Clustering/Tugas_11_ML_FirmanFadilah.ipynb`](./Tugas-11-Clustering/Tugas_11_ML_FirmanFadilah.ipynb)

---

### Tugas 12 — Deep Learning (MLP & CNN)

Klasifikasi gambar pakaian dari dataset **Fashion MNIST** menggunakan dua arsitektur neural network: Multi-Layer Perceptron (MLP) dan Convolutional Neural Network (CNN), dengan eksperimen hyperparameter tuning.

**Algoritma:** MLP & CNN (Deep Learning - Image Classification)

**Dataset:** Fashion MNIST (built-in di TensorFlow/Keras)

**Cakupan:**
- Data preprocessing dan normalisasi
- Visualisasi sample gambar dengan label kelas
- Implementasi MLP Default (baseline)
- Implementasi MLP Tuned (hyperparameter tuning: tambah layer, perbesar neuron, ganti optimizer, naik epoch)
- Implementasi CNN dengan Conv2D dan MaxPooling
- Training dan evaluasi 3 model secara berurutan
- Comparison plot training accuracy & loss
- Classification report & confusion matrix
- Analisis komparatif: kapan pakai MLP vs CNN

**File:** [`Tugas-12-Deep-Learning/Tugas_12_ML_FirmanFadilah.ipynb`](./Tugas-12-Deep-Learning/Tugas_12_ML_FirmanFadilah.ipynb)

---

## Struktur Repository

```
machine-learning-ai-b10/
├── Tugas-9-Linear-Regression/
│   └── Tugas_9_ML_FirmanFadilah.ipynb
├── Tugas-10-Decision-Tree/
│   └── Tugas_10_ML_FirmanFadilah.ipynb
├── Tugas-11-Clustering/
│   └── Tugas_11_ML_FirmanFadilah.ipynb
├── Tugas-12-Deep-Learning/
│   └── Tugas_12_ML_FirmanFadilah.ipynb
├── .gitignore
├── LICENSE
└── README.md
```

---

## Cara Menjalankan

### Opsi 1 — Google Colab (Recommended)

1. Buka file `.ipynb` di GitHub
2. Klik tombol "Open in Colab" atau salin URL ke [Google Colab](https://colab.research.google.com/)
3. Untuk **Tugas 12**: aktifkan GPU di `Runtime → Change runtime type → T4 GPU`
4. Untuk **Tugas 9**: upload dataset CSV yang dibutuhkan ke session Colab
5. Run All

### Opsi 2 — Local

```bash
# Clone repository
git clone https://github.com/manrandomside/machine-learning-ai-b10.git
cd machine-learning-ai-b10

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow joblib jupyter

# Jalankan Jupyter
jupyter notebook
```

---

## Workflow Pengerjaan

Setiap tugas dikerjakan secara bertahap dengan workflow Git yang terstruktur:

1. **Setup** — inisialisasi struktur folder dan template kosong
2. **Implementasi bertahap** — setiap section dikerjakan dalam commit terpisah
3. **Insight & dokumentasi** — penambahan analisis dan kesimpulan untuk setiap TODO
4. **Final review** — pengecekan akhir dan finalisasi

Pendekatan ini bertujuan untuk menjaga history yang rapi dan mudah ditelusuri, sekaligus mensimulasikan workflow tim development di dunia nyata.

**Convention commit message** yang digunakan (Conventional Commits):
- `feat:` untuk implementasi kode/algoritma baru
- `docs:` untuk dokumentasi, insight, dan analisis
- `chore:` untuk setup dan konfigurasi
- `refactor:` untuk perbaikan struktur tanpa mengubah fungsi
- `fix:` untuk perbaikan bug

---

## Lisensi

Repository ini menggunakan lisensi MIT — lihat file [LICENSE](./LICENSE) untuk detail.

---

<div align="center">

**Made with care by Firman Fadilah**

Part of AI Development B10 program at [Infinite Learning](https://infinitelearning.id/)

</div>
