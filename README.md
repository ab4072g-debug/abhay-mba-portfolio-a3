# Abhay Partap Thakur – MBA Portfolio Website (Assignment 3)

Live site: https://ab4072g-debug.github.io/abhay-mba-portfolio-a3/

This repository contains a multi-page MBA portfolio website built with **Quarto** and hosted on **GitHub Pages**.

## Pages
- **Home/About** (`index.qmd`)
- **Resume** (`resume.qmd`) – includes an “Open resume (PDF)” button
- **Projects/Case Studies** (`projects.qmd`)
- **Skills & Certifications** (`skills.qmd`)
- **Leadership & Community** (`leadership.qmd`)
- **Contact** (`contact.qmd`)
- **Appendix** (`appendix.md`) – LLM prompts/outputs + revisions + citations
- **Reflection** (`reflection-a3.md`) – 300–500 word reflection on LLM use

## Build locally (Quarto)
1. Install Quarto: https://quarto.org/
2. From the repo root, run:
   ```bash
   quarto render
   ```
3. The rendered website will be written to the `docs/` folder (configured in `_quarto.yml`).

## Deploy on GitHub Pages
This site is deployed using **GitHub Pages** with:
- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/docs`

After editing any `.qmd` or `.md` source files:
1. Run `quarto render`
2. Commit both the source changes and the updated `docs/` output
3. Push to GitHub

## File structure (expected)
- `_quarto.yml` – site configuration (navbar, footer, output-dir)
- `*.qmd` / `*.md` – page source files
- `styles.css` – custom theme styling
- `assets/` – downloadable files (e.g., `resume.pdf`) and shared site assets
- `images/` – images used in pages (optional; keep paths consistent)
- `docs/` – rendered output used by GitHub Pages (do not hand-edit)

## LLM disclosure and citations
- LLM-assisted outlining/drafting is documented in `appendix.md`.
- Any sources referenced are listed in the appendix references section.
