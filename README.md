# ETF Comparison Tool 🧮📊

This is a beginner Python project that allows users to compare two ETFs or index funds by fetching their top holdings and identifying common and unique stock tickers between them.

The goal is to help users explore the overlap and differences between ETFs using real-time data from Yahoo Finance.

---

## 🔧 Features

- Accepts two ETF or index fund tickers (like `SPY`, `VTI`, etc.)
- Fetches the **top 10 holdings** of each fund
- Compares them to find:
  - 📌 Common stocks
  - 🔹 Unique to ETF 1
  - 🔸 Unique to ETF 2
- Displays results in the terminal

---

## 📦 Requirements

- Python 3.8 or higher
- [`yahooquery`](https://pypi.org/project/yahooquery/) library

You can install `yahooquery` using pip:

```bash
pip install yahooquery
