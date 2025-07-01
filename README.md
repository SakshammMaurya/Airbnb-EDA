
# 🏠 Airbnb Data Analysis (EDA)

This project presents an **Exploratory Data Analysis (EDA)** of the Airbnb dataset. The goal is to understand the structure, trends, and key insights from Airbnb listings data through visualizations and statistical summaries.

---

## 📊 Objectives

- Perform initial data loading and cleaning
- Explore geographic distribution of listings
- Analyze pricing patterns
- Understand host activity and review behavior
- Visualize relationships between room types, neighborhoods, and availability

---

## 📁 Dataset

The dataset used is a **public Airbnb dataset** containing details about listings such as:
- Host and location information
- Room types and prices
- Number of reviews
- Availability and review metrics

You can load it via:
```python
df = pd.read_csv('Datasets.csv')
```

---

## 📌 Key Insights

- **Room Type Distribution**: Most listings are entire homes/apartments, followed by private rooms.
- **Top Neighborhoods**: Certain neighborhoods dominate the number of listings and average pricing.
- **Price Outliers**: A few listings are priced extremely high, skewing the price distribution.
- **Availability**: Many listings are seasonal, with limited availability across the year.
- **Review Patterns**: Listings with more availability tend to have higher review counts.

---

## 📈 Visualizations

The notebook includes:
- Bar plots of top neighborhoods
- Heatmaps for correlation analysis
- Pie charts for categorical breakdowns
- Histograms of price distributions
- Scatter plots showing spatial pricing trends

---
## 📌 Screenshots

<p align="left">
  <a href="https://imgbb.com/"><img src="https://i.ibb.co/PGrN0qpK/Screenshot-2025-07-01-195801.png" height ="300" weight = "50%"></a>
<a href="https://ibb.co/84cVGb3J"><img src="https://i.ibb.co/Xk8T6DB9/Screenshot-2025-07-01-195835.png" height ="300" weight = "50%"></a>
<a href="https://ibb.co/gFmMSgDW"><img src="https://i.ibb.co/Nnt69YLN/Screenshot-2025-07-01-195857.png" height ="300" weight = "50%"></a>
<a href="https://ibb.co/6JGRg3yT"><img src="https://i.ibb.co/G3GvcKd8/Screenshot-2025-07-01-195912.png" height ="300" weight = "50%"></a>
<a href="https://ibb.co/dstQVqf4"><img src="https://i.ibb.co/cKwNZHyh/Screenshot-2025-07-01-195818.png" height ="300" weight = "50%"></a>
<a href="https://ibb.co/WWYxPkPW"><img src="https://i.ibb.co/cc7gC6Cc/Screenshot-2025-07-01-195811.png" height ="300" weight = "50%"></a>
</p>

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🚀 Getting Started

To run the notebook locally:

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/airbnb-eda.git
   cd airbnb-eda
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "Airbnb EDA.ipynb"
   ```

---

## 📚 Credits

- Inspired by several public EDA notebooks on Kaggle and YouTube

---


