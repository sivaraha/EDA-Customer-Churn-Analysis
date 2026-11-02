# Exploratory Data Analysis: Telco Customer Churn

Proyek analisis eksplorasi data (*Exploratory Data Analysis* - EDA) ini bertujuan untuk mengidentifikasi faktor-faktor utama yang memicu pelanggan berhenti berlangganan (*customer churn*) pada industri telekomunikasi, serta memberikan rekomendasi bisnis yang *actionable* bagi tim manajemen.

## Ikhtisar Proyek
* **Fokus Analisis:** Pola perilaku pelanggan, lama berlangganan (*tenure*), struktur biaya bulanan (*monthly charges*), dan jenis kontrak.
* **Tools & Library:** Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn.
* **Dataset:** Telco Customer Churn (Open Dataset).

## Key Findings (Temuan Utama)
1. **Pengaruh Jenis Kontrak (*Contract Type*):** Pelanggan dengan kontrak bulanan (*Month-to-month*) mendominasi angka *churn* secara signifikan dibandingkan pelanggan dengan kontrak jangka panjang (1 atau 2 tahun).
2. **Masa Berlangganan (*Tenure*):** Risiko *churn* tertinggi terkonsentrasi pada pelanggan baru (*low tenure* / di bawah 5 bulan pertama). Pelanggan yang berhasil melewati tahun pertama cenderung jauh lebih loyal.
3. **Biaya Bulanan (*Monthly Charges*):** Pelanggan yang melakukan *churn* cenderung berada pada kelompok dengan biaya bulanan yang lebih tinggi (rata-rata di kisaran $80–$90), yang mengindikasikan sensitivitas harga terhadap nilai layanan.

## Business Recommendations (Rekomendasi Bisnis)
* **Program Retensi Dini (*Early Onboarding*):** Mengintensifkan keterlibatan dan dukungan bagi pelanggan baru di 6 bulan pertama berlangganan untuk menekan angka *churn* awal.
* **Insentif Migrasi Kontrak:** Mendorong pengguna kontrak bulanan untuk beralih ke paket jangka panjang melalui penawaran benefit atau potongan harga khusus guna mengamankan *revenue retention*.
* **Evaluasi Nilai Layanan (*Value Bundling*):** Meninjau kembali struktur harga untuk paket dengan biaya bulanan tinggi agar pelanggan merasa mendapatkan nilai yang sepadan dengan pengeluaran mereka.

## Cara Menjalankan Notebook
1. Clone repository ini atau unduh file `.ipynb`.
2. Buka [Google Colab](https://colab.research.google.com/).
3. Upload file `EDA_Customer_Churn_Analysis.ipynb` dan jalankan sel kode dari atas ke bawah.

---
*Dibuat oleh [Siva Rahmatullah](https://github.com/sivaraha)*
