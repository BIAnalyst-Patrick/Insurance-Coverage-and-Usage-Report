# Insurance Coverage and Hospital Visit Frequency Analysis

**Industry**: Public Health / Health Insurance
**Tools**: Power BI, Excel

---

## 🚀 Executive Summary

**Problem**: Stakeholders needed to understand not just who has health insurance, but whether coverage actually translates into more frequent healthcare utilization — and which socioeconomic groups are being left behind on both fronts.
**Action**: Analyzed 6,158 individual records covering demographics, socioeconomic status, insurance coverage, and hospital visit frequency, building a Power BI dashboard to compare healthcare usage between insured and uninsured populations.
**Result**: Found that **59% of the population is insured** but coverage is sharply unequal by income (**90% for high earners vs. 35% for low-income groups**), and that insured individuals visit hospitals more frequently (every **6 months** vs. **7 months** for the uninsured) — evidence that coverage gaps translate directly into reduced healthcare access.

![Dashboard](https://github.com/user-attachments/assets/7acfde87-319a-400d-93af-cc0f49222b7f)

---

## 🎯 Problem Statement

**Core Issue**: Insurance coverage gaps are known to exist, but it was unclear how large the socioeconomic disparity in coverage is, and whether being uninsured measurably changes healthcare-seeking behavior.
**Key Questions**:
1. What share of the population is insured, and how does this vary by income and employment?
2. Do insured individuals use healthcare services more often than the uninsured?
3. Which socioeconomic groups are most underserved by current coverage levels?

---

## 📈 Objectives & Key Metrics

| Objective | Metric Tracked | Result Achieved |
|---|---|---|
| Quantify insurance coverage | % insured vs. uninsured | **59% insured, 41% uninsured** |
| Identify socioeconomic drivers of coverage | Coverage rate by income tier | **90% of high-income earners insured vs. 35% of low-income earners** |
| Assess impact of insurance on healthcare usage | Avg. hospital visit interval | Insured: **6 months** between visits; Uninsured: **7 months** |

---

## 📂 Data Overview

**Data Sources**: 6,158 individual-level records (`Healthcare_original_dataset.xlsx`, processed into `updated_dataset.csv`).
**Key Variables**: Age, gender, marital status, employment status, income level, insurance coverage status, hospital visit frequency.
**Data Challenges**: Income and hospital-visit fields are self-reported and may understate true variation; the dataset captures a single time period and does not reflect ongoing policy or access changes.

![Data Relationships](https://github.com/user-attachments/assets/93cdf492-e3a5-4f0f-8394-81b3ae04c10a)

---

## 🔧 Methodology

**Data Cleaning**: Standardized demographic and income categories, validated insurance and visit-frequency fields for consistency before dashboard construction.
**Analysis Techniques**:
1. Calculated insurance coverage rates segmented by employment status and income tier.
2. Compared average hospital visit intervals between insured and uninsured populations.
3. Cross-tabulated coverage against demographic variables to surface disparity patterns.
**Tools**: **Power BI** for the interactive dashboard, **Excel** for data cleaning and validation.

---

## 💡 Key Insights

#### Insight 1: Coverage Gaps Track Closely With Employment and Income
**What**: 59% of the population is insured overall, but coverage diverges sharply by employment and income status.
**So What**: Vulnerable groups — the unemployed and low-income — show consistently lower coverage, marking a clear accessibility gap rather than a uniformly distributed shortfall.
![Insurance Coverage by Demographics](https://github.com/user-attachments/assets/62d50c84-8653-4110-9de5-f0e18b53b698)

---

#### Insight 2: Income Is the Strongest Predictor of Coverage
**What**: High-income earners are insured at a **90%** rate, compared to just **35%** for low-income earners — a 55-point gap.
**So What**: Subsidized health insurance programs targeted at low-income groups would directly address the single largest driver of the coverage gap.
![Coverage by Employment and Income](https://github.com/user-attachments/assets/b5805630-4233-447c-b015-c6cefba859a4)
![Coverage by Income Tier](https://github.com/user-attachments/assets/8839970f-3c32-444e-99d0-4681e9048201)

---

#### Insight 3: Insurance Status Measurably Changes Healthcare-Seeking Behavior
**What**: Insured individuals visit hospitals roughly every **6 months**, versus **7 months** for the uninsured.
**So What**: Coverage isn't just a financial-protection metric — it has a direct, measurable effect on how often people actually seek care, reinforcing that closing the coverage gap would close the utilization gap as well.
![Hospital Visit Frequency by Insurance Status](https://github.com/user-attachments/assets/aed85190-8586-4b49-abe9-53e3cde3f506)

---

## ✅ Recommendations & Business Impact

| Priority | Recommendation | Expected Impact | Owner |
|---|---|---|---|
| High | Develop subsidized health insurance programs targeted at low-income and unemployed groups | Directly addresses the 55-point income-based coverage gap (90% vs. 35%) | Policy Team |
| High | Promote employer-sponsored insurance enrollment | Increases coverage among the employed population still lacking insurance | Employer Partnerships |
| Medium | Expand community-driven health programs for uninsured individuals | Provides a care pathway for those unlikely to gain coverage near-term | Community Health Orgs |
| Medium | Launch public awareness campaigns on insurance benefits in underserved regions | Improves enrollment among eligible but currently uninsured individuals | Public Health Outreach |

**Business Impact**:
- Narrowing the income-based coverage gap would be expected to shift the uninsured population's hospital visit cadence from ~7 months toward the ~6-month insured benchmark, indicating meaningfully improved care-seeking behavior.

---

## 📉 Caveats & Next Steps

**Limitations**:
- **Data Limitations**: The dataset may not represent the entire population, which could skew coverage and utilization estimates.
- **Self-Reported Bias**: Income and hospital-visit variables are self-reported and may contain inaccuracies.
- **Temporal Context**: Findings reflect a single period and may not capture ongoing policy or behavioral trends.
- **Unmeasured Variables**: Regional healthcare policy and cultural differences are not captured in this dataset.

**Next Steps**:
1. Pilot a subsidized-insurance program for low-income groups and track resulting coverage and visit-frequency changes.
2. Partner with employers to measure enrollment lift from targeted outreach.
3. Refresh the analysis periodically to monitor whether the income-based coverage gap is narrowing.

---

## 👤 Author

**Analyst:** Patrick Mwangi Gichuki
**Portfolio:** [https://gichuki.site](https://gichuki.site)
**LinkedIn:** [https://www.linkedin.com/in/patrick-gichuki-the-bi-analyst](https://www.linkedin.com/in/patrick-gichuki-the-bi-analyst)
