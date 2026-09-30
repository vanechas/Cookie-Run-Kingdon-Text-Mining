# 🍪 CRK Text Mining & Sentiment EDA ✨

> Scraping and exploring reviews for **Cookie Run: Kingdom** from the Google Play Store with Python 🍰🧁[cite: 1]

---

## 🎀 Overview

An adorable little text mining project analyzing player love and feedback for *Cookie Run: Kingdom* (`com.devsisters.ck`)[cite: 1]! 

* 🎮 Scraped **2,000 player reviews** using `google-play-scraper`[cite: 1].
* 🧹 Cleaned and formatted data with `pandas`[cite: 1].
* 📊 Analyzed star ratings and keyword distributions with `seaborn` and `matplotlib`[cite: 1].
* ☁️ Generated visual word clouds of favorite cookies and common topics[cite: 1].

---

## 🍬 Tech Stack

- 🐍 **Python 3.12**[cite: 1]
- 📦 **Libraries:** `google-play-scraper`, `pandas`, `seaborn`, `matplotlib`, `wordcloud`[cite: 1]
- 📓 **Jupyter Notebook**[cite: 1]

---

## 🧁 Rating Breakdown

Most kingdom builders gave 5 sweet stars ⭐[cite: 1]:

| Rating | Count | Share |
| :---: | :---: | :---: |
| ⭐ 5 | 1,557 | ~77.8% |[cite: 1]
| ⭐ 4 | 177 | ~8.8% |[cite: 1]
| ⭐ 1 | 157 | ~7.8% |[cite: 1]
| ⭐ 3 | 64 | ~3.2% |[cite: 1]
| ⭐ 2 | 45 | ~2.2% |[cite: 1]

---

## 📸 Visuals

<p align="center">
  <img src="assets/rating_dist.png" width="45%" alt="Rating Distribution" />
  <img src="assets/wordcloud.png" width="45%" alt="Word Cloud" />
</p>

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone [https://github.com/YOUR-USERNAME/crk-text-mining.git](https://github.com/YOUR-USERNAME/crk-text-mining.git)
cd crk-text-mining

# 2. Install dependencies
pip install google-play-scraper pandas matplotlib seaborn wordcloud

# 3. Open notebook
jupyter notebook Code.ipynb

```

---

## 📁 Project Structure

```text
crk-text-mining/
├── assets/
│   ├── rating_dist.png
│   └── wordcloud.png
├── cookie_run_kingdom.csv   # Scraped dataset
├── Code.ipynb               # Analysis notebook
└── README.md

```

---
