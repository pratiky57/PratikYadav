# yadavpratik.com.np

Personal website of **Pratik Yadav** — computer engineering student. This repository holds the static pages behind [yadavpratik.com.np](https://yadavpratik.com.np/): a couple of short blog notes and a browser-based math game built for classroom use.

## 📄 Pages

### `notes.html`
A small notes/blog page with two posts:
- **Metacognition** — thinking about thinking, and why it matters for learning.
- **Seeing vs. a Camera** — the difference between how human eyes perceive the world and how a camera captures it.

### `tug-of-war-math.html`
A free, self-contained two-team math game — **Tug of War: Math**. Built for use on a classroom smart board / interactive display.

- Two teams (Team Gold vs. Team Crimson) each get their own question and number pad.
- Every correct answer pulls a rope toward that team's side — first team to the target score wins.
- Adjustable question type (multiplication only or mixed +, −, ×), number range, and win score.
- Responsive layout for phone, tablet, and desktop, with a light/dark theme toggle.
- No build step, no dependencies beyond a Google Fonts link — just open the HTML file.
- SEO-ready: meta tags, Open Graph/Twitter cards, and structured data included.

## 🛠️ Tech stack

Plain **HTML, CSS, and vanilla JavaScript** — no frameworks, no bundler, no npm install. Every page is a single self-contained file, which keeps things fast and easy to host anywhere static files are served (GitHub Pages, Netlify, cPanel, etc.).

## 🚀 Running locally

No build tools needed. Just open a file directly in your browser:

```bash
# clone the repo
git clone https://github.com/pratiky57/PratikYadav.git
cd PratikYadav

# open any page directly
open tug-of-war-math.html   # macOS
start tug-of-war-math.html  # Windows
xdg-open tug-of-war-math.html  # Linux
```

Or serve the folder with any static server, e.g.:

```bash
npx serve .
```

## 🌐 Live site

- Website: [yadavpratik.com.np](https://yadavpratik.com.np/)
- Tug of War: Math: [yadavpratik.com.np/tug-of-war-math.html](https://yadavpratik.com.np/tug-of-war-math.html)

## 👤 Author

**Pratik Yadav** — Computer Engineering student.
Website: [yadavpratik.com.np](https://yadavpratik.com.np/)

## 📄 License

© 2026 Pratik Yadav. All rights reserved.
