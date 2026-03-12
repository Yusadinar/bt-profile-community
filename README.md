# 🚀 Barisan Terdepan - Profile Website

Website profil interaktif dan arsip digital untuk sirkel pertemanan **Barisan Terdepan**. Proyek ini dibuat sebagai wadah dokumentasi memori tongkrongan, mulai dari galeri foto kumpul-kumpul hingga pelacak wacana agenda selanjutnya yang harus direalisasikan.
<img width="1429" height="732" alt="image" src="https://github.com/user-attachments/assets/13a1c691-6111-4dee-b5b2-7a8c14bf24ef" />

🌐 **Live Website:** [https://bt-profile.xo.je/](https://bt-profile.xo.je/)

---

## ✨ Fitur Utama

* 🎨 **Modern Dark UI:** Desain antarmuka minimalis nan elegan dengan tema *dark mode*, dilengkapi efek *glassmorphism* pada *floating navbar*.
* 📱 **Fully Responsive:** Tampil mulus di perangkat *mobile* maupun desktop. Menggunakan teknik *Art Direction* pada gambar *Hero background* agar tidak terpotong saat orientasi layar berubah.
* 🎵 **Interactive BGM Player:** Fitur pemutar lagu otomatis saat pengguna berinteraksi dengan halaman, lengkap dengan *floating button* kustom untuk Play/Pause.
* 👥 **Dynamic Member Showcase:** Menampilkan profil 9 anggota sirkel yang terbagi menjadi **BPH** (Lead, Wingman, Secretary) dan **Anggota**, lengkap dengan *modal popup* detail anggota.
* 🗓️ **Agenda Tracker:** Seksi khusus *Coming Soon* dengan animasi elemen berdenyut.
* ✨ **Smooth Scroll Animations:** Implementasi *Intersection Observer* API menggunakan Vanilla JavaScript untuk memberikan efek *fade-in-up* saat elemen memasuki layar.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun murni di sisi *client-side* (*frontend*) agar ringan dan mudah di-*hosting* di mana saja.

* **HTML5** (Struktur semantik)
* **Tailwind CSS** (via CDN untuk *styling* cepat dan utilitas responsif tanpa *build step*)
* **Vanilla JavaScript** (Manipulasi DOM statis, penanganan Modal, interaksi Audio API, dan Scroll Observer)

---

## 💻 Cara Menjalankan Secara Lokal

Karena proyek ini hanya menggunakan HTML statis, menjalankannya sangatlah mudah:

1. *Clone* repositori ini ke komputer lokal kamu:
   ```bash
   git clone [https://github.com/username-kamu/barisan-terdepan.git](https://github.com/username-kamu/barisan-terdepan.git)
2. Buka folder proyek tersebut.
3. Siapkan file musik dengan nama lagu.mp3 dan letakkan di folder yang sama dengan index.html (atau sesuaikan path audio di dalam kode HTML).
4. Klik kanan pada file index.html dan buka menggunakan browser pilihanmu (Chrome, Firefox, Safari, dll).
5. (Opsional) Sangat disarankan untuk membukanya menggunakan ekstensi Live Server di VS Code agar fitur Audio API berjalan sempurna tanpa pemblokiran keamanan lokal (CORS policy).

## 📂 Struktur Direktori Disarankan
Jika ingin mengelola aset gambar dan audio sendiri, disarankan membuat struktur folder seperti ini:
📁 barisan-terdepan/
├── 📄 index.html      # File utama website
├── 📄 README.md       # Dokumentasi repositori
├── 🎵 lagu.mp3        # File background music
└── 📁 assets/         # (Opsional) Folder untuk menyimpan foto anggota dan galeri lokal

## 📝 Lisensi
Proyek ini dibuat untuk keperluan internal sirkel Barisan Terdepan. Silakan jadikan referensi jika bermanfaat!
© 2026 BPH Barisan Terdepan
