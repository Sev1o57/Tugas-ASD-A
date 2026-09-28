# ASD Project — Simulator Linked List

Proyek ini berisi dua cara menjalankan simulator linked list. Keduanya memiliki logika operasi yang sama: sisip depan, sisip belakang, sisip di index, hapus, cari, dan balik list.

## Cara Menjalankan (Flask + Python)

Ini cara utama untuk menjalankan proyek di localhost. Cukup butuh Python 3 yang sudah terpasang di komputer.

1. Buka terminal/CMD, masuk ke folder proyek:

   ```bash
   cd flask-app
   ```

2. (Opsional tapi disarankan) Buat dan aktifkan virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

   Di Windows gunakan:

   ```bash
   venv\Scripts\activate
   ```

3. Pasang dependensi:

   ```bash
   pip install -r requirements.txt
   ```

4. Jalankan aplikasinya:

   ```bash
   python app.py
   ```

5. Buka browser ke alamat berikut:

   **http://127.0.0.1:5000**

Untuk menghentikan aplikasi, tekan `Ctrl + C` di terminal.

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
