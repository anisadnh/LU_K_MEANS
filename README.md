# 🧠 K-Means Clustering: Mall Customer Segmentation

Proyek ini menggunakan algoritma **K-Means Clustering** untuk melakukan segmentasi pelanggan berdasarkan **pendapatan tahunan** dan **skor belanja**, menggunakan dataset *Mall Customers*.

## 📁 Dataset
- Dataset: `Mall_Customers.csv`
- Kolom penting:
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## 🚀 Cara Menjalankan di Google Colab

1. Buka Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. Upload file `KMeans_Mall_Customers.ipynb`
3. Jalankan sel satu per satu
4. Saat diminta, upload file `Mall_Customers.csv`

## 📊 Proses Analisis

- **Preprocessing**: memilih fitur, normalisasi
- **Menentukan jumlah cluster (K)**: menggunakan *Elbow Method*
- **Modeling**: KMeans clustering
- **Visualisasi**: scatter plot hasil segmentasi pelanggan

## 📈 Output

- Grafik Elbow Method
- Grafik hasil clustering
- Dataset dengan kolom tambahan: `Cluster`

## 🛠️ Library yang Digunakan

- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 📌 Referensi

- [Kaggle Dataset – Mall Customers](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/clustering.html#k-means)
- [Analytics Vidhya – Customer Segmentation](https://www.analyticsvidhya.com/blog/2021/05/customer-segmentation-using-k-means-clustering/)

---

🧾 **Catatan**:  
File ini dirancang untuk dijalankan di **Google Colab** dan membutuhkan upload manual file CSV.

