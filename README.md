# OIBSIP_dataanalytics_02
Task 2: App Market Insights via Sentiment Analysis
Internship

Oasis Infobyte – Data Science Internship (Virtual)

Project Goal

The objective of this project was to conduct an in-depth App Market Analysis using a combination of Exploratory Data Analysis (EDA) and User Review Sentiment Analysis.
The project aimed to uncover actionable insights about market trends, pricing strategies, and user satisfaction—helping developers and stakeholders make informed, data-driven decisions.

Dataset

The analysis utilized two datasets:

Google Play Store Apps Dataset – Containing app-level attributes such as Category, Rating, Size, Installs, Type (Free/Paid), and Price.

User Reviews Dataset – Featuring user feedback with Review Text, Sentiment Label, and Polarity Score.

These datasets were merged to perform integrated sentiment and performance analysis.

Key Steps & Methodology

Data Wrangling & Cleaning:

Handled missing values and inconsistent formats.

Standardized key metrics like Installs, Reviews, and Price for numerical accuracy.

Removed noise and duplicates to ensure high-quality data.

Market & Trend Analysis (EDA):

Explored category-wise app distribution.

Investigated relationships between App Size, Price, and User Ratings.

Visualized data patterns using Seaborn and Plotly for better interpretability.

Pricing Strategy Insights:

Analyzed Price Trends across various app categories.

Identified anomalies and filtered out extreme values to capture true market behavior.

Derived insights into how app pricing influences user ratings and popularity.

Sentiment Analysis (NLP):

Merged App Data and User Review Data to assess overall sentiment distribution.

Used TextBlob to calculate sentiment polarity and classify reviews as Positive, Negative, or Neutral.

Compared sentiment polarity across Free vs. Paid apps.

Strategic Recommendations:

Suggested improvements for app store recommendation systems using sentiment insights.

Proposed sentiment-based ranking adjustments for better user experience and app discoverability.

Tools and Libraries

Python

Pandas & NumPy: Data preprocessing and analysis.

Matplotlib & Seaborn: Static data visualizations.

Plotly: Interactive dashboards and charts.

TextBlob: Sentiment polarity computation.

Scikit-learn: Data preprocessing utilities.

Actionable Conclusions & Findings

Pricing Dynamics: Paid apps tend to have higher quality perception but lower install counts.

Sentiment Insights: Free apps attract more reviews, yet paid apps often yield more positive feedback.

Market Trends: The Family and Game categories dominate the app ecosystem.

These insights can directly guide pricing optimization, feature prioritization, and app promotion strategies.

File Structure

app_market_sentiment_analysis.py – Primary Python script containing EDA and Sentiment Analysis pipeline.

googleplaystore.csv – Main dataset containing app information.

user_reviews.csv – Supplementary dataset containing user reviews.

README.md – Documentation file (this file).
