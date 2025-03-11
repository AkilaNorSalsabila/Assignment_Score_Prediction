# Assignment_Score_Prediction

## 📌 Overview
Proyek ini menggunakan teknik Machine Learning untuk memprediksi skor siswa berdasarkan jumlah jam belajar mereka.  
Model yang digunakan termasuk **Linear Regression** dan **Decision Tree** untuk membandingkan performa prediksi.

## 📂 Project Structure
```plaintext
ml-student-scores/
│── data/         # Dataset
│── notebooks/    # Jupyter Notebooks for EDA & modeling
│── models/       # Trained models
│── results/      # Model evaluation results
└── README.md     # Project documentation
```

## 📊 Dataset
Dataset yang digunakan dalam proyek ini adalah **student_scores.xlsx**.  
Dataset ini berisi data jumlah jam belajar siswa dan skor yang mereka peroleh.

## 🚀 Model & Metode
### 1. Linear Regression
- Model sederhana untuk memprediksi skor berdasarkan jumlah jam belajar.
- Cenderung memberikan prediksi yang lebih mulus tetapi bisa gagal menangkap pola kompleks.

### 2. Decision Tree
- Model yang lebih fleksibel dalam menangkap pola non-linear.
- Berpotensi mengalami **overfitting** jika tidak dikontrol dengan baik.

## 🔧 Instalasi
Clone repositori ini:
```bash
git clone https://github.com/AkilaNorSalsabila/Assignment_Score_Prediction.git
```
Masuk ke direktori proyek:
```bash
cd Assignment_Score_Prediction
```
Install dependensi:
```bash
pip install -r requirements.txt
```
Jalankan notebook di Google Colab atau Jupyter Notebook.

## 📈 Visualisasi Hasil  

Beberapa grafik yang dihasilkan dalam proyek ini:  

- 📌 **Scatter Plot** untuk melihat hubungan antara jam belajar dan skor.  
- 📌 **Garis Prediksi Linear Regression** dibandingkan dengan data aktual.  
- 📌 **Prediksi Decision Tree** untuk menangkap pola lebih detail.  
