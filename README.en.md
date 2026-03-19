🇺🇸 English | 🇮🇩 [Bahasa Indonesia](README.md)

---

# 🛡️ TRUST+Positif Block Page

> An unofficial demo of the **TRUST+Positif** block page by Komdigi. This is an unofficial open-source project intended for educational purposes. It may also be used by ISPs, RT/RW Net providers, and home or school routers.

---

## 🌐 Demo

**[trustpositif-internetpositif.vercel.app](https://trustpositif-internetpositif.vercel.app/)**

---

## ⚠️ Disclaimer

This is **not** an official page from Komdigi or the Ministry of Communication and Digital Affairs of the Republic of Indonesia. This project was created independently for educational purposes and can be used as a custom block page on ISP networks, RT/RW Net, and home or school routers.

---

## ✨ Features

- 🌙 **Dark Mode** — Dark theme with glassmorphism effects
- 🌐 **Bilingual** — Supports Indonesian & American English
- 🇮🇩🇺🇸 **Dynamic Logo** — Logo automatically swaps when the language changes (Komdigi ↔ MCDA)
- 📱 **Fully Responsive** — Supports all devices (small phones to ultrawide monitors) using `clamp()` for smooth scaling
- 🎨 **Animations** — Uses Animate.css + AOS (Animate On Scroll)
- ⚖️ **Updated Legal Basis** — References Law No. 1 of 2024 (Second Amendment to the EIT Law), Article 40(2a) & (2b)
- 🚨 **4 Report Buttons** — AduanKonten.id, AduanNomor.id, CekRekening.id, and official email
- 🛑 **Stop Online Gambling** — Information button for anti-gambling campaign #BersamaStopJudiOnline
- 🖱️ **PC/Laptop Support** — Cursor pointer, hover, focus & keyboard navigation
- 🍎 **Safari Support** — `-webkit-` prefix for glassmorphism
- ♿ **Accessible** — `aria-label` on language buttons, blur auto-disabled via `prefers-reduced-motion`
- 🔍 **SEO Ready** — Full meta tags + Open Graph for social media & WhatsApp previews
- ⚡ **Performance** — Google Fonts preconnect, no duplicate scripts

---

## 🗂️ File Structure

```
trustpositif-block-page/
├── index.html              # Main file — Indonesian comments
├── indexen.html            # Main file — English comments
├── README.md               # Documentation (Indonesian)
├── README.en.md            # Documentation (English)
└── (branch: image)         # Image assets
    ├── komdigi.webp            # Komdigi logo (shown when Indonesian is active)
    ├── mcda.webp               # MCDA logo (shown when English is active)
    ├── ogimage.webp            # Preview image when link is shared to social media/WhatsApp
    ├── trustpositif.webp       # TRUST+Positif program logo
    ├── internetpositif.webp    # Internet Positif program logo
    ├── internetsehataman.webp  # Internet Sehat dan Aman program logo
    ├── aduankonten.webp        # Aduan Konten program logo
    ├── cyberdrone9.webp        # Cyber Drone 9 program logo
    └── laporaduankonten.webp   # Report Negative Content banner
```

---

## 💬 Code Comments

Both HTML files include **complete, beginner-friendly code comments** — no prior coding experience required.

Simply search for **`[UBAH]`** (ID) or **`[EDIT]`** (EN) inside the files to find every customizable section.

| File | Comment Language | Link |
|------|-----------------|------|
| `index.html` | 🇮🇩 Indonesian | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/index.html) |
| `indexen.html` | 🇺🇸 American English | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/indexen.html) |

> ⚠️ **Note:** If you are using `indexen.html` and want to deploy it to a server, Vercel, or any hosting platform, **rename the file** to `index.html` first so it can be accessed as the main page.

**Sections with comments:**

- 🎨 Theme colors (CSS variables)
- 🖼️ Header logo + automatic language swap
- 📝 All bilingual text (ID/EN)
- 🔗 All links & contact emails
- 🃏 Internet Positif program image cards
- ⚖️ Legal basis cards & badges
- 🔘 Action buttons (4 buttons) & pill labels
- 🚨 Report buttons (4 buttons)
- ⚡ Animation speed & order (Animate.css + AOS)
- 📐 Responsive breakpoints for all devices
- 🔍 SEO meta tags & Open Graph

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure |
| CSS3 + `clamp()` | Styling, glassmorphism & responsive typography |
| [Animate.css](https://animate.style/) `v4.1.1` | Entry animations on page load |
| [AOS](https://michalsnik.github.io/aos/) `v2.3.4` | Scroll-triggered animations |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Header & badge font |
| [Sora](https://fonts.google.com/specimen/Sora) | Body text font |

> All libraries and fonts are loaded via **CDN (Content Delivery Network)** — no installation needed, just an internet connection.

---

## 🖼️ About Images

All images use an **Embedded via CDN** approach — images are **not stored locally** inside the HTML file. Instead, they are loaded directly from raw GitHub URLs on the `image` branch.

```
https://raw.githubusercontent.com/FarhanAbyss/trustpositif-block-page/refs/heads/image/filename.webp
```

**Advantages of this approach:**
- ✅ The `index.html` file stays lightweight
- ✅ Images can be updated without modifying `index.html`
- ✅ Images can be reused in other projects via their URL
- ⚠️ Requires an internet connection on first load
- ⚠️ The image repository must be set to **Public**

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
| Small / old phones | < 360px | 1 column, smaller fonts |
| Normal phones | 360px – 480px | 1 column vertical |
| Large phones | 481px – 600px | 2 columns |
| Tablet portrait | 601px – 768px | 2 columns |
| Tablet landscape | 769px – 1024px | 2 columns |
| Old 4:3 monitors | 769px – 1024px, height < 800px | 2 columns, adjusted |
| Laptop / Desktop | 1025px – 1440px | 2 columns |
| Ultrawide | > 1440px | 4-column action buttons |
| Phone landscape | height < 500px, width > 600px | Compact header |

> All font sizes and spacing use `clamp()` for smooth, continuous scaling across all screen sizes — no abrupt jumps between breakpoints.

---

## ⚖️ Legal Basis

This page references the following Indonesian laws and regulations:

| Regulation | Description |
|------------|-------------|
| Law No. 1 of 2024 | Second Amendment to Law No. 11 of 2008 on Electronic Information and Transactions — EIT Law (supersedes Law No. 19 of 2016) |
| Article 40(2a) & (2b) | The government is obligated to prevent the dissemination of prohibited content and authorized to terminate access (block websites) |
| Ministerial Regulation of Kominfo No. 19 of 2014 | Management of Internet Sites Containing Negative Content — technical foundation of Trust+Positif |
| Government Regulation No. 71 of 2019 (PP PSTE) | Implementation of Electronic Systems and Transactions |

---

## 📄 License

This project is **open source** and free to use for personal, educational, or local network purposes.

---

## 🙏 Credits

- Logos & image assets belong to the **Ministry of Communication and Digital Affairs of the Republic of Indonesia**
- All code produced by Kimi AI, Qwen Chat, Claude AI
- Prompts authored by **[FarhanAbyss](https://github.com/FarhanAbyss)**

---

<p align="center">
  <i>Not an official Komdigi page — Open Source & Free to Use</i>
</p>
