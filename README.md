

---

## 📄 README.md – Task 1

# British Airways - Task 1: Web Scraping & Customer Review Analysis

This is **Task 1** of the British Airways Virtual Internship by Forage. In this task, I scraped customer reviews from Skytrax using Selenium, performed sentiment analysis, and extracted key topics to understand customer satisfaction levels and common themes in feedback.

---

## 🧾 Description

- ✅ **Web Scraping**: Used **Selenium** and **BeautifulSoup** to scrape real-time reviews from [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways/)
- ✅ **Sentiment Analysis**: Analyzed reviews using **TextBlob** to classify them as Positive, Neutral, or Negative
- ✅ **Topic Modeling**: Extracted underlying topics using **LDA (Latent Dirichlet Allocation)**
- ✅ **Visualizations**: Created word clouds, sentiment bar charts, and feature importance plots
- ✅ **PowerPoint Summary**: Generated a **one-page slide** with insights for stakeholders using `python-pptx`

---

## 📁 Included Files

| File | Purpose |
|------|---------|
| `task1_review_analysis.py` | Python script for scraping and analysis |
| `data/raw_reviews.csv` | Raw customer reviews data collected from Skytrax |
| `data/analyzed_reviews.csv` | Cleaned and analyzed dataset with sentiment scores |
| `visualizations/sentiment_distribution.png` | Sentiment distribution chart |
| `visualizations/wordcloud.png` | Word cloud showing most frequent words |
| `visualizations/top_feature_importances.png` | Top words influencing sentiment |
| `reports/BA_Customer_Insights_Summary.pptx` | PowerPoint summary for management |

---

## 🧰 Requirements

Install dependencies via:

```bash
pip install selenium beautifulsoup4 pandas nltk textblob gensim matplotlib wordcloud python-pptx
```

---

## 🚀 How to Run

1. Place `raw_reviews.csv` inside the `data/` folder
2. Run:
   ```bash
   python task1_review_analysis.py
   ```
3. Output will be saved in:
   - `data/analyzed_reviews.csv`
   - `visualizations/`
   - `reports/BA_Customer_Insights_Summary.pptx`

---

## 🔍 Key Insights

- Customers frequently mention **cabin crew service**, **food quality**, and **lounge experience**
- Common complaints include **outdated entertainment systems**, **poor legroom**, and **inconsistent service**
- The sentiment analysis shows a **mixed customer perception**, with many neutral reviews but strong opinions on comfort and tech
- Visuals and summaries are designed for quick stakeholder understanding

---

## ✈️ Goal

Provide actionable insights that help British Airways improve customer satisfaction and identify areas needing improvement — such as onboard tech, seating, and service consistency.

---
