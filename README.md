# About Me

Junior Data Analyst with an Architecture background and strong skills in data cleaning, exploratory analysis, and
visual storytelling. Experienced in transforming complex datasets into clear,
actionable insights that support data-driven decision-making. Particularly
interested in urban analytics, business intelligence, and building
well-structured visualizations that communicate findings effectively.

### Technical Skills
- **Data analysis & data management** using **Excel, SQL, Python, and R**
- **Data visualization & storytelling** using **Tableau**

### Soft Skills
Data Analysis | Problem Solving | Effective Communication | Team Collaboration | Results-Driven | Organizational Skills | Proactive Mindset | Attention to Detail | Process Optimization

<!-- PARA HACER QUE EL LINK ABRA EN OTRA PESTAÑA
<a href="https://www.linkedin.com/in/samuelalcorro/" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>-->
[![LinkedIn](https://img.shields.io/badge/linkedin-%23295F98.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samuelalcorro/)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-295F98?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:samuel200@outlook.com)

* * *

# Data Analyst Projects

## Urban Mobility and Economic Productivity in LATAM Cities
This project analyzes the relationship between **urban mobility performance** and
**economic productivity** across major Latin American cities. By integrating traffic
congestion data from the **TomTom Traffic Index** with economic indicators from **OECD
Cities**, the analysis identifies urban patterns that may inform **transportation
infrastructure investment decisions**.

The workflow includes **data cleaning**, **standardization**, **dataset integration**,
**exploratory data analysis (EDA)**, and **data visualization** to uncover **actionable
insights** for urban development stakeholders.

#### Tools Used
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge)
![Data Cleaning ](https://img.shields.io/badge/Data_cleaning-295F98?style=for-the-badge)
![Data Wrangling](https://img.shields.io/badge/Data_Wrangling-295F98?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Data_analysis-295F98?style=for-the-badge)
![Predictive Modeling](https://img.shields.io/badge/Predictive_Modeling-295F98?style=for-the-badge)

### Key Questions
1. Which Latin American cities show the highest mismatch between urban congestion and economic productivity?
2. Which cities demonstrate the most efficient balance between mobility performance and economic strength?
3. Which mobility indicators are most strongly associated with urban economic performance?

### Methodology

- **Data Preprocessing:** Cleaned and standardized the dataset by resolving inconsistencies, removing duplicates, and validating missing values to ensure data quality.
- **Exploratory Data Analysis (EDA):** Analyzed customer demographics and usage behavior to identify patterns between retained and churned members.
- **Predictive Modeling:** Trained Logistic Regression and Random Forest models to predict customer churn, achieving accuracy scores of 85% and 84%, respectively.
- **Customer Segmentation:** Applied K-Means clustering to group customers based on behavioral similarity and support targeted retention strategies.

### Key Findings & Recommendations

#### Critical Retention Drivers

- Shorter distance to the gym, longer contract duration, participation in group sessions, and higher visit frequency are strongly associated with lower churn.
- Younger customers with short-term contracts and low visit frequency exhibit significantly higher churn risk.

#### Recommended Strategies

- **Incentivize Contract Extensions:** Promote upgrades from monthly to longer-term memberships through targeted offers.
- **Increase Group Session Engagement:** Develop campaigns highlighting the value of group classes to improve retention.
- **Deploy Targeted Retention Campaigns:** Leverage the predictive model to identify high-risk customers and deliver personalized promotions.
- **Implement Proactive Segmentation:** Classify new customers by age and contract duration to enable early-stage retention interventions.

### Featured Visualizations

1. **Jams Delay Distribution (Boxplot):**  
   The boxplot reveals the distribution and variability of traffic delay times across observations. The visualization highlights the presence of dispersion in congestion levels and allows identification of potential outliers. The average delay is displayed to provide additional context for overall traffic conditions.

   ![Jams Delay Boxplot](/assets/img/p01_jams_delay_boxplot.png)

2. **Jams Delay Distribution (Enhanced Boxplot):**  
   A second boxplot with mean markers provides a clearer view of the central tendency and spread of `jams_delay`. This visualization reinforces the variability in congestion patterns and supports exploratory analysis of traffic behavior in 2024.

   ![Jams Delay Distribution](/assets/img/p01_jams_delay_distribution.png)

3. **Traffic vs. Economic Output by City:**  
   The bar chart compares `jams_delay` and `city_gdp_capita` across cities, enabling visual assessment of the relationship between urban congestion and economic productivity. Preliminary patterns suggest that mobility efficiency may play a relevant role in urban economic performance, supporting the need for deeper multivariate analysis.

   ![Traffic vs Economy by City](/assets/img/p01_traffic_vs_economy.png)

---

## E-commerce Funnel & User Retention Analysis
The objective of this project is to **evaluate the performance of the e-commerce conversion funnel** and **analyze user retention patterns** across Latin American markets. The study aims to understand **user behavior throughout the purchase journey**, identify **key friction points affecting conversion**, and calculate critical metrics such as **step-by-step conversion rates**, **cohort retention (D7–D28)**, and **market-level performance differences** to support data-driven growth decisions.

#### Tools & Techniques

![SQL](https://img.shields.io/badge/SQL-295F98?style=for-the-badge&logo=postgresql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-295F98?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Funnel Analysis](https://img.shields.io/badge/Funnel_Analysis-295F98?style=for-the-badge)
![Cohort Analysis](https://img.shields.io/badge/Cohort_Analysis-295F98?style=for-the-badge)
![Retention Analysis](https://img.shields.io/badge/Retention_Analysis-295F98?style=for-the-badge)
![Conversion Analysis](https://img.shields.io/badge/Conversion_Analysis-295F98?style=for-the-badge)
![Data Aggregation](https://img.shields.io/badge/Data_Aggregation-295F98?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-295F98?style=for-the-badge)

### Key  Questions
1. ¿Cuántos usuarios activos diarios, semanales y mensuales tiene la aplicación?
2. ¿Cuáles son las principales fuentes de adquisición de clientes y su rentabilidad?
3. ¿Qué métricas de ventas y conversiones se pueden mejorar?
4. ¿Qué tan efectiva es cada fuente de marketing según su ROMI?

### Methodology

- **Data extraction & querying:** SQL was used to aggregate user event data and construct funnel metrics and retention cohorts.
- **Funnel analysis:** Calculated step-by-step conversion rates from product interaction to completed purchase.
- **Cohort retention analysis:** Measured user retention at D7, D14, D21, and D28 intervals.
- **Country segmentation:** Compared performance across Latin American markets to identify regional patterns.
- **Executive reporting:** Results were summarized into a business-focused dashboard and executive report.

### Conclusions & Recommendations

#### User Behavior, Sales & Marketing

- Approximately **16% of users return weekly**, while only **4% return monthly**, indicating a clear opportunity to strengthen long-term retention strategies.
- The **average purchase value is $5**, with noticeable peaks in December driven by seasonal promotions. Most users place **one order per month**.
- **Traffic sources 1, 5, and 9 show the strongest ROMI performance**, with most cohorts approaching a ROMI of 1 before completing their first month.
- **Source 1 stands out** as a high-efficiency channel: despite being the **second lowest in marketing spend**, it ranks as the **third highest in user acquisition**.

#### Recommendations

- **Discontinue sources 7, 9, and 10** due to consistently low performance.
- **Reduce investment in source 3**, as it does not generate significant returns.
- **Increase investment in source 1**, which remains a high-performing channel combining **low cost and strong acquisition results**.
  
