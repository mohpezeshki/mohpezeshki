<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Mohammad Pezeshki — Machine Learning and Data Science" src="./assets/banner-light.svg">
</picture>

### Hi, I'm Mohammad 👋

I build machine learning systems and the plumbing that keeps them running — training pipelines, evaluation harnesses, and API clients that turn messy external data into something a model can actually use.

Lately I've been working on **high-energy physics classification**, reproducing the Baldi et al. (2014) deep-learning-vs-boosted-trees comparison on the UCI HIGGS dataset, and on **applied vision + LLM tooling** for plant identification and care.

I care about reproducibility. Every project here ships with pinned dependencies, a documented pipeline, and results you can regenerate from a clean clone.

<br>

### Selected work

| Project | What it is |
| :--- | :--- |
| **[Higgs Boson Detection](https://github.com/mohpezeshki/Higgs-Boson-Detection)** | Deep feedforward network vs XGBoost on 11M simulated collision events. Full metric breakdown — ROC AUC, AMS, calibration — plus threshold analysis showing where each model actually wins. |
| **[Plant Identifier & AI Care Assistant](https://github.com/mohpezeshki/Plant-identifier-and-ai-care-assistant)** | Image-based species identification paired with a language model that generates tailored care guidance. |
| **[LinkedIn Scraper](https://github.com/mohpezeshki/Linkedin-Scraper)** | Python client covering 45 endpoints of the Fresh LinkedIn Scraper API — jobs, profiles, companies, posts, ads, groups — with input validation on every category. |

<br>

### Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br>

<details>
<summary><b>A bit more about how I work</b></summary>

<br>

- **Baselines before architecture.** A tuned XGBoost run tells you whether the problem is hard or your features are. It also tends to win more often than people expect.
- **Metrics that match the domain.** Accuracy hides a model that misses two-thirds of the positive class. Physics has AMS; every domain has something better than the default.
- **Reproducible or it didn't happen.** `uv.lock`, seeded runs, checkpoints, and a `main.py` that goes from raw data to plots in one command.
- **Notebooks explore, modules ship.** Exploration lives in `notebooks/`, but anything that runs twice moves into `src/`.

</details>

<br>

### GitHub stats

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=mohpezeshki&show_icons=true&hide_border=true&theme=github_dark&icon_color=2dd4bf&title_color=818cf8">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=mohpezeshki&show_icons=true&hide_border=true&title_color=4f46e5&icon_color=0d9488">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=mohpezeshki&layout=compact&hide_border=true&theme=github_dark&title_color=818cf8">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohpezeshki&layout=compact&hide_border=true&title_color=4f46e5">
</picture>

<br>
<br>

### Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-pezeshki94/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohpezeshki)

Open to conversations about applied ML, scientific computing, and anything involving a dataset large enough to be annoying.
