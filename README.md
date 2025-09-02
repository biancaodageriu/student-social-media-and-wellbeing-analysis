# Student Social Media and Wellbeing Analysis
A data science project exploring the relationship between social media behaviour and student wellbeing using Power BI and Excel.
## Executive Summary
This project explores how social media use relates to student wellbeing, using a publicly available Kaggle dataset (Shamim, A., 2025). The key hypothesis driving this analysis is: *"Increased daily screen time on social media negatively impacts student mental health, academic performance, and sleep quality"*. The goal was to uncover patterns that could inform better interventions for educators, policymakers and digital wellness initiatives (Global Wellness Institute, n.d.).
*This text is bold*

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

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/3b9df713da63b51e07a378980845dcd3d93ea12a/Excel_Screenshots/Excel_Regression_Correlation%20(6).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/3b9df713da63b51e07a378980845dcd3d93ea12a/Excel_Screenshots/Excel_Regression_Correlation%20(8).png)
![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/3b9df713da63b51e07a378980845dcd3d93ea12a/Excel_Screenshots/Excel_Regression_Correlation_Interpretation_Only%20(18).png)

The regression analysis focused on predicting academic performance and mental health based on screen time, sleep hours, and addiction scores. Model validation was supported through R² values, line fit plots, and residual analysis, confirming a reasonable degree of fit and predictive capability.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/Excel_Screenshots/Excel_Regression_Statistics.png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/Excel_Screenshots/Excel_Regression_Avg_Daily_Residual_And_LineFit.png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/Excel_Screenshots/Excel_Regression_Conflicts_Residual_And_LineFit.png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/Excel_Screenshots/Excel_Regression_MentalHealth_Residual_And_LineFit.png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/Excel_Screenshots/Excel_Regression_SleepHrs_Residual_And_LineFit.png)


## Visualisations

To extend the analysis, a DAX-driven Power BI dashboard was developed. Calculated columns and measures were created to enable dynamic insights, including total student count and average score indicators. Additional legend tables were constructed using DATATABLE (Microsoft Learn, 2025), to support interpretation of mental health and addiction scores.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Data_Model.png)

Each page follows a consistent layout and includes slicers, tooltips, and calculated measures. A colour-blind-friendly theme was applied, and interactive elements—such as slicers for platform, academic level, and mental health category, along with tooltips, enable filtering, drill-down functionality, and an overall enhanced user experience.

 ### Page 1 - Overview Page

Provides a geographic breakdown of student responses and the most frequently used social media platforms. Key statistics such as average screen time, sleep hours, and wellbeing scores are displayed using data cards with gradient-based conditional formatting across mental health and addiction scores data cards to highlight varying levels of concern. Slicers allow filtering by platform and academic level.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page1_Overview%20(1).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page1_Overview%20(4).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page1_Overview%20(5).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page1_Overview%20(2).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page1_Overview_DataCards_Background%20(1).png)

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page1_Overview_DataCards_Background%20(2).png)

 
 ### Page 2 - Mental Health & Addiction Score Page 

Visualises the distribution of mental health and addiction scores using pie charts and classification bands. Users can interpret average scores using custom legends.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page2_Mental_and_Addiction_Scores_Explained%20(1).png)


### Page 3 - Screen Time vs Sleep and Academic Outcomes

Shows scatter plots comparing screen time with sleep duration and academic impact. Filters by mental health category and academic level offer additional segmentation.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page3_ScreenTime_Vs_Sleep_Vs_Performance%20(1).png)


### Page 4 - Social Conflict vs Academic Impact 

Highlights patterns of academic performance in relation to social conflicts caused by social media usage. Visualised with dot plots to display concentrations across usage bands.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/c26c068c78b66ee9160b9bd855b05e30f936fb71/PowerBI_Screenshots/PoweBI_Page4_ScreenTime_Vs_Conflicts_VsPerformance%20(1).png)


### Page 5 – Digital Behaviours vs Mental Health Insights

Examines the relationship between daily screen time and self-rated mental health using a combination of bar charts and scatter plots. Key metrics such as average addiction score, “good” mental health category percentage, and academic impact are displayed using data cards. Slicers enable filtering by academic level and mental health category. Conditional colour formatting enhances the visibility of patterns across screen usage and wellbeing levels.

