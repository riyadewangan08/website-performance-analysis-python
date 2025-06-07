# website_performance_analysis_by_python
📊 Website Performance Analysis – 


![website performance analysis project](https://github.com/riyadewangan08/website_performance_analysis_by_python/blob/ab11cb6b954fdae6a9cfbf9ac6c31c6aab853c71/website%20analysis%20banner.png)
## 📁 Project Overview
This Python project performs a detailed analysis of website traffic data to understand user behavior, engagement, and session trends over time. It addresses seven key questions about traffic sources, user engagement, peak hours, and correlations between sessions and engagement.

Using Pandas and Matplotlib, the project aggregates and visualizes data to provide actionable insights for improving website performance, optimizing marketing channels, and enhancing user engagement.

## 🔧 Tools & Technologies Used
- Jupyter Notebook
-  Python
- Pandas
- Matplotlib
- seaborn 

## 📂 Dataset Info
The dataset used in this project contains detailed website traffic logs, capturing user interactions on an hourly basis. It includes the following key columns:

- DateHour: Timestamp combining date and hour, representing the time of website activity.

- sessions: Number of sessions recorded in that hour. A session represents a single visit by a user.

- users: Count of unique users who visited the website during that hour.

- channel: Marketing or traffic channel through which users arrived (e.g., Organic Search, Paid Search, Direct, Referral, Social).

- engagement_time: Average time users spent engaged during the session (in seconds or minutes).

- engagement_rate: Percentage of engaged sessions out of total sessions, indicating user interest level.

- session_type: Classification of sessions into engaged and non-engaged categories.

This structured data enables detailed analysis of traffic trends, user behavior, and channel effectiveness across different times of day and days of the week.


# ❓ Questions Solved

## 1) What patterns or trends can you observe in website sessions and users over time?

### 🔍 Analysis
-Sessions are consistently higher than users, showing repeat visits.

-Noticeable spikes on April 15–19, likely due to a campaign or event.

-Traffic follows a daily pattern, with regular peaks and drops.

-Post-spike, sessions and users show a slightly stable upward trend
 ![Image](https://github.com/user-attachments/assets/d5975f64-8e79-45f5-b474-01bf84b1b92d)

 ## 2)Which marketing channel brought the highest number of users to the website and how can we use this insight to improve traffic from other sources?
### 🔍 Analysis
-organic social brought the most users -strong performance

-email and video need better stratergy

-focus on improving low-performing channels

-search and direct works but can be improved


## 3) Which channel has the highest average engagement time, and what does that tell us about user behavior and content effectiveness?
### 🔍 Analysis
Organic Video showed the highest average engagement time, indicating strong content effectiveness.

Referral and Email also performed well in keeping users engaged.

Direct and Organic Search had lower engagement, suggesting less user interaction.

Focus on video content can help boost engagement across other channels.



## 4) How does engagement rate vary across different traffic channels?
### 🔍 Analysis
Referral and Organic Search channels show the highest median engagement rate, indicating consistent user interaction.

Organic Social and Direct have moderate engagement but wider variability.

Unassigned and Organic Video have low and inconsistent engagement rates.

Email has a broad range, suggesting mixed user behavior.

Focus on Referral & Organic Search for scalable, high-engagement traffic


## 5) Which channels are driving more engaged sessions compared to non-engaged ones, and what strategies can improve engagement in underperforming channels?
### ✅ Engaged vs Non-Engaged Sessions – Key Insights¶
Organic Social has the highest engagement – strong performance.

Email and Referral also show more engaged than non-engaged sessions.

Direct and Organic Search have more non-engaged users – needs improvement.

Unassigned traffic is minimal and mostly unengaged.

Organic Video shows no data – could be inactive or untracked


## 6) At what hours of the day does each channel drive the most traffic?
### 🕒 Traffic by Hour and Channel – Key Insights
Peak traffic occurs between 11 AM to 6 PM across most channels.

Organic Social shows consistently high traffic, especially around 1 PM to 4 PM.

Email campaigns perform best around 12 PM, with a major spike.

Organic Search drives traffic mostly between 11 AM to 3 PM.

Referral and Direct channels have steady traffic throughout the day, peaking slightly around 2 PM to 4 PM.

Unassigned and Organic Video channels have minimal impact across all hours.

Recommendation: Schedule key campaigns and posts between 11 AM – 4 PM for maximum visibility and engagement.


## 7) Is there any correlation between high traffic (sessions) and high engagement rate over time?
### 📈 Correlation Between Sessions & Engagement Rate – Key Insights
Sessions (orange line) show frequent spikes, indicating high traffic variation across dates.

Engagement rate (red line) remains mostly flat and low throughout the observed period.

There is no strong correlation between high traffic and high engagement — even when session counts rise, engagement doesn't significantly increase.

Conclusion: High traffic does not guarantee high engagement. Focus on content quality and user experience to boost engagement rate
