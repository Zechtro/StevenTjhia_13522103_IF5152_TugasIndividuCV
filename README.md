# Computer Vision: Image Filtering, Edge Detection & Sampling, Feature/Interest Points, dan Camera Geometry & Calibration

Nama    : Steven Tjhia

NIM     : 13522103

Kelas   : K01

### I. Inisiasi Virtual Environment (Windows)

1. Membuat Virtual Environment 

    `python -m venv .venv`

2. Aktivasi Virtual Environment

    `.\.venv\Scripts\activate`

3. Install Dependensi

    `pip install -r requirements.txt`


4. (di VSCode) Pilih Kernel Notebook sesuai dengan Virtual Environment yang telah diaktifkan


### II. Run

1. Run notebook (atau tinggal lihat saja outputnya karena sama saja)


### Ringkasan Fitur Unik

1. Gaussian Filter: Terdapat proses pengubahan RGBA menjadi grayscale terlebih dahulu untuk Filter Median dan Sobel.


2. Median Filter: Penambahan noise salt & pepper pada raw image untuk median filter.

3. Median Filter: Penggunaan kernel Disk untuk Median Filter

4. Edge Detection: Dilakukan konversi dari RGBA pada gambar pribadi menjadi Grayscale.

5. Feature Points: Menampilkan marking feature point beserta dengan jumlahnya.

6. Geometry and Calibration: Simulasi dengan objek 3D sederhana berupa kubus.

7. Geometry and Calibration: Visualisasi interaktif 3D untuk memperjelas simulasi.

8. Geometry and Calibration: Adanya penambahan noise pada hasil proyeksi 2D untuk dilihat hasilnya ketika diproyeksikan kembali ke ruang 3D.