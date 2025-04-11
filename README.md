# Proyek Analisis Sentimen Ulasan ChatGPT

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pengguna mengenai ChatGPT. Proses dimulai dari scraping data, preprocessing, pelatihan model, hingga evaluasi performa model analisis sentimen.

## Struktur Proyek

```
submission proyek analisis sentimen/
├── kode_scraping.ipynb      # Notebook untuk scraping ulasan dari sumber online
├── pelatihan_model.ipynb    # Notebook untuk pelatihan dan evaluasi model
├── ulasan_chatgpt.csv       # Dataset ulasan yang telah dikumpulkan
└── requirements.txt         # Dependensi Python yang dibutuhkan
```

## Cara Menjalankan Proyek

1. **Clone repositori ini:**

```bash
git clone https://github.com/Fina2404/Submission-Proyek-Analisis-Sentimen.git
cd Submission-Proyek-Analisis-Sentimen
```

2. **Install semua dependensi:**

```bash
pip install -r requirements.txt
```

3. **Jalankan notebook scraping:**

```bash
jupyter notebook kode_scraping.ipynb
```

4. **Jalankan notebook pelatihan model:**

```bash
jupyter notebook pelatihan_model.ipynb
```

## Hasil Akhir

Model analisis sentimen yang dilatih dapat mengklasifikasikan ulasan pengguna menjadi tiga kategori:
- Positif
- Negatif
- Netral
