# Student Social Media and Wellbeing Analysis
A data science project exploring the relationship between social media behavior and student wellbeing using Power BI and Excel.
## Executive Summary
This project explores how social media use relates to student wellbeing, using a publicly available Kaggle dataset (Shamim, A., 2025). The goal was to uncover patterns that could inform better interventions for educators, policymakers and digital wellness initiatives (Global Wellness Institute, n.d.).

The dataset contains 705 student responses, covering factors such as daily screen time, nightly sleep hours, relationship status, mental health scores, and academic performance. Initial exploratory analysis was carried out in Excel, followed by a multiple linear regression model to evaluate how screen time influences academic scores, sleep, and mental wellbeing.

To provide interactive insights, a five-page Power BI dashboard was developed. It features demographic breakdowns, mental health visualisations, and cross-filtered views of academic impact and conflict behaviour. Each page addresses a specific research question, using slicers, tooltips, calculated measures, and a clear visual hierarchy.

The dashboard is built on a DAX-driven data model, enabling calculated insights directly in Power BI. Statistical checks in Excel, including residual analysis and R² values, confirmed a reasonable model fit.

Overall, this project demonstrates a structured approach to behavioural data analysis
using accessible tools, blending statistical methods with visual storytelling. It shows how open data can be transformed into actionable insights to support student communities.

## Dataset & Source

The dataset used in this project was sourced from Kaggle’s open platform, titled “Students' Social Media Addiction” by Adil Shamim (2025). It contains 705 anonymised responses from students across diverse demographics and academic levels.

The dataset includes the following key variables:

 - Average daily screen time (in hours)

 - Average nightly sleep (in hours)

 - Mental health self-rated score (1–10)

 - Addiction score (1–10)

 - Academic performance (Yes/No)

 - Number of conflicts caused by social media use

 - Demographic indicators such as gender, country, relationship status, and academic level

The data was already clean and required minimal transformation. A small number of columns were added for clarity, and numerical fields were prepared for regression and visualisation. No personal identifiers were present, ensuring full GDPR compliance (GOV.UK, n.d.).

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/399c12f4cb1838bf0bcf38aae2326de563727139/Excel_Screenshots/Excel_Regression_%20Data_Load(2).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/21d903828cd39bb6609fcad4aa827e9c1505e93d/Excel_Screenshots/Excel_Regression_%20Data_Load(3).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/21d903828cd39bb6609fcad4aa827e9c1505e93d/Excel_Screenshots/Excel_Regression_DataAnalytics%20(1).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/21d903828cd39bb6609fcad4aa827e9c1505e93d/Excel_Screenshots/Excel_Regression_%20EDA%20(3).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/21d903828cd39bb6609fcad4aa827e9c1505e93d/Excel_Screenshots/Excel_Regression_%20EDA%20(4).png)

## Analysis Performed

Initial exploration was carried out in Microsoft Excel to identify early trends and correlations between key variables, including screen time, sleep duration, and academic performance.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/21d903828cd39bb6609fcad4aa827e9c1505e93d/Excel_Screenshots/Excel_Regression_%20EDA%20(5).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/21d903828cd39bb6609fcad4aa827e9c1505e93d/Excel_Screenshots/Excel_Regression_%20EDA%20(6).png)

A correlation matrix, conditional formatting and scatter plots were used to visually detect patterns, followed by a multiple linear regression model to evaluate how these variables interacted.



The regression analysis focused on predicting academic performance and mental health based on screen time, sleep hours, and addiction scores. Model validation was supported through R² values, line fit plots, and residual analysis, confirming a reasonable degree of fit and predictive capability ([Figure 1] – Excel regression and diagnostics output).

To extend the analysis, a DAX-driven Power BI dashboard was developed. Calculated columns and measures were created to enable dynamic insights, including total student count, average score indicators, and custom subtitle generation ([Figure 2] – DAX subtitle and total student measures). Additional legend tables were constructed using DATATABLE to support interpretation of mental health and addiction scores ([Figure 3] – Score legend tables).

Interactive features such as slicers (platform, academic level, gender) and tooltips were implemented to enable filtering and drill-down functionality. Gradient-based conditional formatting was applied across mental health and addiction scores to highlight varying levels of concern ([Figure 4] – Conditional formatting colour rules on dashboard cards).

This combined use of Excel and Power BI enabled a structured and repeatable approach to data modelling and behavioural analysis, aligning visual storytelling with statistical robustness.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/399c12f4cb1838bf0bcf38aae2326de563727139/Excel_Screenshots/Excel_Regression_Correlation%20(6).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/399c12f4cb1838bf0bcf38aae2326de563727139/Excel_Screenshots/Excel_Regression_Correlation%20(8).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/399c12f4cb1838bf0bcf38aae2326de563727139/Excel_Screenshots/Excel_Regression_Correlation_Interpretation_Only%20(18).png)






## References

Global Wellness Institute, n.d. Digital Wellness Initiative. [online] Available at: https://globalwellnessinstitute.org/initiatives/digital-wellness-initiative/ [Accessed 30 August 2025].
GOV.UK, 2021. What is Data Quality? [online] Available at: https://www.gov.uk/government/news/what-is-data-quality [Accessed 16 July 2025].

GOV.UK, n.d. Data protection. [online] Available at: https://www.gov.uk/data-protection [Accessed: 1 June 2025].

Hawthorne, H., 2023. Effective Interventions in Education: Types and Examples. [online] High Speed Training. Available at: https://www.highspeedtraining.co.uk/hub/effective-interventions-in-education/ [Accessed 2 September 2025].

Hirshkowitz, M., Whiton, K., Albert, S.M., Alessi, C., Bruni, O., DonCarlos, L., Hazen, N., Herman, J., Katz, E.S., Kheirandish-Gozal, L., Neubauer, D.N., O’Donnell, A.E., Ohayon, M., Peppard, P.E., Pressman, M.R., and Adams Hillard, P.J., 2018. National Sleep Foundation’s sleep time duration recommendations: methodology and results summary. [online] PubMed Central. Available at: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6267703/ [Accessed 20 August 2025].

IconScout, n.d. Frightened Group Of People Sitting. [online] Available at: https://iconscout.com/free-illustration/frightened-group-of-people-sitting-10445471 [Accessed 20 August 2025].

Menon, K., 2025. Everything You Need to Know About ETL (Extract, Transform & Load). [online] Simplilearn. Available at: https://www.simplilearn.com/what-is-etl-process-article [Accessed 1 July 2025].

Microsoft, 2025. Power BI Overview. [online] Available at: https://learn.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview [Accessed 11 July 2025].

Niaz, M., 2024. How to Perform Regression Analysis in Excel? (3 Methods). [online] ExcelDemy. Available at: https://www.exceldemy.com/learn-excel/statistics/regression/ [Accessed 2 September 2025].

Sagerrald, A., 2023. Correlation vs Causation: Avoiding Statistical Red Herrings. [online] Medium. Available at: https://medium.com/@anantasagerrald/correlation-vs-causation-avoiding-statistical-red-herrings-6a9d05b729bf [Accessed 2 September 2025].

Shamim, A., 2025. Social Media Addiction vs Relationships. [online] Kaggle. Available at: https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships [Accessed 11 July 2025].

