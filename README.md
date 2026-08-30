# Healthcare Financing and Mortality Reduction Dashboard

An interactive Power BI dashboard analyzing the relationship between **healthcare financing, poverty, and mortality indicators** across four countries — Nigeria, Ukraine, the United States, and Yemen — benchmarked against the UN Sustainable Development Goals (SDGs) 2030 targets.

!\[Dashboard Overview](assets/01\_dashboard\_overview.png)

\---

## Table of Contents

* [Objective](#objective)
* [SDGs and Indicators](#sdgs-and-indicators)
* [Data Source](#data-source)
* [Presentation](#presentation)
* [Dashboard Features](#dashboard-features)
* [Key Insights](#key-insights)
* [Glossary of Terms](#glossary-of-terms)
* [Intended Stakeholders](#intended-stakeholders)
* [Policy Recommendations](#policy-recommendations)
* [Conclusion](#conclusion)
* [Tools Used](#tools-used)
* [Repository Structure](#repository-structure)
* [How to Use](#how-to-use)
* [Author](#author)

\---

## Objective

To analyze the relationship between healthcare financing, poverty, and mortality indicators in order to guide policy decisions toward achieving Sustainable Development Goals (SDGs) by 2030.

## SDGs and Indicators

**SDG 1 — End poverty in all its forms everywhere**

|Indicator|Description|
|-|-|
|1.1.1|Proportion of the population living below the international poverty line, by sex, age, employment status and geographic location (urban/rural)|
|1.a.2|Proportion of total government spending on essential services (education, health, and social protection)|

**SDG 3 — Ensure healthy lives and promote well-being for all at all ages**

|Indicator|Description|
|-|-|
|3.1.1|Maternal Mortality Ratio (MMR)|
|3.2.1|Under-5 Mortality Rate (U5MR)|
|3.2.2|Neonatal Mortality Rate (NMR)|

## Data Source

Data was sourced from the **United Nations Global SDG Data Portal**:
https://unstats.un.org/sdgs/dataportal

## Presentation

A fully redesigned, stakeholder-ready deck — `Healthcare\_Dashboard\_Presentation.pptx` — walks through the background, methodology, key findings, and policy recommendations in 17 slides.

|Title|Country Snapshot|Key Finding|
|-|-|-|
|!\[Title slide](assets/06\_deck\_title.jpg)|!\[Country snapshot table](assets/07\_deck\_country\_snapshot.jpg)|!\[Key finding slide](assets/08\_deck\_key\_finding.jpg)|

The deck includes:

* Background on the SDGs and indicators behind the analysis
* Data source, scope, and methodology
* A country-by-country snapshot of mortality indicators vs. SDG 2030 targets
* Four key findings, each paired with supporting visuals and a takeaway
* Policy recommendations and conclusion

## Dashboard Features

The dashboard consists of a single interactive page built in Power BI, with:

* **Country filter** (slicer buttons) — Nigeria, Ukraine, United States, Yemen, or all countries at once
* **Year filter** — view metrics for a specific year or the full time series
* **6 key visuals:**

  1. Avg. Neonatal Mortality vs. SDG Neonatal Target (gauge)
  2. Avg. Under-5 Mortality vs. SDG Under-5 Target (gauge)
  3. Avg. Maternal Mortality vs. SDG Maternal Target (gauge)
  4. Average NMR by Country (bar chart — SDG gap analysis)
  5. Proportion of Govt. Spending on Health vs. Average MMR by Country
  6. NMR trend by Year and Country (line chart)
  7. Proportion Below Poverty Line vs. Average U5M by Country

### Dashboard views

|All countries|Nigeria|
|-|-|
|!\[All Countries](assets/01\_dashboard\_overview.png)|!\[Nigeria](assets/02\_nigeria\_filter.png)|

|Ukraine|United States|
|-|-|
|!\[Ukraine](assets/03\_ukraine\_filter.png)|!\[United States](assets/04\_us\_filter.png)|

|Yemen|
|-|
|!\[Yemen](assets/05\_yemen\_filter.png)|

## Key Insights

* **Nigeria lags on every indicator** and remains off track to meet the 2030 SDG targets across NMR, U5MR, and MMR.
* **Neonatal mortality in Nigeria is declining, but not fast enough** to close the gap with the SDG 2030 target.
* **Nigeria lags behind global peers** in neonatal mortality when benchmarked internationally.
* **Maternal Mortality Ratio falls as government health spending rises** — higher health financing is associated with better maternal outcomes.
* **Poverty strongly drives child mortality** — countries with a higher proportion of the population below the poverty line show markedly higher Under-5 mortality.

## Glossary of Terms

|Term|Definition|
|-|-|
|**Maternal Mortality (MM)**|The death of a woman while pregnant or within 42 days of termination of pregnancy, irrespective of the duration and site of the pregnancy, from any cause related to or aggravated by the pregnancy or its management, but not from accidental or incidental causes *(WHO)*|
|**Maternal Mortality Ratio (MMR)**|The number of women who die from pregnancy-related causes per 100,000 live births *(WHO)*|
|**Neonatal Mortality Rate (NMR)**|Number of deaths within the first 28 completed days of life, per 1,000 live births *(WHO)*|
|**Under-Five Mortality Rate (U5MR)**|The probability a newborn would die before reaching exactly 5 years of age, expressed per 1,000 live births *(UNICEF)*|
|**People Living Below the Poverty Line**|People surviving on less than $3.00 per person per day *(World Bank)*|

## Intended Stakeholders

* Government Decision-Makers
* State Governor
* Commissioner for Health
* Commissioner for Budget \& Planning
* Ministry of Finance officials

## Policy Recommendations

Increased and more efficient healthcare funding, alongside targeted poverty reduction programs, will be critical to achieving the 2030 SDG targets — particularly for NMR, U5MR, and MMR.

## Conclusion

The dashboard shows that Nigeria is currently off track in achieving the SDG targets for neonatal, under-5, and maternal mortality. Although mortality rates are declining, the pace of reduction is insufficient. The analysis also reveals strong relationships between healthcare funding, poverty levels, and mortality outcomes — reinforcing the case for coordinated fiscal and social policy action.

## Tools Used

* **Power BI Desktop** — data modeling, DAX measures, and interactive dashboard design
* **Power Query** — data cleaning and transformation
* **PowerPoint** — stakeholder presentation and project write-up

## Repository Structure

```
healthcare-financing-mortality-dashboard/
│
├── README.md
├── Healthcare\_Dashboard\_Presentation.pptx     # Stakeholder presentation deck (17 slides)
├── data/
│   └── sdg\_data.csv                           # (optional) raw/cleaned dataset used
├── dashboard/
│   └── Healthcare\_Financing\_Dashboard.pbix    # Power BI source file
└── assets/
    ├── 01\_dashboard\_overview.png
    ├── 02\_nigeria\_filter.png
    ├── 03\_ukraine\_filter.png
    ├── 04\_us\_filter.png
    ├── 05\_yemen\_filter.png
    ├── 06\_deck\_title.jpg
    ├── 07\_deck\_country\_snapshot.jpg
    └── 08\_deck\_key\_finding.jpg
```

## How to Use

1. Clone the repository:

```bash
   git clone https://github.com/<your-username>/healthcare-financing-mortality-dashboard.git
   ```

2. Open `dashboard/Healthcare\_Financing\_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft) to explore the live, interactive version.
3. Open `Healthcare\_Dashboard\_Presentation.pptx` for a fully designed, stakeholder-ready walkthrough of the background, methodology, findings, and recommendations.
4. Alternatively, browse the `assets/` folder for a static preview of both the dashboard and the presentation.

## Author

**Abdussamad Yargamji Garba**
Medical Doctor| MSc Data Science Scholar| Nigerian University of Technology and Management

* LinkedIn: *\[https://www.linkedin.com/in/abdoolyargamji/]*
* Email: *\[a.garba@nutm.edu.ng]*

\---

*This project was completed as a data exploration and visualization assignment, using publicly available UN SDG data. It is intended for educational and portfolio purposes.*

