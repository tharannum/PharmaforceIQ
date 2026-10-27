# 💊 PharmaForceIQ – HCP Campaign Performance & ROI Dashboard

## 📌 Project Overview

**PharmaForceIQ** is a Power BI dashboard project designed to analyze pharmaceutical marketing campaign performance, healthcare professional (HCP) engagement, prescription lift, and marketing return on investment.

The dashboard helps pharmaceutical marketing teams understand which HCP segments generate the highest prescription impact, which engagement channels perform most effectively, and how marketing budgets can be allocated to improve campaign efficiency.

Using campaign, engagement, prescription, and expenditure metrics, this project transforms marketing performance data into actionable insights for data-driven decision-making.

## 🎯 Business Objectives

The primary objectives of this project are to:

- Measure HCP reach, campaign engagement, and incremental prescription performance.
- Evaluate marketing expenditure and cost per incremental prescription.
- Compare campaign effectiveness across different engagement channels.
- Identify high-value HCP segments and their contribution to prescription lift.
- Analyze campaign performance across reporting periods and specialties.
- Identify underperforming marketing channels and opportunities for budget optimization.
- Support decisions about resource allocation between field representatives and digital marketing.

## 📊 Dashboard Structure

The Power BI dashboard is organized into four analytical pages.

### 1️⃣ Executive Overview

Provides a high-level summary of overall HCP marketing performance and campaign effectiveness.

**Key Performance Indicators (KPIs):**
- Total HCPs: 361
- Total Marketing Spend: $33,715.78
- Engagement Rate: 2%
- Prescription Lift: 1,000 incremental NRx
- Cost per Engagement: $71
- Cost per Incremental NRx: $26

**Key Insights:**
- The campaigns reached 361 targeted HCPs with approximately $33.72K in marketing expenditure.
- Tier 1 HCPs contributed 774 incremental prescriptions, representing approximately 61% of total prescription lift.
- Rep Visits achieved a 100% engagement rate in the displayed dataset, outperforming the digital channels on this metric.
- Website, Email, and Search recorded lower engagement rates than Rep Visits.

**Business Value:** Provides decision-makers with a consolidated view of campaign reach, marketing costs, and prescription outcomes.

### 2️⃣ Campaign Performance

Evaluates campaign-level performance using engagement, impressions, clicks, prescription lift, and expenditure.

**Key Metrics:**
- Total Clicks: Approximately 2K
- Average Cost per Click (CPC): $21
- Total Impressions: Approximately 26K
- Average Prescription Lift: 15%
- Total Marketing Spend: $33,715.78

**Key Insights:**
- Five campaigns were analyzed: GastroExtend Reach, NeuroNext Education, Launch OncoDrive Q1, EndoPulse Awareness, and CardiaCare Adherence.
- Launch OncoDrive Q1 recorded approximately $7.18K in expenditure.
- GastroExtend Reach generated approximately $7.10K in expenditure.
- The quarterly analysis compares prescription lift and engagement activity across all four quarters.
- Channel-level and campaign-level comparisons help identify differences in marketing costs and performance.

**Business Value:** Helps marketing teams evaluate campaign effectiveness, compare expenditure against outcomes, and identify campaigns that require further investigation.

### 3️⃣ HCP & Segment Analytics

Analyzes healthcare professionals by target segment and evaluates how different groups contribute to prescription performance.

**Key Insights:**
- The dashboard covers 361 HCPs across Tier 1, Tier 2, and Tier 3 segments.
- Tier 1 generated 774 incremental prescriptions, approximately 60.52% of the total displayed in the segment analysis.
- Tier 2 contributed 274 incremental prescriptions.
- Tier 3 contributed 231 incremental prescriptions in the displayed segment breakdown.
- The dashboard compares engagement rate and prescription lift across the three HCP tiers.
- Individual HCP performance is analyzed using HCP NPI identifiers and specialty categories, including Cardiology, Endocrinology, Gastroenterology, Neurology, and Oncology.

**Business Value:** Helps identify high-impact HCP segments and supports more targeted marketing and field-engagement strategies.

### 4️⃣ Budget Allocation & Optimization

Evaluates marketing channels based on engagement, prescription lift, HCP reach, expenditure, and acquisition efficiency.

**Channel Performance Summary:**

| Channel | Total Spend | Prescription Lift | Cost per Incremental NRx |
|---|---:|---:|---:|
| Display | $5,977.20 | 9% | $28 |
| Email | $1,761.97 | 10% | $8 |
| Rep Visit | $19,190.00 | 31% | $49 |
| Search | $3,237.66 | 16% | $12 |
| Website | $3,548.95 | 18% | $22 |
| **Total** | **$33,715.78** | **15%** | **$26** |

