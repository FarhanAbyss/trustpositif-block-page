🇺🇸 English | 🇮🇩 [Bahasa Indonesia](README.md)

---

# 🛡️ TRUST+Positif Block Page

> An unofficial demo of the **TRUST+Positif** block page by Komdigi. An unofficial open-source project for educational purposes. Can be used by ISPs, RT/RW Net providers, and home or school routers.

---

## 🌐 Demo

**[trustpositif-internetpositif.vercel.app](https://trustpositif-internetpositif.vercel.app/)**

---

## ⚠️ Disclaimer

This is **not** an official page from Komdigi or the Ministry of Communication and Digital Affairs of the Republic of Indonesia. This project was created independently for educational purposes and can be used as a custom block page on ISP networks, RT/RW Net, and home or school routers.

---

## ✨ Features

- 🌙 **Dark Mode** — Dark theme with glassmorphism effects throughout all elements
- 🌐 **Bilingual** — Supports Indonesian & American English with a language toggle
- 🖼️ **Dynamic Logo** — Logo automatically swaps when switching languages (Komdigi ↔ MCDA)
- 📱 **Fully Responsive** — Supports all devices from small phones (<360px) to ultrawide monitors (>1440px) using `clamp()` for smooth size transitions
- 🎨 **Fully Dynamic Sizing** — All text, images, icons, buttons, and spacing scale automatically using `clamp()`
- ✨ **Animations** — Uses Animate.css for page-load animations + AOS for scroll-triggered animations
- ⚖️ **Updated Legal Basis** — References Law No. 1 of 2024 (Second Amendment to the EIT Law), Article 40(2a) & (2b)
- 🚨 **4 Report Buttons** — AduanKonten.id, AduanNomor.id, CekRekening.id, and official email — each with a distinct color
- 🛑 **Stop Online Gambling** — Information button for the anti-gambling campaign #BersamaStopJudiOnline
- 🖱️ **PC/Laptop Support** — Pointer cursor, hover effects, focus highlight, and keyboard navigation (Tab key)
- 🍎 **Safari Support** — `-webkit-` prefix for glassmorphism compatibility on Safari (iOS & macOS)
- ♿ **Accessible** — `aria-label` on language buttons; blur auto-disabled via `prefers-reduced-motion`
- 🔍 **SEO Ready** — Full meta tags + Open Graph for WhatsApp and social media previews
- ⚡ **Performance** — Google Fonts preconnect, no duplicate scripts, plain-text email links
- 💬 **Full Code Comments** — Every section has clear, beginner-friendly comments in formal language

---

## 🗂️ File Structure

```plaintext
trustpositif-block-page/
├── index.html              # Main file — Indonesian comments
├── indexen.html            # Main file — English comments
├── README.md               # Documentation (Indonesian)
├── README.en.md            # Documentation (English)
└── (branch: image)         # Image assets — loaded via CDN from GitHub
    ├── komdigi.webp            # Komdigi logo (shown when Indonesian is active)
    ├── mcda.webp               # MCDA logo (shown when English is active)
    ├── ogimage.webp            # Preview image when the link is shared on social media/WhatsApp
    ├── trustpositif.webp       # TRUST+Positif program logo
    ├── internetpositif.webp    # Internet Positif program logo
    ├── internetsehataman.webp  # Internet Sehat dan Aman program logo
    ├── aduankonten.webp        # Aduan Konten program logo
    ├── cyberdrone9.webp        # Cyber Drone 9 program logo
    └── laporaduankonten.webp   # Report Negative Content banner
```

---

## 💬 Code Comments

Both HTML files include complete, beginner-friendly code comments — no prior coding experience required.

Search for **`[UBAH]`** (ID) or **`[EDIT]`** (EN) inside the files to locate every customizable section.

| File | Comment Language | Link |
|------|-----------------|------|
| `index.html` | 🇮🇩 Indonesian | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/index.html) |
| `indexen.html` | 🇺🇸 American English | [View File](https://github.com/FarhanAbyss/trustpositif-block-page/blob/main/indexen.html) |

> ⚠️ **Note:** If you use `indexen.html` and plan to deploy to a server, Vercel, or any hosting platform, rename the file to `index.html` first so it can be accessed as the main page.

**Sections with comments:**

- 🎨 Theme colors (CSS variables)
- 🖼️ Header logo + automatic language swap
- 📝 All bilingual text (ID/EN)
- 🔗 All links and contact email addresses
- 🃏 Internet Positif program image cards
- ⚖️ Legal basis cards and badges
- 🔘 4 Action buttons and pill labels
- 🚨 4 Report buttons with distinct colors
- ⚡ Animation speed and order (Animate.css + AOS)
- 📐 Responsive breakpoints for all devices
- 🔍 SEO meta tags and Open Graph

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure |
| CSS3 + `clamp()` | Styling, glassmorphism & fully responsive typography |
| [Animate.css](https://animate.style/) `v4.1.1` | Entry animations on page load |
| [AOS](https://michalsnik.github.io/aos/) `v2.3.4` | Scroll-triggered animations |
| [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) | Header and badge font |
| [Sora](https://fonts.google.com/specimen/Sora) | Body text font |

> All libraries and fonts are loaded via **CDN** — no installation needed, just an internet connection.

---

## 🖼️ About Images

All images use an **Embedded via CDN** approach — no images are stored locally inside the HTML files. Instead, they are loaded directly from raw GitHub URLs on the `image` branch.

```plaintext
https://raw.githubusercontent.com/FarhanAbyss/trustpositif-block-page/refs/heads/image/filename.webp
```

**Advantages of this approach:**

- ✅ The `index.html` file stays lightweight
- ✅ Images can be updated without modifying `index.html`
- ✅ Images can be reused in other projects by URL
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
| Small/old phones | < 360px | 1 column, all elements scaled down |
| Normal phones | 360px – 480px | 1 column vertical |
| Large phones | 481px – 600px | 2 columns |
| Tablet portrait | 601px – 768px | 2 columns |
| Tablet landscape | 769px – 1024px | 2 columns |
| Old 4:3 monitors | 769px – 1024px, height < 800px | 2 columns, adjusted |
| Laptop / Desktop | 1025px – 1440px | 2 columns |
| Ultrawide | > 1440px | 4-column action buttons, 3-column program images |
| Phone landscape | height < 500px, width > 600px | Compact header, 2 columns |

> All font sizes, spacing, images, icons, and buttons use `clamp()` for smooth, continuous scaling between breakpoints — no abrupt jumps.

---

## ⚖️ Legal Basis

This page references the following Indonesian laws and regulations:

| Regulation | Description |
|------------|-------------|
| UU No. 1 Tahun 2024 | Second Amendment to Law No. 11 of 2008 on Electronic Information and Transactions (EIT Law) — supersedes Law No. 19 of 2016 |
| Article 40(2a) & (2b) | The government is obligated to prevent the dissemination of prohibited content and authorized to terminate access (block websites) |
| Ministerial Regulation of Kominfo No. 19 of 2014 | Management of Internet Sites Containing Negative Content — technical foundation of Trust+Positif; requires Internet Service Providers (ISPs) to block negative content |
| Government Regulation No. 71 of 2019 (PP PSTE) | Implementation of Electronic Systems and Transactions |

---

## 📄 License

This project is **open source** and free to use for personal, educational, or local network purposes.

---

## 🙏 Credits

- Logos and image assets belong to the **Ministry of Communication and Digital Affairs of the Republic of Indonesia**
- All code produced by Kimi AI, Qwen Chat, Claude AI
- Prompts authored by **[FarhanAbyss](https://github.com/FarhanAbyss)**

---

<p align="center">
  <i>Not an official Komdigi page — Open Source & Free to Use</i>
</p>
