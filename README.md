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
Add your SerpAPI (From our Discord):
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

### Git Branching Workflow
Each team member should:
### 1. Create their own feature branch:
```bash
git checkout -b feature/your-feature-name
 ```

### 2. Set their branch as the upstream:
```bash
 git push --set-upstream origin your-feature-branch
```

### 3. Before making new changes, always sync with main using rebase. Make sure your working directory is clean first::
```bash 
 git status  # Check for uncommitted changes
 git pull --rebase origin main
```

### 4. If git status shows changed files (in red), stage them to avoid conflicts:
```bash
git add .
git commit -m "syncing with main"
```

### 5. Make your changes, commit, and push:
```bash
 git add .
 git commit -m "your descriptive commit message"
 git push
```

### 6. Open a Pull Request (PR) on GitHub to merge your feature branch into main.
Once the PR is opened we should all meet to go over the changes and how they work.

---

### Best Practices
- Use meaningful branch names like feature/price-alerts or fix/yoy-analysis.

- Use clear and consistent commit messages.

- Keep PRs small and focused.

- After submitting a PR, avoid making additional commits unless requested during review.

- Use meaningful branch names like `feature/price-alerts` or `fix/yoy-analysis`.

- Try not to make any more commits after you submit your request until it gets approved.

---

**Made with democracy in mind.**
