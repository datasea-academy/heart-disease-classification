# ❤️ Heart Disease Analysis (Data Processing & Visualization)

![Datasea Badge](https://img.shields.io/badge/Unit-Datasea_Labs-blue?style=for-the-badge&logo=github)
![Division Badge](https://img.shields.io/badge/Division-MIDTECH-orange?style=for-the-badge)
![Batch Badge](https://img.shields.io/badge/Batch-1_2025-success?style=for-the-badge)

> **Project Eksanta Data Science**
> Repository ini berisi tugas analisis data medis dan visualisasi untuk acara **Eksanta**, disusun oleh **Kelompok 2 (Divisi MIDTECH)**.

---

## 👥 Anggota Tim (Kelompok 2)

| Nama Anggota | NIM | Username GitHub |
| :--- | :--- | :--- |
| **Rahma Aulia Azzahra Laeho** | 5251811012 | [@username](https://github.com/username) |
| **Ikhwan Aji Darmawan** | 5251811003 | [@username](https://github.com/username) |
| **Gracia Degdouva Imanuela** | 5251811009 | [@username](https://github.com/username) |
| **Roma Wijaya** | 5251811022 | [@username](https://github.com/username) |
| **Katrin Hamka Amrullah** | 5251811025 | [@username](https://github.com/username) |
| **Faa’iza Rahmadhani Khairunnisa** | 5251811010 | [@username](https://github.com/username) |

---

## 📖 Latar Belakang
Penyakit jantung kardiovaskular adalah salah satu penyebab kematian tertinggi. Sebelum melangkah ke tahap prediksi, sangat penting untuk memastikan data klinis yang tersedia bersih, terstandarisasi, dan dipahami polanya. Project ini berfokus pada teknik pemrosesan data (Data Engineering) dan eksplorasi visual.

### 🎯 Tujuan Analisis (Objectives)
Project ini memiliki 4 tahapan utama:

1.  **Data Cleaning:** Membersihkan dataset dari *missing values* (data kosong), menghapus duplikat, dan mengoreksi tipe data yang tidak sesuai standar medis.
2.  **Data Normalization:** Melakukan penyamaan skala data (*Scaling*) pada fitur numerik (seperti Usia, Kolesterol, Tekanan Darah) agar memiliki rentang nilai yang seragam (0-1 atau Standar Deviasi).
3.  **Visualization:** Membuat representasi grafis untuk melihat distribusi pasien (Sehat vs Sakit) dan membandingkan variabel klinis.
4.  **Interpretation:** Menerjemahkan hasil visualisasi menjadi wawasan (*insight*) medis yang dapat dipahami, serta menyimpulkan faktor apa yang paling dominan pada pasien penyakit jantung.

---

## 💾 Tentang Dataset
Dataset ini berisi parameter medis pasien:
* **Sumber:** [Kaggle - Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
* **Target:** `target` (1 = Sakit Jantung, 0 = Sehat).
* **Fitur Utama:** `age`, `sex`, `cp` (Nyeri Dada), `chol` (Kolesterol), `trestbps` (Tekanan Darah).

---

## 📂 Struktur Folder

```text
├── 📂 data/
│   ├── 📂 raw/            # Dataset asli (heart_disease.csv)
│   └── 📂 processed/      # Data bersih yang sudah dinormalisasi
├── 📂 notebooks/
│   ├── 01_data_cleaning.ipynb       # Proses pembersihan & handling missing values
│   ├── 02_data_normalization.ipynb  # Proses scaling/normalisasi data
│   └── 03_visualization_insight.ipynb # Visualisasi & Interpretasi hasil
├── 📄 .gitignore          # File sampah sistem
├── 📄 README.md           # Dokumentasi project
└── 📄 requirements.txt    # Library Python