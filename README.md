# Project # 1
# Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022
Type of analysis : Descriptive analysis     
Source of data :  
https://www.datosabiertos.gob.pe/dataset/atenciones-de-cobertura-oncol%C3%B3gica-periodos-2022-2023-fondo-intangible-solidario-de-salud  
Tool used : Microsoft Excel

# Summary of data set:
This data set contains information about the hospital attention offered by Public Institutions that provide Medical Services to patients who suffer an oncological disease during 2022 in Perú. In addition, it presents information about patients like age, gender, place where they received medical attention, type of oncological disease, date of medical attention and so on.
# Requirements:
It is required a dashboard which summarizes the following metrics:

KPI 1 :  
Percentage of medical attentions treated by Region in Perú during 2022 

KPI 2:  
Number of diagnosed patients by each type of oncological disease ( add a filter which allows to choose by gender) 

KPI 3:  
Present a histogram which shows the number of patient by intervals of age ( range of interval 10 years) 

KPI 4:  
Number of medical attentions carried out by month and by type of oncological diagnosis 

# Review of dataset 
Before starting the process of data cleaning, it was necessary to understand the context and each variable in order to establish what it means or represents and which category is the best suited ( text, float, integer, date). 
The following table explains what means each variable :

![image](https://github.com/Luchini1987/Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022/assets/160271117/d4c13b2b-8ae9-43cc-b4dc-9b4aff6bd15c)

# Data cleaning 
Using Excel’s functions like DATE, LEFT, RIGHT, MID and eliminating duplicates was possible to transform characters into dates and delete duplicate values.  

# Analysis derived from the dataset

To analyze and extract information from the dataset, I used the function called PIVOT TABLES.  
The plot for each KPI is presented below: 

KPI 1 :  
Percentage of medical attentions treated by Region in Perú during 2022 

Using the function GRAPH was possible to create a map corresponding to Perú which indicates the percentage of medical attention by region. 

![image](https://github.com/Luchini1987/Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022/assets/160271117/26b41327-60cf-462e-84f7-2992b0b43744)

KPI 2:  
Number of diagnosed patients by each type of oncological disease ( add a filter which allows to choose by gender) 

![image](https://github.com/Luchini1987/Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022/assets/160271117/cd2179d1-4ab9-4e5d-a26c-c065d9293662)

KPI 3:  
Present a histogram which shows the number of patient by intervals of age ( range of interval 10 years) add a filter by oncological disease

![image](https://github.com/Luchini1987/Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022/assets/160271117/f7eee2a1-9ba5-448f-9858-ef94a188967c)

KPI 4:  
Number of medical attentions carried out by month and by type of oncological diagnosis  
Add a filter by region

![image](https://github.com/Luchini1987/Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022/assets/160271117/bd719afc-48a0-4b81-a319-4bc9d5963757)

# Overview
![image](https://github.com/Luchini1987/Data-analysis-about-hospital-attention-to-patients-with-oncological-diseases-in-Peru-2022/assets/160271117/359b5f4d-a753-4c5d-9ca8-0d1c37c27ef3)


