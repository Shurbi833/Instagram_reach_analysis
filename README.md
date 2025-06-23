# 📱 Instagram Reach Analysis

This project analyzes Instagram post performance using a publicly available dataset from Kaggle. The goal is to uncover insights about post reach, impressions, likes, and overall engagement through data cleaning, exploration, and visualization.

---

## 📁 Dataset

- **Source:** [Kaggle – Instagram Reach Data][(https://www.kaggle.com/](https://www.kaggle.com/datasets/ercharugoyal/instagram-reach-analysis-using-python/data)) 
- **File:** `Instagram data.csv`

The dataset includes the following metrics for each Instagram post:

Impressions – Total number of views (Reach)

From Home – Reach generated from the home feed

From Hashtags – Reach generated via hashtags

From Explore – Reach generated via the Explore page

From Other – Reach generated from other sources

Saves – Number of times the post was saved

Comments – Total comments received

Shares – Number of times the post was shared

Likes – Total likes on the post

Profile Visits – Number of profile visits originating from the post

Follows – Number of new followers gained from the postthe post

Caption: Caption of the post

Hashtags: Hashtags used in the post

---

## 🧠 Objective

- Analyze the relationship between reach and other engagement metrics
- Identify what drives higher visibility for posts
- Visualize patterns that can help improve Instagram performance

---

## 📌 Key Steps Performed

- Data loading and basic inspection using `pandas`
- Data cleaning and formatting
- Exploratory Data Analysis (EDA) using:
  - Descriptive statistics
  - Correlation matrix
  - Bar plots, pie charts, line graphs (via `matplotlib` and `seaborn`)
- Insight generation

---

## 📊 Tools & Libraries Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 🔍 Notable Insights

- Posts with high saves and shares tend to have higher reach
- Engagement (likes + comments + shares) is strongly correlated with impressions
- Profile visits also contribute significantly to reach boost

---

## 📂 Files Included

- `Instagram data.csv`: Dataset used for the analysis
- `Instagram_Reach_Analysis.ipynb`: Jupyter Notebook with all code and visualizations

---

## ✅ How to Run

> You can run this notebook in [Google Colab](https://colab.research.google.com/) or any Jupyter environment.

```python
# Load data
import pandas as pd

df = pd.read_csv("Instagram data.csv")
