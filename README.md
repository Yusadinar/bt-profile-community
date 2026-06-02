# 🌟 BARISAN TERDEPAN Community Profile

Website profil komunitas modern dan interaktif untuk sirkel "Barisan Terdepan". Dibangun dengan fokus pada antarmuka yang estetis (UI), interaksi pengguna yang halus (UX), dan animasi visual tingkat lanjut (Parallax) untuk memberikan kesan premium.

## 🚀 Fitur Utama

- **3D Hero Parallax**: Galeri foto yang bergerak mulus (smooth scrolling) mengikuti guliran halaman dengan efek tiga dimensi yang memukau.
- **Sparkles Text Effect**: Animasi kelap-kelip dinamis pada judul utama menggunakan manipulasi DOM dan SVG secara real-time.
- **Scroll Reveal Animations**: Transisi elemen yang muncul secara perlahan (`fade-in-up` & *text reveal*) saat halaman digulir menggunakan API `IntersectionObserver`.
- **Interactive Modals**: Detail profil masing-masing anggota (Foto, Nama, Role, Bio) ditampilkan melalui modal pop-up estetik dengan efek *backdrop blur*.
- **Background Music Player**: Pemutar musik latar yang responsif, dilengkapi dengan tombol *toggle* interaktif untuk memainkan atau mematikan musik.
- **Responsive Design**: Tata letak yang dioptimalkan secara penuh untuk beroperasi mulus di perangkat Mobile, Tablet, hingga Desktop.

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur *markup* semantik halaman web.
- **Tailwind CSS**: *Utility-first CSS framework* (via CDN) untuk implementasi *styling*, tema gelap (*dark theme*), dan transisi elemen yang rapi.
- **Vanilla JavaScript**: Seluruh logika fungsional mulai dari kalkulasi matriks *parallax*, *state management* musik, hingga interaksi modal tanpa bergantung pada *library* eksternal tambahan.

## 📂 Struktur Direktori

```text
bt-profile/
├── assets/          # Folder untuk aset visual (foto kenangan, profil anggota, ilustrasi)
├── index.html       # Entry point utama; berisi seluruh markup UI dan script logika (JS & Tailwind Config)
├── lagu.mp3         # File audio untuk background music
└── README.md        # File dokumentasi proyek (Anda sedang membacanya)
```

## 💻 Cara Menjalankan (Local Development)

Proyek ini merupakan situs statis murni sehingga cara menjalankannya sangat sederhana:

1. **Clone Repository ini**
   ```bash
   git clone https://github.com/Yusadinar/bt-profile-community.git
   ```
2. **Masuk ke Folder Proyek**
   ```bash
   cd bt-profile-community
   ```
3. **Jalankan Aplikasi**
   - Cukup *double-click* file `index.html` untuk melihatnya di *web browser* Anda.
   - *Rekomendasi:* Gunakan ekstensi **Live Server** di VS Code untuk pengalaman melihat perubahan kode secara langsung (*auto-reload*).

## 🎨 Modifikasi Tema (Tailwind Config)

Skema warna dan tipografi diatur pada blok `<script>` konfigurasi Tailwind di dalam file `index.html`. 
- **Font Utama**: Inter (dari Google Fonts)
- **Warna Aksen (Primary)**: `#3b82f6` (Blue)
- **Tema Gelap**: `#020617` (Bg) & `#0f172a` (Surface)

---
*Dibuat untuk kebutuhan penyimpanan profil kenangan sirkel Barisan Terdepan.*
*"When yaa fullteam :D"*
