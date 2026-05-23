# Databel Telecom — Customer Churn Analysis

![Databel Churn Dashboard](dashboard-screenshot.png)

**Tool:** Tableau Public  
**Dataset:** 6,687 customers · 29 variables  
**Live Dashboard:** [Click to view interactive dashboard](https://public.tableau.com/app/profile/habeeb.odoffin/viz/ChurnAnalysis_17747175850900/Dashboard1)

---

## Business Problem

Databel Telecom was experiencing a 26.9% customer churn rate, placing it at the upper boundary of the telecom industry benchmark of 18–25% annually. With 1,796 customers lost and $793,128 in annual recurring revenue at risk, leadership needed to understand not just that customers were leaving, but which segments were most at risk, what was driving their departure, and where to prioritise retention investment for maximum financial impact. This analysis examines 6,687 customers across 29 variables to answer those questions.

---

## Data & Approach

The dataset contains 6,687 customer records with 29 variables covering contract type, demographics, usage behaviour, payment method, and verbatim churn reasons. In Tableau I built four calculated fields — Churn Rate, Churned Customers, Revenue at Risk (Monthly and Annual), and Age Group bins to power the analysis. The approach combined churn segmentation, revenue impact quantification, geographic analysis, and sample-size-adjusted state prioritisation to produce actionable findings.

---

## Key Findings

- **Contract type is the strongest churn predictor.** Month-to-Month customers churn at 46.3% — 16× higher than Two-Year contracts at 2.8%. With 51% of all customers on M2M, this is the highest-leverage retention opportunity available.
- **Competitor positioning drives 44.8% of all exits.** "Better offer" and "better devices" alone account for 600 exits. This is a product and pricing problem — not a service quality problem. Budget directed at call centre training will not address it.
- **Customers aged 60+ churn at 34.4%** — 7.5 percentage points above the company average of 26.9%. Standard digital retention campaigns typically underperform with this demographic.
- **OH, WV, and OR are the true priority states** — not CA, which shows 63% rate but only 68 customers. Volume-adjusted analysis shows these three states combine elevated churn rates with large customer bases, making them statistically reliable and financially material targets.

---

## Business Recommendations

1. **Launch a contract migration campaign** targeting the 3,411 Month-to-Month customers with incentives to upgrade to One-Year contracts. A 10% conversion rate protects an estimated ~$150K in annual recurring revenue.
2. **Commission competitive benchmarking** against the top 3 rivals in OH, WV, and OR. The product and pricing teams must own this — the exit reasons are specific and actionable.
3. **Build a dedicated 60+ retention programme** combining simplified plans, phone-led outreach, and a loyalty tier for long-tenure customers. Target: 616 at-risk customers in this segment.

---

## Skills Demonstrated

- **Tableau Public** — calculated fields, dashboard filter actions, geographic map analysis, reference lines, bento-grid layout
- **Data preparation** — null value filtering, continuous variable binning (Age Group), churn rate formula construction
- **Business analysis** — revenue impact quantification, segment prioritisation, sample-size-adjusted geographic analysis
- **Communication** — insight-led chart titles, executive KPI design, F-pattern dashboard layout, PowerPoint presentation design

---

## Files in This Repository

| File | Description |
|------|-------------|
| `README.md` | This case study |
| `dashboard-screenshot.png` | Dashboard preview image |
| `Databel - Data.csv` | Raw dataset (6,687 rows) |
| `Churn Rate Slide Deck.pptx` | Executive presentation deck |

---

*Analysis by Habeeb Odoffin · April 2026*  
*[LinkedIn](https://www.linkedin.com/in/adewaleodoffin/) · habeebodoffin@gmail.com*
