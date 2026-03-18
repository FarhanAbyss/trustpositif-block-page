🇮🇩 Bahasa Indonesia | 🇬🇧 [English](README.en.md)

---

# 🛡️ TRUST+Positif Block Page

> Demo tidak resmi halaman blokir **TRUST+Positif** dari Komdigi. Proyek open source tidak resmi, digunakan untuk tujuan edukasi. Dapat digunakan juga untuk ISP, RT/RW Net, Router Rumah/Sekolah, dll.

---

## 🌐 Demo

**[trustpositif-internetpositif.vercel.app](https://trustpositif-internetpositif.vercel.app/)**

---

## ⚠️ Disclaimer

Ini **bukan** halaman resmi Komdigi atau Kementerian Komunikasi dan Digital Republik Indonesia. Proyek ini dibuat secara independen untuk keperluan edukasi dan dapat digunakan sebagai custom block page pada jaringan ISP, RT/RW Net, dan router rumah/sekolah.

---

## ✨ Fitur

- 🌙 **Dark Mode** — Tema gelap dengan efek glassmorphism
- 🌐 **Bilingual** — Mendukung Bahasa Indonesia & English
- 🖼️ **Logo Dinamis** — Logo otomatis berganti saat switch bahasa (Komdigi ↔ MCDA)
- 📱 **Fully Responsive** — Support semua perangkat (HP, Tablet, PC, Ultrawide, Monitor 4:3)
- 🎨 **Animasi** — Menggunakan Animate.css + AOS (Animate On Scroll)
- 🖱️ **PC/Laptop Support** — Cursor pointer, hover, focus & keyboard navigation
- 🍎 **Safari Support** — `-webkit-` prefix untuk glassmorphism
- 🔍 **SEO Ready** — Meta tags lengkap + Open Graph untuk preview sosmed & WhatsApp

---

## 🗂️ Struktur File

```
trustpositif-block-page/
├── index.html              # File utama — komentar Bahasa Indonesia
├── indexen.html            # File utama — komentar Bahasa Inggris
├── README.md               # Dokumentasi (Bahasa Indonesia)
├── README.en.md            # Dokumentasi (English)
└── (branch: image)         # Aset gambar
    ├── komdigi.webp        # Logo Komdigi (ditampilkan saat bahasa Indonesia)
    ├── mcda.webp           # Logo MCDA (ditampilkan saat bahasa Inggris)
    ├── ogimage.webp        # Gambar preview saat link dibagikan ke sosmed/WA
    ├── trustpositif.webp   # Logo program TRUST+Positif
    ├── internetpositif.webp    # Logo program Internet Positif
    ├── internetsehataman.webp  # Logo program Internet Sehat dan Aman
    ├── aduankonten.webp    # Logo program Aduan Konten
    ├── cyberdrone9.webp    # Logo program Cyber Drone 9
    └── laporaduankonten.webp   # Banner Laporkan Konten Negatif
```

---

## 💬 Komentar Kode (Code Comments)

Kedua file HTML dilengkapi dengan **komentar kode yang lengkap** agar siapapun bisa memahami, mengkustomisasi, dan menggunakannya dengan mudah — bahkan tanpa pengalaman coding sebelumnya.

Cukup cari tag **`[UBAH]`** (ID) atau **`[EDIT]`** (EN) di dalam file untuk menemukan semua bagian yang bisa disesuaikan.

| File | Bahasa Komentar | Link |
|------|----------------|------|
| `index.html` | 🇮🇩 Bahasa Indonesia | [Lihat File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/index.html) |
| `indexen.html` | 🇬🇧 English | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/indexen.html) |

⚠️ **Perhatian:**
Jika menggunakan `indexen.html` lalu ingin mendeploy ke server/Vercel/hosting, **ubah nama file** dari `indexen.html` menjadi `index.html` terlebih dahulu agar bisa diakses sebagai halaman utama.

**Bagian yang sudah ada komentarnya:**
- 🎨 Warna tema (CSS variables)
- 🖼️ Logo header + swap bahasa otomatis
- 📝 Semua teks bilingual (ID/EN)
- 🔗 Semua link & email kontak
- 🃏 Kartu program Internet Positif
- ⚖️ Kartu dasar hukum & badge
- 🔘 Tombol aksi & pill badges
- ⚡ Kecepatan & urutan animasi (Animate.css + AOS)
- 📐 Responsive breakpoints semua perangkat
- 🔍 SEO meta tags & Open Graph

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| HTML5 | Struktur halaman |
| CSS3 | Styling & glassmorphism |
| [Animate.css](https://animate.style/) `v4.1.1` | Animasi saat halaman load |
| [AOS](https://michalsnik.github.io/aos/) `v2.3.4` | Animasi saat scroll |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Font header & badge |
| [Sora](https://fonts.google.com/specimen/Sora) | Font body |

> Semua library & font dimuat via **CDN (Content Delivery Network)** — tidak perlu install apapun, cukup koneksi internet.

---

## 🖼️ Tentang Gambar

Semua gambar di proyek ini menggunakan metode **Embedded via CDN** — artinya gambar **tidak disimpan secara lokal** di dalam file `index.html`, melainkan dimuat langsung dari URL raw GitHub di branch `image`.

```
https://raw.githubusercontent.com/FarhanAbyss/trustpositif-block-page/refs/heads/image/namafile.webp
```

**Keuntungan metode ini:**
- ✅ File `index.html` tetap ringan
- ✅ Gambar bisa diupdate tanpa mengubah `index.html`
- ✅ Bisa dipakai ulang di project lain cukup dengan URL-nya
- ⚠️ Membutuhkan koneksi internet saat pertama kali load
- ⚠️ Membutuhkan web penyedia CDN dan repo untuk gambar harus berstatus **Public**

---

## 📋 Kompatibilitas Browser

| Browser | Status |
|---------|--------|
| Chrome | ✅ |
| Firefox | ✅ |
| Edge | ✅ |
| Safari (iOS & macOS) | ✅ |
| Samsung Internet | ✅ |
| Internet Explorer | ❌ |

---

## 📐 Responsive Breakpoints

| Perangkat | Resolusi | Layout |
|-----------|----------|--------|
| HP kecil/jadul | < 360px | 1 kolom, font diperkecil |
| HP normal | 360px – 480px | 1 kolom vertikal |
| Tablet | 481px – 768px | 2 kolom |
| Monitor 4:3 kecil | ~800×600 | 1 kolom, disesuaikan |
| Monitor 4:3 normal | ~1024×768 | 2 kolom, disesuaikan |
| PC 16:9 | 900px – 1399px | 2 atas + 1 tengah |
| Ultrawide 21:9 | ≥ 1400px | 3 kolom horizontal |

---

## 📄 Lisensi

Proyek ini bersifat **open source** dan bebas digunakan untuk keperluan pribadi, edukasi, maupun jaringan lokal.

---

## 🙏 Credits

- Logo & aset gambar milik **Kementerian Komunikasi dan Digital Republik Indonesia**
- Dibuat oleh **[FarhanAbyss](https://github.com/FarhanAbyss)**

---

<p align="center">
  <i>Bukan halaman resmi Komdigi — Open Source & Free to Use</i>
</p>
