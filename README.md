# The Effect of Twitter Sentiments on Driver Performance in Formula One Racing
Examining the relationship between public sentiment and F1 driver performance through data manipulation and analysis.
Contributors: Shriya Ejanthker, Stephen Bloust, Elysia Pil

### Project Overview
This project investigates how public sentiment, particularly through Twitter, affects the performance of Formula One drivers. Using Natural Language Processing (NLP) to analyze tweets and race data, we explore the relationship between social media sentiment and race outcomes. The analysis spans data from July 2021 to August 2023, providing insights into whether positive or negative sentiment influences a driver's confidence, race performance, and qualifying results.

### Motivation
Inspired by research in sport psychology and the growing impact of social media on athletes, this project aims to understand if fan sentiment can play a role in the mental state and subsequent performance of F1 drivers. With Formula One being a global sport, drivers face immense pressure to perform, both on and off the track. By analyzing race data and Twitter trends, we aim to quantify how public perception impacts a driver's performance.

### Data Sources
1. Formula One Race Data (1950-2023):
The dataset includes driver positions, race results, lap times, and other race-related metrics. It was sourced from a Kaggle project that compiled data from the Ergast API.

2. Twitter Data (2021-2022):
A dataset containing tweets with the hashtag #f1 was used to capture public sentiment about drivers leading up to races. This data was downsampled to include tweets related to specific drivers.

### Key Analysis Steps
1. Data Cleaning and Manipulation:
Merged multiple CSV files containing race and driver data.
Preprocessed Twitter data by removing irrelevant information and linking tweets to specific drivers.
Sentiment analysis was performed using VADER, an NLP tool, to score the polarity (positive/negative) of each tweet.
2. Correlation and Sentiment Analysis:
We analyzed the relationship between sentiment scores and various race performance indicators (e.g., qualifying positions, finish positions, position gains).
Correlation heatmaps and regression plots were created to visualize the influence of social media sentiment on driver performance.
3. Prediction Model:
A logistic regression model was built to predict whether a driver would improve in their next race based on previous race performance and Twitter sentiment.

### Key Findings
- Qualifying Impact: Positive sentiment correlates with better qualifying results, which may lead to increased pressure or overconfidence.
Race Performance: More positive sentiment is unexpectedly associated with a decrease in race performance.
- Psychological Hypothesis: The project hypothesizes that drivers may feel overwhelmed by fan expectations or overconfident after receiving positive social media attention.

### Results
- The prediction model achieved an accuracy of 73.74% with reasonable precision, recall, and F1 scores.
- Positive sentiment is generally correlated with poorer race performance, possibly due to the psychological pressure of meeting fan expectations.

### Future Work
-Real-time sentiment monitoring during race weekends could be explored to provide teams with actionable insights on public perception.
-Further research could investigate the psychological effects of social media engagement on driver performance.
