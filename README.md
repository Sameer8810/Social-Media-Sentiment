🛍️ Nykaa Product Reviews – Sentiment Analysis Dashboard
📌 Overview

This project analyzes customer reviews of Nykaa products to uncover insights about sentiment trends across brands and product categories.
The results are visualized in an interactive Power BI dashboard, making it easier to understand what customers love or dislike.

📂 Project Structure
Social-media-sentiment/
│── data/
│   ├── raw/               # Original dataset (Nykaa_Product_Review.csv)
│   ├── processed/         # Cleaned data + sentiment labels
│
│── notebooks/
│   ├── Sentiment_Analysis.ipynb   # Jupyter Notebook (data prep + NLP + EDA)
│
│── dashboard/
│   ├── Nykaa_Sentiment.pbix       # Power BI dashboard file
│
│── README.md              # Project documentation

📊 Dataset

Source: Nykaa Product Reviews (CSV)

Key Columns:

Product Brand → Brand name (e.g., Lakme, Maybelline)

Product Category → Category (e.g., Lipstick, Skincare)

Product Rating → Numeric rating (1–5)

Product Reviews → Customer reviews text

⚙️ Steps Performed
1. Data Preparation (in Jupyter Notebook)

Loaded dataset → Nykaa_Product_Review.csv

Cleaned text (removed stopwords, special chars, etc.)

Performed sentiment classification: Positive, Negative, Neutral

Generated word clouds for positive & negative reviews

2. Power BI Dashboard Design

The dashboard is divided into 3 main sections:

🟢 Top Section – Overview

KPI Cards → Total Reviews, % Positive, % Negative

🟡 Middle Section – Visuals

Sentiment Distribution → Donut Chart

Sentiment by Brand → Stacked Bar Chart

Sentiment by Category → Stacked Column Chart

🔴 Bottom Section – Word Clouds

Positive reviews word cloud (keywords like love, smooth, amazing)

Negative reviews word cloud (keywords like waste, oily, bad)

📌 Insights

Some brands have high review counts but also high negatives (e.g., Brand A).

Categories like Skincare show more negative sentiment compared to Makeup.

Positive keywords include love, smooth, amazing, while negative ones include waste, oily, irritation.

🛠️ Tools Used

Python (pandas, nltk, wordcloud, matplotlib) → Data cleaning & NLP

Power BI → Dashboard design & visualization

🚀 How to Use

Clone this repo:

git clone https://github.com/your-username/Social-media-sentiment.git


Open the Jupyter notebook in notebooks/ to reproduce preprocessing.

Open Nykaa_Sentiment.pbix in Power BI to interact with the dashboard.
