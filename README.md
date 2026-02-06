# SummitEdge — Consulting / Agency Landing

Elegant, responsive consulting landing page built with **Tailwind CSS (CDN)** and vanilla JavaScript.
This repository contains a single static page (`index.html`) designed as a portfolio piece to showcase product strategy and growth consulting work.

---

## What’s included
- `index.html` — full landing page (Tailwind CDN, JS handlers for modal & contact form).
- `assets/` — images and logos used by the page (place your images here).
- `README.md` — this file.
- `screenshot.png` — preview image for the project.

---

## Preview
Use the included `screenshot.png` as a quick thumbnail in your portfolio or README. You can also open `index.html` locally (instructions below).

---

## ✨ Key Features

- Fully responsive layout (mobile → desktop)
- Clean hero section with clear value proposition
- Services section with structured content blocks
- Case studies / social proof section
- Call-to-action sections optimized for conversion
- Modal interaction (JavaScript)
- Tailwind CSS utility-first styling (no external CSS files)
- SEO-friendly semantic HTML structure

---

## 🛠 Tech Stack

- **HTML5**
- **Tailwind CSS (CDN version)**
- **Vanilla JavaScript**
- **GitHub Pages** (deployment)

No frameworks, no build tools - intentionally kept simple to showcase fundamentals and design sense.

---

## 📁 Project Structure
landing-consulting/
│
├── index.html
├── README.md
├── screenshot.png
│
├── assets/
│ ├── consulting-team.jpg
│ ├── logo-a.png
│ ├── logo-b.png
│ ├── case-a.jpg
│
└── (optional future folders)


---

## How to publish on GitHub Pages (step-by-step)

> I **cannot** push to your GitHub or enable Pages for you from here. Below are the exact commands and UI steps you should run on your machine to deploy the site. If you want, run them and paste any terminal output here and I’ll help debug.

### Option A — Create repo on GitHub website (recommended if you prefer UI)
1. Create a new **public** repository on GitHub named `landing-consulting` (or a name of your choice).
2. From your local project folder (where `index.html` is), run the following:

```bash
git init
git add .
git commit -m "Initial commit: SummitEdge consulting landing"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/landing-consulting.git
git push -u origin main
```

3. On GitHub, open the repository → **Settings** → **Pages** (or "Pages & deployments").
   - Under "Build and deployment" or "Source", select **Branch: main** and folder **/ (root)**.
   - Save. Your site will be published at:
     `https://<YOUR_GITHUB_USERNAME>.github.io/landing-consulting/`
   - Wait a minute and then visit the URL.

### Option B — Create & push repo using the GitHub CLI
(If you have `gh` installed and authenticated)

```bash
cd /path/to/landing-consulting
gh repo create <YOUR_GITHUB_USERNAME>/landing-consulting --public --source=. --remote=origin --push
# (Then enable Pages via web UI as above, or use gh api if you prefer advanced automation)
```

---

## Netlify / Vercel (optional)
If you prefer automatic deploys and previews, connect the GitHub repo to **Netlify** or **Vercel**:
- Netlify: "New site from Git" → select repo → Deploy.
- Vercel: "Import Project" → select repo → Deploy.
Both services will auto-deploy on each push. For CDN + static HTML no build is needed.

---

## Image credits & suggestions
Download free asset images from:
- [Unsplash](https://unsplash.com) — keywords: "team meeting", "startup dashboard", "product analytics"
- [Pexels](https://pexels.com)

Place images in `assets/` with the following names (used by `index.html`):
- `consulting-team.jpg`
- `logo-a.png`, `logo-b.png`, `logo-c.png`
- `case-a.jpg`, `case-b.jpg`, `case-c.jpg`
- `og-summitedge.png` (optional - for rich previews)

---

## License
MIT — feel free to reuse and modify for your portfolio.

---

## Need help?
Run the git commands above and paste any errors here. I’ll walk you through fixing them and verifying the GitHub Pages URL.
