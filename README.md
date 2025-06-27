# 📈 YouTube Trending Video Analytics Project

## 📝 Project Overview

This project focuses on analyzing YouTube trending video datasets from multiple countries to extract insights into viewer behavior, content popularity, and regional differences. By applying data preprocessing, sentiment analysis, SQL querying, and visualization, we aim to present a comprehensive dashboard and final report with storytelling insights.

---

## 🎯 Objectives

- Clean and standardize multi-region YouTube datasets
- Analyze sentiment in video titles and tags
- Rank video categories by average views using SQL
- Visualize the trending duration of videos per region
- Create a multi-tab dashboard with KPIs, comparisons, and story-driven visuals
- Export insights to Excel, PDF, and PowerPoint

---

## 🛠️ Tools & Technologies Used

| Tool            | Purpose                           |
|-----------------|-----------------------------------|
| **Python**      | Data preprocessing & analysis     |
| **Pandas**      | Data cleaning and transformation  |
| **TextBlob**    | Sentiment analysis                |
| **Matplotlib** / **Seaborn** | Visualization        |
| **SQLite**      | Structured querying via SQL       |
| **Power BI**    | Dashboard and data storytelling   |
| **Excel/CSV**   | Output data storage               |
| **PowerPoint**  | Final project presentation        |


---

## 🔍 Steps Performed

1. **Data Cleaning**
   - Merged datasets from multiple countries (US, IN, GB, CA, etc.)
   - Standardized column names and formats
   - Converted trending and publish dates to `datetime` format

2. **Sentiment Analysis**
   - Used `TextBlob` to classify video titles and tags as Positive, Negative, or Neutral
   - Stored sentiment labels and polarity scores

3. **SQL Analysis**
   - Created SQLite database from cleaned data
   - Queried average views per category per region using `GROUP BY`
   - Exported results for dashboard integration

4. **Trending Duration Calculation**
   - Measured how many days a video stayed on the trending list per country
   - Aggregated duration data by video and category

5. **Visualization**
   - Used `seaborn` and `matplotlib` to create:
     - Sentiment distribution bar plots
     - Average views bar charts
     - Region-wise comparison charts
     - Time-series for trending durations

6. **Dashboard (Power BI / Python)**
   - Designed dashboard with:
     - KPIs (Avg Views, Total Videos, Sentiment Ratio)
     - Region filters, slicers
     - Charts comparing views, likes, and durations
     - Sentiment breakdown visuals

7. **Final Reporting**
   - Exported cleaned data and outputs to Excel
   - Generated presentation and PDF report with insights and conclusions

---

## 📊 Dashboard Features

- ✅ **KPIs**: Average Views, Avg Likes, Total Videos, Sentiment Scores
- 🌍 **Region-wise Filters**: Toggle across US, IN, GB, etc.
- 🧠 **Sentiment Chart**: Sentiment distribution of trending titles
- 📈 **Trending Duration Chart**: Which categories trend longest per region
- 🎬 **Category-Wise Engagement**: Views per category per region
- 📌 **Storytelling Slides**: Top insights in a visual format

---

## 📤 Final Deliverables

| File | Description |
|------|-------------|
| `YouTube_Analytics_Report.xlsx` | All cleaned & analyzed data across sheets |
| `sentiment_by_region.xlsx` | Sentiment distribution per country |
| `duration_by_region.xlsx` | Avg. trending duration per region |
| `avg_views_by_category_region.xlsx` | Category-wise avg. views by country |
| `YouTube_Trending_Analytics_Report.pptx` | PowerPoint summary |
| `final_report.pdf` | 1–2 page write-up with project overview |
| `dashboard.pbix` | Power BI dashboard (optional) |

---

## 📘 Conclusion

This project highlights how multi-region YouTube trending data can be transformed into actionable insights through structured analytics. By comparing video performance, audience sentiments, and engagement across countries, we gain deeper visibility into online content trends, aiding content creators, marketers, and platform analysts.

---

## 🙋‍♂️ Author

- **Name:** Shobana Balusamy
- **Email:** shobana1115@gmail.com
- **Internship/Project Title:** YouTube Trending Data Analysis

---

