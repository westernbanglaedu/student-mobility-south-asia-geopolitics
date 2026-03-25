# Student Mobility South Asia — Research Website

This repository contains the static, SEO-optimized website for the white paper: **Student Mobility in South Asia (2020–2025): Opportunity, Disruption, and Decision-Making**. 

The site is built as purely static HTML/CSS and is optimized for both traditional Search Engines (Google) and AI Generative Answer Engines (GEO).

## 🚀 Live Site
**[View the Website Here](https://westernbanglaedu.github.io/student-mobility-south-asia-geopolitics/)**

## 🏗 Directory Structure
Since this repository serves the website directly, the core files are at the root level:

- `index.html` — The main white paper overview and entry point.
- `pillar-study-abroad-bangladesh.html` — Pillar guide covering study abroad choices for Bangladeshi students.
- `blog/` — Contains authority articles analyzing UNESCO data and decision factors.
- `conversion/` — Contains practical, action-oriented guides (e.g., studying in India, Indian Student visa requirements).
- `assets/` — Images and Open Graph assets.
- `student-mobility-south-asia-2020-2025.pdf` — The full, downloadable white paper PDF.
- `sitemap.xml` & `robots.txt` — SEO infrastructure.
- `_config.yml` — Tells GitHub Pages to parse the site using the Jekyll environment globally.

## 🔎 SEO & GEO Architecture
This site was specifically engineered for high visibility on AI Search Engines (Perplexity, Google AI Overviews, SearchGPT) and traditional search:

1. **JSON-LD Structured Data**: Every page includes strict `FAQPage` and `Article`/`ScholarlyArticle` schemas.
2. **Authoritative Citation**: The site is explicitly linked to the published DOI research record (`10.5281/zenodo.19208750`) to establish E-E-A-T (Experience, Expertise, Authoritativeness, and Trustworthiness).
3. **Canonical Routing**: All canonical metadata hard-links to the `westernbanglaedu.github.io` domain to prevent duplicate content indexing.
4. **Fast Load Times**: Built without heavy JavaScript frameworks. Styled entirely with lightweight inline/CSS rules and Google Fonts (Inter) loaded with `display=swap`.

## 💻 Running Locally
Because this is a static site without a build step, you can run it locally using any basic HTTP server right from the root of this folder.

**Using Python:**
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

**Using Node.js (npx):**
```bash
npx http-server
```

## 🛠 Deployment
This site is configured to deploy seamlessly to **GitHub Pages**. 
When pushing to the `main` branch, ensure your GitHub repository settings under **Settings > Pages** are set to deploy from the `/ (root)` directory.
# student-mobility-south-asia-geopolitics
