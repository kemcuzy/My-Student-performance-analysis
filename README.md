# Student Performance Analysis Using Python and Power BI

## Project Overview

This project explores factors associated with students’ examination performance using data analytics. Python was used for data cleaning and preparation, while Microsoft Power BI was used to build an interactive dashboard and communicate key findings.

The analysis examines attendance, study hours, previous academic scores, tutoring participation, motivation, parental involvement, sleep duration, and internet access.

The objective is to transform student data into meaningful insights that can help educators identify performance patterns and make informed decisions about student support.

## Project Objectives

- Analyze overall student examination performance.
- Explore relationships between study hours, attendance, and examination scores.
- Compare examination outcomes across previous-score and tutoring groups.
- Investigate motivation, parental involvement, sleep duration, and internet access.
- Develop an interactive Power BI dashboard.
- Provide practical, evidence-informed recommendations.

## Dataset Overview

- **Total records:** 6,607 students
- **Total columns:** 20
- **Primary outcome variable:** `Exam_Score`

The dataset contains academic, behavioral, and contextual variables related to student performance.

## Tools and Technologies

- **Python:** Data cleaning and preparation
- **Pandas:** Data manipulation and quality checks
- **Jupyter Notebook:** Python analysis environment
- **Microsoft Power BI:** Dashboard development and visualization
- **Power Query:** Data preparation within the Power BI workflow, where applicable

## Data Cleaning

The dataset was examined for missing values, duplicate records, and examination scores outside the valid range of 0–100.

### Final Data Quality Results

| Check | Result |
|---|---:|
| Records | 6,607 |
| Columns | 20 |
| Missing values | 0 |
| Duplicate rows | 0 |
| Exam scores outside 0–100 | 0 |

These results indicate that the final dataset passed the three reported data-quality checks.

## Key Findings

### 1. Attendance and Examination Performance

- Attendance group 90–100: average exam score of **70.12**
- Attendance group 60–69: average exam score of **64.21**
- Difference: **5.91 points**

The higher-attendance group recorded a higher average examination score.

### 2. Study Hours and Examination Performance

- Students studying 30+ hours: average exam score of **70.88**
- Students studying 1–9 hours: average exam score of **63.82**
- Difference: **7.06 points**

The higher-study-hours group recorded a higher average examination score.

### 3. Tutoring Participation

Students attending 6+ tutoring sessions recorded an average examination score of **71.08**, the highest among the reported tutoring groups.

This pattern warrants further investigation; it does not establish that tutoring alone caused higher scores.

### 4. Motivation

- High motivation: **67.70**
- Medium motivation: **67.33**
- Low motivation: **66.73**

The differences between motivation groups were relatively small.

### 5. Parental Involvement

- High parental involvement: **68.09**
- Low parental involvement: **66.33**

The high-involvement group recorded a higher average examination score.

### 6. Internet Access

- With internet access: **67.29**
- Without internet access: **66.47**

The difference between the two groups was **0.82 points**.

### 7. Sleep Duration

The reported average examination scores for the 4–5, 6–7, and 8–10 sleep-hour groups were **67.40**, **67.21**, and **67.19**, respectively. These averages were very similar.

## Power BI Dashboard

The report contains five pages:

1. **Pre-Analysis** — project objectives, dataset overview, and analytical workflow.
2. **Academic Performance Overview** — key performance indicators and visual comparisons.
3. **Academic History & Performance** — previous academic performance and related group comparisons.
4. **In-Analysis** — chart-specific observations and insights.
5. **Recommendations & Action Plan** — practical recommendations based on the findings.

### Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Students | 6,607 |
| Average Exam Score | 67.23 |
| Average Attendance | 79.98 |
| Average Study Hours | 19.98 |

## Recommendations

- **Strengthen academic support:** Provide targeted revision and mentoring for students who need additional help.
- **Improve attendance:** Monitor attendance patterns and investigate barriers to classroom participation.
- **Promote effective study habits:** Encourage structured revision and consistent study schedules.
- **Evaluate tutoring programmes:** Review tutoring participation and outcomes to assess the usefulness of different support approaches.
- **Encourage family engagement:** Strengthen constructive communication between schools and families.
- **Support digital learning:** Consider access to reliable internet and appropriate learning resources.
- **Monitor student progress:** Use dashboard filters and comparable data over time to review performance patterns and assess interventions.

## Limitations

This project uses descriptive analysis and group comparisons. The observed differences do not establish causation. Group averages may conceal individual differences, and other unmeasured factors may contribute to student performance.

Further statistical analysis would be required to assess the strength of relationships, statistical significance, and the independent contribution of individual factors.

## Conclusion

This project demonstrates an end-to-end analytics workflow using Python and Power BI. Data cleaning improved the consistency of the dataset, while exploratory analysis and dashboard visualizations helped identify patterns across academic and contextual factors.

The findings highlight attendance, study habits, and tutoring participation as useful areas for further investigation. The dashboard translates these findings into a clear report intended to support evidence-informed educational decision-making.

## Skills Demonstrated

- Data cleaning and preparation
- Exploratory data analysis
- Data quality validation
- Descriptive statistics
- Data visualization
- Power BI dashboard development
- Insight generation
- Analytical storytelling
- Evidence-informed recommendations

## Project Workflow

**Pre-Analysis → Python Cleaning → EDA → Power BI Dashboard → Insights → Recommendations**

## Dashboard Preview

![Pre-Analysis Dashboard](pre-analysis.png)
