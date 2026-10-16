# Tugas UTS Machine Learning

**Identitas Mahasiswa:**
- **Nama**  : Anggela Merici Moruk
- **NIM**   : 241011401654
- **Kelas** : 05TPLM004
- **Reg**   : B
- **Prodi** : Teknik Informatika - Universitas Pamulang

---

## 📌 Ringkasan Hasil UTS

### 1. Bagian A – Linear Regression (Ads_Data.csv)
- **Normal Equation**:
  - Intercept ($b$): `27.8884`
  - Koefisien ($m$): `9.3474`
  - Persamaan: $\hat{y} = 27.8884 + 9.3474 \cdot X$
- **Evaluasi Model**:
  - **Data Training**: $R^2$ = `0.9570`, RMSE = `5.13`
  - **Data Testing**: $R^2$ = `0.8240`, RMSE = `8.99`
- **Prediksi Baru**:
  - Biaya Iklan 4.5 Juta $\rightarrow$ Penjualan: `69.95`
  - Biaya Iklan 7.0 Juta $\rightarrow$ Penjualan: `93.32`
  - Biaya Iklan 12.0 Juta $\rightarrow$ Penjualan: `140.06`

---

### 2. Bagian B – Logistic Regression (Email_Data.csv)
- **Model Parameters**:
  - Intercept ($b$): `-15.1396`
  - Koefisien $m_1$ (JumlahLink): `1.3306`
  - Koefisien $m_2$ (KataPromo): `1.2444`
- **Evaluasi Threshold Optimal (Threshold = 0.7)**:
  - Accuracy: `0.8000`
  - Precision: `1.0000` (False Positive = 0)
  - Recall: `0.5000`
- **Prediksi Email Baru (Threshold 0.7)**:
  - **E1** (Link: 1, Promo: 2) $\rightarrow$ Probabilitas: `0.0000` (**Bukan Spam**)
  - **E2** (Link: 5, Promo: 6) $\rightarrow$ Probabilitas: `0.2650` (**Bukan Spam**)
  - **E3** (Link: 9, Promo: 10) $\rightarrow$ Probabilitas: `0.9999` (**Spam**)
  - **E4** (Link: 2, Promo: 11) $\rightarrow$ Probabilitas: `0.7703` (**Spam**)

---

### 3. Bagian C – Pemahaman Konsep
Telah dijawab secara lengkap dan mandiri pada notebook `tugas_UTS.ipynb`.

---

### 4. Bonus – Perbandingan dengan scikit-learn
- Perbandingan antara algoritma manual vs `scikit-learn` beserta analisis pengaruh L2 Regularization dan feature scaling telah diselesaikan pada notebook `tugas_UTS.ipynb`.
