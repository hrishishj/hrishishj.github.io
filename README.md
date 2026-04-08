# Hrishish Jain — Portfolio

Personal portfolio website for **Hrishish Jain**, Gen AI Engineer at Capgemini.

Live at → **[hrishishj.github.io](https://hrishishj.github.io)**

---

## About

Minimal, fast, single-file portfolio built with semantic HTML, vanilla CSS, and a tiny scroll-reveal script. No frameworks, no build tools, no dependencies — just drop and deploy.

Design inspired by editorial print aesthetics: warm parchment tones, Fraunces serif typography, and a terracotta accent palette.

---

## Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, grid, flexbox, IntersectionObserver animations
- **Fonts** — [Fraunces](https://fonts.google.com/specimen/Fraunces) · [Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans) · [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts
- **JS** — ~15 lines, scroll reveal only
- **Hosting** — GitHub Pages (free)

---

## Sections

- **Hero** — name, positioning statement, terminal-style AI prompt
- **About** — bio + stat cards
- **Projects** — Enterprise CRAG System, AI DevOps Agents
- **Skills** — categorised tag grid (Gen AI, Cloud, Backend, Data)
- **Certifications** — Google ML Engineer, Microsoft AI-900, Gen AI
- **Contact** — email, LinkedIn, GitHub

---

## Local Preview

No setup needed. Just open the file:

```bash
# Option 1 — open directly in browser
open index.html

# Option 2 — serve locally (optional, needs Python)
python -m http.server 8000
# then visit http://localhost:8000
```

---

## Deployment

Hosted on **GitHub Pages** from the `main` branch root.

Any push to `main` → site updates automatically within ~60 seconds.

---

## Customisation

All content lives in `index.html`. To update:

| What | Where in the file |
|---|---|
| Name / title | `<h1>` in hero section |
| Bio text | `#about` section |
| Project links | `href` on `.project-cta` anchors |
| Skills | `.skill-tags` inside each `.skill-group` |
| Email / socials | `#contact` section |
| Colors | `:root` CSS variables at top of `<style>` |

---

## Contact

- Email — hrishishjain21@gmail.com
- LinkedIn — [hrishish-jain-463a83223](https://www.linkedin.com/in/hrishish-jain-463a83223/)
- GitHub — [@hrishishj](https://github.com/hrishishj)
