# OIBSIP_dataanalytics_02

# 📊 Task 2: Google Play Store Data Analysis & Sentiment Mining

## **Internship**
**Oasis Infobyte** - Data Science Internship (Virtual)

## **Project Goal**
The primary objective of this project was to perform an in-depth analysis of the Android App Market by combining **Exploratory Data Analysis (EDA)** on app characteristics with **Natural Language Processing (NLP)** on user reviews. The goal was to uncover market trends, pricing strategies, and user satisfaction metrics.

## **Datasets**
1.  `apps.csv`: Contains metadata for over 10,000 Google Play Store applications.
2.  `user_reviews.csv`: Contains user reviews and sentiment metadata linked to various apps.

## **Key Steps & Methodology**

1.  **Data Cleaning & Wrangling:**
    * Cleaned column names (e.g., replacing spaces with underscores).
    * **Converted messy string formats** (`Installs`, `Size`, `Price`) into clean, standardized numeric metrics (e.g., millions, MB, USD).
    * Handled duplicates and ensured data integrity for the merged analysis.

2.  **Exploratory Data Analysis (EDA):**
    * Visualized the **distribution of app categories** (Top Categories).
    * Analyzed the split between **Free vs. Paid** applications.
    * Explored relationships between key features, such as **App Size vs. Installs** and **Price vs. Rating**.
    * Analyzed **App Pricing Trends** across popular categories, filtering outliers to show true market prices.

3.  **Sentiment Analysis (NLP):**
    * Merged the apps and reviews datasets.
    * Applied a lexicon-based tool (VADER) to calculate the **compound sentiment score** for each user review.
    * Visualized the **Top 10 Apps** with the highest average positive sentiment.

## **Tools and Libraries**
* **Python**
* **Pandas & NumPy:** Data manipulation and cleaning.
* **Matplotlib & Seaborn:** Standard statistical visualization.
* **Plotly:** Interactive visualization for charts like Category counts and Rating distribution.
* **NLTK (VADER Lexicon):** For sentiment analysis.

## **Key Insights**
* Identified the **most saturated and popular app categories** in the market.
* Quantified the high volume of **free applications** compared to paid ones, along with their respective download patterns.
* Determined the **apps with the highest user satisfaction** based on positive sentiment polarity.

## **File Structure**
* `sentiment_analysis_(1).py` (or `google_play_store_data.py`) - Primary Python script containing the entire analysis and visualizations.
* `apps.csv` - Original apps dataset.
* `user_reviews.csv` - Original user reviews dataset.
* `apps_cleaned.csv` - Final cleaned and engineered app dataset (output).
* `reviews_cleaned.csv` - Final processed reviews dataset (output).
* `README.md` - This documentation file.
