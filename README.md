# EXPLORATORY-DATA-ANALYSIS-ON-YOUTUBE-DATA

# YouTube Dislike Analysis

# Project Overview
This project analyzes YouTube video data to understand patterns in the number of dislikes on videos. By investigating key factors like video duration, category, view count, and other variables, the analysis aims to discover what contributes to higher dislike counts. Insights from this analysis can help content creators optimize their videos and improve audience satisfaction.

# Key Objectives:
- Identify patterns: Explore what factors influence the number of dislikes on a video.
- Correlation Analysis: Examine the relationships between dislikes and other variables like views, likes, comments, and category.
- Predictive Model: Build a model to predict the dislike count based on key video metrics.

# Tools & Technologies
- Programming Language: Python
- Data Libraries: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn

  # Data
The data consists of multiple attributes for each video, including:

- Video ID: Unique identifier for the video.
- Title: The title of the video.
- Views: Total view count.
- Likes: Total like count.
- Dislikes: Total dislike count.
-0 Comments: Total comment count.
- Category: Category the video belongs to (e.g., Entertainment, Education).
- Duration: The length of the video.
The dataset may be sourced from YouTube's public data, and pre-processing steps include handling missing data, outliers, and feature engineering.

# Data Preprocessing
- Handling Missing Values: Remove or impute missing data to ensure the dataset is clean.
- Feature Engineering: Add useful features like like-dislike ratio, view-dislike ratio, and engagement rate.
- Normalization: Normalize data to ensure all variables have similar scales.

# Results
The analysis reveals several key findings:

- High Views ≠ Fewer Dislikes: Videos with a high view count can also attract more dislikes, especially if they cover controversial topics.
- Category Influence: Certain categories (like Politics) see more dislikes regardless of the quality of content.
- Engagement Metrics: Videos with higher comments or likes tend to have fewer dislikes, indicating positive audience interaction.
