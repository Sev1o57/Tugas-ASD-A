# Proyek Mata Kuliah ASD — Simulator Linked List

Selamat datang di repositori Proyek Algoritma dan Struktur Data (ASD). Proyek ini merupakan sebuah Simulator Linked List yang bertujuan untuk memvisualisasikan cara kerja struktur data *linked list*. Terdapat enam operasi utama yang didukung dalam simulator ini, yaitu: sisip depan, sisip belakang, sisip pada indeks tertentu, hapus, cari, dan balik urutan (*reverse*).

Aplikasi ini dapat dijalankan menggunakan dua pendekatan antarmuka yang berbeda. Berikut adalah panduan lengkap untuk menjalankan proyek ini di komputer lokal (localhost).

---

## Persiapan Awal (Penting)
Dikarenakan adanya batasan ukuran unggahan file yang utuh ke GitHub, seluruh file sumber (*source code*) proyek ini dikompresi menjadi format `.zip`. 

Sebelum mulai menjalankan aplikasi, **mohon pastikan Bapak/Ibu telah mengunduh file `.zip` tersebut dan mengekstraknya (unzip)** ke dalam satu folder di komputer. Setelah diekstrak, silakan ikuti salah satu dari dua cara di bawah ini untuk mencoba simulator.

---

## 1. Cara Menjalankan Backend (Flask + Python)
Metode ini adalah cara utama untuk menjalankan proyek. Pastikan Python 3 sudah terpasang di komputer yang digunakan.

1. Buka Terminal atau Command Prompt (CMD), lalu arahkan direktori ke dalam folder `flask-app` yang ada di folder hasil ekstrak:
   ```bash
   cd flask-app
   ```

2. (Opsional namun sangat disarankan) Buat dan aktifkan virtual environment agar dependensi proyek tidak bercampur dengan sistem utama :
    ```bash
   python -m venv venv
   ```

3. Instal seluruh dependensi dan pustaka yang dibutuhkan:
    ```bash
   pip install -r requirements.txt
   ```

4. Jalankan aplikasi server:
    ```bash
   python app.py
   ```

5. Buka web browser dan akses alamat berikut:
http://127.0.0.1:5000
(Note : Press Ctrl + c To Stop the server).

## Cara Menjalankan (Aplikasi Web React)

Cara ini butuh Node.js (versi 18 atau lebih baru) yang sudah terpasang di komputer.

1. Buka terminal/CMD di folder utama proyek (bukan folder `flask-app`).

2. Pasang dependensi:

   ```bash
   npm install
   ```

3. Jalankan aplikasinya:

   ```bash
   npm run dev
   ```

4. Buka browser ke alamat yang muncul di terminal, biasanya:

   **http://localhost:5173**

5. Setelah halaman terbuka, klik tombol **Continue as Guest** untuk masuk tanpa perlu akun, lalu simulator siap digunakan.

   Terima kasih banyak atas waktu dan perhatian Bapak.
