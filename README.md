# 📊 Segmentasi Pelanggan menggunakan RFM dan K-Means Clustering

## 🌤️ Overview Project

Proyek ini bertujuan untuk melakukan segmentasi pelanggan menggunakan analisis **RFM (Recency, Frequency, Monetary)** dan algoritma **K-Means Clustering** untuk mengidentifikasi perilaku pelanggan dan membantu dalam penyusunan strategi pemasaran yang lebih tepat sasaran.

Dataset yang digunakan berisi data transaksi penjualan dari sebuah bisnis retail online, yang mencakup informasi seperti ID pelanggan, tanggal transaksi, jumlah pembelian, dan nilai total pembelian. Data ini digunakan untuk menghitung skor RFM dan mengelompokkan pelanggan ke dalam segmen tertentu berdasarkan pola pembelian mereka.

## 📖 Dataset

Dataset yang digunakan dalam analisis ini diambil dari website UC Irvine Online Retail yang berisi 541.910 instance dengan fitur **InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country**. 
Dataset dapat diakses melalui link berikut [Dataset Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail).

## 🎯 Tujuan 
a. Mengidentifikasi segmen pelanggan berdasarkan perilaku pembelian.

b. Menentukan pelanggan potensial, pelanggan yang hampir churn, dan pelanggan loyal.

c. Memberikan insight untuk strategi pemasaran berbasis data.

## 🛠️ Tools & Library

- Python 3.x
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn (KMeans, PCA, Silhouette Score)

## 💡 Hasil & Insight 

![image](https://github.com/user-attachments/assets/2dc6d47b-2429-42c7-ba3e-6bd43fe41879)


- Cluster 0: Pelanggan loyal dengan frekuensi dan nilai pembelian tinggi.
- Cluster 1: Pelanggan tidak aktif dengan jarak waktu pembelian yang lama.
- Cluster 2: Pelanggan baru atau berpotensi meningkat.
- Cluster 3: Pelanggan sangat aktif dengan pembelian besar dan rutin.

Insight ini dapat digunakan untuk menyusun strategi pemasaran seperti personalisasi promosi, loyalitas program, atau reaktivasi pelanggan.



