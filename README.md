# Ohnmar Soe — Personal Portfolio

Live site: **https://ohnmarsoe-git.github.io/personal-portfolio/**

Personal branding site for Ohnmar Soe, Project Manager and Technical Lead with 10+ years in software delivery and 2+ years leading Odoo ERP implementations.

- [Download CV (PDF)](cv/Ohnmar_Soe_CV_Project_Manager.pdf)
- [LinkedIn](https://www.linkedin.com/in/ohnmar-soe-79834357)

## Structure

| Path | Purpose |
|---|---|
| `index.html` | Single-page site content |
| `assets/css/style.css` | Styles (light / dark theme, responsive) |
| `assets/js/main.js` | Navigation, theme toggle, scroll animations |
| `assets/img/` | Profile photo |
| `cv/cv.html` | CV source (A4, print-ready) |
| `cv/Ohnmar_Soe_CV_Project_Manager.pdf` | Exported CV |

## Run locally

```bash
python3 -m http.server 5173
```

Then open http://localhost:5173.

## Re-export the CV PDF

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --no-pdf-header-footer \
  --print-to-pdf="$PWD/cv/Ohnmar_Soe_CV_Project_Manager.pdf" "file://$PWD/cv/cv.html"
```

Deployed with GitHub Pages from the `main` branch.
