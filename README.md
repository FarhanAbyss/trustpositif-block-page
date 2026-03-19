🇮🇩 Bahasa Indonesia | 🇺🇸 [English](README.en.md)

---

# 🛡️ TRUST+Positif Block Page

> Demo tidak resmi halaman blokir **TRUST+Positif** dari Komdigi. Proyek sumber terbuka tidak resmi, digunakan untuk tujuan pendidikan. Dapat digunakan juga untuk ISP, RT/RW Net, Router Rumah/Sekolah, dan lain-lain.

---

## 🌐 Demo

**[trustpositif-internetpositif.vercel.app](https://trustpositif-internetpositif.vercel.app/)**

---

## ⚠️ Sanggahan

Ini **bukan** halaman resmi Komdigi atau Kementerian Komunikasi dan Digital Republik Indonesia. Proyek ini dibuat secara independen untuk keperluan pendidikan dan dapat digunakan sebagai halaman blokir kustom pada jaringan ISP, RT/RW Net, dan router rumah/sekolah.

---

## ✨ Fitur

- 🌙 **Mode Gelap** — Tema gelap dengan efek glassmorphism
- 🌐 **Dwibahasa** — Mendukung Bahasa Indonesia & English (American)
- 🇮🇩🇺🇸 **Logo Dinamis** — Logo otomatis berganti saat ganti bahasa (Komdigi ↔ MCDA)
- 📱 **Sepenuhnya Responsif** — Mendukung semua perangkat (HP kecil hingga Ultrawide) dengan `clamp()` untuk scaling mulus
- 🎨 **Animasi** — Menggunakan Animate.css + AOS (Animate On Scroll)
- ⚖️ **Dasar Hukum Diperbarui** — Merujuk UU No. 1 Tahun 2024 (Perubahan Kedua UU ITE), Pasal 40 ayat (2a) & (2b)
- 🚨 **4 Tombol Laporan** — AduanKonten.id, AduanNomor.id, CekRekening.id, dan email resmi
- 🛑 **Stop Judi Online** — Tombol informasi pemberantasan judi daring #BersamaStopJudiOnline
- 🖱️ **Dukungan PC/Laptop** — Cursor pointer, hover, focus & navigasi keyboard
- 🍎 **Dukungan Safari** — Prefix `-webkit-` untuk glassmorphism
- ♿ **Aksesibel** — `aria-label` pada tombol bahasa, blur otomatis dimatikan via `prefers-reduced-motion`
- 🔍 **Siap SEO** — Meta tag lengkap + Open Graph untuk pratinjau sosial media & WhatsApp
- ⚡ **Performa** — Preconnect Google Fonts, tanpa duplikasi skrip

---

## 🗂️ Struktur File

```
trustpositif-block-page/
├── index.html              # File utama — komentar Bahasa Indonesia
├── indexen.html            # File utama — komentar Bahasa Inggris
├── README.md               # Dokumentasi (Bahasa Indonesia)
├── README.en.md            # Dokumentasi (English)
└── (branch: image)         # Aset gambar
    ├── komdigi.webp            # Logo Komdigi (ditampilkan saat bahasa Indonesia)
    ├── mcda.webp               # Logo MCDA (ditampilkan saat bahasa Inggris)
    ├── ogimage.webp            # Gambar pratinjau saat tautan dibagikan ke sosmed/WA
    ├── trustpositif.webp       # Logo program TRUST+Positif
    ├── internetpositif.webp    # Logo program Internet Positif
    ├── internetsehataman.webp  # Logo program Internet Sehat dan Aman
    ├── aduankonten.webp        # Logo program Aduan Konten
    ├── cyberdrone9.webp        # Logo program Cyber Drone 9
    └── laporaduankonten.webp   # Banner Laporkan Konten Negatif
```

---

## 💬 Komentar Kode

Kedua file HTML dilengkapi dengan **komentar kode yang lengkap dan mudah dipahami** — bahkan tanpa pengalaman pemrograman sebelumnya.

Cukup cari tag **`[UBAH]`** (ID) atau **`[EDIT]`** (EN) di dalam file untuk menemukan semua bagian yang dapat disesuaikan.

| File | Bahasa Komentar | Tautan |
|------|----------------|--------|
| `index.html` | 🇮🇩 Bahasa Indonesia | [Lihat File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/index.html) |
| `indexen.html` | 🇺🇸 American English | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/indexen.html) |

> ⚠️ **Perhatian:** Jika menggunakan `indexen.html` dan ingin mendeploy ke server/Vercel/hosting, **ubah nama file** menjadi `index.html` terlebih dahulu agar dapat diakses sebagai halaman utama.

**Bagian yang sudah ada komentarnya:**

