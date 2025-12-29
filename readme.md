Pangayoman - Sahabat Siswa 🛡️

Aplikasi web sederhana untuk layanan Bimbingan Konseling (BK) di sekolah. Aplikasi ini dirancang sebagai Single File Application yang berjalan sepenuhnya di browser tanpa perlu instalasi backend server.

🌟 Fitur Utama

1. Portal Siswa

🚨 Tombol SOS Darurat: Mengirim pesan template darurat langsung ke WhatsApp Guru BK.

📝 Lapor Masalah: Form untuk melaporkan perundungan (bullying) atau masalah pribadi (mendukung laporan Anonim).

📅 Booking Jadwal: Fitur untuk membuat janji temu konseling dengan memilih hari dan jam yang tersedia.

😊 Mood Tracker: Fitur sederhana untuk mencatat perasaan siswa saat membuka aplikasi.

2. Portal Guru BK (Admin)

📊 Dashboard Ringkas: Statistik jumlah laporan masuk, SOS, dan status penanganan.

list Manajemen Laporan: Melihat detail laporan yang masuk.

✅ Update Status: Menandai laporan sebagai "Selesai".

💬 Balas Cepat: Tombol One-click untuk membalas laporan via WhatsApp.

🛠️ Teknologi

Project ini dibuat seringan mungkin menggunakan:

HTML5

React 18 (via CDN)

Tailwind CSS (via CDN)

Lucide Icons (via CDN)

LocalStorage (sebagai database browser sementara)

🚀 Cara Menjalankan

Download file index.html dan README.md.

Letakkan dalam satu folder.

Klik dua kali index.html untuk membuka di browser (Chrome/Edge/Firefox).

Selesai! Tidak perlu npm install atau setup server.

🔐 Akun Demo Admin

Untuk mencoba fitur Guru BK:

Username: admin

Password: 123

📦 Cara Upload ke GitHub

Jika Anda ingin menyimpan kode ini ke GitHub, ikuti langkah berikut:

Pastikan Anda sudah menginstal Git di komputer.

Buat New Repository di GitHub Anda (jangan centang "Add README" karena kita sudah punya).

Buka folder proyek ini di terminal/CMD, lalu ketik:

git init
git add .
git commit -m "Rilis pertama aplikasi Pangayoman"
git branch -M main
git remote add origin [https://github.com/USERNAME_ANDA/NAMA_REPO_ANDA.git](https://github.com/USERNAME_ANDA/NAMA_REPO_ANDA.git)
git push -u origin main
