# ✈️ Customer Satisfaction & Churn Risk Analysis

## Project Overview

Project ini bertujuan untuk menganalisis tingkat kepuasan pelanggan maskapai sekaligus mengidentifikasi faktor-faktor layanan yang berkontribusi terhadap ketidakpuasan dan risiko customer churn. Analisis dilakukan menggunakan Python untuk proses data preprocessing dan exploratory data analysis (EDA), kemudian hasilnya divisualisasikan dalam dashboard Power BI. Dashboard menampilkan metrik utama seperti Customer Satisfaction Score (CSAT), Net Promoter Score (NPS), Churn Risk Rate, distribusi loyalitas pelanggan, serta service gap untuk membantu perusahaan menentukan prioritas peningkatan kualitas layanan. :contentReference[oaicite:2]{index=2}

---

## Problem Statement

Meskipun mayoritas pelanggan merupakan pelanggan loyal, tingkat kepuasan pelanggan masih belum optimal dan masih terdapat pelanggan yang berpotensi melakukan churn. Oleh karena itu, perusahaan perlu mengetahui layanan mana yang memiliki kesenjangan terbesar terhadap harapan pelanggan serta mengidentifikasi segmen pelanggan yang membutuhkan perhatian khusus agar strategi peningkatan layanan dapat dilakukan secara lebih efektif. :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4}

---

## Business Questions

1. Faktor layanan apa yang paling memengaruhi rendahnya tingkat kepuasan pelanggan?
2. Segmen pelanggan mana yang memiliki tingkat kepuasan paling rendah dan berisiko mengalami churn?
3. Bagaimana tingkat loyalitas pelanggan berdasarkan Net Promoter Score (NPS)?
4. Strategi apa yang perlu diprioritaskan perusahaan untuk meningkatkan kepuasan pelanggan dan mengurangi risiko churn? :contentReference[oaicite:5]{index=5}

---

## Method

Project ini dikerjakan melalui beberapa tahapan analisis sebagai berikut:

- **Data Understanding**
  - Memahami struktur dataset yang terdiri dari 100.000 data pelanggan.
  - Melakukan pengecekan tipe data, missing value, duplicate, dan statistik deskriptif untuk memahami karakteristik data. :contentReference[oaicite:6]{index=6} :contentReference[oaicite:7]{index=7}

- **Data Preparation**
  - Menghapus kolom yang tidak relevan.
  - Menyeragamkan format data kategorikal dengan menghilangkan spasi berlebih dan mengubah seluruh nilai menjadi huruf kecil.
  - Melakukan feature engineering untuk menghasilkan metrik bisnis seperti CSAT, NPS, Promoter, Passive, Detractor, Churn Risk Rate, dan Dissatisfied Customer. :contentReference[oaicite:8]{index=8}

- **Exploratory Data Analysis (EDA)**
  - Menganalisis hubungan antara kelas penerbangan, tipe perjalanan, loyalitas pelanggan, usia, dan tingkat kepuasan.
  - Mengidentifikasi layanan dengan penilaian terendah yang berpotensi meningkatkan risiko churn. :contentReference[oaicite:9]{index=9}

- **Dashboard Visualization**
  - Menyusun dashboard interaktif menggunakan Power BI untuk memvisualisasikan CSAT, NPS, Churn Risk Rate, Service Gap Analysis, serta perbandingan rating layanan antara pelanggan puas dan tidak puas. :contentReference[oaicite:10]{index=10}

---

## Business Recommendations

- Prioritaskan peningkatan kualitas **WiFi**, **Online Booking**, dan **Gate Location** karena memiliki service gap terbesar dibandingkan harapan pelanggan.
- Tingkatkan kualitas layanan pada **Eco Class**, karena memiliki tingkat kepuasan yang lebih rendah dibandingkan Business Class.
- Kumpulkan feedback pelanggan secara berkala setelah penerbangan untuk memantau perubahan tingkat kepuasan dan mengidentifikasi area yang perlu diperbaiki.
- Pertahankan kualitas layanan yang sudah memperoleh penilaian tinggi, seperti Inflight Service, Entertainment, dan Baggage Handling, agar loyalitas pelanggan tetap terjaga. :contentReference[oaicite:11]{index=11} :contentReference[oaicite:12]{index=12}

---

## Conclusion

Hasil analisis menunjukkan bahwa meskipun **81,71% pelanggan merupakan pelanggan loyal**, lebih dari **56% pelanggan masih berada pada kategori netral atau tidak puas**, sehingga terdapat peluang besar untuk meningkatkan kualitas layanan. Analisis juga menunjukkan bahwa **WiFi, Online Booking, dan Gate Location** merupakan layanan dengan kesenjangan terbesar terhadap harapan pelanggan, sementara pelanggan **Business Class** dan kelompok usia **46–60 tahun** memiliki tingkat kepuasan tertinggi. Dengan memprioritaskan perbaikan pada layanan yang memiliki service gap terbesar serta mempertahankan kualitas layanan yang sudah baik, perusahaan dapat meningkatkan kepuasan pelanggan, memperkuat loyalitas, dan mengurangi risiko customer churn. :contentReference[oaicite:13]{index=13} :contentReference[oaicite:14]{index=14}
