# 📊 YouTube Analytics Dashboard

This project explores **global YouTube statistics**, analyzing channels, subscribers, views, earnings, and trends.
It uses Python, Pandas, Matplotlib, and Seaborn to provide insights into YouTube’s top creators and global reach.

---

## 🚀 Project Overview

The goal of this analysis is to:

* Clean and prepare the YouTube dataset.
* Explore correlations between subscribers, views, and earnings.
* Analyze trends by:

  * Channel type
  * Content category
  * Country
  * Creation year/month
* Visualize growth over time and across demographics.
* Identify top-performing channels globally.

---

## 📂 Dataset Description

The dataset includes **995 top YouTube channels** with 28 features, including:

| Column                                          | Description                                        |
| ----------------------------------------------- | -------------------------------------------------- |
| rank                                            | Global rank of the channel                         |
| Youtuber                                        | Channel name                                       |
| subscribers                                     | Total subscribers                                  |
| video views                                     | Total views                                        |
| category                                        | Content category (Music, Gaming, Education, etc.)  |
| Title                                           | Channel title                                      |
| uploads                                         | Total videos uploaded                              |
| Country                                         | Channel’s country                                  |
| channel_type                                    | Type of channel (Entertainment, Music, Tech, etc.) |
| lowest_monthly_earnings                         | Estimated minimum earnings per month               |
| highest_monthly_earnings                        | Estimated maximum earnings per month               |
| lowest_yearly_earnings                          | Estimated minimum earnings per year                |
| highest_yearly_earnings                         | Estimated maximum earnings per year                |
| created_year/month/date                         | Channel creation date                              |
| subscribers_for_last_30_days                    | Subscribers gained in last 30 days                 |
| Population, Unemployment rate, Urban_population | Country statistics                                 |
| Latitude, Longitude                             | Geographic location                                |

---

## 🧹 Data Cleaning Steps

* Checked for duplicates (none found).
* Handled missing values for categories, countries, and other columns.
* Verified numeric columns for correct type and format.
* Filtered and aggregated statistics for analysis.

---

## 📊 Visualizations & Insights

### 1️⃣ Subscribers by Category

* Education, Shows, and Film & Animation channels have the highest mean subscribers.
* Visualized with a **bar chart**.

### 2️⃣ Channel Type Distribution

* Entertainment and Music dominate top channels.
* Visualized with a **pie chart**.

### 3️⃣ Subscribers vs Video Views

* Scatter plot shows correlation between subscribers and total video views.

### 4️⃣ Subscribers by Country

* US and India dominate in total subscribers.
* Bar chart shows the top 10 countries.

### 5️⃣ Subscribers Growth Over Time

* Area plots show subscriber growth by year and month.
* Top channel types show trends in subscriber gain over creation years.

### 6️⃣ Earnings Analysis

* Boxplots show highest yearly earnings by channel type.

### 7️⃣ Heatmaps & Trend Analysis

* Subscribers by channel type and creation year.
* Monthly average subscribers line chart.

---

## 🛠 Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Google Colab**

---

## 📁 Project Structure

```
📦 youtube-analytics-dashboard
│
├── GlobalYouTubeStatistics.csv
├── youtube_analytics.ipynb
├── README.md   ← (You are here)
```

---

## 📈 Key Insights

* Entertainment, Shows, and Film & Animation channels dominate subscribers.
* US and India are the largest markets by subscriber count.
* Newer channels may have rapid growth depending on niche.
* Earnings correlate strongly with subscribers and views.
* Subscriber growth trends vary by channel type and creation year.

---

## 📬 Contact

For questions, suggestions, or collaboration ideas, feel free to reach out. This analysis can be extended for predictive analytics, growth projections, or regional insights.

---