- 🎨 Warna tema (CSS variables)
- 🖼️ Logo header + swap bahasa otomatis
- 📝 Semua teks dwibahasa (ID/EN)
- 🔗 Semua tautan & email kontak
- 🃏 Kartu program Internet Positif
- ⚖️ Kartu dasar hukum & badge
- 🔘 Tombol aksi (4 tombol) & label pill
- 🚨 Tombol laporan (4 tombol)
- ⚡ Kecepatan & urutan animasi (Animate.css + AOS)
- 📐 Breakpoint responsif semua perangkat
- 🔍 Meta tag SEO & Open Graph

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| HTML5 | Struktur halaman |
| CSS3 + `clamp()` | Styling, glassmorphism & typography responsif |
| [Animate.css](https://animate.style/) `v4.1.1` | Animasi saat halaman pertama dibuka |
| [AOS](https://michalsnik.github.io/aos/) `v2.3.4` | Animasi saat halaman digulir |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Font header & badge |
| [Sora](https://fonts.google.com/specimen/Sora) | Font teks isi halaman |

> Semua pustaka & font dimuat via **CDN (Content Delivery Network)** — tidak perlu memasang apapun, cukup koneksi internet.

---

## 🖼️ Tentang Gambar

Semua gambar menggunakan metode **Embedded via CDN** — gambar **tidak disimpan secara lokal** di dalam file HTML, melainkan dimuat langsung dari URL raw GitHub di branch `image`.

```
https://raw.githubusercontent.com/FarhanAbyss/trustpositif-block-page/refs/heads/image/namafile.webp
```

**Keuntungan metode ini:**
- ✅ File `index.html` tetap ringan
- ✅ Gambar dapat diperbarui tanpa mengubah `index.html`
- ✅ Dapat dipakai ulang di proyek lain cukup dengan URL-nya
- ⚠️ Membutuhkan koneksi internet saat pertama kali dimuat
- ⚠️ Repositori gambar harus berstatus **Public**

---

## 📋 Kompatibilitas Peramban

| Peramban | Status |
|----------|--------|
| Chrome | ✅ |
| Firefox | ✅ |
| Edge | ✅ |
| Safari (iOS & macOS) | ✅ |
| Samsung Internet | ✅ |
| Internet Explorer | ❌ |

---

## 📐 Breakpoint Responsif

| Perangkat | Resolusi | Layout |
|-----------|----------|--------|
| HP kecil/jadul | < 360px | 1 kolom, font diperkecil |
| HP normal | 360px – 480px | 1 kolom vertikal |
| HP besar | 481px – 600px | 2 kolom |
| Tablet portrait | 601px – 768px | 2 kolom |
| Tablet landscape | 769px – 1024px | 2 kolom |
| Monitor 4:3 jadul | 769px – 1024px, tinggi < 800px | 2 kolom, disesuaikan |
| Laptop / Desktop | 1025px – 1440px | 2 kolom |
| Ultrawide | > 1440px | 4 kolom tombol aksi |
| HP landscape | tinggi < 500px, lebar > 600px | Header kompak |

> Semua ukuran font dan jarak menggunakan `clamp()` agar berubah mulus tanpa lompatan kasar antar perangkat.

---

## ⚖️ Dasar Hukum

Halaman ini merujuk pada peraturan perundang-undangan berikut:

| Peraturan | Keterangan |
|-----------|------------|
| UU No. 1 Tahun 2024 | Perubahan Kedua atas UU No. 11 Tahun 2008 tentang ITE (mencabut UU No. 19 Tahun 2016) |
| Pasal 40 ayat (2a) & (2b) | Pemerintah wajib mencegah penyebarluasan konten melanggar hukum & berwenang memutus akses |
| Peraturan Menteri Kominfo No. 19 Tahun 2014 | Penanganan Situs Internet Bermuatan Negatif — landasan teknis Trust+Positif |
| PP No. 71 Tahun 2019 (PP PSTE) | Penyelenggaraan Sistem dan Transaksi Elektronik |

---

## 📄 Lisensi

Proyek ini bersifat **sumber terbuka** dan bebas digunakan untuk keperluan pribadi, pendidikan, maupun jaringan lokal.

---

## 🙏 Penghargaan

- Logo & aset gambar milik **Kementerian Komunikasi dan Digital Republik Indonesia**
- Seluruh kode dibuat oleh Kimi AI, Qwen Chat, Claude AI
- Penulis prompt oleh **[FarhanAbyss](https://github.com/FarhanAbyss)**

---

<p align="center">
  <i>Bukan halaman resmi Komdigi — Sumber Terbuka & Bebas Digunakan</i>
</p>
