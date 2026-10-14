# 📊 Case Study: Social Media Engagement Analysis

Análisis performa konten media sosial berbasis data untuk mengevaluasi efektivitas konten, mengidentifikasi pola interaksi audiens, serta memberikan insight strategis bagi tim pemasaran konten.

---

## 📌 Project Overview

Proyek ini bertujuan untuk mengukur dan menganalisis performa beberapa konten media sosial menggunakan dataset metrik engagemen (*reach*, *impression*, *likes*, *comments*, *shares*, *saves*, dan *clicks*). 

Dengan menghitung metrik utama seperti **Engagement Rate (ER)**, **Interaction-per-Reach (IPR)**, **Interaction-per-Impression (IPI)**, dan **Click-Through Rate (CTR)**, analisis ini menyajikan gambaran kuantitatif tentang konten mana yang paling efektif serta faktor-faktor yang mendorong keterlibatan pengguna.

---

## 🎯 Objectives

1. **Memahami Konsep Engagement**: Menjelaskan relevansi metrik keterlibatan dalam konteks *Social Media Analytics*.
2. **Identifikasi Metrik Relevan**: Menentukan minimal 4 metrik engagemen kunci untuk evaluasi konten.
3. **Kalkulasi Metrik**: Menghitung metrik engagemen secara presisi beserta penyajian rumus dan langkah perhitungannya.
4. **Analisis Perbandingan**: Membandingkan performa antar konten berbasis angka secara rasional.
5. **Interpretasi & Insight**: Menghasilkan insight deskriptif mengenai efektivitas format konten dan pola interaksi pengguna.
6. **Refleksi Strategis**: Menjawab pertanyaan reflektif mengenai pentingnya analisis engagemen dan batasan metrik tertentu.

---

## 📁 Repository Structure

```text
.
├── data/
│   └── Social_Media_Engagement_Dataset.xlsx   # Dataset mentah yang dianalisis
├── notebooks/
│   └── Social_Media_Analytics.ipynb           # Python Notebook / Colab Script
├── dashboards/
│   └── Social_Media_Analytics.pbix            # Power BI Interactive Dashboard
├── docs/
│   ├── Assignment_Social_Media_Analytics.pdf  # Laporan Analisis Lengkap (PDF)
│   └── Reflection_Questions.pdf               # Jawaban Pertanyaan Refleksi (PDF)
└── README.md                                  # Dokumentasi Portofolio
```
---
## 🛠️ Tools & Technologies Used

- **Python / Google Colaboratory**: Pemrosesan data, agregasi, dan perhitungan metrik.
- **Power BI**: Visualisasi data interaktif dan pembuatan dashboard performa konten.
- **Google Docs / PDF / PPTX**: Penyusunan laporan ringkas dan dokumentasi analisis.

---

## 📐 Engagement Metrics & Formulas

Berikut adalah metrik utama yang digunakan beserta rumusnya:

| Metrik Engagement | Rumus / Formula | Deskripsi & Tujuan |
| :--- | :--- | :--- |
| **Engagement Rate (ER)** | `(Total Interaksi / Total Reach) * 100%` | Mengukur proporsi unik pengguna yang berinteraksi dari total audiens yang dijangkau. |
| **Interaction-per-Reach (IPR)** | `(Likes + Comments + Shares + Saves) / Reach` | Mengukur intensitas interaksi organik per individu yang dijangkau. |
| **Interaction-per-Impression (IPI)** | `(Likes + Comments + Shares + Saves) / Impressions` | Mengukur efisiensi interaksi dibanding berapa kali konten tampil di layar. |
| **Click-Through Rate (CTR)** | `(Clicks / Impressions) * 100%` | Mengukur tingkat konversi tampilan konten menjadi tindakan (*action*) berupa klik. |

---

## 📈 Key Findings & Insights Summary

1. **Top Performing Content**: Konten berformat *Carousel/Video Reel* mencatatkan **Engagement Rate (ER)** tinggi, didorong oleh tingginya jumlah *shares* dan *saves*.
2. **Pola Interaksi Audiens**: Konten edukasi berbasis *visual/carousel* secara konsisten menghasilkan *interaction-per-reach* (IPR) yang lebih tinggi dibandingkan postingan gambar tunggal yang cenderung lebih dominan pada *likes* pasif.
3. **Penyebab Utama**: Tingginya nilai simpan (*saves*) dan bagikan (*shares*) mengindikasikan bahwa audiens menganggap informasi dalam konten tersebut memiliki nilai guna (*utility*) tinggi untuk dirujuk kembali di masa mendatang.
4. **Evaluasi Reach vs. Engagement**: Ditemukan beberapa konten dengan *reach* tinggi namun *engagement rate* rendah. Hal ini menunjukkan bahwa judul/thumbnail konten mampu menarik jangkauan algoritma, namun isi materi kurang relevan atau kurang memicu aksi dari audiens.

---

## 💭 Reflection Questions Summary

### 1. Mengapa engagement dianggap indikator penting, dan kapan Engagement Rate dapat menyesatkan?
Engagement menunjukkan sejauh mana konten mampu membangun hubungan emosional dan ketertarikan aktif audiens, bukan sekadar lewat di layar (*passive impression*). Namun, ER bisa menyesatkan apabila:
- **Ukuran Sampel/Reach Sangat Kecil**: Konten dengan 10 reach dan 5 interaksi memiliki ER 50%, tetapi tidak berarti lebih sukses daripada konten dengan 100.000 reach dan 5.000 interaksi (ER 5%).
- **Interaksi Negatif**: ER tidak membedakan *sentiment* (misal: komentar negatif/kritikan masif tetap dihitung sebagai interaksi).

### 2. Bagaimana perbandingan antar konten membantu menentukan strategi berikutnya?
Dengan membandingkan metrik secara kualitatif dan kuantitatif antar format/topik, tim konten dapat mengidentifikasi *winning formula* (format konten mana yang efisien memicu pendaftaran/klik, mana yang cocok untuk *awareness*). Hal ini membantu alokasi sumber daya pembuatan konten menjadi lebih fokus dan terukur.

### 3. Interpretasi konten dengan Reach tinggi tetapi Engagement rendah:
Indikasi awal menunjukkan adanya **ketidaksesuaian (*mismatch*) antara daya tarik awal dengan relevansi isi konten**. *Thumbnail* atau *headline* berhasil memicu algoritma (distribusi luas), tetapi audiens tidak merasa tertarik untuk menyukai, mengomentari, atau membagikan. Hal ini perlu diwaspadai agar audiens tidak menganggap konten sebagai *clickbait*, yang dalam jangka panjang menurunkan kredibilitas akun.

---

## 📸 Dashboard Preview
 <img width="866" height="489" alt="social-media-analytics-dashboard" src="https://github.com/user-attachments/assets/279f8007-36ab-4557-b068-35d3fd6e48bb" />


---

## 👤 Author

- **Nama**: Muhammad Rizky Ginanjar
- **Role**: Data Analyst
- **LinkedIn**: [Muhammad Rizky Ginanjar](https://www.linkedin.com/in/rizkyginan/)
