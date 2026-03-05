# 📊 Big Data E-Commerce Analytics Dashboard
Project ini merupakan implementasi **Big Data Analytics Pipeline menggunakan Apache Spark** untuk memproses data transaksi e-commerce dan divisualisasikan menggunakan **Power BI Dashboard**.
Project ini dibuat sebagai bagian dari praktikum **Big Data Technology – Batch Analytics & Visualization**.

# 🧠 Arsitektur Pipeline
Pipeline analytics terdiri dari beberapa layer:
Raw Data → Data Cleaning → Curated Data → Analytics Layer → Power BI Dashboard

# ⚙️ Teknologi yang Digunakan

- **Python**
- **Apache Spark (PySpark)**
- **Power BI**
- **Git & GitHub**
- **WSL Ubuntu**
- **VS Code**

---

🔄 Data Pipeline
1️⃣ Batch Pipeline
Script:
scripts/batch_pipeline_enterprise.py
Proses:
- Load raw transaction data
- Data cleaning
- Data transformation
- Save curated dataset

Output disimpan di:
data/curate

2️⃣ Analytics Layer
Script:
scripts/analytics_layer.py
Analytics yang dihitung:

- **Total Revenue**
- **Top Products**
- **Revenue by Category**
- **Average Transaction per Customer**

Output disimpan di:
data/serving

# 📊 Dashboard Visualization
Dashboard dibuat menggunakan **Power BI** dengan beberapa visualisasi utama:
### 📌 Total Revenue
Menampilkan total pendapatan dari seluruh transaksi.
### 📌 Top Products
Menampilkan produk dengan penjualan tertinggi.
### 📌 Revenue by Category
Distribusi pendapatan berdasarkan kategori produk.
### 📌 Average Transaction per Customer
Rata-rata nilai transaksi setiap pelanggan.

▶️ Cara Menjalankan Project
1️⃣ Jalankan Batch Pipeline
```bash
python scripts/batch_pipeline_enterprise.py
2️⃣ Jalankan Analytics Layer
python scripts/analytics_layer.py
3️⃣ Buka Power BI

Load dataset dari folder:
data/serving
📈 Contoh Output Analytics
Metric	Description
Total Revenue	Total pendapatan dari transaksi
Top Products	Produk dengan penjualan tertinggi
Revenue Category	Pendapatan per kategori
Avg Transaction	Rata-rata transaksi pelanggan
👨‍💻 Author

Nama: Syti Masidah
Project: Big Data Analytics Dashboard