*Values are taken from the dashboard's displayed channel summary.*

**Key Insights:**
- Rep Visits delivered the highest displayed prescription lift at 31%, making them an important channel for direct HCP engagement.
- Email had the lowest displayed cost per incremental NRx at $8.
- Search recorded a 16% prescription lift at $12 per incremental NRx.
- Display recorded a 9% prescription lift and a $28 cost per incremental NRx.
- The analysis highlights opportunities to review passive display advertising and strengthen high-impact field engagement.

**Business Recommendations:**
- **Scale:** Strengthen Rep Visits and prioritize high-value HCP segments where field engagement generates meaningful prescription impact.
- **Optimize:** Use Email and Search as cost-efficient supporting channels for HCP education and pre-visit engagement.
- **Review:** Reassess Display campaign expenditure and investigate whether its prescription outcomes justify its costs.
- **Measure:** Monitor cost per incremental NRx alongside engagement to avoid optimizing campaigns solely for clicks or interactions.

**Business Value:** Supports evidence-based marketing budget allocation and helps teams balance HCP engagement, prescription outcomes, and campaign costs.

## 🛠️ Tools & Skills Demonstrated

### Tools
- **Power BI Desktop** – Interactive dashboards, KPI cards, visual analytics, and report design.

### Analytical Skills
- Pharmaceutical marketing campaign analysis
- HCP segmentation and performance analysis
- Marketing expenditure and ROI analysis
- Channel performance comparison
- Prescription lift analysis
- Cost-efficiency analysis
- Budget allocation and optimization
- Business insight generation and data storytelling

### Dashboard Features
- Executive KPI cards
- Campaign performance tables
- HCP segment comparisons
- Channel-level performance analysis
- Quarterly trend analysis
- Specialty and target-segment analysis
- Interactive filters for year, specialty, channel, geography, and target segment

## 📈 Key Business Outcomes

This project demonstrates how a Power BI dashboard can support pharmaceutical marketing decisions by connecting campaign expenditure with engagement and prescription outcomes.

The analysis highlights several potential opportunities:

1. **Prioritize high-impact HCPs:** Tier 1 accounts for approximately 61% of prescription lift in the executive overview.
2. **Improve channel efficiency:** Compare cost per incremental NRx across marketing channels rather than relying on engagement alone.
3. **Strengthen field engagement:** Rep Visits show the highest engagement rate in the dashboard.
4. **Improve budget allocation:** Investigate channels with relatively high acquisition costs and lower prescription lift.
5. **Support targeted marketing:** Use HCP segment and specialty analysis to inform campaign planning.

## 📂 Repository Structure

```text
PharmaForceIQ-HCP-Campaign-Analytics/
│
├── Data/
│   └── campaign_data.csv
│
├── PowerBI_Files/
│   └── PharmaForceIQ_Dashboard.pbix
│
├── Assets/
│   ├── Executive_Overview.png
│   ├── Campaign_Performance.png
│   ├── HCP_Segment_Analytics.png
│   └── Budget_Optimization.png
│
└── README.md
```

*This is a suggested repository structure. Replace the example filenames with the actual files included in your GitHub repository.*

## 🚀 How to Explore the Project

1. Clone or download this repository.
2. Open `PharmaForceIQ_Dashboard.pbix` using Power BI Desktop.
3. Explore the four dashboard pages.
4. Use the available filters to analyze performance by year, channel, specialty, geography, and target segment.
5. Compare campaign expenditure, engagement, and prescription outcomes to explore potential optimization opportunities.

## 💡 Conclusion

PharmaForceIQ demonstrates how business intelligence can help pharmaceutical marketing teams evaluate campaign effectiveness, understand HCP behavior, and identify opportunities to improve marketing efficiency.

By combining executive reporting, campaign analysis, HCP segmentation, and budget optimization in one Power BI solution, the project illustrates how data-driven insights can support more informed marketing decisions.

## ⚠️ Data Disclaimer

This is a portfolio analytics project. The figures and insights presented in the dashboard describe the dataset used for the project and should not be interpreted as independently verified results from a real pharmaceutical company or actual clinical evidence. Incremental NRx and prescription lift are presented as marketing performance metrics within the project dataset.

---

**#PowerBI #PharmaAnalytics #HealthcareAnalytics #MarketingAnalytics #CampaignPerformance #HCPAnalytics #ROIAnalysis #BusinessIntelligence #DataAnalytics**
