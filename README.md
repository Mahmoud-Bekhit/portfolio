# Mahmoud Bekhit — AI & ML Engineer Portfolio

[![Live Site](https://img.shields.io/badge/Live%20Site-mahmoud-bekhit.github.io%2Fportfolio-22d3ee?style=for-the-badge&logo=githubpages&logoColor=white)](https://mahmoud-bekhit.github.io/portfolio/)

Personal portfolio of **Mahmoud Bekhit**, a Computer & Control Engineer working on machine learning, computer vision and data analytics.

**🌐 Live: [mahmoud-bekhit.github.io/portfolio](https://mahmoud-bekhit.github.io/portfolio/)**

---

## Featured projects

| Project | Area | Highlight | Code |
|---|---|---|---|
| **Plant Disease Detection** | Deep Learning · Computer Vision | Two-stage CNN pipeline (leaf validator + classifier), ~93% accuracy on 38 classes, Gradio app | [repo](https://github.com/Mahmoud-Bekhit/plant-disease-detection-deep-learning) |
| **AI Employment Impact Analytics** | ML · Analytics | 15,000 records, 7-table star schema, 9 regressors benchmarked, Extra Trees R² 0.957 | [repo](https://github.com/Mahmoud-Bekhit/ai-employment-impact-analytics-ml) |
| **FC Barcelona Match Analytics** | BI · Data Modeling | 562 matches (2015–2025) in an interactive Excel / Power Pivot dashboard | [repo](https://github.com/Mahmoud-Bekhit/fc-barcelona-match-analysis-excel) |
| **Olist Retail Intelligence** | Data Science (in progress) | E-commerce case study: SQL, RFM segmentation, delivery-risk model | [repo](https://github.com/Mahmoud-Bekhit/olist-retail-intelligence) |

## Site features

- Interactive terminal in the About section (`help`, `whoami`, `projects`, `skills`, `contact`)
- Project filters (Deep Learning / Machine Learning / BI & Analytics)
- Replay of the plant-disease inference pipeline
- Live GitHub activity pulled from the GitHub API
- Responsive layout, downloadable CV

## Tech stack

Single static page: **HTML, CSS and vanilla JavaScript**, no build step. Fonts from Google Fonts. Hosted on **GitHub Pages**.

## Project structure

```
portfolio/
├── index.html   # the whole site, with images and CV embedded inline
└── README.md
```

Everything (demo images and the downloadable CV) is embedded inside `index.html`, so the site is a single self-contained file with no external assets.

## Run locally

```bash
git clone https://github.com/Mahmoud-Bekhit/portfolio.git
cd portfolio
python -m http.server 8000   # then open http://localhost:8000
```

## Deploy

GitHub Pages serves the `main` branch root. Any push to `main` updates the live site within a minute or two.

## Contact

- LinkedIn: [mahmoud-ahmed-data](https://linkedin.com/in/mahmoud-ahmed-data)
- Email: [mahmoudahmed1147@gmail.com](mailto:mahmoudahmed1147@gmail.com)
- GitHub: [@Mahmoud-Bekhit](https://github.com/Mahmoud-Bekhit)
