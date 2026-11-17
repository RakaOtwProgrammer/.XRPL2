XRPL2 — WEB APP KELAS

CARA MENJALANKAN
1. Ekstrak folder XRPL2-WebApp.
2. Buka index.html di browser, atau jalankan dengan Live Server di VS Code.
3. Login admin demo:
   Username: adminxrpl2
   Password: XRPL2Admin!

FILE
- index.html : struktur halaman
- style.css  : tampilan responsif, tema gelap/cerah, animasi bintang jatuh
- script.js  : interaksi, data contoh, login demo, penyimpanan localStorage

PENTING — SEBELUM DIPAKAI BERSAMA KELAS
- Ganti nama 35 murid, nama wali kelas, dan username Instagram di array `members` pada script.js.
- Ganti username/password demo pada bagian ADMIN_USERNAME dan ADMIN_PASSWORD.
- Data saat ini tersimpan di localStorage browser masing-masing. Artinya data tidak otomatis sinkron antarperangkat.
- Login admin ini hanya simulasi frontend. Jangan gunakan untuk melindungi data penting di website publik.
- Agar bisa dipakai seluruh kelas secara online, deploy frontend dan hubungkan backend/database + autentikasi sungguhan (misalnya Firebase/Supabase).
- Untuk absensi, masukkan URL Google Spreadsheet melalui Admin Panel > Absensi. Atur izin spreadsheet dengan hati-hati.
- File materi dapat diunggah ke hosting/penyimpanan online, lalu URL-nya dimasukkan dari Admin Panel > Materi.
- Foto anggota belum disediakan secara default; field `photo` dapat diisi URL gambar setelah mendapat izin anggota.

Fitur tersedia:
kata pembuka, notes, admin panel, jadwal piket, mata pelajaran, 35 murid + 1 wali kelas,
pembagian materi PDF/Word/PowerPoint/audio/video/link, tugas wajib dari guru, akun Instagram,
foto opsional, galeri Memories yang dapat diisi dari Admin Panel, tautan absensi spreadsheet,
tema gelap/cerah, dan animasi bintang jatuh. Foto Memories dikompres dan disimpan di browser
perangkat ini; foto tidak otomatis tersinkron ke perangkat lain.
