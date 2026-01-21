**FIFA Players Exploratory Data Analysis (EDA)**

**Project Overview**

This project performs Exploratory Data Analysis (EDA) on a FIFA players dataset using Python.
The goal is to extract meaningful insights about player demographics, salaries, physical attributes, and preferences using data cleaning and visualization techniques.

∙**Dataset**

Source: FIFA Players Dataset

File Used: fifa_data.csv

Key Columns:

Name

Nationality

Club

Wage

Height

Preferred Foot

**Technologies Used**

Python

Pandas – data manipulation

Matplotlib – data visualization

Seaborn – statistical plots

∙**Analysis Performed**

The following insights were derived from the dataset:

Country with the most players

Identifies which nationality appears most frequently in the dataset.

Top 5 countries by player count

A bar chart visualization showing the countries that produce the most FIFA players.

Highest salary player

Determines the player earning the highest wage after cleaning salary data.

Salary distribution

A histogram illustrating the salary range and distribution among players.

Tallest player in FIFA

Converts player height into inches to accurately find the tallest player.

Club with the most players

Finds the football club with the highest number of registered players.

Preferred foot analysis

Displays which foot (Left/Right) is most commonly preferred by players using a bar chart.

∙**Data Cleaning**

Salary (Wage)

Converted from string values like €110K or €2M into numeric format.

Height

Converted from string format (e.g., 6'2) into total inches for comparison.

∙**Visualizations**

Bar chart for Top 5 Countries

Histogram for Salary Distribution

Count plot for Preferred Foot

All plots are generated using matplotlib and seaborn.

∙**How to Run the Project**

Navigate to the project directory:

cd fifa-eda

Install required libraries:

pip install pandas matplotlib seaborn


Run the script:

python fifa_eda.py

∙**Key Insights**

A small number of countries dominate player representation.

Salary distribution is highly skewed, with very few top earners.

Most players prefer their right foot.

Height and salary extremes highlight physical and financial diversity in professional football.

∙**Conclusion**

This project demonstrates how EDA helps uncover trends and patterns in sports datasets.
It is suitable for data analysis coursework, portfolio projects, and beginner-friendly data science practice.
