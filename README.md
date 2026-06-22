# Harsh Singh — Data Analyst Internship Portfolio

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Data%20Analytics-Internship%20Portfolio-7C3AED?style=for-the-badge&logo=python&logoColor=white)
![Weeks](https://img.shields.io/badge/Duration-5%20Weeks-06B6D4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-10B981?style=for-the-badge)
![Org](https://img.shields.io/badge/ApexPlanet-Software%20Pvt.%20Ltd.-F59E0B?style=for-the-badge)

**A complete, end-to-end Data Analytics Internship — from raw data to professional portfolio.**

[🌐 View Portfolio Website](https://harshsinghps57-spec.github.io/harshsinghps57-DataAnalyst-Internship-Portfolio) · [📊 GitHub Profile](https://github.com/harshsinghps57-spec)

</div>

---

## 🎯 Overview

This master repository is the **capstone deliverable** for my 5-week Data Analytics Internship at **ApexPlanet Software Pvt. Ltd.** It consolidates all four weekly projects into a single professional portfolio, showcasing a complete data analytics lifecycle:

```
Raw Data → Cleaning → EDA → SQL → Advanced Analytics → Statistical Testing → Storytelling → Portfolio
```

**Dataset used throughout:** Sample - Superstore (9,994 orders, 2014–2017)

---

## 📁 Repository Structure

```
harshsinghps57-DataAnalyst-Internship-Portfolio/
│
├── index.html                  # GitHub Pages portfolio website
├── README.md                   # This file
│
├── presentation/
│   └── capstone_presentation.html   # Final presentation deck
│
└── docs/
    ├── linkedin_post.md             # LinkedIn post draft
    ├── skills_summary.md            # Technical skills summary
    └── internship_reflection.md     # Professional reflection
```

---

## 📚 Weekly Projects

### Week 1 — Data Immersion & Wrangling
[![Repo](https://img.shields.io/badge/GitHub-Data--Immersion--Wrangling-7C3AED?style=flat-square&logo=github)](https://github.com/harshsinghps57-spec/Data-Immersion-Wrangling)

**Objective:** Load, explore, clean and prepare the Superstore dataset for analysis.

| Task | Details |
|------|---------|
| Dataset | 9,994 rows × 21 columns |
| Missing Values | Handled nulls in Postal Code, fixed date formats |
| Duplicates | Removed duplicate Order IDs |
| Feature Engineering | Profit Margin (%), Order-to-Ship Days |
| Output | `cleaned_superstore.csv` — analysis-ready dataset |

**Key Tools:** `Python`, `Pandas`, `NumPy`

---

### Week 2 — Exploratory Data Analysis & Business Intelligence
[![Repo](https://img.shields.io/badge/GitHub-EDA--Business--Intelligence-06B6D4?style=flat-square&logo=github)](https://github.com/harshsinghps57-spec/Exploratory-Data-Analysis-and-Business-Intelligence)

**Objective:** Uncover patterns, relationships and business insights through systematic EDA and SQL.

| Analysis | Finding |
|----------|---------|
| Top Category | Technology — highest profit margin (~18%) |
| Loss Leader | Furniture Tables — consistently negative profit |
| Regional Winner | West region — highest total sales & profit |
| Discount Impact | Sales spike but profit collapses above 30% discount |
| SQL Queries | 6 business questions answered with SQLite |

**Key Tools:** `Pandas`, `Seaborn`, `Matplotlib`, `SQLite`, `HTML/CSS`

---

### Week 3 — Deep Dive Analysis & Interactive Dashboard
[![Repo](https://img.shields.io/badge/GitHub-Deep--Dive--Dashboard-10B981?style=flat-square&logo=github)](https://github.com/harshsinghps57-spec/Deep-Dive-Analysis-Interactive-Dashboard)

**Objective:** Advanced analytics with customer segmentation, cohort analysis and interactive dashboard.

| Analysis | Output |
|----------|--------|
| RFM Segmentation | Champions, Loyal, At-Risk, Lost customers identified |
| Cohort Analysis | Retention heatmap showing YoY customer behaviour |
| Time Series | Seasonal decomposition — Q4 peak, Q1 trough pattern |
| Dashboard | Multi-page interactive HTML with JS live filters |

**Key Tools:** `Pandas`, `Matplotlib`, `Seaborn`, `HTML`, `CSS`, `JavaScript`

---

### Week 4 — Data Storytelling & Statistical Validation
[![Repo](https://img.shields.io/badge/GitHub-Storytelling--Statistical--Validation-F59E0B?style=flat-square&logo=github)](https://github.com/harshsinghps57-spec/Data-Storytelling-and-Statistical-Validation)

**Objective:** Validate findings with hypothesis tests and craft compelling data narratives.

| Test | Variables | Result |
|------|-----------|--------|
| Shapiro-Wilk | Profit distribution | Reject H₀ — NOT normal (p < 0.001) |
| T-Test | Consumer vs Corporate margin | Fail to Reject H₀ (p = 0.40) |
| ANOVA | Sales across Regions | Fail to Reject H₀ (p = 0.49) |
| Chi-Square | Ship Mode vs Region | Reject H₀ — Dependent (p = 0.005) |
| Pearson r | Discount vs Profit | r = −0.22 (negative correlation) |

**Key Tools:** `SciPy`, `Matplotlib`, `Seaborn`, `HTML/CSS/JavaScript`

---

## 🛠️ Technical Skills Demonstrated

### Programming & Libraries
- **Python 3** — Core language for all analysis
- **Pandas** — Data manipulation, groupby, pivot tables, merging
- **NumPy** — Numerical computation and array operations
- **SciPy** — Statistical hypothesis testing
- **Matplotlib / Seaborn** — Publication-quality data visualizations

### Data Analytics
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Segmentation (RFM Analysis)
- Cohort & Retention Analysis
- Time-Series Decomposition
- Hypothesis Testing (4 test types)
- Correlation Analysis

### Database & SQL
- SQLite database design and querying
- 6+ business SQL queries
- Aggregation, filtering, joins, subqueries

### Visualization & Presentation
- Interactive HTML/CSS/JavaScript dashboards
- Dark-mode premium chart aesthetics
- Data storytelling with narrative structure
- GitHub Pages portfolio hosting

### Professional
- GitHub version control & repository management
- Markdown documentation
- Data-driven business recommendations
- Professional report writing

---

## 📊 Key Insights Discovered

> **The Discount Trap** — Products with discounts above 40% almost universally generate losses. Pearson correlation: r = −0.22 between Discount and Profit (p < 0.001).

> **Technology Dominates** — Technology category generates ~50% of total profit despite being only ~36% of revenue. Copiers and Phones are the top sub-categories.

> **Furniture is a Loss Center** — Tables and Bookcases consistently lose money. A pricing and supplier audit is recommended.

> **Shipping Mode is Region-Dependent** — Chi-square test confirms ship mode and region are not independent (χ² = 23.85, p = 0.005).

> **Profit Distribution is Not Normal** — Shapiro-Wilk (W = 0.25, p < 0.001) confirms heavy skew, meaning non-parametric methods are more appropriate for profit analysis.

---

## 🚀 How to Explore

1. **Portfolio Website:** Open `index.html` or visit the [GitHub Pages site](https://harshsinghps57-spec.github.io/harshsinghps57-DataAnalyst-Internship-Portfolio)
2. **Final Presentation:** Open `presentation/capstone_presentation.html`
3. **Individual Projects:** Click any repository badge above
4. **LinkedIn Post:** Read `docs/linkedin_post.md`

---

## 🏢 About the Internship

| Detail | Info |
|--------|------|
| **Organisation** | ApexPlanet Software Pvt. Ltd. |
| **Duration** | 5 Weeks |
| **Role** | Data Analytics Intern |
| **Dataset** | Sample - Superstore (Tableau Public) |
| **Total Records Analysed** | 9,994 orders |

---

<div align="center">

Made with dedication during a 5-week Data Analytics Internship · 2026

**[GitHub Profile](https://github.com/harshsinghps57-spec)**

</div>
