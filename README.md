# Sistem Prediksi Rawan Banjir **Revo Pratama G1A022058**

Proyek ini merupakan implementasi sistem prediksi wilayah rawan banjir menggunakan model machine learning berbasis Random Forest dan visualisasi interaktif dengan Folium.

## Fitur

- Preprocessing dan analisis dataset terkait banjir
- Training model prediksi menggunakan Random Forest Classifier
- Evaluasi model dengan metrik klasifikasi
- Visualisasi hasil prediksi pada peta interaktif (Folium)

## Instalasi

Gunakan Python 3.8+ dan pastikan Anda telah menginstal dependensi berikut:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn folium
```

Jika menggunakan Google Colab, Anda tidak perlu instalasi tambahan.

## Cara Penggunaan

1. Jalankan notebook `sistem_prediksi_rawan_banjir.ipynb` di Google Colab.
2. Upload dataset CSV melalui cell yang berisi `files.upload()`.
3. Sistem akan:
   - Membersihkan dan menyiapkan data
   - Melatih model klasifikasi
   - Menampilkan evaluasi performa
   - Memetakan hasil prediksi dalam peta interaktif

## Contoh Output

- **Confusion Matrix & Classification Report**
- **Peta Interaktif** wilayah rawan banjir berdasarkan hasil prediksi

## Struktur Notebook

- Import Library
- Upload & Praproses Data
- Pelatihan Model (Random Forest)
- Evaluasi Model
- Visualisasi Interaktif (Folium)
