Selamat datang di repositori Proyek Algoritma dan Struktur Data (ASD). Proyek ini merupakan sebuah Simulator Linked List yang bertujuan untuk memvisualisasikan cara kerja struktur data linked list. Terdapat enam operasi utama yang didukung dalam simulator ini, yaitu: sisip depan, sisip belakang, sisip pada indeks tertentu, hapus, cari, dan balik urutan (reverse).

Aplikasi ini dapat dijalankan menggunakan dua pendekatan antarmuka yang berbeda. Berikut adalah panduan lengkap untuk menjalankan proyek ini di komputer lokal (localhost).

Persiapan Awal (Penting)
Dikarenakan adanya batasan ukuran unggahan file yang utuh ke GitHub, seluruh file sumber (source code) proyek ini dikompresi menjadi format .zip.

Sebelum mulai menjalankan aplikasi, mohon pastikan Bapak/Ibu telah mengunduh file .zip tersebut dan mengekstraknya (unzip) ke dalam satu folder di komputer. Setelah diekstrak, silakan ikuti salah satu dari dua cara di bawah ini untuk mencoba simulator.

1. Cara Menjalankan Backend (Flask + Python)
Metode ini adalah cara utama untuk menjalankan proyek. Pastikan Python 3 sudah terpasang di komputer yang digunakan.

Buka Terminal atau Command Prompt (CMD), lalu arahkan direktori ke dalam folder flask-app yang ada di folder hasil ekstrak:

Bash
cd flask-app
(Opsional namun sangat disarankan) Buat dan aktifkan virtual environment agar dependensi proyek tidak bercampur dengan sistem utama:

Bash
python -m venv venv
Cara aktivasi:

Untuk pengguna Mac/Linux: source venv/bin/activate

Untuk pengguna Windows: .\venv\Scripts\activate

Instal seluruh dependensi dan pustaka yang dibutuhkan:

Bash
pip install -r requirements.txt
Jalankan aplikasi server:

Bash
python app.py
Buka web browser dan akses alamat berikut:
http://127.0.0.1:5000

(Catatan: Untuk menghentikan server, silakan tekan Ctrl + C pada terminal).

2. Cara Menjalankan Frontend (Aplikasi Web React)
Metode ini digunakan untuk menjalankan antarmuka berbasis React. Pastikan Node.js (versi 18 atau lebih baru) sudah terpasang di komputer.

Buka Terminal atau CMD baru, lalu arahkan ke folder utama hasil ekstrak proyek (bukan di dalam folder flask-app).

Instal dependensi Node.js yang dibutuhkan:

Bash
npm install
Jalankan aplikasi antarmuka:

Bash
npm run dev
Buka web browser dan akses tautan lokal yang muncul di terminal (umumnya berada di alamat ini):
http://localhost:5173

Setelah halaman termuat, silakan klik tombol "Continue as Guest" untuk masuk dan menggunakan simulator tanpa perlu membuat akun.

Terima kasih banyak atas waktu dan perhatian Bapak/Ibu.
