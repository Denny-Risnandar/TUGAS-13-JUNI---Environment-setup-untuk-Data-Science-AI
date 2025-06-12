## TUGAS 13 JUNI
**Environment setup untuk Data Science AI** 

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
- Jangan simpan di folder system

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
```
Tampilan tersebut merupakan nomor versi menunjukkan keberhasilan proses instalasi.

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
---
## 5. Aplikasi / Environment Conda
---
A. Membuat Environment Conda
- Apa: Lingkungan Conda adalah ruang terisolasi untuk Python dan paket proyek.
- Kenapa: Isolasi mencegah konflik versi paket, memastikan stabilitas.

Do and Don'ts:
- Do: Beri nama lingkungan yang relevan.
- Don't: Jangan buat di direktori tidak terkait.

Langkah-langkah:
- Di terminal VS Code (Ctrl+`), ketik: conda create -p venv python=3.12
- Ketik y saat diminta.

hasil akan menampilkan sbb :
```
C:\Users\Denny>conda create -p venv python=3.12
Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\Denny\venv

  added / updated specs:
    - python=3.12


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    expat-2.7.1                |       h8ddb27b_0         259 KB
    pip-25.1                   |     pyhc872135_2         1.3 MB
    python-3.12.11             |       h716150d_0        16.5 MB
    setuptools-78.1.1          |  py312haa95532_0         2.2 MB
    tk-8.6.14                  |       h5e9d12e_1         3.5 MB
    tzdata-2025b               |       h04d1e81_0         116 KB
    vc-14.42                   |       haa95532_5          11 KB
    vs2015_runtime-14.42.34433 |       hbfb602d_5         1.2 MB
    wheel-0.45.1               |  py312haa95532_0         177 KB
    xz-5.6.4                   |       h4754444_1         280 KB
    ------------------------------------------------------------
                                           Total:        25.5 MB

The following NEW packages will be INSTALLED:

  bzip2              pkgs/main/win-64::bzip2-1.0.8-h2bbff1b_6
  ca-certificates    pkgs/main/win-64::ca-certificates-2025.2.25-haa95532_0
  expat              pkgs/main/win-64::expat-2.7.1-h8ddb27b_0
  libffi             pkgs/main/win-64::libffi-3.4.4-hd77b12b_1
  openssl            pkgs/main/win-64::openssl-3.0.16-h3f729d1_0
  pip                pkgs/main/noarch::pip-25.1-pyhc872135_2
  python             pkgs/main/win-64::python-3.12.11-h716150d_0
  setuptools         pkgs/main/win-64::setuptools-78.1.1-py312haa95532_0
  sqlite             pkgs/main/win-64::sqlite-3.45.3-h2bbff1b_0
  tk                 pkgs/main/win-64::tk-8.6.14-h5e9d12e_1
  tzdata             pkgs/main/noarch::tzdata-2025b-h04d1e81_0
  vc                 pkgs/main/win-64::vc-14.42-haa95532_5
  vs2015_runtime     pkgs/main/win-64::vs2015_runtime-14.42.34433-hbfb602d_5
  wheel              pkgs/main/win-64::wheel-0.45.1-py312haa95532_0
  xz                 pkgs/main/win-64::xz-5.6.4-h4754444_1
  zlib               pkgs/main/win-64::zlib-1.2.13-h8cc25b3_1


Proceed ([y]/n)? y


Downloading and Extracting Packages:

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate C:\Users\Denny\venv
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```
---
B. Mengaktifkan Environment Conda

- Apa: Aktivasi menggunakan Python dan paket dari lingkungan Conda.
- Kenapa: Ini memastikan perintah menggunakan lingkungan proyek, bukan dasar.

Do and Don'ts:
- Do: Periksa prompt untuk konfirmasi aktivasi.
- Don't: Jangan jalankan perintah sebelum aktif.

Langkah-langkah:
- Ketik:
conda activate venv/

```
C:\Users\Denny>conda activate venv/

(C:\Users\Denny\venv) C:\Users\Denny>
```





 
