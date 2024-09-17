# Twitter Dashboard Internship Report - Nullclass

This repository contains the completed internship tasks and training projects undertaken during my internship at Nullclass EdTech. The primary focus of the internship was on **data analytics** and **dashboard creation** using **Power BI**. Below is a breakdown of the key contents and dashboards developed during the internship.

## Overview

As part of this internship, I was tasked with developing dynamic and interactive dashboards using Power BI. These dashboards provide insights into tweet performance based on various engagement metrics. The key components of the project include:

- **Calculating engagement rates**
- **Filtering tweets** based on specific criteria (likes, word count, and time of posting)
- **Displaying insights** through visualizations, including bar charts, pie charts, and KPI visuals.

## Key Deliverables

### 1. **Task 1: Top 10% Tweets by Engagement Rate**
- **Objective**: Develop a chart displaying the top 10% of tweets based on engagement rates.
- **Criteria**: Tweets with more than 50 likes, posted on weekdays, with a word count below 30.
- **Time-Based Filter**: This chart dynamically updates to only show data between **1 PM and 4 PM**.
- **Visualizations**:
  - **Clustered Bar Chart**: Highlights the engagement rates of the top 10% of tweets, making it easier to compare them with others.
  - **KPI Card**: Displays key metrics such as the engagement rate of the top tweets.
  - **Pie Chart**: Shows the proportion of tweets in the top 10%, giving a clear visual representation.

### 2. **Task 2: Top 10 Tweets by Retweets and Likes**
- **Objective**: Build a chart identifying the top 10 tweets by the sum of retweets and likes.
- **Criteria**: Tweets posted on weekdays, with an even number of tweet impressions, odd tweet dates, and a word count below 30.
- **Time-Based Filter**: This chart works only between **3 PM and 6 PM**.
- **Visualizations**:
  - **Clustered Column Chart**: Shows the combined sum of retweets and likes for the top 10 tweets.
  - **User Profile Display**: Includes information on the user profile that posted each tweet, providing valuable insights into the top performers.

### 3. **Task 3: Media Views and Engagements by Day of the Week**
- **Objective**: Create a dual-axis chart that visualizes the number of media views and media engagements by the day of the week for the last quarter.
- **Criteria**: Tweets must have even tweet impressions, odd tweet dates, and a word count below 30.
- **Time-Based Filter**: The chart dynamically updates only between **3 PM and 6 PM**.
- **Visualizations**:
  - **Dual-Axis Chart**: One axis shows media views, and the other shows media engagements. It highlights days with significant spikes in interactions.
  - **Color Coding for Spikes**: Days with high levels of media engagement and media views are color-coded to easily identify spikes and trends.

### 4. **Time-Based Functionality Across All Tasks**
Each dashboard includes time-based functionality that dynamically updates the visualizations based on the system's local time. Depending on the task, the dashboards will either be **"Active"** or **"Inactive"** within the designated timeframes:
- **Task 1**: Active between **1 PM and 4 PM**.
- **Task 2 & 3**: Active between **3 PM and 6 PM**.
This ensures that the insights are only available within the specified time windows, adding a unique real-time element to the dashboards.

## Files

1. **twitter_dashboard-1.pbix**: The Power BI file containing all the visualizations and tasks completed as part of this internship.
2. **Internship Reports**: Detailed documentation of each task, including the learning objectives, challenges, and outcomes.

## Instructions

To view the dashboard and reports:
1. Clone or download the repository.
2. Open the **twitter_dashboard-1.pbix** file in Power BI Desktop.
3. Use the filters and interact with the visualizations to explore the data and insights.
4. Refer to the internship reports for detailed explanations of the tasks and methodologies used.

## Acknowledgments

This project was completed as part of the internship at Nullclass EdTech. The experience has greatly enhanced my skills in Power BI, data analytics, and dashboard creation, providing practical, hands-on knowledge in real-world data scenarios.
