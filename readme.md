# 🐾 Proyek Klasifikasi Gambar: [ANIMALS-10](https://huggingface.co/datasets/dgrnd4/animals-10)

## 📌 Deskripsi
Proyek ini merupakan implementasi model deep learning untuk melakukan **klasifikasi gambar hewan** dari dataset **Animals-10** menggunakan arsitektur **MobileNetV2**. Proyek mencakup proses mulai dari persiapan data, pelatihan model, evaluasi, hingga konversi ke format **TensorFlow Lite** dan **TensorFlow.js**, serta fitur **prediksi gambar interaktif**.

## 👤 Informasi
- **Nama:** Bagus Angkasawan Sumantri Putra  
- **Email:** bagusasp01@gmail.com  
- **ID Dicoding:** bagusangkasawan  

## 🧰 Library yang Digunakan
- TensorFlow (dan Keras)
- scikit-learn
- numpy, pandas
- matplotlib
- Pillow
- tensorflowjs
- tkinter (untuk pemilihan file gambar)

## 📂 Struktur Proyek
- `saved_model/` : Model hasil pelatihan (SavedModel)
- `tflite/` : Model dalam format `.tflite` + label
- `tfjs_model/` : Model dalam format TensorFlow.js

## 🏗️ Langkah Utama
1. **Preprocessing** dataset gambar dan membaginya menjadi train/val/test.
2. **Pelatihan model** klasifikasi gambar dengan MobileNetV2.
3. **Evaluasi dan visualisasi** akurasi dan loss model.
4. **Konversi model** ke berbagai format: SavedModel, TFLite, dan TFJS.
5. **Prediksi gambar interaktif** menggunakan GUI sederhana (Tkinter) dan visualisasi hasil klasifikasi.

## 📸 Demo Prediksi
Setelah model dikonversi ke `.tflite`, pengguna dapat memuat gambar dari perangkatnya, dan sistem akan:
- Menampilkan gambar tersebut
- Menunjukkan label hasil klasifikasi
