📄 Final `README.md` (You Can Copy-Paste)

```markdown
# 📊 Sentiment-Driven Trading Analysis

This project explores how market sentiment (Fear vs Greed) affects trading behavior on the Hyperliquid platform. Using real trading data and sentiment scores, we perform data cleaning, merging, EDA, and derive insights that can help traders adapt their strategies based on sentiment dynamics.

---

👤 Author

- Name:Thilak
- Internship Platform:Internshala
- Company:Primetrade.ai
- Project:Data Science Internship Project
- Duration:July 2025

---

🎯 Aim

To investigate the relationship between market sentiment and trading behavior by analyzing execution data and the Fear & Greed Index — identifying patterns in profit/loss and trade size across different market emotions.

---

🔧 Tools & Technologies Used

- Google Colab (Python Jupyter Notebook)
- Pandas, Seaborn, Matplotlib, Plotly
- CSV data parsing & merging
- GitHub for version control
- Git CLI for large file push

---

📝 Objectives

1. Integrate Hyperliquid trading data with Fear & Greed sentiment index.
2. Clean, parse, and merge time-based data sources correctly.
3. Perform visual analysis to detect sentiment-driven trading patterns.
4. Summarize key financial metrics (PnL, trade size) per sentiment class.
5. Provide actionable insights for strategy optimization.

---

🗃️ Folder Structure
ds\_thilak/
├── notebook\_1.ipynb              # Final Google Colab notebook
├── ds\_report.pdf                 # Final project report (2 pages)
├── csv\_files/                    # Source data
│   ├── historical\_data.csv
│   └── fear\_greed\_index.csv
├── outputs/                      # Generated plots for EDA
│   ├── sentiment\_distribution.png
│   ├── pnl\_vs\_sentiment.png
│   ├── trade\_size\_vs\_sentiment.png
│   └── pnl\_vs\_trade\_size\_by\_sentiment.png
└── README.md                     # You're reading it!

````

---

📁 Dataset Overview

1. `historical_data.csv`
- Trader-level data from Hyperliquid
- Columns: `Execution Price`, `Size USD`, `Side`, `Closed PnL`, `Timestamp`

2. `fear_greed_index.csv`
- Daily market sentiment index
- Columns: `date`, `classification` (Fear/Greed/Neutral)

---

📈 Exploratory Data Analysis (EDA)

- Sentiment Distribution:How often Fear, Greed, or Neutral days occur.
- PnL vs Sentiment:Distribution of profits and losses for each sentiment class.
- Trade Size vs Sentiment:Variation in trade size by sentiment.
- PnL vs Trade Size (Interactive):Scatterplot to see how trade size correlates with PnL, segmented by sentiment.

🖼️ All plots are saved inside `outputs/`.

---

🔍 Insights & Inference

- 📉 On Feardays, traders tend to make smaller, less risky trades.
- 📈 On Greed days, larger trades with more volatile PnL are common — suggesting aggressive behavior.
- 🎯 Strategy Tip: Use sentiment classification as a signal to adjust trade volume and risk appetite.

---

📥 Google Colab Link

🔗 [Click here to view the working Colab Notebook](https://colab.research.google.com/drive/18X6plWSX040M6Qs1dzgPhwE3g-DJHued?usp=sharing)

---

🧠 What I Learned

- Working with multi-source time series data and aligning formats (IST, date)
- Cleaning and merging sentiment datasets with transactional data
- Using statistical plots (box, scatter, strip) for visual storytelling
- Automating insights via `groupby` aggregations
- Managing large files with Git CLI and project structuring on GitHub

---

🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Thilakbangera/ds_thilak.git
````

2. Open `notebook_1.ipynb` in Google Colab
3. Run each step from data loading → visualization → insights

---

📬 Contact

If you'd like to learn more or collaborate:

* 📧 Email: \[thilak.22ad059@sode-edu.in]
* 🧑 GitHub: [github.com/Thilakbangera](https://github.com/Thilakbangera)
