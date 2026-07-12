<h1 align="center">Andrey Naymushin</h1>

<p align="center">
  <b>ML Engineer · Python Developer</b>
</p>

<p align="center">
  <a href="https://github.com/AndHunter">GitHub</a> ·
  <a href="https://t.me/main4562">Telegram</a> ·
  <a href="https://www.kaggle.com/andrewsokolovsky">Kaggle</a>
</p>

---

## 👋 About

I'm focused on **Machine Learning**, **Data Science** and building practical ML-based systems.

Mostly working with:

- recommender systems
- computer vision
- tabular ML
- feature engineering
- ranking models
- ML pipelines
- backend services around ML models

I like projects where ML is not just a notebook, but a working pipeline: data preprocessing, validation, model training, inference logic and integration with an API or product.

---

## 🏆 Achievements

- **[AIIJC / AI Challenge](https://aiijc.com/en/)** — prize-winner, School Track  
- **[National Technology Olympiad, Artificial Intelligence track](https://ntcontest.ru/tracks/nto-school/proekt-po-iskusstvennomu-intellektu/iskusstvennyy-intellekt/)** — prize-winner

---

## 🛠 Stack

**ML / DS:**  
Python, pandas, NumPy, scikit-learn, CatBoost, PyTorch, TensorFlow, SciPy

**RecSys / Ranking:**  
CatBoostRanker, ALS, BM25, item-to-item similarity, learning-to-rank, reranking

**Computer Vision:**  
OpenCV, ViT, image preprocessing, color correction, histogram-based models

**Backend / Tools:**  
FastAPI, Flask, Django, Docker, PostgreSQL, SQLite, MongoDB, Git

**Languages:**  
Python, SQL, C++

---

## 🚀 Projects

### [Auto White Balance — AIIJC](https://github.com/AndHunter/Auto-White-Balance-AIIJC)

Computer Vision solution for the **Automatic White Balance** problem in mobile cameras.

The task was to predict a distribution of possible white points in a scene under different lighting conditions.

What I used:

- Vision Transformer backbone
- image metadata
- log-chroma histogram features
- edge maps
- depth features
- Gaussian Mixture Model parameterization
- Wasserstein/KL-based loss

**Tech:** Python, PyTorch, OpenCV, NumPy, timm, image processing  
**Result:** 3rd place, AIIJC School Track

---

### [Recovering Lost Implicit Feedback — NTO AI Final](https://github.com/AndHunter/Recovering-lost-implicit-feedback-NTO-AI-Final)

Recommender system solution for the **NTO AI Final 2025/26**.

The task was to recover lost positive user-book interactions after a logging failure.

The solution is based on a two-stage RecSys pipeline:

- candidate generation
- feature engineering
- CatBoostRanker
- PU-learning logic
- time-window validation
- final top-20 ranking

Candidate generators included:

- ALS
- BM25
- popularity baseline
- item-to-item similarity
- metadata-based retrieval
- incident-window generators

**Tech:** Python, pandas, implicit, CatBoost, scikit-learn  
**Score:** ~0.144289 NDCG@20

---

### [By Pages Hackathon Solution](https://github.com/AndHunter/by-pages-hackathon-solution)

Personalized book recommendation system for the AI Academy hackathon **“По страницам”**.

The task was to generate top-20 book recommendations for each user while balancing relevance and genre diversity.

The final pipeline included:

- handcrafted user/item features
- text and graph features
- collaborative filtering features
- CatBoost / LightGBM / XGBoost models
- neural network meta-features
- CatBoostRanker with YetiRank
- diversity-aware MMR reranking

**Tech:** Python, pandas, CatBoost, LightGBM, XGBoost, PyTorch, implicit, sentence-transformers  
**Score:** 0.719

---

### [Telegram Bot for Quantorium](https://github.com/AndHunter/Telegram_bot_for_quantorium)

Telegram bot for automating educational course workflows.

The bot handles:

- course registration
- user interaction through inline keyboards
- certificate generation
- contact information
- Google Sheets integration
- PostgreSQL storage

**Tech:** Python, aiogram, PostgreSQL, Google Sheets API

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AndHunter&theme=github_dark" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AndHunter&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=AndHunter&theme=github_dark" />
</p>

---

## 📫 Contacts

- Telegram: [@main4562](https://t.me/main4562)
- GitHub: [github.com/AndHunter](https://github.com/AndHunter)
- Kaggle: [andrewsokolovsky](https://www.kaggle.com/andrewsokolovsky)
