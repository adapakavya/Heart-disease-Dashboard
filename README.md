# Heart-disease-Dashboard
### 1.   Project Title

❄️CardioCare Analytics: Heart Disease Survival Dashboard
A Power BI dashboard designed to analyze survival outcomes and key health indicators in heart disease patients.

### 2.  Short Description / Purpose

The CardioCare Analytics Dashboard provides an interactive view of heart disease survival trends. It enables users to analyze how factors such as age group, serum sodium levels, gender, and diabetes influence patient outcomes. The dashboard helps clinicians and analysts identify high-risk categories and make informed healthcare decisions.

### 3.  Tech Stack
   
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) –.Used for calculated measures(Alives %, averages, totals) dynamic visuals and conditional logic.<br>
•	📝 Data Modeling – Relationships established among patient attributes to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

### 4.  Data Source

Dataset sourced from publicly available Heart Disease datasets (Kaggle/UCI Repository).
Contains patient details such as:

•	Age and age groub<br>
•	Serum sodium levels<br>
•	Diabetes status<br>
•	Survival status (Alive/Death)<br>
•	Additional clinical features<br>
Data preparation included age segmentation, handling missing values, and calculation of survival measures.

### 5.  Features and Highlights

### Business Problem

Healthcare teams often lack an easy way to interpret survival trends and risk factors from raw clinical data. Identifying which age groups or health conditions contribute to higher mortality is critical.

### Goal of the Dashboard

•	To provide a visual analytical tool that highlights:<br>
•	Survival trends across age categories<br>
•	Influence of serum sodium levels on survival<br>
•	Impact of diabetes on patient outcomes<br>
•	Gender-based differences in survival<br>
The dashboard supports early detection strategies and risk-based patient monitoring.

### Key Visuals Explained

### •	 KPI Cards

•	Alive Percentage<br>
•	Average Alive Value<br>
•	Total Alive<br>
•	Total Death<br>
These metrics give an overall snapshot of patient outcomes.

### •	 Total Alive by Category

A bar and line chart displaying how many patients are alive across different age segments. Shows highest survival in the 51–60 group and lowest in 71+.

### •	 Average Serum Sodium by Age Group

A combined bar and line visual comparing the average serum sodium levels across age groups and its relation to survival outcomes.

### •	 Total Alive by Age Group

A line/area chart illustrating survival distribution. Shows a clear decline in survival as age increases.

### •	 Total Alive vs Diabetes Count

A stacked chart indicating how the presence of diabetes impacts survival in each age segment.

### •	 Gender Slicer

Interactive buttons to filter the dashboard by male or female patients for targeted analysis.

### 6.  Business Impact and Insights

•	Survival probability decreases significantly in patients aged 71+.<br>
•	Serum sodium levels are strongly correlated with survival outcomes.<br>
•	Diabetes is a prominent risk factor in the 51–70 age groups.<br>
•	Gender filtering reveals differences in survival distribution and risk levels.<br>
•	Supports clinicians and researchers in making early diagnosis and targeted interventions.


### 7.  Screenshot
![Dashboard Preview](https://github.com/adapakavya/Heart-disease-Dashboard/blob/main/heart_disease.png)
