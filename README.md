# Loan-Analysis-for-SuperBANK
This project involves analyzing loan data for SuperBANK to gain insights and support decision-making.



# Project Description

This project involves analyzing loan data for SuperBANK to gain insights and support decision-making. The original dataset includes columns such as "ApplicationID," "PIN," "Status," "Product," "Timestamp," and "Amount." Data transformation and analysis were performed using Python in Jupyter Notebook, followed by visualization and reporting using PowerBI.

# Data Transformation Steps

Data transformation was performed first using Python in Jupyter Notebook, and then using Power Query on PowerBI, with the following steps:
- Null values were dropped from the "Timestamp" column to ensure data integrity.
- Null values in the "Amount" column were replaced with the mean value to address missing data.
- New columns such as "Year," "Month," "Day," and "Date" were created using Python, but were not utilized in the analysis.
- A new column "Amount Category" was created with Power Query to categorize the loan amounts based on predefined ranges.

# Analysis and Visualization

PowerBI was used to create a comprehensive report that provides insights into various aspects of the loan data. DAX measures were utilized to calculate key performance indicators (KPIs) and customize calculations. The report includes visualizations such as charts, graphs, and tables to present trends, patterns, and metrics related to the loan data.

# Conclusion

The loan analysis project using PowerBI and DAX measures aims to provide valuable insights to support decision-making and strategic planning for SuperBANK. The interactive and visual nature of the report facilitates a deeper understanding of the loan data, enabling stakeholders to make informed decisions.
