# Spotify Social Media Analytics — Excel

## Project Overview

This project is an **Excel-based Social Media Analytics project for Spotify** focused on social media engagement, platform performance, hashtag strategy, campaign effectiveness, and follower growth.

The analysis uses Excel to clean the data, calculate engagement metrics, compare platforms, evaluate hashtags and content types, measure campaign performance, and analyze follower retention and loyalty.

---

## Business Objective

The main objective of this project is to use social media data to identify:

- High-performing platforms
- High-performing content types
- Effective hashtags
- Successful marketing campaigns
- Follower growth trends
- The relationship between advertising spend and audience growth
- Data-driven recommendations for Spotify's social media strategy

---

## Tools & Excel Skills Used

- Microsoft Excel
- Data Cleaning & Preprocessing
- Excel Formulas
- Pivot Tables
- Ranking using `RANK`
- Engagement Rate Analysis
- Campaign Analysis
- KPI Analysis
- Correlation Analysis
- Moving Average
- Data Visualization
- Business Insights & Recommendations

---

# Project Tasks

## Task 1 — Data Preprocessing & Cleaning

The first step was to prepare the data for analysis.

### Work Performed

- Checked for duplicate records
- Standardized data formats
- Corrected numeric columns
- Separated hashtag fields
- Prepared the dataset for further analysis

### Conclusion

No duplicate records were found. Data formats were standardized, numeric columns were corrected, and hashtag fields were separated. The dataset was ready for analysis.

---

## Task 2 — Engagement Analysis

This task focused on understanding engagement across platforms and identifying high-performing content and hashtags.

### Key Findings

- **Twitter** had the highest engagement rate.
- **Instagram** ranked second.
- **YouTube** ranked third.
- Text content performed best, especially on Instagram, based on likes, shares, and comments.

### Top Hashtags by Average Clicks

| Rank | Hashtag | Average Clicks |
|---|---|---:|
| 1 | #SpotifyWrapped | 208 |
| 2 | #DiscoverWeekly | 197 |
| 3 | #SoundtrackOfLife | 192 |
| 4 | #NowPlaying | 187 |
| 5 | #MusicForEveryone | 183 |

The `RANK` formula was used to rank hashtag performance.

### Conclusion

Twitter recorded the highest engagement rate, followed by Instagram and YouTube. Text content performed particularly well on Instagram. **#SpotifyWrapped** and **#DiscoverWeekly** were the top-performing hashtags based on average clicks.

---

## Task 3 — Platform Performance

This task compared platform performance using engagement, growth trends, and advertising spend.

### Platform Engagement

| Platform | Engagement |
|---|---:|
| Twitter | 527,370 |
| Instagram | 301,576 |
| YouTube | 228,696 |

### Conclusion

Twitter and Instagram were identified as the most effective platforms because they generated higher engagement, provided better growth trends, and delivered stronger returns on advertising spend.

Continuing to divide resources equally across all three platforms could reduce efficiency. YouTube can be treated as a secondary or experimental platform.

### Recommendation

Focus primarily on **Twitter and Instagram**, while keeping YouTube as a secondary platform.

---

## Task 4 — Hashtag & Content Strategy

This task evaluated how hashtags and different content types perform across platforms.

### Recommended Content Type–Platform Combinations

| Platform | Recommended Content | Engagement |
|---|---|---:|
| Instagram | Text | 226,112 |
| Twitter | Story | 317,039 |
| YouTube | Reel | 105,783 |

### Key Findings

- Using the right hashtags can make a significant difference in engagement.
- `#MusicForEveryone` and `#SpotifyWrapped` generated stronger audience engagement even though `#NowPlaying` was used more frequently.
- Different content types perform better on different platforms.

### Conclusion

The best strategy is to match the **content type and hashtag with the platform**.

- **Instagram → Text**
- **Twitter → Story**
- **YouTube → Reel**

Using platform-specific content and effective hashtags can improve overall reach and engagement.

---

## Task 5 — Campaign Effectiveness

This task evaluated campaign performance using ROI, impressions, likes, engagement uplift, follower growth, and app-download growth.

### Key Findings

**Highest ROI**

- **ChillVibes:** 276%
- **IndieWave:** 203%

This indicates that these campaigns generated strong engagement relative to their advertising spend.

**Strongest Follower Growth**

- **SummerBeats:** 13,558 new followers
- **IndieWave:** 12,726 new followers

**Campaign Scale & Engagement**

- **ChillVibes:** 6.3 million impressions
- **ChillVibes:** 471,034 total likes
- **SummerBeats:** highest average likes per post at 3,099

### Engagement Uplift

- **Wrapped2024:** 73.07% uplift, increasing from 2,758 to 4,773
- **IndieWave:** 35.90% uplift
- **SummerBeats:** -1.33% change in engagement

### Conclusion

ChillVibes achieved the highest ROI, while SummerBeats generated the strongest follower growth. Wrapped2024 showed the strongest engagement uplift, demonstrating that campaign success can differ depending on the metric being evaluated.

---

## Task 6 — Follower Retention & Loyalty

This task focused on follower growth trends and the relationship between advertising spend and audience growth.

### Key Findings

- Highest net follower gain: **04-Nov-2024**
- Net follower gain during that week: **3,576 followers**
- The moving average showed a **stable upward trend**.
- Correlation between Ad Spend and Net Followers was approximately **-0.02**.

### Conclusion

Follower growth showed a consistent and sustainable upward trend. The nearly zero correlation between advertising spend and follower growth indicates that content quality and audience engagement were more important drivers of follower growth than advertising spend alone.

---

# Overall Business Insights

The complete analysis provides several important insights for Spotify's social media strategy:

### 1. Prioritize High-Performing Platforms

Twitter and Instagram showed stronger overall performance and should receive greater strategic focus.

### 2. Use Platform-Specific Content

Different platforms respond better to different content formats. Text works well on Instagram, Stories on Twitter, and Reels on YouTube.

### 3. Improve Hashtag Selection

Hashtag frequency alone does not guarantee high engagement. Hashtags such as **#SpotifyWrapped** and **#MusicForEveryone** can generate stronger audience engagement.

### 4. Evaluate Campaigns Using Multiple KPIs

ROI, follower growth, impressions, likes, and engagement uplift can tell different stories. Campaign performance should therefore be evaluated using multiple KPIs rather than a single metric.

### 5. Focus on Content Quality and Engagement

The near-zero correlation between ad spend and follower growth suggests that increasing advertising spend alone may not be enough to improve audience growth. Strong content and audience engagement remain important.

---

# Project Structure

```text
spotify-social-media-analytics-excel/
│
├── README.md
├── task_1.xlsx
├── task_2.xlsx
├── task_3.xlsx
├── task_4.xlsx
├── task_5.xlsx
└── task_6.xlsx
```

The original dataset is not included in this repository.

---

# Conclusion

This project demonstrates the use of **Microsoft Excel for practical social media and marketing analytics**.

The project covers the complete analytical workflow:

**Data Cleaning → Engagement Analysis → Platform Analysis → Hashtag & Content Strategy → Campaign Effectiveness → Follower Retention & Loyalty**

The analysis converts social media data into practical business insights that can support better platform selection, content planning, hashtag strategy, campaign evaluation, and audience-growth decisions.

---

## Author

**Umesh Rajput**

Data Analytics | Excel | Power BI | SQL | Python
