🇮🇩 Bahasa Indonesia | 🇺🇸 [English](README.en.md)

---

# 🛡️ TRUST+Positif Block Page

> Demo tidak resmi halaman blokir **TRUST+Positif** dari Komdigi. Proyek sumber terbuka tidak resmi, digunakan untuk tujuan pendidikan. Dapat digunakan untuk ISP, RT/RW Net, Router Rumah/Sekolah, dan lain-lain.

---

## 🌐 Demo

**[trustpositif-internetpositif.vercel.app](https://trustpositif-internetpositif.vercel.app/)**

---

## ⚠️ Sanggahan

Ini **bukan** halaman resmi Komdigi atau Kementerian Komunikasi dan Digital Republik Indonesia. Proyek ini dibuat secara independen untuk keperluan pendidikan dan dapat digunakan sebagai halaman blokir kustom pada jaringan ISP, RT/RW Net, dan router rumah/sekolah.

---

## ✨ Fitur

- 🌙 **Mode Gelap** — Tema gelap dengan efek glassmorphism di seluruh elemen
- 🌐 **Dwibahasa** — Mendukung Bahasa Indonesia & English (American) dengan sakelar bahasa
- 🖼️ **Logo Dinamis** — Logo otomatis berganti saat ganti bahasa (Komdigi ↔ MCDA)
- 📱 **Sepenuhnya Responsif** — Mendukung semua perangkat dari HP kecil (<360px) hingga ultrawide (>1440px) menggunakan `clamp()` untuk perubahan ukuran yang mulus
- 🎨 **Sepenuhnya Dinamis** — Semua teks, gambar, ikon, tombol, dan jarak menyesuaikan layar secara otomatis menggunakan `clamp()`
- ✨ **Animasi** — Menggunakan Animate.css untuk animasi saat halaman dibuka + AOS untuk animasi saat halaman digulir
- ⚖️ **Dasar Hukum Diperbarui** — Merujuk UU No. 1 Tahun 2024 (Perubahan Kedua UU ITE), Pasal 40 ayat (2a) & (2b)
- 🚨 **4 Tombol Laporan** — AduanKonten.id, AduanNomor.id, CekRekening.id, dan surel resmi — masing-masing dengan warna berbeda
- 🛑 **Stop Judi Online** — Tombol informasi pemberantasan judi daring #BersamaStopJudiOnline
- 🖱️ **Dukungan PC/Laptop** — Kursor pointer, efek hover, sorotan fokus, dan navigasi papan ketik (Tab)
- 🍎 **Dukungan Safari** — Awalan `-webkit-` untuk glassmorphism agar berfungsi di Safari (iOS & macOS)
- ♿ **Aksesibel** — `aria-label` pada tombol bahasa; efek buram otomatis dimatikan melalui `prefers-reduced-motion`
- 🔍 **Siap SEO** — Meta tag lengkap + Open Graph untuk pratinjau WhatsApp dan media sosial
- ⚡ **Performa** — Preconnect Google Fonts, tanpa duplikasi skrip, tautan surel berupa teks biasa
- 💬 **Komentar Kode Lengkap** — Setiap bagian memiliki komentar baku yang mudah dipahami bahkan oleh pemula

---

## 🗂️ Struktur Berkas

```plaintext
trustpositif-block-page/
├── index.html              # Berkas utama — komentar Bahasa Indonesia
├── indexen.html            # Berkas utama — komentar Bahasa Inggris
├── README.md               # Dokumentasi (Bahasa Indonesia)
├── README.en.md            # Dokumentasi (English)
└── (branch: image)         # Aset gambar — dimuat via CDN dari GitHub
    ├── komdigi.webp            # Logo Komdigi (ditampilkan saat bahasa Indonesia aktif)
    ├── mcda.webp               # Logo MCDA (ditampilkan saat bahasa Inggris aktif)
    ├── ogimage.webp            # Gambar pratinjau saat tautan dibagikan ke sosial media/WhatsApp
    ├── trustpositif.webp       # Logo program TRUST+Positif
    ├── internetpositif.webp    # Logo program Internet Positif
    ├── internetsehataman.webp  # Logo program Internet Sehat dan Aman
    ├── aduankonten.webp        # Logo program Aduan Konten
    ├── cyberdrone9.webp        # Logo program Cyber Drone 9
    └── laporaduankonten.webp   # Banner Laporkan Konten Negatif
```

---

## 💬 Komentar Kode

Kedua berkas HTML dilengkapi dengan komentar kode yang lengkap dan mudah dipahami — bahkan tanpa pengalaman pemrograman sebelumnya.

Cari tanda **`[UBAH]`** (ID) atau **`[EDIT]`** (EN) di dalam berkas untuk menemukan semua bagian yang dapat disesuaikan.

| Berkas | Bahasa Komentar | Tautan |
|--------|----------------|--------|
| `index.html` | 🇮🇩 Bahasa Indonesia | [Lihat Berkas](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/index.html) |
| `indexen.html` | 🇺🇸 American English | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/indexen.html) |

