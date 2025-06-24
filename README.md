# 📊 Trader Behavior & Bitcoin Market Sentiment Analysis

This project explores how **trader performance metrics** (like PnL, trade size, and execution price) relate to **Bitcoin market sentiment** (measured by the Fear & Greed Index). Using data science techniques such as clustering and classification, the analysis uncovers behavior patterns and builds a predictive model to classify market sentiment from trader activity.

---

## 📁 Files in This Repository

- `Final.ipynb` – Main Jupyter notebook containing the full analysis
- `fear_greed_index.csv` [📈 fear_greed_index.csv]([https://drive.google.com/file/d/FILE_ID/view?usp=sharing](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)) – Market sentiment data (Fear & Greed Index)
- `historical_data.csv` [📉 historical_data.csv]([https://drive.google.com/file/d/FILE_ID/view?usp=sharing](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)) – Historical trades with timestamps, PnL, and trade size

---

## 🎯 Project Objectives

- Analyze how market sentiment influences trader behavior
- Cluster traders based on PnL, trade size, and execution characteristics
- Predict market sentiment using only trader behavior
- Generate strategic recommendations for sentiment-aware trading

---

## 🛠️ Tools & Techniques Used

- **Python Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for clustering and classification
- **Machine Learning**:
  - KMeans Clustering for behavioral segmentation
  - Random Forest Classifier for sentiment prediction

---

## 📊 Key Findings

- **Trader behavior reflects sentiment**:
  - Higher PnL and trade sizes during _Greed_ phases
  - More conservative activity during _Fear_
  
- **Three behavioral clusters identified**:
  - Cluster 0: Conservative, low-risk traders
  - Cluster 1: Aggressive traders with high PnL during Greed
  - Cluster 2: Inconsistent traders active in all conditions

- **Sentiment prediction accuracy: 88%**
  - Trade features alone were effective in predicting whether the market was in a Fear or Greed phase
  - Most misclassifications occurred during sentiment transitions

---

## ✅ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/dhirajp1603/trader-sentiment-analysis.git
cd trader-sentiment-analysis
```
### 2. Install Required Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Launch the Notebook

```bash
jupyter notebook Final.ipynb
```
