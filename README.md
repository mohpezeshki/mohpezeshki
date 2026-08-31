<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Mohammad Pezeshki — AI / Machine Learning Engineer" src="./assets/banner-light.svg">
</picture>

### Hi, I'm Mohammad 👋

AI/ML engineer with a software-engineering foundation. I work across the full path from model to product: training and fine-tuning deep learning models, building LLM-backed systems with retrieval and structured outputs, and deploying them as real services rather than leaving them in notebooks.

**What I focus on**

- **LLM systems** — RAG pipelines with hybrid retrieval and reranking, LoRA fine-tuning, prompt design for structured JSON outputs, hallucination guardrails, and evaluation that goes beyond eyeballing answers.
- **Deep learning** — CNNs and transformers in PyTorch, transfer learning, and computer vision including 3D perception on point clouds.
- **Classical ML** — gradient boosting, embedding models, and the unglamorous baselines that tell you whether a neural network is even worth training.
- **Production engineering** — FastAPI, WebSockets, Postgres, Docker, and React frontends, so the model reaches a user.

I also work on decision-making under uncertainty — Markov Decision Processes and Bayesian methods — in a research context.

<br>

### Selected work

**LLM and retrieval systems**

| Project | What it is |
| :--- | :--- |
| **[Speak Fill](https://github.com/mohpezeshki/speak-fill)** | Voice-dictated form filling. The browser streams 16 kHz PCM over a WebSocket to a FastAPI backend running faster-whisper in-process, reconstructing an interim/final transcript contract through polled re-transcription with bounded chunk commits. An LLM maps free-form speech onto an arbitrary form schema as `{field_key: value}` JSON, with an explicit null contract for low-confidence values and anti-cross-fill constraints. Runs against GPT-4o-mini or a local Qwen2.5-7B-Instruct behind one provider flag. |
| **[Spotify Song Recommendation](https://github.com/mohpezeshki/Spotify-Song-Recommendation)** | Word2Vec trained on playlists-as-sentences — 157K playlist sequences, a 2.7M-track vocabulary, recommendations by cosine similarity in embedding space. Postgres trigram search, live metadata enrichment, React 19 + Tailwind frontend. |
| **[Plant Identifier & AI Care Assistant](https://github.com/mohpezeshki/Plant-identifier-and-ai-care-assistant)** | A fine-tuned EfficientNet identifies 50 houseplant species; an LLM generates location- and season-aware care advice with Pydantic-structured outputs, hallucination guardrails, and response caching. Deployed on Hugging Face Spaces. |

**Modeling and data**

| Project | What it is |
| :--- | :--- |
| **[Higgs Boson Detection](https://github.com/mohpezeshki/Higgs-Boson-Detection)** | Deep feedforward network vs XGBoost on the UCI HIGGS dataset (28 features, 11M events). XGBoost led on AUC (0.81 vs 0.74) and calibration (Brier 0.18 vs 0.26); the network won on recall (0.77 vs 0.32) and F1 (0.76 vs 0.48) — a clean illustration of the precision/recall trade-off between model families. |
| **[LinkedIn Scraper](https://github.com/mohpezeshki/Linkedin-Scraper)** | Python client covering 45 endpoints of the Fresh LinkedIn Scraper API — jobs, profiles, companies, posts, ads, groups — with input validation on every category. |

<br>

### Toolbox

**Deep learning & LLMs**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-1F6FEB?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Engineering**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-4B5563?style=for-the-badge&logo=socketdotio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

<br>

<details>
<summary><b>How I work</b></summary>

<br>

- **Baselines before architecture.** A tuned gradient-boosting run tells you whether the problem is hard or your features are. It wins more often than people expect.
- **Evaluate properly.** For retrieval that means recall@k, nDCG, and MRR on a real relevance set; for classification, metrics that match the domain rather than accuracy hiding a model that misses two-thirds of the positive class.
- **Constrain the model's output.** Structured JSON schemas, explicit null contracts for low-confidence values, and parsing that survives whatever the model actually returns.
- **Local-first where it's practical.** Running speech-to-text or a 7B model in-process means fewer keys, fewer failure modes, and no data leaving the machine.
- **Notebooks explore, modules ship.** Exploration lives in `notebooks/`; anything that runs twice moves into `src/` with an entry point and pinned dependencies.

</details>

<details>
<summary><b>Background</b></summary>

<br>

**Education**

- **M.Sc. Computer Engineering in Artificial Intelligence** — University of Padova. Focus on computer vision, 3D perception, robotics, and decision-making models. Thesis on an MDP-based automated experiment-design framework.
- **B.Sc. Computer Engineering** — Persian Gulf University.

**Academic projects**

- **3D point cloud matching with PointNet** — a modified PointNet architecture producing 3D descriptors for point-cloud alignment, with improved robustness in noisy environments.
- **Food recognition and segmentation** — a CV pipeline detecting and segmenting food items, comparing remaining against original portions.

**Earlier career**

Two and a half years as a senior mobile developer — React Native, Kotlin, Flutter — shipping to real users. It's why the ML work here tends to come with a working frontend attached.

**Certifications**

Deep Learning Specialization and Machine Learning Specialization, DeepLearning.AI.

**Languages**

English (professional working) · Persian (native) · Italian (basic)

</details>

<br>

### Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-pezeshki94/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohammad.pezeshki1994@gmail.com)
&nbsp;
![Followers](https://img.shields.io/github/followers/mohpezeshki?style=for-the-badge&logo=github&label=Followers&labelColor=181717&color=2dd4bf)
![Stars](https://img.shields.io/github/stars/mohpezeshki?affiliations=OWNER&style=for-the-badge&logo=github&label=Stars&labelColor=181717&color=818cf8)

Open to conversations about LLM systems, deep learning, and applied ML.
