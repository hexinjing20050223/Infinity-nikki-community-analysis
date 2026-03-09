# Infinity nikki Reddit community analysis

## Project Goals
1. What topics players discuss most frequently(topics analysis of Posts)
2. How players feel about different aspects of the game (sentiments analysis of Posts)
3. Which issues or features generate the most engagement(Engagement analysis/Post-#Comments)
4. 一个post下面的Comments（sentiments analysis/Percentage-Topic/Keyword Analysis/- Post）
5. post x comment分析，哪个类型的post引发最多评论
6. What insights can be extracted to support player feedback analysis and community-facing decision-makin

##Respositary Tree
infinity-nikki-reddit-feedback-analysis/
│
├── 01_data_collection/
│   ├── 01_extract_post_data.ipynb
│   └── 02_collect_comments.ipynb
│
├── 02_data_processing/
│   ├── 01_clean_posts.ipynb
│   └── 02_clean_comments.ipynb
│
├── 03_post_analysis/
│   ├── 01_post_topic_classification.ipynb
│   ├── 02_post_sentiment_analysis.ipynb
│   ├── 03_post_karma_analysis.ipynb
│   └── 04_post_engagement_overview.ipynb
│
├── 04_comment_analysis/
│   ├── 01_sentiment_analysis.ipynb
│   ├── 02_topic_analysis.ipynb
│   ├── 03_feedback_type_analysis.ipynb
│   └── 04_keyword_frequency.ipynb
│
├── 05_engagement_analysis/
│   └── 01_post_comment_relationship.ipynb
│
├── 06_visualization/
│   └── 01_generate_charts.ipynb
│
├── 07_dashboard/
│   └── infinity_nikki_feedback_dashboard.pbix
│
├── data/
│   ├── raw/
│   │   ├── reddit_posts_raw.csv
│   │   └── reddit_comments_raw.csv
│   │
│   └── processed/
│       ├── reddit_posts_clean.csv
│       ├── reddit_comments_clean.csv
│       ├── posts_with_sentiment.csv
│       ├── comments_with_sentiment.csv
│       └── comments_with_topics.csv
│
├── output/
│   ├── charts/
│   │   ├── post_topic_distribution.png
│   │   ├── post_sentiment_distribution.png
│   │   ├── comment_sentiment_distribution.png
│   │   ├── topic_frequency.png
│   │   ├── feedback_type_distribution.png
│   │   └── engagement_analysis.png
│   │
│   └── tables/
│       ├── post_topic_summary.csv
│       ├── post_sentiment_summary.csv
│       ├── comment_sentiment_summary.csv
│       ├── topic_summary.csv
│       ├── feedback_type_summary.csv
│       └── engagement_summary.csv
│
├── requirements.txt
└── README.md
