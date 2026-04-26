# Harsh Lakhera — Personal Portfolio

A designer-crafted personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build tools — just clean, fast, and intentional code.

---

## Live Preview

> Deploy to [GitHub Pages](https://pages.github.com/) or drag `index.html` into [Netlify Drop](https://app.netlify.com/drop) for an instant live URL.

---

## About the Project

This portfolio was designed to feel like a **printed editorial magazine crossed with a developer's notebook** — not a generic AI template. Every design decision was intentional:

- **Palette:** Warm paper `#f5f0e8` + deep ink `#0d0d0d` + rust red `#c0392b`
- **Typography:** DM Serif Display (editorial) × Syne (geometric sans) × JetBrains Mono (technical)
- **Layout:** Asymmetric grids, sticky sidebars, full-width dark panels — no stacked card clichés
- **Animations:** Custom cursor with trailing ring, orbital hero graphic, staggered scroll reveals

---

## Features

- **Zero dependencies** — single HTML file, self-contained
- **Fully responsive** — mobile-first breakpoints
- **Accessible** — semantic HTML5, proper heading hierarchy, sufficient color contrast
- **Custom cursor** — smooth dot + ring follower (auto-hidden on touch devices)
- **Scroll-reveal animations** — IntersectionObserver-powered, no library needed
- **Fast loading** — no JavaScript frameworks, fonts loaded via Google Fonts

---

## Project Structure

```
portfolio/
├── index.html          # The entire site (HTML + CSS + JS, single file)
└── README.md           # This file
```

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | Introduction | Hero with name, tagline, and orbital animation |
| 02 | About | Story-driven bio with academic stats |
| 03 | Skills | Dark-panel layout with language, tools, and soft skills |
| 04 | Selected Work | Case-study style project rows |
| 05 | Journey | Two-column education and experience timeline |
| 06 | Achievements | Sticky-sidebar achievement list |
| 07 | Contact | Full-width rust-red contact panel |

---

## Getting Started

### Option 1 — Open locally

```bash
# Clone the repo
git clone https://github.com/your-username/portfolio.git

# Open in browser
open index.html
```

No server needed. Works directly from the file system.

### Option 2 — GitHub Pages

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://your-username.github.io/portfolio`

### Option 3 — Netlify Drop

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the `index.html` file
3. Get an instant live URL

---

## Customization

All content is in `index.html`. Key areas to update:

| What | Where to find it |
|------|-----------------|
| Name, tagline, bio | `<!-- HERO -->` and `<!-- ABOUT -->` sections |
| Skills list | `<!-- SKILLS -->` section |
| Projects | `<!-- PROJECTS -->` section — add/remove `.project-card` blocks |
| Education & Experience | `<!-- TIMELINE -->` section |
| Contact details | `<!-- CONTACT -->` section |
| Color palette | `:root` CSS variables at the top of `<style>` |
| Fonts | `<link>` tag in `<head>` + `--display`, `--sans`, `--mono` variables |

---

## Color Variables

```css
:root {
  --ink:    #0d0d0d;   /* Primary text, dark backgrounds */
  --paper:  #f5f0e8;   /* Page background */
  --rust:   #c0392b;   /* Accent, CTAs, highlights */
  --sand:   #d9c9a8;   /* Dividers, subtle borders */
  --muted:  #7a7060;   /* Secondary text */
}
```

---

## Browser Support

Works in all modern browsers: Chrome, Firefox, Safari, Edge.  
Custom cursor is automatically hidden on touch/mobile devices.

---

## Author

**Harsh Lakhera**  
B.Tech Computer Science Engineering — BIET Jhansi (2026–2030)  
📧 harshlakhera538@gmail.com  
📍 Jhansi, Uttar Pradesh

---

## License

This project is open source and available under the [MIT License](LICENSE).  
Feel free to fork, adapt, and make it your own — just don't copy the content.
