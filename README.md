# ABC Company Employee Data Analysis — Capstone Project 2

## 📘 Project Overview
This project analyzes employee data from **ABC Company**, containing 458 rows and 9 columns. 
The goal was to clean the dataset, perform multiple analyses, and visualize key insights using Python libraries such as **pandas**, **numpy**, **matplotlib**, and **seaborn**.

The tasks were based on the project instructions provided in the assignment PDF and include:
1. Preprocessing the data (fixing the Height column)
2. Analyzing employee distribution across teams
3. Grouping employees by position
4. Identifying the predominant age group
5. Finding the team and position with the highest salary expenditure
6. Studying the correlation between age and salary
7. Visualizing overall relationships with a correlation heatmap

---

##  Step 1 — Data Preprocessing
The `Height` column contained inconsistent values, so it was replaced with random integers between **150 and 180** centimeters using NumPy. 
A fixed random seed (`42`) was used to ensure reproducible results. This cleaned the dataset and made it ready for analysis.

---

## Step 2 — Employee Distribution Across Teams
Using `value_counts()`, I calculated the number of employees in each team and their percentage share of the total workforce.  
There were **30 teams** in total, each having around 15 members.  
Teams such as **New Orleans Pelicans** and **Memphis Grizzlies** had slightly higher counts, while **Orlando Magic** and **Minnesota Timberwolves** had slightly fewer.  
The bar chart visualization showed that the team sizes were fairly balanced overall.

---

##  Step 3 — Employees by Position
The position-wise analysis showed that **Shooting Guards (SG)** formed the largest group, followed by **Power Forwards (PF)** and **Point Guards (PG)**.  
This indicates a slightly guard-heavy workforce structure.  
A bar chart was used to visualize how many employees belonged to each position.

---

##  Step 4 — Predominant Age Group
The employees were divided into age groups (20–24, 25–29, 30–34, 35–39, 40–44).  
Most employees fell into the **25–29** age group, followed by the **20–24** range.  
This suggests a **young and dynamic workforce**, likely at early to mid-career stages.  
The bar chart clearly highlighted that the younger groups dominate the organization.

---

## Step 5 — Highest Salary Expenditure

By grouping data by both `Team` and `Position`, I calculated the total salary expenditure for each combination.  
The **Los Angeles Lakers – Small Forward (SF)** combination had the **highest total salary (≈ 31.86 million)**, showing where the company invests most heavily.  
The bar graph of top salary combinations made this insight very clear.

---

##  Step 6 — Correlation Between Age and Salary
To understand the relationship between age and salary, I computed their correlation and plotted a scatter graph.  
The correlation coefficient was **+0.21**, indicating a **weak positive relationship** — older employees tend to earn slightly more.  
The regression line on the scatter plot confirmed this mild upward trend.

---

##  Step 6 — Correlation Heatmap
To explore all numeric relationships, a correlation heatmap was created.  
It revealed that **Height and Weight** were strongly correlated, while **Age and Salary** had a weak positive correlation.  
This heatmap provided a quick visual overview of how different numeric variables relate to one another.

---

##  Insights & Conclusion
- The dataset was successfully cleaned by fixing height values.
- The company has 30 teams, with nearly balanced employee counts.
- Shooting Guards (SG) make up the largest position group.
- The workforce is mostly aged between 25–29 years.
- The Cleveland Cavaliers’ Power Forwards have the highest total salary expenditure.
- Age and salary show a weak positive correlation.
- Height and weight show a strong positive correlation.

Overall, the analysis revealed a **balanced and youthful workforce**, moderate salary variation across roles, and logical relationships between key numeric variables.  

---

##  Final Reflection
Working on this project strengthened my skills in data cleaning, grouping, visualization, and data storytelling with Python.  
I learned how to:
- Handle real-world datasets using pandas  
- Use NumPy for random number generation and reproducibility  
- Visualize data effectively using Matplotlib and Seaborn  
- Derive insights and present them clearly through visuals and narrative

This project helped bridge the gap between coding and real-world data interpretation — demonstrating not only technical skill but also analytical thinking and communication.

---
