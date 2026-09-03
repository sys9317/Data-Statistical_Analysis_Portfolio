# Yosup Shin - Statistic/Data Analyst Portfolio

## About

My name is Yosup. I hold a Master of International Development Policy from Georgetown University (McCourt School of Public Policy), specializing in Impact Evaluation and Quantitative Analysis.

My passion lies in bridging the gap between **raw data** and **actionable policy insights**. I have hands-on experience in managing large-scale **RCTs (Kenya)**, validating firm-level data at the **World Bank**, and applying econometric models to solve development challenges.

In my free time, I enjoy exploring new data analysis tools and techniques, and I am always looking for opportunities to expand my knowledge and skills. Whether working on a team or independently, I am driven by the thrill of discovering new insights and the satisfaction of using data to solve complex problems.

You may see my CV in [pdf](https://github.com/sys9317/Data-Statistical_Analysis_Portfolio/blob/main/Resume_Yosup.pdf)

This is a repository to show my previous works, quantitative analysis, and track my progress in International Development journey.

## Table of Contents

- [About](#about)
- [Projects](#projects)
  - [R](#r)
  - [Stata](#stata)
- [Education](#education)
- [Contact](#contact)

---

## Projects

### R

**[The U.S. Gender Pay Gap: How Much Survives Controls?](https://github.com/sys9317/pay-equity-wage-gap)**

Wage regression and Oaxaca-Blinder decomposition of the U.S. gender pay gap on 2022 American Community Survey microdata. Estimates how much of the raw gap is accounted for by measurable worker and job characteristics and how much is left unexplained, with an explicit treatment of what the residual can and cannot show.

| | |
|---|---|
| **Tools** | R, tidyverse, tidycensus (`get_pums`), sandwich / lmtest (robust SEs), Quarto |
| **Data** | 2022 ACS 1-year PUMS (civilian workers age 25-54, full-time / full-year) |
| **Topics** | Labor economics, wage decomposition, weighted least squares, limits of causal inference |

[Rendered report](https://sys9317.github.io/pay-equity-wage-gap/)

---

**[DC Region Capital Flows: Poverty & Investment Patterns](https://github.com/sys9317/dc-capital-flows-analysis)**

Exploratory analysis of capital investment across DC-region counties, examining the relationship between county population, poverty rates, and aggregate investment by racial demographic category.

| | |
|---|---|
| **Tools** | R, tidyverse, ggplot2, tigris, sf |
| **Data** | Urban Data Catalog (2023) |
| **Topics** | Spatial analysis, demographic equity, capital distribution |

[Rendered report](https://sys9317.github.io/dc-capital-flows-analysis/)

---

#### **[Chicago Homicide Geography: A Spatial Analysis](https://github.com/sys9317/chicago-homicide-analysis)**

Geospatial analysis of homicide patterns across Chicago neighborhoods, examining arrest rate disparities and socioeconomic correlates using census tract-level data. Combines crime records with Census API data to surface policy-relevant insights.

| | |
|---|---|
| **Tools** | R, sf, tidycensus, ggplot2, Census API |
| **Data** | Chicago PD Crime Data (8M+ records), ACS 2019 |
| **Topics** | Spatial analysis, public safety, equity in policing, socioeconomic determinants of crime |

[Rendered report](https://sys9317.github.io/chicago-homicide-analysis/)

---

### Stata

#### **[Processing Census Data in Low-Resource Contexts](https://github.com/sys9317/census-data-processing)**

Automated extraction and standardization of government administrative data from non-standard formats. Demonstrates data wrangling techniques essential for development research in contexts where digital infrastructure is still developing.

**Part 1:** Pakistan District Census Data — Automated loop extracts citizenship card data from 135 inconsistently-formatted Excel sheets  
**Part 2:** Tanzania Student Exam Records — Regex-based extraction of school rankings and individual student performance from HTML strings

| | |
|---|---|
| **Tools** | Stata, regex pattern matching, data reshaping |
| **Data** | Pakistan Bureau of Statistics (2017), Tanzania NECTA Exam Results |
| **Topics** | Data wrangling, text processing, automation, quality control |
| **Key Skills** | Loop automation, regex extraction, reshape operations, validation checks |

**Technical highlights:**
- Processes 135 Excel files in a single script
- Extracts structured data from unstructured HTML
- Implements comprehensive data validation

---

## Education

**Georgetown University — McCourt School of Public Policy**
Master of International Development Policy | Awarded May 2026
Specialization: Impact Evaluation & Quantitative Analysis

**Leiden University**
BSc International Relations and Organisations | 2024
Specialization: International Development, Political Economy, Quantitative Analysis

---

## Contact

- GitHub: [sys9317](https://github.com/sys9317)
- LinkedIn: [linkedin.com/in/yosupshin0426](https://linkedin.com/in/yosupshin0426)
- Website: [sys9317.github.io](https://sys9317.github.io)
- Email: shinys9317@gmail.com
