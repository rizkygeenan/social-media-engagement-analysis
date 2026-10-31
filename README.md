# 📊 Case Study: Social Media Engagement Analysis

A data-driven social media performance analysis project evaluating content effectiveness, identifying audience interaction patterns, and delivering strategic insights for content marketing teams.

---

## 📌 Project Overview

This project aims to measure and analyze the performance of various social media posts using an engagement metrics dataset (*reach*, *impression*, *likes*, *comments*, *shares*, *saves*, and *clicks*). 

By calculating core metrics such as **Engagement Rate (ER)**, **Interaction-per-Reach (IPR)**, **Interaction-per-Impression (IPI)**, and **Click-Through Rate (CTR)**, this analysis provides a quantitative view of which content types are most effective and the underlying factors driving user engagement.

---

## 🎯 Objectives

1. **Understand Engagement Concepts**: Explain the relevance of engagement metrics in the context of Social Media Analytics.
2. **Identify Relevant Metrics**: Determine at least 4 key engagement metrics for content evaluation.
3. **Calculate Metrics**: Compute engagement metrics precisely alongside clear mathematical formulas and calculation steps.
4. **Comparative Analysis**: Compare performance across different content types objectively based on quantitative data.
5. **Interpretation & Insights**: Generate descriptive insights regarding content format effectiveness and audience interaction behavior.
6. **Strategic Reflection**: Address reflective questions regarding the importance of engagement analysis and the limitations of specific metrics.

---

## 📁 Repository Structure

```text
.
├── data/
│   └── Social_Media_Engagement_Dataset.xlsx   # Raw dataset analyzed
├── notebooks/
│   └── Social_Media_Analytics.ipynb           # Python Notebook / Colab Script
├── dashboards/
│   └── Social_Media_Analytics.pbix            # Power BI Interactive Dashboard
├── docs/
│   ├── Assignment_Social_Media_Analytics.pdf  # Full Analysis Report (PDF)
│   └── Reflection_Questions.pdf               # Reflection Answers (PDF)
└── README.md                                  # Portfolio Documentation
```
---
## 🛠️ Tools & Technologies Used

- **Python / Google Colaboratory**: Data processing, aggregation, and metric calculations.
- **Power BI**: Interactive data visualization and content performance dashboard creation.
- **Google Docs / PDF / PPTX**: Concise report drafting and analysis documentation.

---

## 📐 Engagement Metrics & Formulas

Below are the primary metrics used in this analysis along with their operational formulas:

| Engagement Metric | Formula | Description & Purpose |
| :--- | :--- | :--- |
| **Engagement Rate (ER)** | `(Total Interactions / Total Reach) * 100%` | Measures the proportion of unique reached users who actively interacted with the content. |
| **Interaction-per-Reach (IPR)** | `(Likes + Comments + Shares + Saves) / Reach` | Measures the intensity of organic interactions per unique individual reached. |
| **Interaction-per-Impression (IPI)** | `(Likes + Comments + Shares + Saves) / Impressions` | Measures interaction efficiency relative to total screen displays. |
| **Click-Through Rate (CTR)** | `(Clicks / Impressions) * 100%` | Measures the conversion rate of content impressions into direct user actions (clicks). |

---

## 📈 Key Findings & Insights Summary

1. **Top Performing Content**: *Carousel/Video Reel* formats achieved significantly higher **Engagement Rates (ER)**, driven primarily by strong *share* and *save* volumes.
2. **Audience Interaction Patterns**: Educational *visual/carousel* posts consistently yielded higher *Interaction-per-Reach (IPR)* compared to single static images, which tended to receive predominantly passive *likes*.
3. **Root Drivers**: High *save* and *share* metrics indicate that audiences perceived the content as highly utilitarian, offering value worth bookmarking or forwarding to others.
4. **Reach vs. Engagement Disconnect**: Certain posts exhibited high *reach* but low *engagement rates*. This indicates that while titles or thumbnails were effective at leveraging algorithm distribution, the core message failed to trigger meaningful engagement actions.

---

## 💭 Reflection Questions Summary

### 1. Why is engagement considered a critical indicator, and when can Engagement Rate be misleading?
Engagement reflects how effectively content builds emotional connection and active audience interest rather than passive screen scrolls (*impressions*). However, ER can be misleading when:
- **Sample Size / Reach is Extremely Small**: A post with 10 reach and 5 interactions yields a 50% ER, yet it is not more successful than a post with 100,000 reach and 5,000 interactions (5% ER).
- **Negative Sentiment**: Standard ER formulas do not account for sentiment (e.g., massive waves of negative comments or criticism still count toward total interactions).

### 2. How does comparative content analysis inform future strategy?
Comparing qualitative and quantitative metrics across formats and topics allows content teams to uncover their *winning formula* (identifying which formats drive sign-ups/clicks vs. those ideal for top-of-funnel *awareness*). This enables more focused and measurable content resource allocation.

### 3. Interpreting High Reach with Low Engagement:
This pattern serves as an early indicator of a **mismatch between initial hook and content relevance**. The thumbnail or headline successfully engaged algorithmic distribution, but the actual body content failed to incentivize users to like, comment, or share. Addressing this avoids creating perceived *clickbait*, which can degrade brand credibility over time.

---

## 📸 Dashboard Preview
 <img width="866" height="489" alt="social-media-analytics-dashboard" src="https://github.com/user-attachments/assets/279f8007-36ab-4557-b068-35d3fd6e48bb" />


---

## 👤 Author

- **Nama**: Muhammad Rizky Ginanjar
- **Role**: Data Analyst
- **LinkedIn**: [Muhammad Rizky Ginanjar](https://www.linkedin.com/in/rizkyginan/)
