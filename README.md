# Experiment 11 : Categorical Data Analysis using Python
# 1. Aim
To study and analyze categorical data using Python by applying various data analysis techniques such as frequency analysis, identification of unique values, cross-tabulation, grouping, filtering, and sorting using the Pandas library.
# 2. Introduction
Categorical data refers to data that can be classified into distinct groups or categories. These categories represent qualitative attributes such as gender, department, grade, product type, or payment method.
In data analysis, categorical variables play a significant role in understanding patterns and relationships within datasets. Python, along with the Pandas library, provides efficient tools for handling, summarizing, and analyzing such data in a structured manner.
# 3. Theoretical Background

3.1 Frequency Count

Frequency count is used to determine how often each category appears in a dataset. It helps in understanding the distribution of categorical variables.

3.2 Unique Values

This method identifies all distinct categories present in a dataset, providing insight into the different groups within a variable.

3.3 Number of Unique Values

This calculates the total number of distinct categories in a column, helping to understand the diversity of the data.

3.4 Cross Tabulation

Cross tabulation is used to analyze the relationship between two or more categorical variables by creating a contingency table.

3.5 Percentage Distribution

This shows the relative proportion of each category in percentage form, making it easier to compare distributions.

3.6 Filtering Data

Filtering allows selection of specific data entries based on given conditions, enabling focused analysis.

3.7 Grouping Data

Grouping organizes data into categories based on one or more variables, making it easier to analyze patterns and relationships.

3.8 Sorting Data

Sorting arranges the dataset in a specified order (ascending or descending), improving readability and interpretation.

# 4. Procedure
Create datasets containing categorical variables
Import the Pandas library
Load data into a DataFrame
Perform frequency analysis
Identify unique values in categorical columns
Perform cross-tabulation between variables
Analyze percentage distribution
Apply filtering, grouping, and sorting operations

# 5. Dataset Description
Dataset 1: Order Dataset
Order ID
Product Category
Payment Method
Delivery Type
Customer Type
Used to analyze product orders and customer behavior.
Dataset 2: Student Dataset
Student Grade
Department
Gender
Used to analyze academic performance and demographic distribution.

| S.No | Function        | Purpose                              |
|------|-----------------|--------------------------------------|
| 1    | DataFrame()     | Creates a structured data table      |
| 2    | value_counts()  | Calculates frequency of categories   |
| 3    | nunique()       | Counts unique values                 |
| 4    | crosstab()      | Performs cross-tabulation            |
| 5    | groupby()       | Groups data based on categories      |
| 6    | sort_values()   | Sorts the dataset                   |
| 7    | read_csv()      | Loads data from CSV file            |
| 8    | normalize       | Converts counts into proportions    |

# 7. Tools Used
Python
Jupyter Notebook
Pandas Library
Google Colab / VS Code
# 8. Applications
Business and sales analysis
Customer behavior analysis
Market research
Academic performance evaluation
Data-driven decision making
# 9. Conclusion
Categorical data analysis is a fundamental aspect of data science and statistics. Using Python and the Pandas library, it becomes efficient to analyze categorical variables, identify trends, and extract meaningful insights.
This experiment demonstrated essential techniques such as frequency analysis, cross-tabulation, grouping, filtering, and sorting, which are highly useful in real-world data analysis scenarios.

