# Infinity nikki Reddit community analysis

## Project Goals
1. What topics players discuss most frequently(topics analysis of Posts)
2. How players feel about different aspects of the game (sentiments analysis of Posts)
3. Which issues or features generate the most engagement(Engagement analysis/Post-#Comments)
4. 一个post下面的Comments（sentiments analysis/Percentage-Topic/Keyword Analysis/- Post）
5. post x comment分析，哪个类型的post引发最多评论
6. What insights can be extracted to support player feedback analysis and community-facing decision-makin

## Respositary Tree
```text
infinity-nikki-reddit-analysis
│
├──01_post_analysis
│  ├── post_sentiment_analysis.ipynb
│  ├── post_topic_analysis.ipynb
│  └── top_posts_analysis.ipynb
│
├── 02_comments_analysis
│   ├── comment_sentiment_analysis.ipynb
│   ├── keyword_frequency.ipynb
│   └──  comment_length_analysis.ipynb
│  
├── 03_engagement_analysis
│    ├──01_engagement_level_analysis.ipynb
│    ├──02_engagement_drivers_anaysis.ipynb
│    └──03-engagement_trends_analysis.ipynb
│
├── data
│   ├── raw_data
│   │   ├── reddit_posts_raw.csv
│   │   └── reddit_comments_raw.csv
│   └── processed_data
│       └── merged_reddit_data.csv
│



├── output
│   │
│   ├── figures
│   │   ├── engagement_trend.png
│   │   ├── sentiment_distribution.png
│   │   └── topic_frequency.png
│   │
│   └── tables
│       ├── engagement_metrics.csv
│       └── sentiment_summary.csv
│
│
├── powerbi
│   └── reddit_dashboard.pbix
│
│
└── README.md
```
# Order to Run
# Project Structure

# Data Source
Reddit API
