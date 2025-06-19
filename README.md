# Tumor_Otak
# 🧠 Klasifikasi Gambar Tumor Otak dengan CNN

Proyek ini bertujuan untuk mengembangkan model Convolutional Neural Network (CNN) untuk mengklasifikasikan gambar MRI otak guna mendeteksi keberadaan tumor.

## ⬇️ Dataset

Dataset yang digunakan dalam proyek ini diunduh dari Kaggle: [Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection).

## 📚 Library yang Digunakan

*   **PIL (Pillow)**: Untuk pemrosesan gambar.
*   **Os**: Untuk berinteraksi dengan sistem operasi (misalnya, membaca file).
*   **NumPy**: Untuk operasi array numerik.
*   **TensorFlow & Keras**: Untuk membangun dan melatih model CNN.
*   **OpenCV (cv2)**: Untuk operasi gambar (digunakan untuk resizing).
*   **Matplotlib**: Untuk visualisasi data dan gambar.
*   **Sklearn**: Untuk membagi dataset.

## 🚀 Cara Menjalankan Notebook

1.  **Unduh Dataset**: Jalankan sel yang mengunduh dataset dari Kaggle.
2.  **Import Library**: Jalankan sel untuk mengimpor semua library yang diperlukan.
3.  **Import dan Pra-pemrosesan Data**: Muat gambar dan lakukan pra-pemrosesan seperti resizing dan normalisasi.
4.  **Labeling**: Berikan label pada gambar (tumor/tidak ada tumor).
5.  **Split Data**: Bagi dataset menjadi set pelatihan, validasi, dan pengujian.
6.  **Training Model**: Definisikan dan latih model CNN.
7.  **Evaluasi Model**: Evaluasi kinerja model menggunakan set pengujian.
8.  **Test Model**: Uji model dengan gambar baru.

## ✨ Hasil

Notebook ini akan menampilkan:

*   Visualisasi contoh gambar dari dataset.
*   Ringkasan arsitektur model CNN.
*   Plot akurasi dan loss selama pelatihan.
*   Hasil evaluasi model pada set pengujian.
*   Prediksi pada gambar yang diunggah.

## 📝 Catatan

Pastikan Anda memiliki akses ke Kaggle API atau mengunduh dataset secara manual ke lingkungan kerja Anda.

---

Semoga notebook ini bermanfaat!
