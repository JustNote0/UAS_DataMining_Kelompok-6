# ✈️ Analisis Penerapan Model Klasifikasi Decision Tree dan K-Nearest Neighbors untuk Mengetahui Hasil Kepuasan Penumpang Maskapai

---

## 👥 Anggota Kelompok

- Ananda Sakinah (23031554060)
- Nurus Shobah Hidayati (23031554163)
- Hesti Anjani Rara (23031554023)

---

## 📌 Ringkasan Proyek

Proyek ini bertujuan untuk menganalisis dan memprediksi tingkat kepuasan penumpang maskapai menggunakan dua model klasifikasi: **Decision Tree** dan **K-Nearest Neighbors (KNN)**. Dataset terdiri dari 129.880 data dengan 24 fitur, yang bersumber dari Javen Analytics.

---

## 🎯 Tujuan

- Mengidentifikasi faktor utama yang memengaruhi kepuasan penumpang.
- Menganalisis pengaruh kelas penerbangan, kualitas layanan, dan keterlambatan.
- Membangun dan membandingkan model klasifikasi untuk memprediksi kepuasan.

---

## ❓ Rumusan Masalah

- Faktor apa saja yang memengaruhi kepuasan penumpang maskapai?
- Bagaimana pengaruh layanan dan keterlambatan terhadap ketidakpuasan?
- Model mana yang memberikan performa lebih baik: Decision Tree atau KNN?

---

## 🧠 Metodologi

### 1. Analisis Data Eksploratif (EDA)

- Memeriksa data yang hilang, outlier, distribusi kategori, dan lain sebagainya.
- Visualisasi distribusi fitur, outliers, dan swewness.
  
### 2. Pra-pemrosesan Data

- Drop kolom yang tidak perlu
- Handling Missing value, outliers, dan skewness
- Label Encoding untuk variabel kategorik.
- Normalisasi/ scaling data numerik dengan `StandardScaler`.
- Encoding fitur object

### 3. Seleksi Fitur & Split Data

- Split data: 80% data latih, 20% data uji.
- Memilih fitur relevan berdasarkan korelasi.
- Mengambil keseluruhan fitur.

### 4. Pembuatan Model

- Menerapkan **Decision Tree Classifier** dan **KNN Classifier**.
- Evaluasi menggunakan:
  - Akurasi
  - Presisi
  - Recall
  - F1-score
  - Confusion Matrix

### 5. Evaluasi Model

- Membandingkan metrik antar model.
- Menganalisis confusion matrix dan fitur penting.

---

## 📊 Hasil & Analisis

- **Decision Tree dengan seluruh fitur** memberikan hasil terbaik dalam akurasi dan generalisasi.
- **Skor Model:**

| Model                            | Akurasi    | Presisi | Recall | F1-Score |
| -------------------------------- | ---------- | ------- | ------ | -------- |
| Decision Tree (All Features)     | **94.65%** | 94.65%  | 94.65% | 94.65%   |
| KNN (All Features)               | 92.71%     | 92.70%  | 92.71% | 92.70%   |
| Decision Tree (Dropped Features) | 91.83%     | 91.84%  | 91.83% | 91.84%   |
| KNN (Dropped Features)           | 91.70%     | 91.69%  | 91.70% | 91.69%   |

---

## 🧾 Kesimpulan & Insight

Decision Tree lebih andal dalam mengklasifikasikan kepuasan penumpang dibanding KNN.

---

## 📁 Struktur Repository

```
├── README.md
├── Poster_Project.png
├── PROJECT_DATA_MINING_KELOMPOK_6.ipynb
├── airline_passenger_satisfaction.csv
```

---

## ⚙️ Cara Menjalankan Proyek

1. Buka file `PROJECT_DATA_MINING_KELOMPOK_6.ipynb` di Jupyter Notebook atau Google Colab.
2. Input data airline_passenger_satisfaction.csv
3. Jalankan semua cell secara berurutan.

---

## 🧰 Dependensi

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn






