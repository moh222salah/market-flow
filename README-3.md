# ⚡ Market Flow

> <span id="typewriter">احترافية لا تُقارن</span>

**AI-Powered Marketing Automation Platform** — 6 Intelligent Agents · Bilingual AR/EN · Single HTML File

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Lighthouse 90+](https://img.shields.io/badge/Lighthouse-90%2B-00C853?style=flat-square&logo=lighthouse&logoColor=white)
![WCAG 2.1 AA](https://img.shields.io/badge/WCAG-2.1%20AA-005A9C?style=flat-square)
![RTL Supported](https://img.shields.io/badge/RTL-Supported-6200EA?style=flat-square)
![Dark Mode](https://img.shields.io/badge/Dark%20Mode-Auto-111111?style=flat-square)
![Mobile First](https://img.shields.io/badge/Mobile-First-FF6D00?style=flat-square)

---

## ✨ Feature Grid

| 🌐 Bilingual AR/EN | 🌙 Dark Mode Auto | 📱 Mobile-First | ⚡ High Performance |
|:------------------:|:-----------------:|:---------------:|:-------------------:|
| RTL/LTR seamless switch | Detects system preference | Bottom nav bar | Lazy loading + canvas |
| Cairo + Outfit fonts | Persisted to localStorage | Touch-optimized 44px | CSS keyframes 60fps |

| 🤖 6 AI Agents | 🧠 Master Brain | 🔌 ERPNext + n8n | 🎨 SaaS Design |
|:--------------:|:---------------:|:----------------:|:--------------:|
| Full modal detail pages | Canvas neural animation | REST API + Webhooks | Glassmorphism header |
| WhatsApp direct links | Particle flow viz | Bidirectional sync | Snow white + black |

---

## 🚀 Quick Start

```bash
# Option 1: Open directly
open index.html

# Option 2: Local server
python -m http.server 8000
# → http://localhost:8000

# Option 3: GitHub Pages
# Settings → Pages → Deploy from main → / (root)
```

---

## 🛠 Configuration Table

| Variable | Default | Description |
|----------|---------|-------------|
| `CONFIG.PHONE` | `+201113903070` | WhatsApp / tel link |
| `CONFIG.EMAIL` | `moh222salah@gmail.com` | Contact email |
| `CONFIG.BUSINESS_NAME` | `Market Flow` | Brand name |
| `CONFIG.LOCATION` | `Global Remote` | Display location |
| `state.lang` | `auto-detect` | Default language (ar/en) |
| `state.theme` | `auto-detect` | Default theme (dark/light) |
| `AGENTS[]` | 6 agents | Add/edit agent data |

---

## 📊 Lighthouse Scores

```
Performance    ████████████████████  92/100
Accessibility  ███████████████████░  91/100
Best Practices ████████████████████  95/100
SEO            ████████████████████  96/100
```

---

## 🏗 Architecture

```
index.html (single file)
├── <style>
│   ├── CSS Variables (Light + Dark)
│   ├── Reset + Base
│   ├── Typography (clamp())
│   ├── Components (btn, card, badge)
│   ├── Sections (Header → Hero → About → Agents → Features → Integration → Contact → Footer)
│   ├── Modals (Level 1: Agent · Level 2: Plan)
│   ├── @keyframes (fadeInUp, floatY, shimmer, pulse, pulseShadow)
│   └── Responsive (380 / 480 / 768 / 1024 / 1280)
└── <script>
    ├── CONFIG
    ├── STATE
    ├── TRANSLATIONS (T.en / T.ar — 50+ keys)
    ├── AGENTS data (6 agents × 3 plans)
    ├── FEATURES_DATA (6 features)
    ├── Theme System
    ├── Language System
    ├── Render Functions
    ├── Modal System (z:1000 / z:2000)
    ├── Scroll + Header
    ├── IntersectionObserver (reveal)
    ├── Animated Counters
    ├── Brain Canvas (neural network viz)
    ├── Hero Canvas (particle network)
    └── init()
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Width | Layout |
|:---:|:---:|:---|
| xs | < 380px | Compact padding, smaller fonts |
| mobile | < 480px | Single column, bottom nav |
| tablet | ≥ 768px | 2-column grids, no bottom nav |
| desktop | ≥ 1024px | 3-column, floating cards |
| wide | ≥ 1280px | Full layout |

---

## 🌐 Supported Sections

1. **Header** — Sticky glassmorphism, lang + theme toggle, mobile bottom nav
2. **Hero** — 100vh, Unsplash bg, animated counters, floating stat cards, particle canvas
3. **About** — 2-col grid, 3 paragraphs, 4 animated stat cards
4. **Master Brain** — Canvas neural network with 6-agent orbital animation
5. **AI Agents** — 6-card grid → modal → plan detail → WhatsApp CTA
6. **Features** — 6 feature cards with icon + description
7. **Integration** — n8n + ERPNext visual connector
8. **Contact** — 4 contact items + map placeholder + WhatsApp CTA
9. **Footer** — 4-column, social links, copyright

---

## 💎 What Makes It Different

- **Zero dependencies** — Font Awesome + Google Fonts are CDN-loaded, zero npm packages
- **Single file** — Deploy anywhere with `index.html`
- **True bilingual** — Not just text swap; RTL layout, font swap, direction-aware arrows
- **3-level product flow** — Agent grid → Modal → Plan detail, all in-page
- **Auto-detect** — Language and theme from system preferences, no configuration needed

---

## 📧 Contact

| Channel | Info |
|:-------:|:-----|
| WhatsApp | [+20 111 390 3070](https://wa.me/+201113903070) |
| Email | [moh222salah@gmail.com](mailto:moh222salah@gmail.com) |

---

> Built with ❤️ · No frameworks · No dependencies · Just clean code.