> ⚠️ **Perhatian:** Jika menggunakan `indexen.html` dan ingin menerapkan ke server/Vercel/hosting, ubah nama berkas menjadi `index.html` terlebih dahulu agar dapat diakses sebagai halaman utama.

**Bagian yang sudah memiliki komentar:**

- 🎨 Warna tema (variabel CSS)
- 🖼️ Logo header + pergantian bahasa otomatis
- 📝 Semua teks dwibahasa (ID/EN)
- 🔗 Semua tautan & alamat surel kontak
- 🃏 Kartu gambar program Internet Positif
- ⚖️ Kartu dasar hukum & lencana
- 🔘 4 Tombol aksi & label pill
- 🚨 4 Tombol laporan dengan warna berbeda
- ⚡ Kecepatan & urutan animasi (Animate.css + AOS)
- 📐 Titik putus responsif semua perangkat
- 🔍 Meta tag SEO & Open Graph

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| HTML5 | Struktur halaman |
| CSS3 + `clamp()` | Penataan, glassmorphism & tipografi responsif sepenuhnya |
| [Animate.css](https://animate.style/) `v4.1.1` | Animasi saat halaman pertama dibuka |
| [AOS](https://michalsnik.github.io/aos/) `v2.3.4` | Animasi saat halaman digulir |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Fon header & lencana |
| [Sora](https://fonts.google.com/specimen/Sora) | Fon teks isi halaman |

> Semua pustaka dan fon dimuat via **CDN** — tidak perlu memasang apapun, cukup koneksi internet.

---

## 🖼️ Tentang Gambar

Semua gambar menggunakan metode **Embedded via CDN** — gambar tidak disimpan secara lokal di dalam berkas HTML, melainkan dimuat langsung dari URL raw GitHub di branch `image`.

```plaintext
https://raw.githubusercontent.com/FarhanAbyss/trustpositif-block-page/refs/heads/image/namafile.webp
```

**Keuntungan metode ini:**

- ✅ Berkas `index.html` tetap ringan
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

| Perangkat | Resolusi | Tata Letak |
|-----------|----------|------------|
| HP kecil/jadul | < 360px | 1 kolom, semua elemen diperkecil |
| HP normal | 360px – 480px | 1 kolom vertikal |
| HP besar | 481px – 600px | 2 kolom |
| Tablet portrait | 601px – 768px | 2 kolom |
| Tablet landscape | 769px – 1024px | 2 kolom |
| Monitor 4:3 jadul | 769px – 1024px, tinggi < 800px | 2 kolom, disesuaikan |
| Laptop / Desktop | 1025px – 1440px | 2 kolom |
| Ultrawide | > 1440px | 4 kolom tombol aksi, 3 kolom gambar program |
| HP landscape | tinggi < 500px, lebar > 600px | Header kompak, 2 kolom |

> Semua ukuran teks, jarak, gambar, ikon, dan tombol menggunakan `clamp()` untuk perubahan yang mulus dan berkelanjutan di antara setiap titik putus — tanpa lompatan kasar.

---

## ⚖️ Dasar Hukum

Halaman ini merujuk pada peraturan perundang-undangan berikut:

| Peraturan | Keterangan |
|-----------|------------|
| UU No. 1 Tahun 2024 | Perubahan Kedua atas UU No. 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik — mencabut UU No. 19 Tahun 2016 |
| Pasal 40 ayat (2a) & (2b) | Pemerintah wajib mencegah penyebarluasan konten melanggar hukum & berwenang melakukan pemutusan akses (pemblokiran situs) |
| Peraturan Menteri Kominfo No. 19 Tahun 2014 | Penanganan Situs Internet Bermuatan Negatif — landasan teknis Trust+Positif; mewajibkan Penyedia Layanan Internet (PLI) untuk memblokir konten negatif |
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
