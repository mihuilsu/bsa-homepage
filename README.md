<div align="center">

# 📄 Michael Rimsky — Developer Resume

**A clean, modern, responsive personal résumé built with pure HTML & CSS**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://fonts.google.com)

[![W3C Validated](https://img.shields.io/badge/W3C-Validated-009639?style=flat-square&logo=w3c&logoColor=white)](https://validator.w3.org)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen?style=flat-square)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Open_to_Work-4ade80?style=flat-square)](https://www.linkedin.com/in/mihuilsu/)

</div>

---

## 🖼️ Preview

> Dark editorial header · Orange accent palette · Smooth scroll-reveal animations

The resume features a two-tone layout — a deep dark header contrasted with a warm off-white body — using **DM Serif Display** for the name and **DM Mono** for labels and tags.

---

## ✨ Features

- **Fully responsive** — works on mobile, tablet, and desktop
- **Semantic HTML5** — proper heading hierarchy (`h1 → h2 → h3`), ARIA labels, W3C-validated
- **CSS custom properties** — easy to theme with a single block of variables
- **Scroll-reveal animations** — sections and cards animate in as you scroll
- **Interactive contacts** — clickable chips for email, phone, Telegram, LinkedIn, GitHub, and location
- **Project cards** — portfolio entries with live demo links and tech-stack tags
- **Animated avatar** — dashed ring, pulse halo, hover scale
- **"Open to work" badge** — pulsing green dot

### 🥚 Easter Eggs

| Trigger | Reward |
|---|---|
| Click the avatar **5 times** | Hidden first-commit message appears |
| Type the **Konami code** (`↑↑↓↓←→←→BA`) | ASCII art dev screen |

---

## 🗂️ Project Structure

```
resume/
├── index.html        # Main resume page
├── style.css         # All styles (CSS variables, layout, animations)
├── favicon.png       # Website icon
└── assets/
    └── avatar.png    # Profile photo
```

---

## 🎨 Design Tokens

| Variable | Value | Usage |
|---|---|---|
| `--accent` | `#e85d2e` | Borders, links, tags, timeline dots |
| `--accent-2` | `#f4a24a` | Italic name, Konami art |
| `--ink` | `#1a1a1f` | Primary text |
| `--ink-soft` | `#5a5762` | Secondary text |
| `--bg` | `#f8f7f4` | Page background |
| `--serif` | DM Serif Display | Name / display headings |
| `--mono` | DM Mono | Labels, dates, tags, code |
| `--sans` | DM Sans | Body text |

---

## 🚀 Getting Started

No build step, no dependencies, no npm. Just open the file.

```bash
git clone https://github.com/mihuilsu/bsa-homepage.git
cd bsa-homepage

# Option 1 — open directly
open index.html

# Option 2 — serve locally (recommended for font loading)
npx serve .
# or
http-server -c-1
```

Then visit `http://localhost:8080`.

---

## ♿ Accessibility & Validation

- All `<section>` elements have associated headings (`aria-labelledby` + visible or `.sr-only` `h2`)
- Heading levels never skip (`h1 → h2 → h3`, no jumps)
- Void elements (`<meta>`, `<img>`, `<link>`) have no trailing slashes per HTML5 spec
- Color contrast meets WCAG AA on all text/background combinations
- All interactive elements are keyboard-navigable

---

## 📦 Sections

| Section | Description |
|---|---|
| **Header** | Name, role, tagline, avatar, open-to-work badge |
| **Contacts** | Email, phone, Telegram, LinkedIn, GitHub, location |
| **About** | Short intro quote |
| **Skills** | Frontend / Backend / DevOps / Soft skills with tag chips |
| **Portfolio** | HLEGAL landing page, MERN Todo App |
| **Experience** | Binary Studio, 100Shin, Silpo |
| **Education** | Hillel IT (×2), EF SET English certificate |
| **Languages** | Ukrainian (Native), English (B2) |
| **Hobbies** | Cinema, Music, History, Politics |

---

## 🌐 Live Projects

| Project | Stack | Demo |
|---|---|---|
| HLEGAL Law Company | HTML · CSS · JS · Tailwind | [hlegal-law-company-indol.vercel.app](https://hlegal-law-company-indol.vercel.app) |
| MERN Todo App | MongoDB · Express · React · Node | [mern-todo-app-eight-omega.vercel.app](https://mern-todo-app-eight-omega.vercel.app) |

---

## 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-czech.hudek@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:czech.hudek@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mihuilsu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mihuilsu/)
[![GitHub](https://img.shields.io/badge/GitHub-mihuilsu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mihuilsu)
[![Telegram](https://img.shields.io/badge/Telegram-@mihuilsu-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/mihuilsu)

</div>

---

<div align="center">

Made with ♥ and JavaScript &nbsp;·&nbsp; Odesa, Ukraine 🇺🇦

</div>
