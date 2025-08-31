# Tweet Sentiment Analysis Dashboard
Visualizing sentiment and engagement metrics from tweets using Power BI.

---

## Project Overview
This repository demonstrates a Power BI dashboard created to analyze tweet sentiment.
The dashboard summarizes sentiment distribution, user engagement (likes, retweets, replies), and key insights.

---

## Dataset Description
- The Power BI dashboard was created using **real tweet data**, but the raw dataset is not included for privacy.
- A **dummy dataset** is included (`data/sample_tweets_dummy.csv`) to show the columns used:

| Column Name        | Description                              |
|-------------------|------------------------------------------|
| URL               | Tweet link                               |
| Date              | Date of the tweet                        |
| Tweet             | Text content of the tweet                |
| English           | Whether the tweet is in English          |
| Replies           | Number of replies                        |
| Retweets          | Number of retweets                       |
| Likes             | Number of likes                          |
| Quotes            | Number of quote tweets                   |
| Conv_ID           | Conversation ID                          |
| Language          | Language of the tweet                     |
| Links             | Any external links in the tweet          |
| Media             | Media attached to the tweet              |
| Retweeted_Tweet   | If the tweet is a retweet, original text |
| Bookmarks         | Number of bookmarks                       |
| Username          | Username of the author                    |
| Sentiment         | Sentiment label: positive / negative / neutral |

---

## Workflow / Methodology
Even though the raw dataset is not included, the workflow for this project was:

1. **Data Preprocessing** – Cleaning, tokenization, labeling tweets  
2. **Machine Learning (Descriptive)** – SVM & Naive Bayes; evaluation metrics: accuracy, precision, recall, F1-score  
3. **Power BI Visualization** – Sentiment distribution, engagement metrics, key insights  

---

## How to Explore
1. Open `powerbi/sentiment dashboard.pbix` in **Power BI Desktop**.  
2. Optional: Load `data/sample_tweets_dummy.csv` to view column structure.  

---

## Notes / Disclaimer
- The dashboard is fully functional, but the underlying raw dataset is omitted for privacy.  
- Dummy dataset is provided solely to illustrate **data structure and workflow**.  

---

## License
This project is for demonstration purposes only.
