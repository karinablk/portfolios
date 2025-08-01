## Portfolios

---

### Featured Projects
[Instacart Reorder Prediction (Machine Learning, Python)](https://github.com/karinablk/instacart-project)
- Performed extensive exploratory data analysis (EDA) on a dataset of over 20 million records to understand user behavior and reorder trends in e-commerce.
- Engineered 20+ features across user, product, and time dimensions (e.g. reorder frequency, cart position, order timing) to enrich the model input.
- Carefully designed features to avoid data leakage by respecting the chronological sequence of orders and excluding target-period information.
- Achieved best performance with XGBoost, reaching a macro F1-score of 0.61, outperforming logistic regression, random forest, CatBoost, and a GRU deep learning model.
<p align="center"><strong>EDA – Features Boxplots and SHAP Feature Importance</strong></p>
<img src="images/instacart_features.jpg?raw=true"/>
<img src="images/instacart_shap_classes.png?raw=true"/>

---

[Crypto Web Scraping & Analysis (Python)](https://github.com/karinablk/crypto-webscraping-project/tree/main)
- Collected live data from CoinMarketCap using a combination of Selenium, BeautifulSoup, Requests, and the CMC API, focusing on memecoins and top cryptocurrencies.
- Cleaned and transformed raw HTML data (1,500+ records, 15 features) from dynamic pages using custom Python functions to handle inconsistencies, missing values, and data formatting.
- Compared coins with verified vs. unverified circulating supply and analyzed memecoins in relation to Bitcoin to identify patterns in perceived value and volatility.
- Conducted exploratory analysis to compare market capitalization, volatility, volume, and performance metrics between memecoins and established coins.
- Visualized key patterns using matplotlib and seaborn, revealing insights into price behavior, market concentration, and speculative dynamics in the crypto space.
<p align="center"><strong>EDA – Price Trends & Market Capitalization by Supply Verification</strong></p>
<img src="images/webscraping_project.png?raw=true"/>

---

[Big Data Sentiment Analysis (AWS, PySpark)](https://github.com/karinablk/big-data-sentiment-project)
- Built a sentiment classification pipeline using AWS services (S3, Databricks, Athena, and QuickSight) and PySpark to analyze over 328K Elon Musk–related tweets.
- Cleaned and structured tweet data using SQL and Spark transformations, addressing delimiter inconsistencies, missing values, and column merging issues.
- Applied VADER sentiment analysis for initial labeling — fast and social-media-friendly, though contextually limited, especially in distinguishing neutral from positive tone.
- Ensured chronological train-test split to avoid data leakage caused by repeated retweets or time-sensitive content.
- Achieved 88% F1-score with logistic regression, with strongest performance on negative tweets (~90% accuracy) and most confusion between neutral and negative classes.
- Built an interactive QuickSight dashboard to visualize model evaluation, sentiment distribution, and user behavior patterns by time and day.
<img src="images/dashboard_eda_big_data.png?raw=true"/>
<img src="images/dashboard_model_big_data.png?raw=true"/>

---

[SQL Business Analysis – Airbnb & Movie Rental Data (SQL, MySQL)](https://github.com/karinablk/sql-analytics-projects)
- Performed business analysis using SQL on two datasets: Airbnb guest data and the SAKILA movie rental database.
- Wrote structured queries to explore guest booking behavior, rental activity, customer segmentation, and product performance.
- Used joins, subqueries, aggregations, and window functions to solve real-world business questions.
- Delivered actionable insights on pricing, occupancy trends, inventory planning, and customer behavior to support data-driven decision-making.
<img src="images/sakiila_rental.png?raw=true"/>

---
