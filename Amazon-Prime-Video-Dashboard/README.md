# Amazon Prime Video Content Analysis Dashboard

## 📌 Project Overview

The Amazon Prime Video Content Analysis Dashboard is an end-to-end Business Intelligence project built using Power BI. The dashboard provides a comprehensive analysis of Amazon Prime Video's content library, enabling users to explore content distribution, growth trends, genre preferences, ratings, and geographical coverage.

The primary objective of this project is to demonstrate practical skills in data preparation, modeling, visualization, and business storytelling while transforming raw data into actionable insights.

---

## 🎯 Business Problem

With thousands of movies and TV shows available on the platform, understanding content trends becomes increasingly important for content strategy, audience engagement, and regional expansion.

This dashboard aims to answer the following business questions:

- How has content availability grown over time?
- Which countries contribute the most content?
- What are the most popular genres on the platform?
- How is content distributed across different audience ratings?
- What is the ratio between Movies and TV Shows?
- What trends can be observed in content releases over the years?

By addressing these questions, stakeholders can gain valuable insights into content performance and identify opportunities for strategic decision-making.

---

## 📂 Dataset Information

| Attribute | Details |
|------------|------------|
| Source | Kaggle |
| Dataset | Amazon Prime Video Titles Dataset |
| Total Records | 9,687 |
| Key Fields | Title, Genre, Rating, Country, Release Year, Director, Type |
| Data Type | Structured CSV Dataset |

---

## 🛠️ Tools & Technologies Used

### Power BI
Used to build interactive reports and dashboards.

### Power Query
Used for:
- Data profiling
- Data cleansing
- Data transformation
- Handling null values
- Data standardization

### DAX (Data Analysis Expressions)
Used to create:
- KPI Measures
- Aggregations
- Dynamic calculations
- Performance indicators

### Data Modeling
Used to establish relationships and optimize report performance.

---

## 💡 Skills Demonstrated

This project showcases the following analytics and business intelligence skills:

### Data Preparation
- Data Cleaning
- Handling Missing Values
- Data Transformation
- Data Validation

### Data Modeling
- Creating Relationships
- Structuring Data Models
- Optimizing Report Performance

### DAX Development
- Calculated Measures
- KPI Creation
- Aggregation Functions
- Business Logic Implementation

### Dashboard Development
- Interactive Report Design
- KPI Cards
- Bar Charts
- Donut Charts
- Geographic Analysis
- Trend Analysis

### Business Analytics
- Data Interpretation
- Insight Generation
- Business Storytelling
- Recommendation Development

---

## 📊 Dashboard Components

### KPI Summary Cards
Provides a quick overview of key platform statistics:

- Total Titles
- Total Ratings
- Total Genres
- Total Directors
- Start Year
- End Year

### Rating Distribution Analysis
Visualizes the number of titles available under each content rating category.

### Country-wise Content Distribution
Displays content availability by country using a geographic map visual.

### Genre Analysis
Highlights the most popular genres based on content volume.

### Movies vs TV Shows Analysis
Compares content distribution between Movies and TV Shows.

### Content Growth Trend
Tracks content release patterns across years to identify growth trends.

---

## 📈 Key Insights

### 1. Movies Dominate the Platform

Movies account for approximately **80.82%** of the total content library, while TV Shows represent only **19.18%**.

**Business Impact:**
Amazon Prime Video's content strategy appears heavily focused on movies, presenting an opportunity to expand TV show offerings and increase audience retention.

---

### 2. Rapid Content Growth After 2015

Content releases increased significantly after 2015, with a steep growth trend observed in recent years.

**Business Impact:**
This indicates aggressive content acquisition and expansion efforts to compete with major streaming platforms.

---

### 3. Drama Leads All Genres

Drama emerged as the most popular genre on the platform, followed by Comedy and Drama-Comedy combinations.

**Business Impact:**
Future content investments could prioritize high-performing genres to maximize viewer engagement.

---

### 4. Strong Geographic Presence in the United States

The United States contributes the highest volume of content available on the platform.

**Business Impact:**
This suggests a strong dependence on US-produced content and highlights opportunities for expanding regional content catalogs.

---

### 5. Diverse Audience Rating Coverage

The platform serves a wide range of audiences through content distributed across multiple rating categories.

**Business Impact:**
Maintaining balanced content across age groups supports broader audience reach and market penetration.

---

## 📋 Sample DAX Measures

### Total Titles

```DAX
Total Titles =
COUNTROWS('Prime Video')
```

### Total Directors

```DAX
Total Directors =
DISTINCTCOUNT('Prime Video'[director])
```

### Total Genres

```DAX
Total Genres =
DISTINCTCOUNT('Prime Video'[listed_in])
```

### Start Year

```DAX
Start Year =
MIN('Prime Video'[release_year])
```

### End Year

```DAX
End Year =
MAX('Prime Video'[release_year])
```

---

## 📸 Dashboard Preview

> Add dashboard screenshots here.

### Overview Dashboard

![Dashboard Overview](/dashboard-overview.png)

---

## 🚀 Business Recommendations

Based on the analysis, the following recommendations can be considered:

### Expand TV Show Portfolio
The platform is heavily movie-centric. Increasing investment in TV series may improve user retention and engagement.

### Invest in High-Performing Genres
Drama and Comedy consistently dominate viewer preferences and should remain strategic focus areas.

### Strengthen Regional Content Libraries
Expand content acquisition efforts in emerging markets to improve global representation.

### Optimize Audience Segmentation
Leverage rating distribution insights to tailor content offerings for specific audience groups.

---

## 📚 Learning Outcomes

Through this project, I strengthened my skills in:

- Power Query Transformations
- Data Modeling Best Practices
- DAX Measure Development
- Interactive Dashboard Design
- Business Storytelling with Data
- Data Visualization Principles
- KPI Development

---

## 👨‍💻 Author

**Deepak Baskaran**
Power BI Developer | Business Intelligence Enthusiast

### Skills
- Power BI
- SQL
- Power Query
- DAX
- Data Analytics
- KPI Development
- Process Improvement

## ⭐ Conclusion

This project demonstrates the complete lifecycle of a Business Intelligence solution—from raw data transformation to dashboard development and insight generation. It highlights the ability to translate data into meaningful business insights and communicate findings through interactive visualizations and storytelling.