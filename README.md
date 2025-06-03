# Healthcare-Management-Insights (Interactive Dashboard Creation using Power BI)
A data-driven dashboard built with SQL and Power BI to help healthcare professionals make smarter decisions. It analyzes patient demographics, hospital performance, billing, and medical trends from 5 years of healthcare data.

### Overview
This Project was designed to help healthcare administrators, medical professionals, and decision makers with a tool that enhances data-driven decisions and improves operational efficiency. This project involves analyzing a healthcare dataset and building a dynamic dashboard that consolidates multiple data points including patient information, admission/discharge details, medical conditions, medications, billing data, insurance provider and hospital logistics.

### Data Source
The dataset of this project was sourced from `Kaggle.com`, exported in CSV format. It includes details of patients, doctors and hospitals of a particular area spanning from August 2019 to July 2024. The key variables of the dataset include Name Of Patient, Age, Gender, Blood Type, Medical Condition, Date Of Admission, Name Of Doctor, Name Of Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results.

### Tools used:
I made use of SQL first, which I used extract, manipulate and analyze the data. I used SQL because of how large the dataset was. Then, I used Power BI for the visualization.

### Data cleaning: 
The dataset was very large, so I used SQL and then Power query in Power BI, the first step I took was to create a duplicate of the dataset for error recovery, then I removed the duplicates which I achieved by creating temporary row numbers and deleting the duplicate rows. I standardized some of the data that needed to be standardized using Power query and also changed the data type of the date column. There were no missing values.

### Analysis techniques:
I analyzed the patients, doctors and hospitals separately, I used the filters to segment patients by gender, days spent in the hospitals, blood type etc. I also did same with the doctors and the hospitals. I identified the top doctors and top hospitals under many categories. I also created a new column to identify various age groups to simplify and enhance the interpretability of data.

### Visualizations used:
I used Bar charts, Waterfall Chart, Pie chart, Line chart, Tables and KPI cards for simplicity and easy understanding. I also used slicers for easy interaction and dynamism.
<a href="https://github.com/fabbiiee/Healthcare-Management-Insights-PowerBI-SQL-Project-/blob/main/Screenshot%202025-04-14%20171943.png">View Page 1 of Dashboard</a>,
<a href="https://github.com/fabbiiee/Healthcare-Management-Insights-PowerBI-SQL-Project-/blob/main/Screenshot%202025-04-14%20172021.png">View Page 2 of Dashboard</a>,
<a href="https://github.com/fabbiiee/Healthcare-Management-Insights-PowerBI-SQL-Project-/blob/main/Screenshot%202025-04-14%20172053.png">View Page 3 of Dashboard</a>



### Challenges and learnings:
I faced some challenges while cleaning the data with SQL while standardizing the data, I figured out how to fix the issue using SQL but I used power query instead to save time. It becomes clearer day by day how important it is to prioritize time saving techniques in one’s daily activities taking efficiency and accuracy into consideration.

### Conclusion: 
This project aimed to create a tool to provide insights and identify key trends in the healthcare performance of a certain area and it was achieved.
I recommend you to continue tracking the KPIs(key performance indicators) using the dynamic dashboard I created and update the dataset regularly to monitor changes.

### Dashboard:
![Page 1]("C:\Users\HP Pavilion 15\Pictures\Screenshots\Screenshot 2025-04-14 171943.png")

