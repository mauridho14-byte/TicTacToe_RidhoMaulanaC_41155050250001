Aplikasi Mobile Tic Tac Toe (React Native & Expo)

Aplikasi mobile sederhana Tic Tac Toe yang dibuat menggunakan React Native dan Expo. Proyek ini disusun sebagai tugas mata kuliah Pemrograman Mobile untuk mempelajari konsep-konsep dasar pengembangan Front-End dan aplikasi mobile modern.

📌 Fitur Utama

    -Papan Permainan 3x3: Tampilan grid 3x3 yang didesain menggunakan Flexbox.
    -Deteksi Otomatis Pemenang: Menghitung kombinasi pemenang secara otomatis (horizontal, vertikal, dan diagonal).
    -Status Permainan Dinamis: Menampilkan indikator giliran pemain (X atau O), pengumuman pemenang, atau status seri (draw).
    -Mulai Ulang (Reset): Tombol untuk mengembalikan papan ke kondisi awal.
    -Warna Simbol Berbeda: Pemain X ditandai dengan warna merah (#e74c3c) dan pemain O dengan warna biru (#3498db).

🛠️ Konsep Pembelajaran (Front-End & React Native)

    Melalui proyek ini, beberapa konsep penting yang diimplementasikan meliputi:
      -Declarative UI (useState): Perubahan data state pada board atau xIsNext secara otomatis memperbarui (re-render) antarmuka aplikasi tanpa perlu memanipulasi DOM secara manual.
      -Immutability ([...board]): Pembaruan array papan permainan menggunakan spread operator agar React dapat mendeteksi perubahan referensi memori secara efektif.
      -Flexbox Layout: Pengaturan tata letak responsif menggunakan properti flexDirection: 'row', alignItems, dan justifyContent.

🚀 Panduan Memulai (Getting Started)

    Prasyarat
    Sebelum menjalankan proyek, pastikan perangkat komputer Anda telah terpasang:
      -Node.js (Versi LTS direkomendasikan)
      -npm (Bawaan Node.js)
      -Editor Kode (VS Code / VSCodium)
      -Aplikasi Expo Go terinstal di Smartphone (Play Store / App Store)

Langkah-Langkah Instalasi & Menginstal Proyek

    1.Clone repository ini
      git clone https://github.com/username-anda/TicTacToeApp.git
      cd TicTacToeApp
    2.Instal dependensi proyek
      npm install
    3.Jalankan development server Expo
      npx expo start
    4.Jalankan di HP (Real Device)
      -Buka aplikasi Expo Go di HP Anda.
      -Pindai (Scan) QR Code yang muncul pada terminal komputer.
      -Aplikasi akan langsung berjalan di layar HP Anda secara real-time.

📁 Struktur Berkas

    TicTacToeApp/
    ├── src/
    │   └── app/
    │       └── index.tsx      # Kode utama permainan Tic Tac Toe
    ├── app.json                # Konfigurasi proyek Expo
    ├── package.json            # Manifest proyek dan daftar dependensi
    └── README.md               # Dokumentasi proyek

Hasil

<img width="1080" height="2400" alt="Test01" src="https://github.com/user-attachments/assets/bcc9152e-30c1-48a9-99bd-416bdca1a8f1" />
<img width="1080" height="2400" alt="Test02" src="https://github.com/user-attachments/assets/f000ba53-20e4-4047-ad2c-d6b0e522edd7" />


