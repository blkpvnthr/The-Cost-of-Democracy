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

### 2. Install Dependencies then go to  and create an account to get your API key.
```bash
pip install -r requirements.txt
```
Create a free SerpAPI account at [serpapi.com](https://serpapi.com/)and get your API key.


### 3. 3. Create a .env file and add your SerpAPI key (Git will automatically ignore this file):
```bash
SERPAPI_KEY = "your_api_key_here"
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
> Once the PR is opened we should all meet to go over your changes and how they work.


---

### Best Practices
- Use meaningful branch names like feature/price-alerts or fix/yoy-analysis.

- Use clear and consistent commit messages.

- Keep PRs small and focused.

- After submitting a PR, avoid making additional commits unless requested during review.

- Use meaningful branch names like `feature/price-alerts` or `fix/yoy-analysis`.


---

**Made with democracy in mind.**
