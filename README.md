# saurabhraj-115.github.io

Personal portfolio of **Saurabh Raj** — AI Product Manager & UVA Darden MBA candidate.

🔗 **Live:** https://saurabhraj-115.github.io

## About this site

A single-page, self-contained portfolio built from scratch — no framework, no build step, no runtime dependencies. Just `index.html` with inline CSS and vanilla JS.

**Features**
- Light / dark theme (respects system preference, remembers your choice)
- Signature animated voice-waveform hero (a nod to voice-AI work) on `<canvas>`
- Scroll-reveal animations, animated counters, interactive cards
- Fully responsive (desktop → mobile) with an accessible mobile menu
- SEO: Open Graph, Twitter cards, JSON-LD `Person` schema
- Accessible: keyboard focus states, `prefers-reduced-motion` support, semantic landmarks
- Résumé download at `assets/Saurabh_Raj_Resume.pdf`

## Structure

```
index.html                       # the whole site (HTML + CSS + JS)
assets/img/                      # portrait + testimonial photos
assets/Saurabh_Raj_Resume.pdf    # downloadable résumé
.nojekyll                        # serve as static files (skip Jekyll)
```

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

GitHub Pages serves the `master` branch root automatically. Push to publish.

---
*Content is drawn from Saurabh's résumé. Testimonials are from real colleagues.*
