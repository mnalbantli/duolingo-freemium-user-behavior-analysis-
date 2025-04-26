# Duolingo Freemium User Behavior Analysis

## Project Overview

This project explores the emotional and behavioral patterns of Duolingo users through the analysis of real user reviews.  
By understanding which behaviors and sentiments correlate with user retention or churn, the goal is to generate actionable insights for product and marketing teams to optimize engagement strategies in freemium app models.

---

## Business Problem

Freemium apps like Duolingo rely heavily on user retention for long-term success.  
Key questions addressed:

- What emotional and behavioral patterns predict user retention vs churn?
- What user segments emerge based on motivation and sentiment?
- What product and marketing strategies can improve user loyalty?

---

## Data Source

- 100 real user reviews scraped from the Duolingo Google Play Store page.
- English language, US market focus.
- Cleaned to remove empty and extremely short reviews for meaningful analysis.

---

## Methodology

- **Data Cleaning**: Removed empty or too-short reviews.
- **Exploratory Data Analysis (EDA)**: Analyzed score distributions and keyword patterns.
- **Sentiment Analysis**: Classified reviews as Positive, Neutral, or Negative using a rule-based approach.
- **Behavioral Segmentation**: Created user personas based on sentiment and keyword signals.
- **Strategic Recommendations**: Proposed actionable strategies to improve user retention and satisfaction.

---

## Key Findings

- **57% Positive Reviews**: Strong emotional connection to the app’s gamification and learning experience.
- **11% Negative Reviews**: Frustration driven mainly by technical issues (e.g., bugs, glitches) and ad interruptions.
- **Personas Identified**:
  - **Loyal Advocates**: Highly satisfied, emotionally connected users.
  - **Silent Users**: Functional users with low emotional engagement — opportunity for reactivation.
  - **Frustrated Users**: High churn risk group — needs immediate product attention.

---

## Business Recommendations

- **Loyalty Programs**: Leverage highly engaged users through referral and rewards.
- **Silent User Reactivation**: Design campaigns to emotionally re-engage passive users.
- **Product Improvements**: Address technical issues and optimize ad experiences to reduce churn risk.

---

## Tools Used

- Python (Pandas, Matplotlib, WordCloud)
- Google Play Scraper (for data collection)
- Jupyter Notebook / Google Colab

---

## Next Steps (Optional Enhancements)

- Larger-scale sentiment analysis using VADER or a fine-tuned transformer model.
- Topic modeling (LDA / BERTopic) for deeper theme extraction.
- Predictive churn modeling if behavioral event data becomes available.

---

## Author

Mustafa [Data Analytics Graduate Student | University of Tennessee at Chattanooga]  
[Connect with me on LinkedIn!](https://www.linkedin.com/in/mustafanalbantli)

