# LRZ · Presence & Impact
## Social Media Engagement Dashboard

---

## Project Overview
A 12-month social media performance dashboard built for 
Little Red Zombies (LRZ), an indie creative studio, as part 
of a Data Visualization Artist hiring assignment.

The goal was to help stakeholders understand LRZ's social 
media performance, identify trends and highlight what needs 
attention — using only publicly available data.

---

## Dataset
- 125 posts manually collected from public social media profiles
- Platforms: Instagram, LinkedIn, ArtStation
- Period: April 2025 – April 2026
- Metrics tracked: Likes, Comments, Shares
- Post Categories: Artwork, Announcement, Hiring, 
  Celebrations, Collaboration, Summit

> Note: All data was collected from publicly visible post 
> metrics only. Impressions and reach are not publicly 
> available and were excluded. All data decisions are 
> documented in the Assumptions Log.

---

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Google Sheets | Data collection, cleaning, pivot tables, dashboard |
| Power BI | Interactive dashboard with slicers |
| DAX | Calculated columns and measures in Power BI |

---

## Project Workflow

### 1. Data Collection
- Manually collected post data from Instagram, LinkedIn 
  and ArtStation public profiles
- Categorised each post by intent into 6 categories
- Documented all assumptions and data limitations

### 2. Data Preparation (Google Sheets)
- Added calculated columns:
  - Total Engagement = Likes + Comments + Shares
  - Engagement Rate % = Total Engagement / Followers × 100
  - Month = TEXT formula for readable month labels
- Treated blank Comments and Shares as 0 using IFERROR
- Created Assumptions Log documenting every data decision

### 3. Data Analysis (Google Sheets Pivot Tables)
- Platform Overview — total engagement and post count by platform
- Category Performance — engagement by post category
- Monthly Trend — engagement over time
- Post Distribution — cross table of platform vs category
- Avg Interactions Per Post — average engagement by 
  platform and category combination

### 4. Data Visualization (Google Sheets Dashboard)
- 4 KPI cards — Total Posts, Total Engagement, 
  Avg Engagement Rate %, Top Platform
- 4 charts — Bar, Pie, Line, Column
- Key Insights section with 6 findings
- LRZ branded colour scheme throughout

### 5. Data Visualization (Power BI)
- Connected Google Sheets CSV to Power BI
- Recreated all 4 charts with interactive slicers
- Added Platform and Post Category slicers
- DAX measure for Top Platform KPI
- Month_Sort calculated column for chronological sorting

---

## Dashboard Preview

### Google Sheets Dashboard
[Add screenshot here]

### Power BI Dashboard
[Add screenshot here]

---

## Key Insights
1. **ArtStation leads engagement** despite only posting 
   Artwork — averaging 274 interactions per post, highest 
   of all three platforms
2. **Artwork drives 70.7%** of all engagement across 
   platforms — LRZ's audience follows them for the work first
3. **Celebrations posts outperform Artwork** per post on 
   both Instagram (234 avg) and LinkedIn (265 avg)
4. **Collaboration posts are the weakest category** — 
   averaging just 70 interactions on Instagram and 58 on LinkedIn
5. **Engagement peaked in Jul–Aug 2025** and declined 
   sharply through early 2026
6. **X (Twitter) has zero posts** in the analysis period — 
   an untapped channel worth evaluating

---

## Learnings
- Working with incomplete public data taught me to be 
  transparent about limitations rather than filling gaps 
  with estimates
- Categorising posts by intent rather than format gives 
  more meaningful insights for stakeholders
- Power BI's DAX language is powerful for creating 
  calculated columns and measures that Google Sheets 
  formulas can't easily replicate
- A well documented Assumptions Log is as important as 
  the dashboard itself — it builds trust in the data

---

## Conclusion
This project showed that even with limited public data, 
meaningful insights can be extracted with the right 
structure and approach. LRZ has a strong creative presence 
— ArtStation is their most engaged platform and Artwork 
is clearly what their audience comes for. The decline in 
2026 engagement and underperformance of Collaboration 
posts are areas worth attention.

---

## Files
| File | Description |
|------|-------------|
| LRZ_Raw_Data.csv | 125 posts with calculated metrics |
| LRZ_Written_Summary.pdf | Approach, insights and assumptions |
| Dashboard_Screenshot_Sheets.png | Google Sheets dashboard |
| Dashboard_Screenshot_PowerBI.png | Power BI dashboard |

---

## Connect
[Your LinkedIn profile link]
