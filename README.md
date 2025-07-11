# 🗳️ The Cost of Democracy

**Track how retail prices have changed since the 2024 U.S. presidential election.**

> A lightweight, data-driven project that scrapes and analyzes product prices over time to explore the economic aftermath of U.S. democratic transitions. Built using Python, SerpAPI, and pandas.

---

## 🔍 What This Project Does

- 🔎 Search Google Shopping for product prices via [SerpAPI](https://serpapi.com)
- 🕒 Store historical price data in CSV for longitudinal analysis
- 📈 Run price comparisons
- 📊 Visualize product-level price changes over time
- 🔔 (Optional) Get alerts when prices shift dramatically

---

## ⚙️ Tech Stack

- Python 3.9+
- [SerpAPI](https://serpapi.com/) – for structured Google Shopping results
- `pandas` – for data manipulation
- `matplotlib` – (optional) for visualizations
- `schedule` – (optional) for automating daily price logs

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/the-cost-of-democracy.git
cd the-cost-of-democracy
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Your SerpAPI Key
Add your SerpAPI key to a `.env` file or directly in `scraper.py`:
```python
SERPAPI_KEY = "your_api_key_here"
```

### 4. Run a Product Price Scrape
```bash
python scraper.py "Nintendo Switch OLED"
```

### 5. Run Price Analysis
```bash
python analyze.py --product "Nintendo Switch OLED"
```

---

## 🤝 Working as a Team

We encourage collaborative development. Here's how to contribute effectively:

### Use Branches as Upstream
Each team member should:
1. Create their own feature branch:
   ```bash
   git checkout -b your-feature-branch
   ```
2. Set their branch as the upstream:
   ```bash
   git push --set-upstream origin your-feature-branch
   ```
3. Regularly pull from `main` and rebase or merge to stay in sync:
   ```bash
   git fetch origin
   git checkout your-feature-branch
   git merge origin/main
   ```
4. Push updates and open a Pull Request (PR) against `main`.

Use meaningful branch names like `feature/price-alerts` or `fix/yoy-analysis`.

> Please follow good commit practices and write meaningful messages. Keep each PR focused and small where possible. (Try not to make any more commits after you submit your request.)

---

**Made with democracy in mind.**
