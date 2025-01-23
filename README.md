# Diabetes-Health-Indicators
This project showcases an analysis of diabetes-related data based on the Behavioral Risk Factor Surveillance System (BRFSS) survey. SQL was used for data preparation, and Python (pandas, matplotlib, seaborn) was employed for visualization and analytics.

Step-by-Step Overview of Analysis
Preparation:

Download the database file diabetes.db and open the analysis document Diabetes Health Indicators.pdf.
Review the data description in the document to understand the context and structure of the dataset.
Database:

The initial database consisted of a single table diabetes, containing 22 columns and over 250,000 records.
The data was segmented into several logical tables for further analysis:
patients: demographic information (age, sex, education, income).
health_conditions: medical data (blood pressure, cholesterol, BMI, diabetes status).
lifestyle: lifestyle habits (smoking, physical activity, fruit and vegetable consumption).
healthcare_access: access to healthcare.
health_status: general health conditions (mental and physical health, walking difficulty).
Table Creation:

New SQL tables were created to organize the data, and data from the original table was transferred using INSERT INTO queries.
An ER diagram was built to visualize the relationships between the tables.
Simple Analysis:

Diabetes Distribution:
Diabetes_012 = 0: No diabetes (84% of patients).
Diabetes_012 = 1: Prediabetes (1.8% of patients).
Diabetes_012 = 2: Diabetes (14% of patients).
Age Distribution:
Older age groups (65+) showed the highest number of patients with diabetes.
Deeper Analysis:

Patients with High Blood Pressure and Diabetes:
Most of these patients belonged to older age categories.
Relationship Between Physical Activity and Diabetes:
Individuals who were physically inactive had a significantly higher prevalence of diabetes compared to those who were active.
Visualization:

Python libraries (matplotlib, seaborn) were used to create various types of visualizations:
Bar plots: To show diabetes distribution by categories.
Histograms: To display age distribution among patients with high blood pressure and diabetes.
Heatmap: To analyze the relationship between physical activity levels and diabetes status.
These visualizations added clarity and made the findings more accessible.
Key Findings:

Most Vulnerable Groups:
Physically inactive individuals.
Older age groups (especially 65+).
Impact of Physical Activity:
Physical activity significantly reduces the risk of diabetes, regardless of age.
Type 2 Diabetes:
Patients with Type 2 Diabetes (Diabetes_012=2) were the most prevalent group.
Recommendations:

Implement programs that promote physical activity, especially among older adults.
Conduct regular medical screenings for seniors and sedentary individuals.
Educate the public about the benefits of a healthy lifestyle for diabetes prevention.
