# 🏏 IPL Toss Decision Analysis
### Venue-Wise Batting First vs Chasing Performance | Sports Analytics

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Excel](https://img.shields.io/badge/Excel-Reporting-green)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Project](https://img.shields.io/badge/Project-Sports%20Analytics-orange)

## 📌 Project Overview

The IPL Toss Decision Analysis project uses historical Indian Premier League match data to identify venue-wise patterns in batting-first and chasing performances.

The main objective is to help cricket captains make informed toss decisions by analyzing whether teams have historically performed better batting first or chasing at different IPL venues.

## 🎯 Business Problem

Winning the toss can influence a team's match strategy. However, deciding whether to bat or bowl first requires an understanding of venue conditions and historical match outcomes.

This project addresses the following questions:

- Which venues favor batting first?
- Which venues favor chasing?
- What is the average first-innings score at each venue?
- What toss decision does historical venue performance suggest?

## 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data cleaning and analysis |
| Pandas | Data manipulation |
| Excel | Data analysis and reporting |
| Power BI | Interactive dashboard and visualization |

## 📂 Dataset

**Source:** [Cricsheet – IPL Match Data](https://cricsheet.org/)

The analysis uses 1,234 IPL match records.

Key fields include:
- Match ID and date
- Venue
- Batting-first and batting-second teams
- First-innings score
- Match winner
- Batting-first win indicator
- Chasing win indicator

## ⚙️ Project Workflow

1. Data collection from Cricsheet.
2. Data cleaning and preparation using Python.
3. Venue name standardization.
4. Calculation of batting-first and chasing wins.
5. Calculation of venue-wise win percentages.
6. Calculation of average first-innings scores.
7. Development of toss recommendations.
8. Creation of Excel analysis and Power BI dashboard.

## 📊 Key Findings

| Venue | Matches | Bat First Win % | Chasing Win % | Toss Recommendation |
|---|---:|---:|---:|---|
| Sawai Mansingh Stadium, Jaipur | 68 | 35.29% | 64.71% | Bowl First |
| MA Chidambaram Stadium, Chennai | 98 | 54.08% | 45.92% | Bat First |
| Wankhede Stadium, Mumbai | 132 | 45.45% | 54.55% | Bowl First |

![Uploading Power BI dashboard screenshot.png…]()


### Business Insights

- Sawai Mansingh Stadium shows a historical chasing advantage.
- MA Chidambaram Stadium shows a historical batting-first advantage.
- Wankhede Stadium shows a modest historical chasing advantage.
- Historical venue trends can support toss decisions, but match-day conditions remain important.

## 📈 Project Deliverables

- Python analysis notebook
- Cleaned IPL match-level dataset
- Venue-level analysis dataset
- Excel analysis workbook
- Interactive Power BI dashboard
- Captain's decision brief

## 📁 Repository Structure

```text
IPL-Toss-Decision-Analysis/
│
├── IPL_Toss_Analysis.ipynb
├── README.md
├── Data/
│   ├── IPL_Match_Level_Data.csv
│   └── IPL_Venue_Analysis.csv
├── Excel/
├── PowerBI/
├── Report/
└── Screenshots/
```

## 💡 Business Recommendation

Captains can use historical venue performance as an initial reference when choosing to bat or bowl first.

The final decision should also consider:

- Pitch condition and surface behavior
- Weather and dew conditions
- Team batting and bowling strengths
- Playing XI and match strategy

## ⚠️ Limitations

- Historical performance does not guarantee future match results.
- Day/night analysis was excluded because reliable match-timing data was unavailable.
- Sample reliability categories are based on match counts and are not statistical confidence intervals.
- Match-day conditions may influence the final toss decision.

## 🏁 Conclusion

This project demonstrates how Python, Excel, and Power BI can transform historical cricket data into actionable insights for sports-related decision-making.

**Project Category:** Sports Analytics | Data Analytics | Business Intelligence

**Dataset Source:** [Cricsheet](https://cricsheet.org/)
