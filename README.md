# 🌍 Land Use Land Cover (LULC) Classification in IKN using Random Forest and SVM on Google Earth Engine

Repositori ini berisi kode sumber dan **Jupyter Notebook** untuk perbandingan algoritma Random Forest & SVM untuk klasifikasi penutup lahan (*land cover*) di wilayah **Ibu Kota Nusantara (IKN)** menggunakan **citra Sentinel-2** pada platform **Google Earth Engine (GEE)**.

Alur kerja ini mencakup:
- Pra-pemrosesan citra **Sentinel-2 Level-2A**.
- Definisi data pelatihan (*training*) dan validasi.
- Implementasi *classifier* **Random Forest** dan **SVM**.
- Pembuatan dan ekspor peta klasifikasi penutup lahan.

---

## 🚀 Jalankan Notebook di Google Colab

Anda dapat langsung membuka dan menjalankan *notebook* ini di Google Colab menggunakan pintasan di bawah ini tanpa perlu instalasi lokal:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/denshanif/lulc_ikn/blob/main/lulc_ikn.ipynb)

---

## 🧠 Persyaratan (Requirements)

Proyek ini memanfaatkan **Google Earth Engine (GEE)** melalui **Earth Engine Python API** dan pustaka **geemap** untuk visualisasi.
