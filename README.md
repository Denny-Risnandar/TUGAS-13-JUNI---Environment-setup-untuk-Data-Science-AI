## TUGAS-13-JUNI
**Environment-setup-untuk-Data-Science-AI** 
TUGAS 13 JUNI - Environment setup untuk Data Science/AI dengan:

**📚Anaconda**  
**📚Conda**  
**📚UV** 
---
**Nama** : Denny Risnandar  
**Batch** : 9  
**No. Absen** : 9.030.DB2025
---
kita kupas dulu apa itu python, anaconda, dan conda (bukan ular anaconda ya) 

Anaconda adalah sebuah paket distribusi bahasa pemrograman python dan R yang dilengkapi beberapa package dan tool tambahan untuk  keperluan komputasi ilmiah (scientific computing) seperti data science, machine learning, data processing skala luas, analisis prediksi dan lainnya.

Sedangkan Pyhton Adalah bahasa pemrograman tingkat tinggi yang dapat melakukan sejumlah instruksi multiguna secara langsung dengan metode orientasi obyek. Pyhton merupakan bahasa pemrograman yang paling mudah dipahami dan banyak digunakan untuk membangun berbagai  aplikasi serta pengolahan data 

lalu apa sih perbedaan antara Anaconda dengan Python 

Anaconda 
Package Manager : menyediakan conda sebagai package manager, 
Package Management : dependensi python dan non python,
Kegunaan : Pengolahan data science dan machine learning.

Python
Package Manager : Menyedian PIP sebagai Package manager nya,
Package Management : Dependensi python saja,
Kegunaan : Membangun/mengembangkan berbagai aplikasi.

Jadi Anaconda ditulis menggunakan Bahasa python sehingga dapat mengembangkan berbagai aplikasi pengolahan data science, pengembangan web, analisis prediktif, pemrograman jaringan dan lain lain.

Analogi Singkat:
Python saja = seperti mesin mobil.
Anaconda = seperti mobil lengkap siap jalan (sudah ada mesin + roda + bensin).

Adapun keuntungan menggunakan aplikasi anaconda diantaranya Kemudahan membangun berbagai aplikasi komputasi ilmiah seperti machine learning, dan pengolahan data science skala luas, dapat mengetahui posisi eror pada script dengan fitur interactive console yang tersedia pada spyder, dan memudahkan ekspor data hasil visualisasi.

Kemudian di dalam anaconda terdapat istilah Conda, apa itu conda :
Conda adalah manajer paket dan lingkungan yang disertakan dalam Anaconda. Conda memungkinkan pengguna untuk mengelola paket dan lingkungan secara efisien, menghindari konflik dependensi, dan memastikan konsistensi proyek.

---
## 1. Cara Instalasi Anaconda

***Download Installer Anaconda**

Apa: Anaconda adalah distribusi Python yang menyertakan ratusan paket siap pakai, ideal untuk analisis data dan komputasi ilmiah.

Kenapa : Mengunduh Anaconda memberikan akses ke alat-alat penting untuk Data Science tanpa instalasi paket manual. Ini memastikan kompatibilitas dan menghemat waktu.
   
   Langkah-langkah:
   
    - Googling dulu dan cari aplikasi anaconda, atau bisa buka pada link https://www.anaconda.com/products/distribution
    - Sign Up, (verifikasi email) dan ikuti perintah selanjutnya (mudahlah)
    - Pilih versi sesuai OS Anda (Windows/macOS/Linux), pilih yang python 3.12
    - Klik tombol Download (lumayan besar hampir 950 mb)
    - berikut tampilan nya.

![image](https://github.com/Denny-Risnandar/TUGAS-13-JUNI---Environment-setup-untuk-Data-Science-AI/blob/main/ANACONDA%202.png)

Do's 
- Download dari situs resmi Anaconda
- Simpan file exe installer di folder yang mudah diakses dan aman (misal driver D)
Don'ts:
- Jangan download dari sumber tidak resmi
- Jangan simpan di folder system**********

---

 ## 2. Cara instalasi Anaconda ##

Setelah berhasil download file tersebut, gaskeun kita instal aja di pc kalian.

Apa: Instalasi file yaitu menjalankan file penginstal dan mengatur konfigurasi sistem pada komputer.

Kenapa: Instalasi yang benar memungkinkan Anaconda terintegrasi dengan sistem, sehingga perintah Conda dan Python dapat diakses dari terminal.

Langkah-langkah:

1. Klik dua kali Anaconda3-2024.10-1-Windows-x86_64.exe.
2. Klik "Next" pada layar sambutan.
3. Setujui syarat lisensi.
4. Pilih "Just Me (recommended)".
5. Gunakan lokasi default (C:\Users\NAMA_ANDA\anaconda3).
6. Centang:
✓ Tambahkan Anaconda3 ke PATH.
✓ Jadikan Anaconda3 sebagai Python 3.12 default.
7. Klik "Install" dan tunggu selesai.

Do and Don'ts:
- Do: Centang opsi untuk menambahkan Anaconda ke PATH.
- Don't: Jangan ubah lokasi instalasi default tanpa alasan kuat.

![image](https://github.com/Denny-Risnandar/TUGAS-13-JUNI---Environment-setup-untuk-Data-Science-AI/blob/main/instal%20anaconda%202.png)

---
## 3. Verifikasi Keberhasilan Instalasi

Apa: Verifikasi memastikan Anaconda terinstal dan dapat diakses.

Kenapa: Ini mendeteksi masalah seperti PATH yang salah, memungkinkan perbaikan dini.

Do and Don'ts:
- Do: Buka terminal baru untuk menerapkan perubahan PATH.
- Don't: Jangan abaikan pesan kesalahan.

Langkah-langkah:

- Buka Command Prompt.
- Ketik dan eksekusi:

```
conda --version
- Output = conda 24.1.0
menunjukkan keberhasilan.
- Keberhasilan: Nomor versi mengonfirmasi instalasi berhasil.
```
---
## 4. Konfigurasi PATH

Apa: PATH memberi tahu sistem operasi lokasi program berada seperti Conda dan Python.

Kenapa: Tanpa PATH yang benar, perintah Anaconda tidak dapat dijalankan dari terminal.

Do and Don'ts:
- Do: Verifikasi semua jalur ditambahkan.
- Don't: Jangan hapus entri PATH lain.

Langkah-langkah:

1. Tekan Windows + R, ketik sysdm.cpl, tekan Enter.
2. Pergi ke tab "Advanced", klik "Environment Variables".
3. Pilih "Path" di "System variables", klik "Edit".
4. Tambahkan (ganti NAMA_ANDA):

hasil pengecekan akan menampilkan sebagai berikut :
```
C:\Users\Denny\anaconda3
C:\Users\Denny\anaconda3\Library\mingw-w64\bin
C:\Users\Denny\anaconda3\Library\usr\bin
C:\Users\Denny\anaconda3\Library\bin
C:\Users\Denny\anaconda3\Scripts
```






 
