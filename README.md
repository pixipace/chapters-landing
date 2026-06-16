<div align="center">

![Chapters Banner](https://capsule-render.vercel.app/api?type=waving&color=0:16376d,100:25ad9f&height=200&section=header&text=Chapters&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Sell%20Online%20Courses%20on%20Shopify&descAlignY=55&descSize=20)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=for-the-badge&logo=shopify&logoColor=white)](https://shopify.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](./LICENSE)

**A modern, conversion-optimized landing page for a Shopify course-selling application.**

[Live Demo](https://chapters.pixipace.com) · [Report Bug](https://github.com/pixipace/chapters-landing/issues) · [Request Feature](https://github.com/pixipace/chapters-landing/issues)

</div>

---

## Overview

Chapters is a beautifully designed landing page for a Shopify app that enables merchants to sell online video courses directly from their store. Built with modern web technologies and optimized for conversions.

<div align="center">

### Desktop Preview

```
┌─────────────────────────────────────────────────────────────┐
│  ┌─────┐                              Features  Pricing  │▓▓│
│  │LOGO │                                         [Install]  │
│  └─────┘                                                    │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│              Sell Online Courses                            │
│              Directly from Shopify                          │
│                                                             │
│     Create beautiful video courses, manage enrollments,     │
│         and track student progress seamlessly.              │
│                                                             │
│        [Get Started Free]    [See How it Works]             │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│  ✓ Secure Video    ✓ Shopify Native    ✓ Auto Enrollment   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌──────────┐   ┌──────────┐   ┌──────────┐                │
│  │ Feature  │   │ Feature  │   │ Feature  │                │
│  │    1     │   │    2     │   │    3     │                │
│  └──────────┘   └──────────┘   └──────────┘                │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

## Features

<table>
<tr>
<td width="50%">

### Design
- Fully responsive layout
- Modern gradient aesthetics
- Smooth hover animations
- Professional typography
- Custom color palette

</td>
<td width="50%">

### Sections
- Hero with dual CTA
- Trust badges bar
- 6-card feature grid
- 4-step process flow
- Pricing card
- Footer with links

</td>
</tr>
</table>

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure & Semantics |
| ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) | Styling & Responsive Design |
| ![SVG](https://img.shields.io/badge/SVG-FFB13B?style=flat-square&logo=svg&logoColor=black) | Icons & Graphics |

---

## Quick Start

### Option 1: Direct Download

```bash
# Clone the repository
git clone https://github.com/pixipace/chapters-landing.git

# Navigate to directory
cd chapters-landing

# Open in browser
open index.html
```

### Option 2: Use as Template

Click the **"Use this template"** button at the top of this repository to create your own copy.

---

## Project Structure

```
chapters-landing/
├── index.html           # Home
├── features.html        # All features (hub)
├── pricing.html         # Pricing detail
├── courses.html         # Courses & video deep-dive
├── exams.html           # Examinations deep-dive
├── certificates.html    # Certificates deep-dive
├── live-classes.html    # Live classes deep-dive
├── storefront.html      # Sell on Shopify deep-dive
├── engagement.html      # Engage & grow deep-dive
├── privacy.html         # Privacy policy
├── terms.html           # Terms of service
├── zoom-setup.html      # Zoom integration guide
├── robots.txt           # Crawler directives
├── sitemap.xml          # Sitemap
├── assets/
│   ├── favicon.png      # Browser favicon
│   ├── logo.svg         # Brand wordmark
│   ├── icon.svg         # App icon ("C" mark)
│   ├── og-image.png     # Social share image (1200×630)
│   ├── og-image.svg     # Source for og-image.png
│   ├── site.css         # Shared styles (gradients, fonts, reveal, prose)
│   └── site.js          # Shared behaviour (mobile nav, reveal-on-scroll, year)
├── LICENSE              # MIT License
└── README.md            # Documentation
```

Every page shares one `<head>` (Tailwind CDN config + Inter/Fraunces fonts + `assets/site.css`),
one fixed nav with a Features dropdown, and one footer — keep these blocks identical across pages.

---

## Customization

### Colors

The landing page uses a custom color palette defined in Tailwind config:

```javascript
colors: {
    navy: {
        800: '#16376d',  // Primary dark blue
        900: '#0f2744',  // Footer background
    },
    teal: {
        500: '#25ad9f',  // Primary accent
        300: '#65d6ad',  // Light accent
    }
}
```

### Content

Edit `index.html` to customize:
- Hero headline and subtext
- Feature cards (icons, titles, descriptions)
- Pricing details
- Footer links and company info

---

## Pages Included

| Page | Description |
|------|-------------|
| `index.html` | Home — hero, six product pillars, storefront, how-it-works, pricing teaser, FAQ |
| `features.html` | Full feature hub, grouped by pillar |
| `pricing.html` | Free + 5% commission + optional storage, with examples and FAQ |
| `courses.html` | Course builder, secure video, player, quizzes & assignments |
| `exams.html` | Examinations — exam hall, question types, timed sittings, paid retakes |
| `certificates.html` | Branded, verifiable PDF certificates |
| `live-classes.html` | Live classes via Zoom |
| `storefront.html` | Native Shopify selling, blocks, auto-enrollment, branding |
| `engagement.html` | Q&A, reviews, email, push, PWA, analytics |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |
| `zoom-setup.html` | Zoom integration setup & usage guide |

---

## Performance

- **Zero JavaScript dependencies** (except Tailwind CDN)
- **Optimized SVG** icons and graphics
- **Semantic HTML** for accessibility
- **Mobile-first** responsive design

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| Edge | ✅ |
| IE11 | ❌ |

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## Author

<div align="center">

**Built with precision by [Pixipace](https://pixipace.com)**

[![Website](https://img.shields.io/badge/pixipace.com-000?style=for-the-badge&logo=vercel&logoColor=white)](https://pixipace.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pixipace)

*Crafting digital experiences that drive business growth.*

</div>

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:16376d,100:25ad9f&height=100&section=footer)

</div>
