<h1 align="center">📊 NEPSE Open Data 🇳🇵</h1>

<p align="center">
  <strong>The first open-source financial dataset for Nepal Stock Exchange (NEPSE)</strong><br/>
  Built for transparency, learning, and innovation in Nepal's capital market.
</p>

<p align="center">
  <a href="https://github.com/socrateai/nepse-open-data">
    <img alt="Repo Size" src="https://img.shields.io/github/repo-size/socrateai/nepse-open-data" />
  </a>
  <a href="https://github.com/socrateai/nepse-open-data/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/socrateai/nepse-open-data" />
  </a>
  <a href="https://github.com/socrateai/nepse-open-data/stargazers">
    <img alt="Stars" src="https://img.shields.io/github/stars/socrateai/nepse-open-data?style=social" />
  </a>
</p>

---

## 📁 What’s Inside?

```bash
nepse-open-data/
├── floorsheet/              # Daily raw trade data
├── ohlc_adjusted/           # Adjusted OHLC prices (stock-specific)
├── ohlc_unadjusted/         # Unadjusted OHLC prices
├── ohlc_adjusted_index/     # Index-wise adjusted data
├── ohlc_unadjusted_index/   # Index-wise unadjusted data
├── ohlc_adjusted_stock/     # Stock-wise adjusted OHLC
├── ohlc_unadjusted_stock/   # Stock-wise unadjusted OHLC
├── meta/
│   ├── symbols.csv          # Company symbol master
│   └── sector_map.csv       # Sector classification
├── LICENSE
└── README.md