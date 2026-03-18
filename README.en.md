🇮🇩 [Bahasa Indonesia](README.md) | 🇬🇧 English

---

# 🛡️ TRUST+Positif Block Page

> Unofficial demo of the **TRUST+Positif** block page by Komdigi. An unofficial open source project used for educational purposes. Can also be used for ISP, RT/RW Net, Home/School Router, etc.

---

## 🌐 Demo

**[trustpositif-internetpositif.vercel.app](https://trustpositif-internetpositif.vercel.app/)**

---

## ⚠️ Disclaimer

This is **not** an official Komdigi or Ministry of Communications and Digital of the Republic of Indonesia page. This project was made independently for educational purposes and can be used as a custom block page on ISP, RT/RW Net, and home/school router networks.

---

## ✨ Features

- 🌙 **Dark Mode** — Dark theme with glassmorphism effect
- 🌐 **Bilingual** — Supports Bahasa Indonesia & English
- 🖼️ **Dynamic Logo** — Logo automatically switches when changing language (Komdigi ↔ MCDA)
- 📱 **Fully Responsive** — Supports all devices (Mobile, Tablet, PC, Ultrawide, 4:3 Monitor)
- 🎨 **Animations** — Using Animate.css + AOS (Animate On Scroll)
- 🖱️ **PC/Laptop Support** — Cursor pointer, hover, focus & keyboard navigation
- 🍎 **Safari Support** — `-webkit-` prefix for glassmorphism
- 🔍 **SEO Ready** — Complete meta tags + Open Graph for social media & WhatsApp preview

---

## 🗂️ File Structure

```
trustpositif-block-page/
├── index.html              # Main file — Indonesian comments
├── indexen.html            # Main file — English comments
├── README.md               # Documentation (Bahasa Indonesia)
├── README.en.md            # Documentation (English)
└── (branch: image)         # Image assets
    ├── komdigi.webp        # Komdigi logo (shown when Indonesian language is active)
    ├── mcda.webp           # MCDA logo (shown when English language is active)
    ├── ogimage.webp        # Preview image when link is shared on social media/WhatsApp
    ├── trustpositif.webp   # TRUST+Positif program logo
    ├── internetpositif.webp    # Internet Positif program logo
    ├── internetsehataman.webp  # Internet Sehat dan Aman program logo
    ├── aduankonten.webp    # Aduan Konten program logo
    ├── cyberdrone9.webp    # Cyber Drone 9 program logo
    └── laporaduankonten.webp   # Report Negative Content banner
```

---

## 💬 Code Comments

Both HTML files come with **complete code comments** so anyone can understand, customize, and use them easily — even without prior coding experience.

Simply search for the **`[EDIT]`** tag inside the file to find all customizable sections.

| File | Comment Language | Link |
|------|-----------------|------|
| `index.html` | 🇮🇩 Bahasa Indonesia | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/index.html) |
| `indexen.html` | 🇬🇧 English | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/indexen.html) |

**Sections that have been commented:**
- 🎨 Theme colors (CSS variables)
- 🖼️ Header logo + automatic language swap
- 📝 All bilingual text (ID/EN)
- 🔗 All links & contact emails
- 🃏 Internet Positif program cards
- ⚖️ Legal basis cards & badges
- 🔘 Action buttons & pill badges
- ⚡ Animation speed & order (Animate.css + AOS)
- 📐 Responsive breakpoints for all devices
- 🔍 SEO meta tags & Open Graph

---

## 🛠️ Technologies

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure |
| CSS3 | Styling & glassmorphism |
| [Animate.css](https://animate.style/) `v4.1.1` | Page load animations |
| [AOS](https://michalsnik.github.io/aos/) `v2.3.4` | Scroll animations |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Header & badge font |
| [Sora](https://fonts.google.com/specimen/Sora) | Body font |

> All libraries & fonts are loaded via **CDN (Content Delivery Network)** — no installation needed, just an internet connection.

---

## 🖼️ About Images

All images in this project use the **Embedded via CDN** method — meaning images are **not stored locally** inside `index.html`, but are loaded directly from the raw GitHub URL in the `image` branch.

```
https://raw.githubusercontent.com/FarhanAbyss/trustpositif-block-page/refs/heads/image/filename.webp
```

**Advantages of this method:**
- ✅ `index.html` file stays lightweight
- ✅ Images can be updated without modifying `index.html`
- ✅ Can be reused in other projects using just the URL
- ⚠️ Requires an internet connection on first load
- ⚠️ Requires a CDN provider and the image repository must be set to **Public**

---

## 📋 Browser Compatibility

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

| Device | Resolution | Layout |
|--------|------------|--------|
| Small/Old Mobile | < 360px | 1 column, reduced font |
| Normal Mobile | 360px – 480px | 1 column vertical |
| Tablet | 481px – 768px | 2 columns |
| 4:3 Small Monitor | ~800×600 | 1 column, adjusted |
| 4:3 Normal Monitor | ~1024×768 | 2 columns, adjusted |
| PC 16:9 | 900px – 1399px | 2 top + 1 center |
| Ultrawide 21:9 | ≥ 1400px | 3 columns horizontal |

---

## 📄 License

This project is **open source** and free to use for personal, educational, or local network purposes.

---

## 🙏 Credits

- Logos & image assets belong to **Ministry of Communications and Digital of the Republic of Indonesia**
- Created by **[FarhanAbyss](https://github.com/FarhanAbyss)**

---

<p align="center">
  <i>Not an official Komdigi page — Open Source & Free to Use</i>
</p>
