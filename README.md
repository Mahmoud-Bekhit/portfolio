# Mahmoud Bekhit — AI & ML Engineer Portfolio

[![Live Site](https://img.shields.io/badge/Live%20Site-nagato1pain2.github.io%2Fportfolio-22d3ee?style=for-the-badge&logo=githubpages&logoColor=white)](https://nagato1pain2.github.io/portfolio/)

Personal portfolio of **Mahmoud Bekhit**, a Computer & Control Engineer working on machine learning, computer vision and data analytics.

**🌐 Live: [nagato1pain2.github.io/portfolio](https://nagato1pain2.github.io/portfolio/)**

---

## Featured projects

| Project | Area | Highlight | Code |
|---|---|---|---|
| **Plant Disease Detection** | Deep Learning · Computer Vision | Two-stage CNN pipeline (leaf validator + classifier), ~93% accuracy on 38 classes, Gradio app | [repo](https://github.com/Nagato1pain2/plant-disease-detection-deep-learning) |
| **AI Employment Impact Analytics** | ML · Analytics | 15,000 records, 7-table star schema, 9 regressors benchmarked, Extra Trees R² 0.957 | [repo](https://github.com/Nagato1pain2/ai-employment-impact-analytics-ml) |
| **FC Barcelona Match Analytics** | BI · Data Modeling | 562 matches (2015–2025) in an interactive Excel / Power Pivot dashboard | [repo](https://github.com/Nagato1pain2/fc-barcelona-match-analysis-excel) |
| **Olist Retail Intelligence** | Data Science (in progress) | E-commerce case study: SQL, RFM segmentation, delivery-risk model | [repo](https://github.com/Nagato1pain2/olist-retail-intelligence) |

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
├── index.html                  # the whole site
├── assets/
│   ├── Mahmoud_Bekhit_CV.pdf   # "Download CV" button
│   ├── demo-diagnosed.jpg      # pipeline demo output (leaf)
│   ├── demo-rejected.jpg       # pipeline demo output (non-leaf)
│   ├── sample-leaf.jpg         # demo input
│   └── sample-moon.jpg         # demo input
└── README.md
```

## Run locally

```bash
git clone https://github.com/Nagato1pain2/portfolio.git
cd portfolio
python -m http.server 8000   # then open http://localhost:8000
```

## Deploy

GitHub Pages serves the `main` branch root. Any push to `main` updates the live site within a minute or two.

## Contact

- LinkedIn: [mahmoud-ahmed-data](https://linkedin.com/in/mahmoud-ahmed-data)
- Email: [mahmoudahmed1147@gmail.com](mailto:mahmoudahmed1147@gmail.com)
- GitHub: [@Nagato1pain2](https://github.com/Nagato1pain2)
