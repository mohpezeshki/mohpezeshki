<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Mohammad Pezeshki — Machine Learning and Data Science" src="./assets/banner-light.svg">
</picture>

### Hi, I'm Mohammad 👋

I build machine learning systems and ship them as working products — not just notebooks. Most of what's here follows the same arc: train a model, then wrap it in a FastAPI backend and a React frontend so someone can actually use it.

Recently that's meant a **local-first voice dictation tool** running faster-whisper in-process, a **playlist-embedding recommender** trained on 12.9M track-playlist pairs, and a **deep-learning-vs-boosted-trees comparison** on 11M simulated particle collisions.

I care about reproducibility. Pinned dependencies, seeded runs, and a documented path from raw data to results on a clean clone.

<br>

### Selected work

**Full-stack ML applications**

| Project | What it is |
| :--- | :--- |
| **[Speak Fill](https://github.com/mohpezeshki/speak-fill)** | Build a form, then fill it by talking. Audio streams as raw PCM over a WebSocket to a local faster-whisper model — no API key, no external service — and an LLM maps free-form speech onto the right fields. FastAPI + React 19, installable as a single `speakfill` command. |
| **[Spotify Song Recommendation](https://github.com/mohpezeshki/Spotify-Song-Recommendation)** | Word2Vec trained on playlists-as-sentences: 157K playlist sequences, a 2.7M-track vocabulary, recommendations by cosine similarity in embedding space. Fuzzy search via Postgres trigram indexes, enriched with live cover art and Spotify links. |

**Modeling and data**

| Project | What it is |
| :--- | :--- |
| **[Higgs Boson Detection](https://github.com/mohpezeshki/Higgs-Boson-Detection)** | Deep feedforward network vs XGBoost on 11M simulated collision events. Full metric breakdown — ROC AUC, AMS, calibration — plus threshold analysis showing where each model actually wins. |
| **[Plant Identifier & AI Care Assistant](https://github.com/mohpezeshki/Plant-identifier-and-ai-care-assistant)** | Image-based species identification paired with a language model that generates tailored care guidance. |
| **[LinkedIn Scraper](https://github.com/mohpezeshki/Linkedin-Scraper)** | Python client covering 45 endpoints of the Fresh LinkedIn Scraper API — jobs, profiles, companies, posts, ads, groups — with input validation on every category. |

<br>

### Toolbox

**ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)
![gensim](https://img.shields.io/badge/gensim-4B5563?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Data**
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Shipping**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=uv&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br>

<details>
<summary><b>A bit more about how I work</b></summary>

<br>

- **Baselines before architecture.** A tuned XGBoost run tells you whether the problem is hard or your features are. It also wins more often than people expect — it did on the Higgs data.
- **Metrics that match the domain.** Accuracy hides a model that misses two-thirds of the positive class. Physics has AMS; every domain has something better than the default.
- **Local-first where it's possible.** Speak Fill runs speech-to-text in-process rather than calling out to a paid API. Fewer keys, fewer failure modes, no data leaving the machine.
- **Notebooks explore, modules ship.** Exploration lives in `notebooks/`; anything that runs twice moves into `src/` with a CLI entry point.
- **Write the architecture down.** If a design decision took an afternoon to reach, it's worth a paragraph in `ARCHITECTURE.md`.

</details>

<br>

### Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-pezeshki94/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohpezeshki)
&nbsp;
![Followers](https://img.shields.io/github/followers/mohpezeshki?style=for-the-badge&logo=github&label=Followers&labelColor=181717&color=2dd4bf)
![Stars](https://img.shields.io/github/stars/mohpezeshki?affiliations=OWNER&style=for-the-badge&logo=github&label=Stars&labelColor=181717&color=818cf8)

Open to conversations about applied ML, speech and language tooling, and anything involving a dataset large enough to be annoying.
