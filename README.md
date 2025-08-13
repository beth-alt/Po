# Cybersecurity Portfolio

A simple, fast, accessible one‑page portfolio for an aspiring cybersecurity analyst. Built with semantic HTML and a touch of CSS — no frameworks or build tools required.

---

## Table of Contents

* [Demo](#demo)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Project Structure](#project-structure)
* [Getting Started](#getting-started)
* [Customization Guide](#customization-guide)

  * [Branding & Hero](#branding--hero)
  * [About & Timeline](#about--timeline)
  * [Skills](#skills)
  * [Projects](#projects)
  * [Contact Form](#contact-form)
  * [Colors & Theme](#colors--theme)
* [Accessibility (a11y)](#accessibility-a11y)
* [SEO & Social Cards](#seo--social-cards)
* [Performance Tips](#performance-tips)
* [Deployment](#deployment)

  * [GitHub Pages](#github-pages)
  * [Netlify](#netlify)
* [Screenshots](#screenshots)
* [Roadmap / Ideas](#roadmap--ideas)
* [Attribution](#attribution)
* [License](#license)
* [Contact](#contact)

---


## Features

* **Zero build**: single `index.html` with inline CSS, ready to drop on any static host.
* **Responsive layout**: grid-based design adapts to phones, tablets, and desktops.
* **Accessible by default**: semantic landmarks (`<nav>`, `<header>`, `<section>`), labels, focusable controls, and reduced motion-friendly.
* **SEO-ready**: descriptive title/description, Open Graph tags, and social share preview.
* **Portfolio sections**: About, Skills, Projects, Highlights, and Contact.
* **Lightweight interactions**: small, accessible mobile menu toggle.

---

## Tech Stack

* **HTML5** + **CSS3** custom properties, responsive grid
* **Vanilla JS** tiny menu toggle
* **Hosting**: GitHub

---

## Project Structure

```
.
├── index.html   # Main one‑page site (HTML, CSS, small JS)

```
---


### Colors & Theme

Global colors live in the `:root` CSS custom properties:

```css
:root{
  --bg:#0b1220; --card:#0f172a; --muted:#94a3b8; --text:#e2e8f0;
  --brand:#22d3ee; --brand-2:#a78bfa; --ring:0 0 0 2px var(--brand);
  --shadow:0 10px 30px rgba(0,0,0,.35); --radius:16px;
}
```

---

## Accessibility (a11y)

This template uses:

* Semantic landmarks (`<nav>`, `<header>`, `<section>`, `<footer>`)
* Meaningful `aria-label`s and `sr-only` text
* Sufficient color contrast and large touch targets

**Recommended checks:**

1. Run **Lighthouse** (Chrome DevTools → Lighthouse → Accessibility).
2. Test keyboard navigation: `Tab`, `Shift+Tab`, `Enter`, `Space`, arrow keys.


## Roadmap / Ideas

* Dark‑mode toggle (current palette is already dark‑friendly)
* Project pages fed by a simple JSON file (data‑driven content)
* Blog/Notes section for lab write‑ups (static Markdown)
* Analytics (privacy‑friendly: Plausible, Umami, GoatCounter)

---

## Attribution

* **Hero image**: Unsplash (see `img src` in the hero). Replace or host locally with credit as required by the image license.
* **Inter font**: Google Fonts.

---

## License

```
MIT License — Copyright (c) 2025 Bethlehem B
```


---

### Notes for Reviewers/Hiring Managers

* Projects highlight **reproducible labs** (Nessus, Wireshark, Burp Suite, Recon‑ng, John). Each emphasizes findings, remediation, and communication to technical & non‑technical audiences.
* Code is intentionally minimal for transparency and portability.
