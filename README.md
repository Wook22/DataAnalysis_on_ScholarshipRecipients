# Scholarship Data Analysis Project - README

## Project Overview

This project focuses on analyzing a sample dataset of scholarship recipients for a nonprofit organization, 10,000 Degrees. The goal is to provide actionable insights to organizational leadership about scholarship acceptance, student demographics, application types, high school partnerships, and institution types.

## Dataset

* **File:** `Data_sample_Data_Analyst.xlsx`
* **Number of rows:** 4,357
* **Number of columns:** 14
* **Columns:**

  * `10KD Student ID`
  * `Application Type` (New / Renewal)
  * `High School Region`
  * `Fall award Acceptance` (Accepted / Not Accepted)
  * `Total Offered Award Amount`
  * `High School Graduation Year`
  * `First Generation` (Yes / No / Unknown)
  * `Gender`
  * `Race/Ethnicity`
  * `Field of Study`
  * `Institution Type`
  * `Current Highest Degree` (Dropped due to high missing values)
  * `Preferred Language`
  * `Attended Partner High School` (0/1)

## Project Goals

1. Analyze scholarship acceptance rate and explore trends by gender, race/ethnicity, and field of study.
2. Evaluate the renewal rate for scholarship applications.
3. Examine distribution of scholarship recipients based on high school partnerships.
4. Investigate award amounts by application type and institution type.
5. Prepare a non-technical presentation summarizing key insights for organizational leadership.
6. Demonstrate methods to evaluate the impact of financial aid (A/B style comparison, before/after outcomes).

## Data Preprocessing

* Checked for missing values and identified `Current Highest Degree` as highly missing (91.5%) → dropped.
* Verified column names matched the prompt.
* Ensured categorical columns are appropriately formatted.
* Assessed uniqueness of each column for further insights.

## Analysis Steps

1. **Acceptance Rate**

   * Calculated overall acceptance rate: 88.7%
   * Explored differences by gender, race/ethnicity, and field of study.
2. **Application Type & Renewal Rate**

   * Renewal rate: 71.5%
   * Insight: renewals indicate continued engagement with the program.
3. **First-Generation Students**

   * Count: 3,605 Yes, 699 No, 53 Unknown
   * Shows strong support for students facing educational barriers.
4. **High School Partnerships**

   * 3,024 attended partner high schools, 1,333 did not
   * Insight: partnerships improve program reach.
5. **Total Offered Award Amount**

   * Range: $500 – $69,148, median $1,000
   * Most awards are under $20,000
6. **Institution Type Analysis**

   * Boxplots by institution type to show award distributions.

## Technical Approach

* Python libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`
* Methods:

  * Exploratory Data Analysis (EDA)
  * Grouping and aggregations for categorical comparisons
  * Boxplots, bar plots, histograms for visualization
* Considered metrics for evaluating financial aid impact: acceptance, renewal, awards by student type, and high school partnerships.

## Presentation Prep

* 5–8 slides targeting organizational leadership
* Slide topics include:

  1. Title Slide
  2. Acceptance Rate Overview
  3. Application Type & Renewal Rate
  4. First-Generation Students
  5. High School Partnerships
  6. Institution Type Analysis
  7. Key Takeaways / Financial Aid Impact
  8. Next Steps / Recommendations
* Plots are placeholders; descriptive bullet points summarize insights.

## Notes

* Focus on **non-technical storytelling** for leadership.
* Highlight **equity and student support** insights.
* Dashboard-ready insights include acceptance rates, renewal trends, awards, and institutional reach.

## Contact

Prepared by: JongWook Choe
Email: [Your Email]
Date: January 2026
