# Global-Forest-Dynamics-A-20-Year-Comparative-Analysis-2000-2020-

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/ea9ea0b0-a70c-407f-ac25-f6808e5920f2" />

SDG 15 promotes the protection and sustainable use of forests and terrestrial ecosystems. Forests support biodiversity, livelihoods and climate regulation. However, global forest area declined by 2.4% between 2000 and 2020, highlighting the need for conservation, restoration and sustainable forest management.

## Project Overview

This project analyzes changes in global forest cover between *2000 and 2020* across *227 countries and territories*.

The analysis focuses on changes in forest share as a percentage of total land area and supports the assessment of global progress toward *Sustainable Development Goal (SDG) 15: Life on Land*.

The project identifies countries experiencing forest gain, forest loss, or stability; highlights major forest-loss hotspots; compares global averages over time; and examines whether a country's starting forest density is associated with its long-term forest trend.

---

## Project Objectives

The main objectives of this analysis are to:

* Compare forest coverage between 2000 and 2020.
* Identify countries with the greatest increases and decreases in forest share.
* Examine the overall global direction of forest cover.
* Classify countries according to whether they gained, lost, or maintained forest cover.
* Identify major forest-loss hotspots.
* Examine how initial forest density relates to subsequent forest-cover trends.
* Present findings through charts, summary statistics, and an interactive dashboard.

---

## Business Questions

The project addresses five main questions:

1. *What is the 20-year trajectory of forest cover for the top five most forested nations?*

2. *How has the average global forest cover changed from 2000 to 2020?*

3. *Which ten countries represent the highest absolute forest-loss hotspots?*

4. *What is the global distribution of forest status: Gained, Loss, or Stable?*

5. *How do 20-year forest-cover trends differ among countries with low, medium, and high starting forest density?*

---

## Dataset Description

The main dataset contains *227 country and territory records*.

### Main Variables

| Variable          | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| iso3c           | Three-character country or territory code                         |
| forests_2000    | Forest share as a percentage of land area in 2000                 |
| forests_2020    | Forest share as a percentage of land area in 2020                 |
| trend           | Percentage change in forest share between 2000 and 2020           |
| Absolute Change | Percentage-point difference between forest share in 2020 and 2000 |
| Status          | Classification of the country as Gained, Loss, or Stable          |

### Absolute Change

Absolute forest-cover change is calculated as:

*Absolute Change = Forest Share 2020 − Forest Share 2000*

A positive result represents an increase in forest share, while a negative result represents a decrease.

### Status Classification

Countries are classified as:

* *Gained* – forest share increased.
* *Loss* – forest share decreased.
* *Stable* – no change was recorded.

### Forest Density Classification

For the density analysis, countries are grouped using their forest share in 2000:

* *Low Density:* below 33%
* *Medium Density:* 33% to 67%
* *High Density:* above 67%

---

## Analysis Methodology

The analysis was completed using Microsoft Excel with calculated fields, tables, PivotTables, charts, and dashboard visualizations.

The main analytical steps included:

1. Cleaning and organizing the forest-share dataset.
2. Comparing forest share in 2000 and 2020.
3. Calculating absolute changes.
4. Classifying countries by forest status.
5. Restructuring the data for year-by-year comparison.
6. Calculating average global forest coverage.
7. Ranking countries according to absolute forest loss.
8. Counting countries according to forest status.
9. Grouping countries into low, medium, and high starting forest-density categories.
10. Creating PivotTables and charts for the five business questions.
11. Developing an executive dashboard to summarize the findings.

---

## Key Findings

### 1. Top Five Most Forested Countries

The five countries or territories with the highest forest shares at the beginning of the study were:

| Country/Territory       |  2000 |  2020 |
| ----------------------- | ----: | ----: |
| Suriname (SUR)          | 98.3% | 97.4% |
| French Guiana (GUF)     | 97.7% | 96.6% |
| Guyana (GUY)            | 94.3% | 93.6% |
| Equatorial Guinea (GNQ) | 93.2% | 87.3% |
| Gabon (GAB)             | 92.0% | 91.3% |

All five remained highly forested, but each recorded a decline over the twenty-year period. Equatorial Guinea recorded the largest decrease within this group.

---

### 2. Global Average Forest Cover

The average forest share across the countries and territories analyzed decreased from approximately:

* *33.68% in 2000*
* *32.98% in 2020*

This represents an average decline of approximately *0.70 percentage points* over the twenty-year period.

---

### 3. Major Forest-Loss Hotspots

The ten largest absolute reductions in forest share identified in the analysis were:

