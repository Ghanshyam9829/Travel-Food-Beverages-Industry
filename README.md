# Travel, Food & Beverages Industry: Adverse Event Reporting Analysis

## Case Study Overview

### **Background**
The CAERS database contains adverse event and product complaint reports related to foods, dietary supplements, and cosmetics from 2004 to Q2 2017. It includes detailed records using MedDRA terminology to ensure standardized reporting.

### **Objective**
Analyze the CAERS dataset to understand adverse events associated with foods, dietary supplements, and cosmetics reported to the FDA. Identify patterns and trends in event distribution, demographics, symptom types, and severities to enhance product safety surveillance, inform regulatory policies, and improve public health outcomes.

### **Data Source**
[CAERS_ASCII_2004_2017Q2.csv](https://drive.google.com/file/d/1KlKIEL4e68XekgMe-rLqlR_JxuYwYQyQ/view?usp=sharing)

### **Updated Data After Cleaning**
[CAERS_ASCII_2004_2017Q2.csv](https://drive.google.com/file/d/1KlKIEL4e68XekgMe-rLqlR_JxuYwYQyQ/view)


### **Analysis Steps in Tableau**
1. **Data Preparation**: Import and clean the CAERS dataset in Tableau.
2. **Adverse Event Analysis**: Analyze the distribution of events across product categories.
3. **Severity of Events Analysis**: Assess common severe outcomes by product.
4. **Demographic Analysis**: Study the impact on different age and gender groups.
5. **Symptom Frequency Analysis**: Identify common symptoms across product categories.
6. **Temporal Trends**: Investigate reporting trends over time.
7. **Product Severity Impact**: Correlate product types with event severity.
8. **Predictive Model**: Create a model to predict event outcomes based on initial reports.

### **Dashboard**
- **Interactive Dashboard**: Visualize adverse event frequency, severity, demographics, and symptoms with filters for product type, event date, and demographic details.
- **Summary & Insights**: Highlight key findings such as frequently reported products, demographic insights, and reporting trends.

### **Key Findings**
- Most frequently reported products and symptoms.
- Demographic insights on adverse event reports.
- Trends in adverse event reporting over time.


### **Dashboard Explanation**
I have created four interactive dashboards in Tableau to visualize and analyze the data:

![Screenshot (186)](https://github.com/Ghanshyam9829/Travel-Food-Beverages-Industry/assets/125486967/d2de5672-38b2-48a9-a735-b8036fa5417a)


1. **Outcome Analysis**: This dashboard focuses on the severity and types of adverse event outcomes. It provides insights into common outcomes such as hospitalizations, ER visits, and non-serious injuries, allowing users to understand the impact of different products on public health.

2. **Symptom Analysis**: This dashboard examines the frequency and types of symptoms reported in adverse events. Users can explore which symptoms are most commonly associated with different product categories and identify patterns in symptom occurrence.

3. **Demographic Analysis**: This dashboard analyzes how adverse events affect different demographic groups, including age and gender. It helps identify any notable differences in the types and severities of events experienced by various demographic segments.

4. **Trend Analysis**: This dashboard investigates temporal trends in adverse event reporting. Users can observe changes in reporting frequency over time, identify seasonal patterns, and analyze trends related to specific product categories.

   ### **Dashboard: Outcome Analysis**

![Screenshot (187)](https://github.com/Ghanshyam9829/Travel-Food-Beverages-Industry/assets/125486967/fc04361f-d5c5-41ea-be07-fa36919c417c)


1. Majority of adverse events reported are serious, indicating significant impact.
2. Non-serious and hospitalization cases follow in frequency.
3. Life-threatening outcomes like death and disability are relatively low.
4. Products related to the Vit/Min/Prot/Unconv Diet (Human/Animal) industry often cause serious, hospitalization, and life-threatening outcomes.
5. "Redacted" is the most risky product category resulting in serious outcomes.
6. Non-serious outcomes have the highest percentage, closely followed by serious outcomes.

### **Dashboard: Symptom Analysis**
![Screenshot (188)](https://github.com/Ghanshyam9829/Travel-Food-Beverages-Industry/assets/125486967/51d00f5d-580f-47d8-813f-ffa26f8ac481)

1. Top 5 reported symptoms: diarrhea, vomiting, ovarian cancer, nausea, and choking.
2. Severe symptoms are mostly linked to 'Vit/Min/Prot/Unconv Diet (Human/Animal)' products, except ovarian cancer, which is linked to cosmetics.
3. Choking is mainly caused by nuts/edible seeds and vegetable products.
4. Year-on-year growth shows significant increases in symptoms like abdominal pain, diarrhea, and malaise.

### **Dashboard: Demographic Analysis**
![Screenshot (189)](https://github.com/Ghanshyam9829/Travel-Food-Beverages-Industry/assets/125486967/d62dec43-0f7d-44e9-911d-a1066429c0d1)


1. Middle-aged adults (40-60 years) are most affected, followed by young adults (20-40 years).
2. Females experience more serious outcomes, while males experience more non-serious outcomes; outcomes for unknown gender are mostly non-serious.
3. Females constitute 63% of cases, while males account for 30%.
4. Clustering analysis shows distinct groups based on products, symptoms, and severity.

### **Dashboard: Trend Analysis**
![Screenshot (190)](https://github.com/Ghanshyam9829/Travel-Food-Beverages-Industry/assets/125486967/3153d25a-15ef-4fcd-9956-dc4710f16931)

1. Bars show yearly total reported cases trend; line chart displays year-on-year percentage change.
2. Highest number of cases in 2016, with a significant decline in 2017.
3. Average time lag is highest for general physician visit cases.
4. Severe outcome cases have a shorter average time lag.
5. Adverse events related to Vitamin D and redacted products show a higher time lag.
6. Forecast for 2018 is higher than 2017 but around previous averages.
7. High correlation between non-serious outcomes and common symptoms; significant correlation between serious outcomes and specific symptoms like choking and ovarian cancer.
