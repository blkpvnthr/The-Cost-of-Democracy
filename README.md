# 🗳️ The Cost of Democracy

**Track how retail prices have changed since the 2024 U.S. presidential election.**

> A lightweight, data-driven project that scrapes and analyzes product prices over time to explore the economic aftermath of democratic transitions. Built using Python, SerpAPI, and pandas.

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

### 5. Run YoY Price Analysis
```bash
python analyze.py --product "Nintendo Switch OLED"
```

---

## 🧠 Why This Exists

Politics influence markets — sometimes subtly, sometimes dramatically. This project explores how the **cost of living shifts over the course of presidential terms**, beginning with the 2024 election. By tracking changes over time, it brings evidence to economic conversations too often driven by speculation.

---

## 🤝 Working as a Team

Here's how to stay in sync:

### Git Branching Workflow

1. **Create a new branch for your work:**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes and commit them:**
   ```bash
   git add .
   git commit -m "Describe your change"
   ```

3. **Pull latest changes from `main` before pushing:**
   ```bash
   git checkout main
   git pull origin main
   git checkout feature/your-feature-name
   git merge main
   ```

4. **Push your branch and open a pull request (PR):**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Submit a PR** on GitHub and request a review.

> Please follow good commit practices and write meaningful messages. Keep each PR focused and small where possible.

---

**Made with democracy in mind.**
