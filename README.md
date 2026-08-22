# 📊 Superstore Sales & Profit Performance Analysis

[![Tableau](https://img.shields.io/badge/Tableau-Interactive%20Dashboard-E97627?logo=tableau)](LINK_TABLEAU_PUBLIC_KAMU_DI_SINI)
[![Python](https://img.shields.io/badge/Python-Data%20Cleaning-3776AB?logo=python)](Cleaning.ipynb)

## 📌 DummmyProject Overview
Proyek ini bertujuan untuk menganalisis performa penjualan, profitabilitas, dan demografi pelanggan pada dataset Superstore. Analisis dilakukan secara *end-to-end*, mulai dari pembersihan data mentah (*data cleaning*) hingga pembuatan *dashboard* interaktif untuk membantu pengambilan keputusan bisnis.

🔗 **[Klik di sini untuk melihat Dashboard Interaktif di Tableau Public](https://public.tableau.com/views/SuperstoreSalesProfitAnalysis_17873815109170/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## 🛠️ Tech Stack & Workflow
1. **Data Cleaning & Preprocessing:** Python (`Pandas`) — Menangani *missing values*, mengubah tipe data tanggal, memformat nilai numerik, dan mengekspor data bersih ke format Excel.
2. **Data Visualization:** Tableau Public — Membangun *dashboard* interaktif dengan KPI utama, analisis tren bulanan, distribusi produk, dan peta penjualan.

---

## 💡 Key Business Insights
* **Penjualan vs Profit:** Total penjualan mencapai **$1.04M** dengan profit sebesar **$128.9K** dari **706** pelanggan.
* **Performa Produk:** Kategori produk tertentu (seperti *Copiers* dan *Bookcases*) mendorong angka penjualan tertinggi, namun beberapa sub-kategori mempunyai *profit margin* yang sangat tipis akibat adanya diskon berlebih.
* **Tren Musiman:** Penjualan mengalami lonjakan signifikan pada periode akhir tahun (Q4), menunjukkan pola pembelian musiman (*seasonal pattern*).
* **Distribus Wilayah:** Penjualan terkonsentrasi pada wilayah negara tertentu di Eropa, di mana area dengan warna hijau gelap memberikan kontribusi profit terbesar.

---

## 🚀 Business Recommendations
1. **Optimize Discount Strategy:** Evaluasi kebijakan diskon pada sub-kategori produk yang menghasilkan profit rendah untuk mempertahankan *margin*.
2. **Capitalize on Peak Season:** Meingkatkan persediaan stok (*inventory*) dan alokasi anggaran pemasaran pada periode Q3-Q4 untuk memaksimalkan tren kenaikan penjualan bulanan.
3. **Regional Focus:** Alokasikan tim *sales* untuk melakukan penetrasi pasar di wilayah dengan tingkat penjualan yang masih rendah namun memiliki potensi pasar tinggi.

---

## 📁 Repository Structure
```text
├── Cleaning.ipynb            # Script Python untuk proses data cleaning
├── Superstore_Cleaned.xlsx   # Dataset hasil pembersihan (Cleaned Data)
└── README.md                 # Dokumentasi proyek