| Rank | Country/Territory              | Absolute Change |
| ---- | ------------------------------ | --------------: |
| 1    | Paraguay (PRY)                 |           -17.4 |
| 2    | Nicaragua (NIC)                |           -16.6 |
| 3    | Northern Mariana Islands (MNP) |           -16.5 |
| 4    | Cambodia (KHM)                 |           -15.4 |
| 5    | Gambia (GMB)                   |           -11.3 |
| 6    | Myanmar (MMR)                  |            -9.7 |
| 7    | Tanzania (TZA)                 |            -9.0 |
| 8    | Malawi (MWI)                   |            -8.9 |
| 9    | Benin (BEN)                    |            -8.9 |
| 10   | Angola (AGO)                   |            -8.9 |

These locations represent important areas for further investigation into the environmental and economic factors driving forest loss.

---

### 4. Distribution of Forest Status

Of the *227 countries and territories* analyzed:

* *95* recorded a forest loss.
* *87* recorded a forest gain.
* *45* remained stable.

This shows that the global picture is mixed, although more countries experienced forest loss than forest gain.

---

### 5. Forest Density and Long-Term Trend

The average 20-year trends differed according to the level of forest coverage countries had in 2000:

| Starting Density | Average Trend |
| ---------------- | ------------: |
| Low              |        +2.46% |
| Medium           |        -2.27% |
| High             |        -2.67% |

Countries with relatively low initial forest density recorded a positive average trend, while medium- and high-density countries recorded negative average trends.

The results suggest that countries with already-established and extensive forest resources may face greater pressure in maintaining those forests, while some lower-density countries have experienced forest expansion.

---

## Workbook Structure

The Excel workbook contains the following sheets:

### goal15.forest_shares

Contains the main dataset used for the project, including:

* Country codes
* Forest share in 2000
* Forest share in 2020
* Percentage trend
* Absolute change
* Forest status

### Business Question

Contains the five analytical questions guiding the project.

### Analysis

Contains the detailed analytical work, supporting datasets, PivotTables, calculations, and charts used to answer the five business questions.

### Interpretation of Analysis

Provides written interpretations of the results obtained from each analytical question.

### Executive Summary

Summarizes the project background, methodology, key findings, conclusions, and recommendations.

### Dashboard

Provides a visual summary of the analysis using key performance indicators, charts, and interactive filtering elements.

---

## Dashboard

The dashboard provides a high-level overview of global forest dynamics between 2000 and 2020.

It includes headline indicators such as:

* Number of countries and territories analyzed
* Average forest share in 2000
* Average forest share in 2020
* Forest-change indicators
* Visual summaries of the major analytical findings

The dashboard also includes slicers for interactive filtering.

> *Compatibility Note:* Some versions of WPS Office may not fully support the Excel slicers used in the dashboard. Microsoft Excel is recommended for the complete interactive dashboard experience.

---

## Conclusion

The analysis shows that global forest-cover change between 2000 and 2020 is not uniform.

Although a substantial number of countries increased their forest coverage, the average global forest share in the dataset declined. Some of the world's most heavily forested countries also experienced reductions in forest coverage.

The concentration of significant losses in countries such as Paraguay, Nicaragua, Cambodia, Myanmar, and Tanzania highlights the importance of targeted forest-protection interventions.

The density analysis also indicates that countries with high existing forest coverage experienced greater average declines than countries with low initial forest coverage. This emphasizes the importance of protecting established forest ecosystems while continuing reforestation and afforestation efforts.

---

## Recommendations

Based on the findings, the project recommends:

1. Investigating countries that recorded significant forest gains to identify successful conservation and reforestation strategies.

2. Prioritizing forest-protection initiatives in countries with the largest absolute forest losses.

3. Investigating stable countries to understand the policies and conditions that have allowed them to maintain forest coverage.

4. Encouraging organizations sourcing timber, agricultural commodities, minerals, and other natural resources from high-loss regions to conduct sustainability assessments.

5. Supporting long-term forest restoration and conservation initiatives, particularly in areas where established forests are under increasing pressure.

---

## Tools Used

* Microsoft Excel
* Excel Tables
* Formulas and calculated columns
* PivotTables
* PivotCharts and other Excel charts
* Data categorization
* Dashboard design
* Slicers and interactive filters

---

## Project Scope

*Period:* 2000–2020
*Observations:* 227 countries and territories
*Topic:* Global Forest Cover and Forest Dynamics
*SDG Area:* SDG 15 – Life on Land
*Analysis Type:* Descriptive and comparative data analysis

---

## Data Source

The workbook contains the forest-share dataset used for the analysis; however, the original external data-source citation is not specified within the workbook. The original source should be added here before formal publication or submission if available.

Ready to connect with great minds passionate about creating a greener future. Let’s share ideas, collaborate, and join the fight against deforestation. Together, our contributions can make a difference kobbykay2000@gmai.com(mailto:kobbykay2000@gmail.com) 

