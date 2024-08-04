# HR Analysis

## 📜 Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tool](#tool)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings/Insights](#findingsinsights)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

###  Project Overview
This data analysis project aims at providing insights into the performance of a company over the past years. By analyzing various aspects of the dataset, we seek to identify key metrics, trends, and proving insights into employee satisfaction, retention, work-life balance, gender diversity and gain a deeper understanding of the company's HR Department performance.

###  Data Source
The dataset used for this analysis is the "HR_dataset.xlsx" file.

### Tool
Microsoft Excel was used for this project.
- 📈EDA was carried out using Pivot tables.
- 📊Visualizations and Dashboard/Report was designed using Pivot Charts.

###  Data Cleaning and Preparation
The provided dataset has already been cleaned/prepared by the organisers of the workshop. This was confirmed by inspection.

###  Exploratory Data Analysis
EDA involved exploring the HR dataset to answer key questions such as:

📍 Total number of employees since inception.

📍 Total number of current employees.

📍 Total number of terminated employees.

📍 Employee termination rate.

📍 Total salaries paid.

📍 Current employees by gender.

📍 The level of employee education.

📍 How satisfied are employees with their job.

📍 Rate of employee work-life balance.

📍 Quarterly new hires.

📍 Quarterly terminations.

📍 Monthly termination trends.

📍 Monthly salary trends.

📍 Salary spread by number of years the full time employees or contractors spent at the company.

📍 Salary spread by total working  years of the employees by gender.

###  Data Analysis

Data Analytical Expressions (DAX) calculations/measures were adopted in the determination of some key metrics used in the analytical processes. In order to enalbe the use of models, the check box (as illustrated in the image below) must be ticked while inserting the pivot table(s).

|KEY METRICS|DAX CALCULATIONS|
|-----------|---------------|
|Total Employee|=COUNT(Employee[ID employe])|
|Headcount|=CALCULATE([Total Employee], Employee[Attrition]="No")|
|Employee[Attrition]="No")|=CALCULATE([Total Employee],Employee[Attrition]="Yes")|
|Termination Rate|=[Termination]/ [Headcount]|
|Salary|=CALCULATE(SUM(Employee[Salary]),Employee[Attrition]="No")|

![Screenshot (216)](https://github.com/user-attachments/assets/dde3c24c-359c-48e0-a26b-11ab26008a92)

###  Findings/Insights
- **𝐆𝐞𝐧𝐝𝐞𝐫 𝐃𝐢𝐯𝐞𝐫𝐬𝐢𝐭𝐲:** The employees population is comprised of **732 male** and **501 female**, reflecting a commendable effort towards gender balance.
- **𝐓𝐞𝐫𝐦𝐢𝐧𝐚𝐭𝐢𝐨𝐧 𝐑𝐚𝐭𝐞:** The employee attrition rate was **19.22%**. Although **237** terminations were recorded out of **1470** total employees, the headcount of **1233** current employees could still highlight a robust team.
- **𝐉𝐨𝐛 𝐒𝐚𝐭𝐢𝐬𝐟𝐚𝐜𝐭𝐢𝐨𝐧:** On this, **407** employees rated as **very high**, **369 as high**, suggesting that majority are content with their roles, which is for growth.
- **𝐖𝐨𝐫𝐤-𝐋𝐢𝐟𝐞 𝐁𝐚𝐥𝐚𝐧𝐜e:** Although **62%** of the current employess have a **better** work-life balance, it is of importance to address the concerns of the few who recorded **4.46%** as **low**.
- **𝐇𝐢𝐫𝐢𝐧𝐠 𝐓𝐫𝐞𝐧𝐝𝐬:** The company is on an upward growth path, with **315** new hires in Q1, culminating in **323** by Q4.
- **E𝐝𝐮𝐜𝐚𝐭𝐢𝐨𝐧𝐚𝐥 𝐁𝐚𝐜𝐤𝐠𝐫𝐨𝐮𝐧𝐝:** Most employees hold Bachelor's degrees **(473)**, followed by Master's degrees **(340)**, College diplomas **(238)**, and below college level **(139)**. A small number **(4)** have Doctorates, indicating a preference for undergraduate education.
- **𝐒𝐚𝐥𝐚𝐫𝐲 paid:** The highest salary was in October ($54,872), while the lowest was in February ($5,331), likely due to seasonal fluctations.

###  Dashboard
The image of the dashboard efficiently designed to show key findings is displayed below:

![finalDash](https://github.com/user-attachments/assets/78da7565-1358-4771-aaf8-8bd0d2c34db1)

###  Conclusion
Working on this project has further deepened my understanding in data analytics and particularly in the Human Resource department. Key metrics, trends/patterns and insights were drawn, aiding data-driven decision making by the stake holders.

🤝Connect with me on 

[LinkedIn](https://www.linkedin.com/in/sylvester-iheanaetu-434069231/)

[Medium](https://medium.com/@sylvesteriheanaetu) 
