# 🗳️ The Cost of Democracy

**Track how retail prices have changed since the 2024 U.S. presidential election.**

> A lightweight, data-driven project that scrapes and analyzes product prices over time to explore the economic aftermath of democratic transitions. Built using Python, SerpAPI, and pandas.

---

## 🔍 What This Project Does

- 🔎 Search Google Shopping for product prices via [SerpAPI](https://serpapi.com)
- 🕒 Store historical price data in CSV for longitudinal analysis
- 📈 Run Year-over-Year (YoY) price comparisons
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

## 📊 Sample Output
```
Product: Nintendo Switch OLED
Price on 2024-07-11: $349.99
Price on 2025-07-11: $319.00
YoY Change: -8.86%
```

---

## 🧠 Why This Exists

Politics influence markets — sometimes subtly, sometimes dramatically. This project explores how the **cost of living shifts over the course of presidential terms**, beginning with the 2024 election. By tracking changes over time, it brings evidence to economic conversations too often driven by speculation.

---

## 🤝 Contributions

PRs welcome! You can:
- Add price scraping support for more products or sites
- Improve visualizations
- Build a dashboard or web UI

---

## 📄 License

MIT License

---

**Made with democracy in mind.**
