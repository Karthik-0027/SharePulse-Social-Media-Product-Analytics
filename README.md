# SharePulse-Social-Media-Product-Analytics
An end-to-end social media product analytics project focused on user engagement, content performance, growth metrics, and actionable insights using Python, SQL, and Power BI.

<p align="center">
  <b>Turning Social Media Data into Actionable Product Insights</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" />
  <img src="https://img.shields.io/badge/SQL-Analytics-orange?logo=postgresql" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi" />
  <img src="https://img.shields.io/badge/Excel-Data%20Analysis-green?logo=microsoftexcel" />
  <img src="https://img.shields.io/badge/Project-End--to--End-success" />
</p>

## 📌 Project Overview

**SharePulse** is an end-to-end Social Media Product Analytics project designed to analyze user engagement, content performance, audience activity, and platform growth.

The project transforms raw social media data into meaningful business insights through data cleaning, exploratory data analysis, SQL-based querying, KPI development, and interactive Power BI dashboards.

It aims to help product managers and business teams understand how users interact with content, identify engagement patterns, evaluate platform performance, and make data-driven product decisions.

## 🎯 Business Problem

Social media platforms generate large volumes of user interaction data every day. However, raw engagement data alone does not explain:

- Which content formats generate the highest engagement?
- Which users are most active on the platform?
- What days and times produce higher engagement?
- How do likes, comments, and shares vary across content categories?
- Which engagement patterns can help improve user retention?
- How can product teams monitor platform growth and performance?

SharePulse addresses these questions through structured analytics and visualization.

## 🎯 Project Objectives

- Analyze user engagement and content performance.
- Identify trends in likes, comments, shares, and interactions.
- Understand user activity and engagement patterns.
- Compare engagement across content categories and formats.
- Develop meaningful product performance KPIs.
- Build an interactive Power BI dashboard.
- Generate actionable recommendations for product improvement.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Exploratory data visualization |
| SQL | Data querying and aggregation |
| Microsoft Excel | Initial data inspection and validation |
| Power BI | Interactive dashboard and reporting |
| Git & GitHub | Version control and project documentation |

## 📂 Project Structure

```text
SharePulse-Social-Media-Product-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   └── 04_insights_and_analysis.ipynb
│
├── sql/
│   ├── data_exploration.sql
│   ├── engagement_analysis.sql
│   └── user_performance.sql
│
├── dashboard/
│   └── SharePulse_Dashboard.pbix
│
├── reports/
│   └── business_insights.md
│
├── visuals/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## 🔄 End-to-End Project Workflow

### 1. Business Understanding

Define the business questions, identify relevant engagement metrics, and establish the analytical objectives.

Key areas:
- User engagement
- Content performance
- Audience activity
- Platform growth
- Product performance

### 2. Data Collection and Understanding

Collect or obtain a suitable social media interaction dataset containing relevant information such as:

- User ID
- Post ID
- Content type
- Post category
- Likes
- Comments
- Shares
- Views or impressions
- Post timestamp
- User activity information

Examine dataset structure, column types, missing values, duplicates, and data consistency.

### 3. Data Cleaning and Preprocessing

Use Python and Pandas to:

- Handle missing and inconsistent values.
- Remove duplicate records where appropriate.
- Correct data types.
- Standardize categorical values.
- Handle invalid or inconsistent records.
- Prepare structured datasets for analysis.

### 4. Exploratory Data Analysis (EDA)

Perform EDA using Python to discover patterns and relationships.

Analysis areas:

- Distribution of likes, comments, and shares.
- Engagement across content categories.
- User activity distribution.
- Daily and monthly engagement trends.
- High-performing and low-performing content.
- Relationship between views and interactions.

Visualize findings using Matplotlib and Seaborn.

### 5. SQL-Based Data Analysis

Use SQL to perform structured analytical queries and business-level aggregations.

Planned analytical queries:

- Total engagement by content category.
- Top-performing posts.
- Most active users.
- Average engagement per post.
- Daily and monthly engagement trends.
- Engagement comparisons across content types.

### 6. KPI Development

Develop product analytics metrics such as:

| KPI | Purpose |
|---|---|
| Total Users | Measure platform audience |
| Total Posts | Measure content activity |
| Total Likes | Measure positive interactions |
| Total Comments | Measure discussion activity |
| Total Shares | Measure content distribution |
| Total Engagement | Measure overall interactions |
| Average Engagement per Post | Compare content performance |
| Engagement Rate | Measure engagement relative to reach or impressions |

Example engagement calculation:

**Total Engagement**

\[
Likes + Comments + Shares
\]

**Engagement Rate**

\[
\frac{Likes + Comments + Shares}{Impressions}\times100
\]

The denominator and treatment of missing values should be defined consistently before calculating the metric.

### 7. Power BI Dashboard Development

Build an interactive dashboard to communicate analytical findings.

Planned dashboard components:

- KPI cards for overall platform performance.
- Engagement by content category.
- Top-performing posts.
- User activity analysis.
- Monthly engagement trends.
- Likes, comments, and shares comparison.
- Interactive slicers for content type, category, and time period.

### 8. Business Insights and Recommendations

Translate analytical findings into actionable recommendations.

Examples of questions to answer:

- Which content categories should receive more attention?
- When should content be published?
- Which engagement metrics need improvement?
- What types of content generate more interactions?
- Which user segments show higher activity?

Recommendations will be based on actual analytical results rather than assumptions.

## 📈 Expected Business Outcomes

- Better understanding of user engagement.
- Identification of high-performing content categories.
- Improved visibility into platform activity.
- Data-supported content strategy decisions.
- Consistent monitoring of product KPIs.
- Actionable insights for product and growth teams.

## 🚀 How to Run the Project

### Prerequisites

- Python 3.10+
- Jupyter Notebook
- SQL database (SQL Server or PostgreSQL)
- Microsoft Power BI Desktop

### Installation

Clone the repository:

```bash
git clone https://github.com/Karthik-0027/SharePulse-Social-Media-Product-Analytics.git
```

Navigate to the project:

```bash
cd SharePulse-Social-Media-Product-Analytics
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebooks in the numbered order, prepare the analytical dataset, execute the SQL scripts, and open the Power BI dashboard.

## 📌 Current Project Status

**Project Stage:** Repository setup and project planning.

The complete workflow, analysis, dashboard, and business insights will be documented as the implementation progresses.

## 👨‍💻 Author

**Karthik Gollapudi**

B.Tech – Data Science

- GitHub: [Karthik-0027](https://github.com/Karthik-0027)
- LinkedIn: [Karthik Gollapudi](https://www.linkedin.com/in/karthik-gollapudi/)

---

<p align="center">
  <b>SharePulse – Turning Engagement Data into Product Intelligence.</b>
</p>