![Alt text](https://github.com/biancaodageriu/student-social-media-and-wellbeing-analysis/blob/244e4327dd810dfb20c42a56e9d6e6e04a91467b/PowerBI_Screenshots/PoweBI_Page5_ScreenTime_AddictionScore_Vs_Mental%20Health%20(1).png)


## Conclusion

The analysis supported the initial hypothesis that students who spend more time on screens tend to experience lower academic performance, reduced sleep, and poorer mental wellbeing. The data revealed clear patterns linking digital habits to wellbeing outcomes, with addiction scores being noticeably higher among students who reported average or poor mental health. Those who experienced social conflicts as a result of online interactions also tended to perform worse academically, suggesting that the impact of digital behaviour extends beyond individual habits to social dynamics. Sleep emerged as an important protective factor, as students who reported longer and better-quality sleep generally achieved stronger academic results and demonstrated better mental health. By translating these findings into an interactive dashboard, the project provides a practical and accessible way to explore how screen time, conflict, sleep, and academic performance are interconnected, creating a strong foundation for targeted interventions and awareness initiatives.


## Recommendations

 - Expand demographic fields: Future datasets should include variables such as socioeconomic background, device type, and course type to enable more granular segmentation.
 - Implement advanced predictive models: Techniques like time-series forecasting or clustering (GeeksforGeeks, 2025) could help anticipate behavioural trends and identify students at higher risk.
 - Increase dataset size and diversity: Incorporating a larger, more internationally diverse sample would improve generalisability and allow for richer comparative insights.
 - Enable real-time data input: Building a survey-to-dashboard pipeline would allow educators and institutions to apply the dashboard in live environments.
 - Enhance accessibility: Adding narrative summaries, audio support, and detailed tooltip explanations for each insight would improve inclusivity and comprehension.
 - Conduct user testing and feedback cycles: Iterating based on input from educators, wellbeing officers, and students would refine visual prioritisation and overall usability.


## References

Dalesandro, J., 2024. Power BI: Filter Using Card Visualizations and Bookmarks. [online] Available at: https://johndalesandro.com/blog/power-bi-filter-using-card-visualizations-and-bookmarks/ [Accessed 11 June 2025].

GeeksforGeeks, 2025. Clustering in Machine Learning. [online] Available at: https://www.geeksforgeeks.org/machine-learning/clustering-in-machine-learning/ [Accessed 2 September 2025].

GeeksforGeeks, 2025. Time Series Analysis and Forecasting. [online] Available at: https://www.geeksforgeeks.org/machine-learning/time-series-analysis-and-forecasting/ [Accessed 2 September 2025].

Global Wellness Institute, n.d. Digital Wellness Initiative. [online] Available at: https://globalwellnessinstitute.org/initiatives/digital-wellness-initiative/ [Accessed 30 August 2025].

GOV.UK, 2021. What is Data Quality? [online] Available at: https://www.gov.uk/government/news/what-is-data-quality [Accessed 16 July 2025].

GOV.UK, n.d. Data protection. [online] Available at: https://www.gov.uk/data-protection [Accessed: 1 June 2025].

Hawthorne, H., 2023. Effective Interventions in Education: Types and Examples. [online] High Speed Training. Available at: https://www.highspeedtraining.co.uk/hub/effective-interventions-in-education/ [Accessed 2 September 2025].

Hirshkowitz, M., Whiton, K., Albert, S.M., Alessi, C., Bruni, O., DonCarlos, L., Hazen, N., Herman, J., Katz, E.S., Kheirandish-Gozal, L., Neubauer, D.N., O’Donnell, A.E., Ohayon, M., Peppard, P.E., Pressman, M.R., and Adams Hillard, P.J., 2018. National Sleep Foundation’s sleep time duration recommendations: methodology and results summary. [online] PubMed Central. Available at: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6267703/ [Accessed 20 August 2025].

IconScout, n.d. Frightened Group Of People Sitting. [online] Available at: https://iconscout.com/free-illustration/frightened-group-of-people-sitting-10445471 [Accessed 20 August 2025].

Menon, K., 2025. Everything You Need to Know About ETL (Extract, Transform & Load). [online] Simplilearn. Available at: https://www.simplilearn.com/what-is-etl-process-article [Accessed 1 July 2025].

Microsoft Learn, 2025. DATATABLE function - DAX. [online] Available at: https://learn.microsoft.com/en-us/dax/DATATABLE-function-dax [Accessed 30 August 2025].

Microsoft, 2025. Power BI Overview. [online] Available at: https://learn.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview [Accessed 11 July 2025].

Niaz, M., 2024. How to Perform Regression Analysis in Excel? (3 Methods). [online] ExcelDemy. Available at: https://www.exceldemy.com/learn-excel/statistics/regression/ [Accessed 2 September 2025].

Sagerrald, A., 2023. Correlation vs Causation: Avoiding Statistical Red Herrings. [online] Medium. Available at: https://medium.com/@anantasagerrald/correlation-vs-causation-avoiding-statistical-red-herrings-6a9d05b729bf [Accessed 2 September 2025].

Shamim, A., 2025. Social Media Addiction vs Relationships. [online] Kaggle. Available at: https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships [Accessed 11 July 2025].

Statistics Easily, n.d. What is Robust Statistics in Data Analysis? [online] Available at: https://statisticseasily.com/glossario/what-is-robust-statistics-data-analysis/ [Accessed 2 September 2025].
