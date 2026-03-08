📊 Anime Industry Analytics Dashboard
📌 Project Overview

This project analyzes 10,000 anime titles to uncover patterns in ratings, audience engagement, content formats, and industry trends.

Using Python for exploratory data analysis and Power BI for interactive visualization, the project explores:

Relationship between engagement and ratings

Performance of different anime formats

Impact of episode length on audience engagement

Industry growth trends over time

The final output is an interactive 3-page Power BI dashboard supported by Python analysis.

🛠 Tools & Technologies

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

Visualization

Power BI

Version Control

GitHub

📂 Dataset

The dataset contains 10,000 anime titles with attributes including:

Title

Rating (Score)

Popularity Rank

Members (Audience Engagement)

Episodes

Anime Type (TV, Movie, OVA, ONA, Special)

Start and End Dates

🧹 Data Preparation (Python)

Data cleaning and feature engineering were performed using Pandas.

Key transformations:

Converted date columns to datetime format

Extracted release_year

Created is_ongoing indicator

Handled missing values

Created episode length categories

Episode groups:

Short (<12 episodes)

Medium (12–50 episodes)

Long (>50 episodes)

📊 Exploratory Data Analysis
Engagement vs Rating

A moderate positive relationship was observed between audience engagement and ratings, suggesting highly followed anime tend to receive higher ratings.

Format Analysis

Comparison across formats revealed:

TV anime dominates audience engagement

Movies and OVAs show moderate engagement levels.

Episode Length Impact

Anime with 12–50 episodes showed the highest engagement, while short anime had the lowest.

Industry Trends

Time-series analysis shows:

Rapid growth in anime production after 2000

Significant increase in audience engagement during the streaming era

Ratings remained relatively stable (~6.5–7.2)

📊 Power BI Dashboard

An interactive 3-page dashboard was built to present insights.

📄 Executive Overview

KPI metrics (Average Score, Average Members, Total Anime)

Engagement vs Rating scatter plot

Top rated anime titles

📄 Format Analysis

Rating by format

Engagement by format

Episode length analysis

📄 Industry Trends

Anime production growth

Engagement trend

Rating trend over time

💡 Key Insights

Engagement shows moderate correlation with ratings

TV format attracts the largest audience

Medium-length anime (12–50 episodes) perform best

Industry growth accelerated after the 2000s

🎯 Skills Demonstrated

Data Cleaning & Preparation

Exploratory Data Analysis

Feature Engineering

Data Visualization

Dashboard Development

Data Storytelling

⭐ Project Outcome

This project demonstrates how Python analytics combined with Power BI dashboards can generate actionable insights from entertainment industry data.
