# Prorek Akhir Submission Proyek Klasifikasi Gambar

Proyek ini adalah bagian dari [Machine Learning Path Dicoding](https://www.dicoding.com/learningpaths/30). Proyek ini bertujuan untuk membuat model klasifikasi gambar yang mampu mengenali jenis sampah menggunakan teknik pembelajaran mesin.

## Deskripsi Proyek

Proyek ini menggunakan pendekatan Deep Learning dengan memanfaatkan model Convolutional Neural Network (CNN) dan arsitektur Xception. Tujuan utamanya adalah membangun model yang dapat mengklasifikasikan jenis sampah secara akurat untuk mendukung pengelolaan sampah yang lebih baik.

### Fitur Utama
- **Dataset**: Dataset yang digunakan dapat ditemukan di [Kaggle Garbage Classification Dataset](https://www.kaggle.com/datasets/mostafaabla/garbage-classification).
- **Model**: Dibangun menggunakan CNN dan Xception.
- **Format Model**:
  - `.h5` (HDF5)
  - `SavedModel` (TensorFlow)
  - `TF-Lite` (untuk perangkat mobile)
  - `TFJS` (untuk aplikasi berbasis web)
- **Jupyter Notebook**: Implementasi proyek tersedia di [Kaggle Notebook](https://www.kaggle.com/code/angguncaksono/submission-garbage-classification).

## Cara Menggunakan

1. **Instalasi Dependencies**
   Pastikan Anda telah menginstal dependencies yang diperlukan:
   ```bash
   pip install -r requirements.txt
   ```

2. **Pengunduhan Dataset**
   Unduh dataset dari [tautan ini](https://www.kaggle.com/datasets/mostafaabla/garbage-classification) dan letakkan di direktori yang sesuai.

3. **Training Model**
   Jalankan notebook untuk melatih model:
   ```bash
   jupyter notebook
   ```

4. **Ekspor Model**
   Model yang telah dilatih dapat diekspor ke berbagai format untuk digunakan di platform yang berbeda.

## Struktur Direktori

- `notebooks/`: Berisi file Jupyter Notebook untuk training dan evaluasi.
- `models/`: Berisi model yang disimpan dalam berbagai format.
- `data/`: Direktori tempat dataset disimpan.

## Teknologi yang Digunakan

- Python
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

## Kontribusi

Kontribusi sangat diterima! Jika Anda ingin berkontribusi, silakan fork repository ini, buat branch baru, dan ajukan pull request.

```bash
git clone https://github.com/alrescha79-cmd/garbage-classification.git
git checkout -b fitur-baru
```

## Author

Proyek ini dibuat oleh:
- **[Anggun Caksono](https://www.github.com/alrescha79-cmd)**

Jika Anda menemukan masalah, jangan ragu untuk membuka [issue baru](https://github.com/alrescha79-cmd/garbage-classification/issues).
