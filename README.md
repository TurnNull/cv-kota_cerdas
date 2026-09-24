# 🌆 Computer Vision untuk Sistem Informasi Kota Cerdas

Repositori ini berisi kumpulan tugas praktikum, eksperimen kode, dan proyek implementasi *Computer Vision* (CV) menggunakan **Python**. Fokus utama dari praktikum ini adalah penerapan pemrosesan citra digital untuk mendukung infrastruktur dan analisis data pada **Sistem Informasi Kota Cerdas (Smart City)**.

---

## 📌 Identitas Mahasiswa
* **Nama:** MUHAMMAD HUSAIN ALI RIDHA
* **Program Studi:** Sistem Informasi Kota Cerdas
* **Matakuliah:** Computer Vision Dalam Kota Cerdas
* **Kelas:** SIKC-7B

---

## 🛠️ Lingkungan Pengembangan (Environtment)
Untuk menjalankan kode-kode di repositori ini, pastikan Anda telah memasang dependensi berikut:

* **Bahasa Pemrograman:** Python 3.10.x [1]
* **Pustaka Utama (Libraries):**
  * `opencv-python` (Pemrosesan citra utama)
  * `numpy` (Komputasi matriks piksel)
  * `matplotlib` (Visualisasi histogram dan citra)

```bash
# Cara instalasi dependensi
pip install opencv-python numpy matplotlib
```

---

## 📂 Struktur Repositori & Daftar Praktikum

Proyek praktikum dibagi berdasarkan modul pengerjaan yang relevan dengan skenario Smart City:

### 📑 Modul 1: Penyiapan Lingkungan Kerja dan Operasi Dasar Citra Digital
*Persiapan lingkungan kerja Python terisolasi beserta pustaka Computer Vision yang diperlukan.*
* **Topik:** Persiapan Lingkungan Kerja Mahasiswa.
* **Fokus Analisis:** Membaca, menampilkan, dan menyimpan citra digital menggunakan OpenCV. Laporan praktikum yang memuat kode, keluaran, dan pembahasan singkat.
* **Berkas Kode:** [Praktikum-1](https://github.com/TurnNull/cv-kota_cerdas/tree/praktikum-1)

### 📑 Modul 2: Pembentukan Citra dan Penapisan Dasar
*Penerapan citra digital antar ruang warna RGB, aras keabuan, dan HSV menggunakan OpenCV.*
* **Topik:** Implementasi Prinsip Konvolusi dan Operasi Penapisan Citra.
* **Fokus Analisis:** Penggunaan filter *Mean*, *Gaussian*, dan *Median* untuk membersihkan derau.
* **Berkas Kode:** [Praktikum-2](https://github.com/TurnNull/cv-kota_cerdas/tree/praktikum-2)

### 📑 Modul 3: Perbaikan Kualitas Citra
*Penerapan prinsip kerja efektivitas algoritma Global Histogram Equalization (GHE) dan Contrast Limited Adaptive Histogram Equalization (CLAHE) dalam mempertahankan detail informasi citra digital.*
* **Topik:** *Implementasi Histogram Equalization Global*, *Contrast Limited Adaptive Histogram Equalization (CLAHE)*, Operasi Morfologi *Erosi*, *Dilasi*, *Opening*, dan *Closing* pada Citra Biner.
* **Berkas Kode:** [Praktikum-3](https://github.com/TurnNull/cv-kota_cerdas/tree/praktikum-3)

### 📑 Modul 4: Deteksi Tepi
*Penerapan konsep gradien citra sebagai dasar deteksi tepi*
* **Topik:** Implementasi Operator *Sobel*, *Prewitt*, *Laplacian*, serta Penerapan Algoritma *Canny* dan *Menala* Ambang Bawah dan Atas.  
* **Berkas Kode:** [Praktikum-4](https://github.com/TurnNull/cv-kota_cerdas/tree/praktikum-4)

---

<!-- ## 📊 Ringkasan Hasil Eksperimen Utama

### 1. Statistik Perbaikan Citra Malam (Modul 1)
Berdasarkan eksperimen pada citra simpang malam dengan derau Gaussian, didapatkan data kuantitatif sebagai berikut:

| Metode Perbaikan | Rata-rata (*Mean*) | Simpangan Baku (*Std Dev*) | Karakteristik Hasil |
| :--- | :---: | :---: | :--- |
| **Citra Asli** | *[Input Angka]* | *[Input Angka]* | Kontras rendah, gelap. |
| **Global Equalization** | 129.97 | 72.79 | *Over-exposed*, *noise* ikut membesar. |
| **CLAHE (clipLimit=2.0)**| 95.97 | 51.87 | Detail malam terjaga, *noise* diredam. |

### 2. Analisis Efektivitas Morfologi (Modul 2)
* **Opening:** Sangat efektif menghilangkan derau bintik putih terisolasi (*salt noise*) pada latar belakang hitam jalan raya karena melakukan erosi terlebih dahulu.
* **Closing:** Kurang efektif menurunkan jumlah komponen derau putih, namun sangat baik jika digunakan untuk menyambung marka jalan yang terputus atau menutup lubang hitam (*pepper noise*) pada objek gedung. -->

<!-- --- -->

## 🚀 Cara Menjalankan Kode

Karena kode tiap praktikum berada di *branch* yang berbeda, ikuti langkah berikut untuk menguji kode:

1. **Klon Repositori Utama:**
   ```bash
   git clone https://github.com/TurnNull/cv-kota_cerdas
   cd repo-anda
   ```

2. **Lihat Semua Branch yang Tersedia:**
   ```bash
   git branch -a
   ```

3. **Pindah ke Branch Praktikum Spesifik (Misal Modul 1):**
   ```bash
   git checkout praktikum-1
   ```

4. **Jalankan Program:**
   *(Pastikan dependensi seperti `opencv-python`, `numpy`, dan `matplotlib` sudah terpasang).*
   ```bash
   python main.ipynb
   ```


---
💡 *Catatan: Repositori ini dibuat untuk memenuhi tugas akademik mata kuliah Computer Vision Sistem Informasi Kota Cerdas.*
