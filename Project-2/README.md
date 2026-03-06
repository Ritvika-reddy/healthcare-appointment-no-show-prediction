# YouTube Trending Video Analytics

## Project Overview
This project analyzes YouTube trending video datasets to identify patterns in video popularity, viewer engagement, and content characteristics. The goal is to understand factors that influence a video's chances of trending by examining engagement metrics, video categories, publishing patterns, and sentiment in video titles.

The project uses Python for data analysis, SQL for category ranking, and Power BI for interactive dashboard visualization.

---

## Objectives
- Clean and standardize the YouTube trending dataset.
- Perform sentiment analysis on video titles.
- Analyze engagement metrics such as views, likes, and comments.
- Rank video categories based on average views using SQL.
- Identify patterns in publishing time and trending duration.
- Build an interactive Power BI dashboard to visualize insights.

---

## Dataset
The dataset contains information about YouTube trending videos including:

- Video ID
- Video Title
- Channel Title
- Category ID
- View Count
- Likes
- Comment Count
- Published Date
- Trending Date
- Tags and Description

Additional features such as **publish day, publish month, engagement metrics, and sentiment labels** were created during preprocessing.

---

## Tools and Technologies

### Programming
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn
- Power BI

### Text Analysis
- TextBlob (Sentiment Analysis)

### Querying
- SQL

---

## Data Cleaning and Preprocessing
The dataset was cleaned and prepared using the following steps:

- Removed duplicate records
- Standardized column names
- Converted date columns to datetime format
- Created new features such as publish day and publish month
- Calculated engagement metrics
- Performed sentiment analysis on video titles
- Classified titles into **Positive, Neutral, and Negative sentiment**

---

## Sentiment Analysis
Sentiment analysis was applied to video titles using the **TextBlob library**.  
Each title was analyzed and classified into:

- Positive
- Neutral
- Negative

This helps understand the emotional tone used in trending video titles.

---

## Data Analysis
Several analyses were performed to uncover patterns in trending videos:

- Category popularity based on total views
- Sentiment distribution of video titles
- Relationship between views and likes
- Publishing trends across weekdays
- Trending duration analysis

These analyses helped identify key factors influencing video popularity.

---

## Dashboard
An interactive **Power BI dashboard** was created to visualize insights from the dataset.

The dashboard includes:

- Total trending videos
- Total views and likes
- Top video categories by views
- Sentiment distribution of video titles
- Trending videos by weekday
- Trending duration distribution
- Views vs likes engagement analysis

---

## Key Insights
- Most trending video titles have **neutral sentiment**, indicating descriptive titles are common.
- Certain video categories consistently receive **higher view counts**.
- There is a **strong positive relationship between views and likes**.
- Publishing day may influence the likelihood of a video trending.
- Trending duration varies across videos, showing differences in content lifespan.

---

## Project Structure
youtube-trending-video-analytics
│
├── notebook.ipynb
├── cleaned_youtube_trending_data.xlsx
├── youtube_dashboard.pbix
├── project_report.pdf
└── README.md


---

## Conclusion
This project provides insights into YouTube trending videos by analyzing engagement metrics, content characteristics, and sentiment patterns. The findings help understand viewer behavior and content strategies that contribute to video popularity. The Power BI dashboard enables interactive exploration of these insights.

---
