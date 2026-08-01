# Simarin Naidoo — Resume Site

A modern, single-page resume/portfolio site — dark theme, glassmorphism cards, animated gradient background, and scroll-reveal animations. Built with plain HTML, CSS, and JavaScript, so it needs no build step or dependencies.

**Live sections:** Hero · About · Experience · Projects · Skills · Achievements · Education · Contact

## Tech

- HTML5 / CSS3 (custom properties, grid, animations)
- Vanilla JavaScript (`IntersectionObserver` for scroll reveals + active nav highlighting)
- [Google Fonts](https://fonts.google.com/): Sora, Inter, JetBrains Mono

No frameworks, no package manager, no build tooling.

## Project Structure

```
.
├── index.html          # Page content and layout
├── css/
│   └── style.css       # All styling, theme, and animations
├── js/
│   └── script.js       # Nav behavior, scroll progress, reveal-on-scroll
└── assets/
    ├── profile.jpg              # Profile photo
    └── Simarin_Naidoo_CV.pdf    # Downloadable CV
```

## Running Locally

Just open `index.html` in a browser, or serve it locally:

```bash
# Python
python -m http.server 8080

# Node
npx serve .
```

Then visit `http://localhost:8080`.

## Deploying

This is a static site — deploy the folder as-is to any static host:

- **GitHub Pages**: push to a repo, enable Pages on the `main` branch (root or `/docs`).
- **Netlify / Vercel**: drag-and-drop the folder or connect the repo; no build command needed.

## Customizing

- **Content**: edit the relevant section in `index.html`.
- **Colors/theme**: adjust the CSS custom properties at the top of `css/style.css` (`:root`).
- **CV file**: replace `assets/Simarin_Naidoo_CV.pdf` (keep the same filename, or update the `href`/`download` links in `index.html`).
- **Photo**: replace `assets/profile.jpg` (keep the same filename, or update the `src` in the hero section).

## License

Personal project — all rights reserved.
