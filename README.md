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

### 2. Install Dependencies and Get Your SerpAPI Key
```bash
pip install -r requirements.txt
```
Create a free SerpAPI account at [serpapi.com](https://serpapi.com)  and get your API key.

### 3. Create a `.env` file and add your SerpAPI key (Git will automatically ignore this file):
```env
SERPAPI_KEY="your_api_key_here"
```

---

## 🤝 Working as a Team

### Git Branching Workflow

1. **Create a new feature branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Set the branch to track the remote:**
   ```bash
   git push --set-upstream origin feature/your-feature-name
   ```

3. **Before making new changes, sync with `main` using rebase. Ensure your working directory is clean:**
   ```bash
   git status        # Check for uncommitted changes
   git pull --rebase origin main
   ```

4. **If `git status` shows changes (in red), stage them before continuing:**
   ```bash
   git add .
   git commit -m "syncing with main"
   ```

5. **Make your changes, then commit and push:**
   ```bash
   git add .
   git commit -m "your descriptive commit message"
   git push
   ```

6. **Open a Pull Request (PR)** on GitHub to merge your feature branch into `main`.

> Once the PR is opened, we’ll schedule a quick walkthrough to review your changes.

---

### ✅ Best Practices

- Use meaningful branch names like `feature/price-alerts` or `fix/yoy-analysis`.
- Write clear and consistent commit messages.
- Keep PRs small and focused.
- Avoid making more commits after submitting a PR unless part of review feedback.

---

**Made with democracy in mind.**
