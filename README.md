# Liora Media — Landing Page

> **The automation layer for social media.**  
> Built by [AMNEXTECH](https://amnextech.com)

![Liora Media](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![Built With](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-6366f1?style=flat-square)
![License](https://img.shields.io/badge/License-Proprietary-a855f7?style=flat-square)

---

## 🌐 Overview

This is the official production landing page for **Liora Media**, a social media automation platform that lets creators, founders, and brands schedule, publish, and manage content across all major platforms from a single dashboard — powered by AI.

The site is a fully static, zero-dependency HTML/CSS/JS build — no frameworks, no bundlers, no build step. Just open `index.html` and it works.

---

## 🗂 Project Structure

```
lioralanding/
│
├── index.html          # Main landing page
├── index.css           # Global stylesheet (design system + all component styles)
├── index.js            # Scroll animations, navbar effects, FAQ accordion
│
├── about.html          # About Us — mission, story, values, AMNEXTECH credit
├── blog.html           # Blog — launch post + newsletter signup
├── careers.html        # Careers & Investors — contributor roles + investor CTA
│
├── privacy.html        # Privacy Policy (GDPR-aware, 13 sections)
├── terms.html          # Terms of Service (13 sections)
├── cookie-policy.html  # Cookie Policy (with cookie table + opt-out links)
│
├── bagnard.otf         # Custom font used for the Liora Media CSS logo
└── logo.jpg            # Original logo asset (referenced as fallback)
```

---

## ✨ Features

### Landing Page (`index.html`)
- **Hero** — Animated gradient headline, hero CTA buttons, floating dashboard mockup panels
- **Features** — 4-card grid (Smart Scheduling, AI Post Generation, Unified Analytics, Cross-Platform Sync)
- **Integrations** — 8 platform cards (Twitter/X, Instagram, LinkedIn, Facebook, TikTok, YouTube, Pinterest, Discord)
- **How It Works** — 3-step visual guide with numbered gradient bubbles
- **Testimonials** — Social proof cards with 5-star reviews
- **Pricing** — 3-tier cards (Starter $29 / Pro $79 / Enterprise $199) with "Most Popular" badge
- **FAQ** — Interactive accordion powered by vanilla JS
- **Contact / Enquiry Form** — Name, Email, Message fields routing to `lioramedia.official@gmail.com`
- **Footer** — Full link matrix, social handles, AMNEXTECH badge, legal links

### Inner Pages
| Page | Contents |
|---|---|
| `about.html` | Mission, origin story, 6 core values, AMNEXTECH built-by section |
| `blog.html` | Full launch post (Apr 9, 2026), teaser card, newsletter subscribe form |
| `careers.html` | 6 open contributor roles (all `mailto:` linked), 3-tier investor section, pitch deck CTA |
| `privacy.html` | 13-section GDPR-compliant Privacy Policy |
| `terms.html` | 13-section Terms of Service incl. billing, cancellation, IP, governing law |
| `cookie-policy.html` | Cookie categories table, named cookies table, third-party opt-out links |

---

## 🎨 Design System

All design tokens are defined as CSS custom properties in `index.css`:

```css
--bg-dark:       #0a0a10   /* Page background        */
--accent-1:      #6366f1   /* Indigo                 */
--accent-2:      #a855f7   /* Purple                 */
--accent-3:      #ec4899   /* Pink                   */
--text-secondary: #9ca3af  /* Muted body text        */
--border-color:  rgba(255,255,255,0.08)
```

**Typography:** [Inter](https://fonts.google.com/specimen/Inter) (weights 300–800) via Google Fonts  
**Logo font:** Bagnard (custom `.otf` self-hosted)  
**Style:** Dark mode, glassmorphism panels, gradient text, micro-animations

---

## 🚀 Running Locally

No build step required. Simply open the file in your browser:

```bash
# Option 1 — Double-click index.html in Explorer

# Option 2 — Use a simple local server (recommended to avoid CORS on fonts)
npx serve .
# then open http://localhost:3000
```

---

## 📦 Deployment

### GitHub Pages
1. Push this repo to GitHub (see below)
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git branch -M main
git push -u origin main
```

---

## 📬 Contact

For enquiries, early access, or investment interest:

📧 [lioramedia.official@gmail.com](mailto:lioramedia.official@gmail.com)  
🌐 Built by [AMNEXTECH](https://amnextech.com)

---

## 📄 License

This project and its source code are proprietary and owned by **AMNEXTECH**.  
Unauthorized copying, modification, or distribution is prohibited without explicit written permission.

© 2026 Liora Media. All rights reserved.
