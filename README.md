# Capstone-Project

# TheLook Fintech Data Analysis

## Description
This project involves collecting, processing, and storing data in BigQuery to analyze loan information for TheLook Fintech, a financial technology startup. This project is part of a capstone project, showcasing skills in cloud data analysis and SQL.

## Project Overview
**Objective**: Develop and implement a plan to help the Treasury department use data effectively to track performance and growth.

### Key Business Questions:
1. How can we better monitor our cash flow to make sure the loans we are funding each month are not greater than the money coming in?
2. How can we identify the top reasons customers take out loans from our company?
3. How can we track the locations where borrowers have taken out loans?

### Key Metrics Analyzed:
- **Cash Flow**: Monitor money coming in and going out.
- **Loan Purposes**: Track primary purposes for taking loans.
- **Borrower Locations**: Understand geographical distribution of loans.

## Tasks Completed

1. **Set Up BigQuery Environment**: Opened BigQuery, selected an existing project, and located the Fintech dataset.
   ![Locate the dataset](screenshots/Capstone Project part 1.Locate the dataset.jpg)
   
2. **Explore Fintech Data**: Identified key tables and columns containing loan amounts and issuance dates.
   ![Task 2 Explored the dataset](screenshots/Capstone Project part 1.Task 2 Explored the dataset.jpg)
   
3. **Import CSV and Create Table**: Imported a CSV file mapping US states to regions and created a standard table.
   ![Task 3 Import a CSV file and create a standard table](screenshots/Capstone Project part 1.Task 3 Import a CSV file and create a standard table.jpg)
   
4. **Join Data from Two Tables**: Combined loan data with region information using SQL JOIN to create a comprehensive report.
   ![Task 4 Join data from two tables](screenshots/Capstone Project part 1.Task 4 Join data from two tables.jpg)
   
5. **Create Table with CTAS**: Used CREATE TABLE AS SELECT to store data results and connected it to Google Sheets.
   ![Task 5. Create a table based on the results of a query using CTAS](screenshots/Capstone Project part 1.Task 5. Create a table based on the results of a query using CTAS.jpg)
   
6. **Work with Nested Data**: Extracted loan purposes from nested columns to generate a detailed report.
   ![Task 6 Work with nested data](screenshots/Capstone Project part 1.Task 6 Work with nested data.jpg)
   ![Task 6 application.purpose notation](screenshots/Capstone Project part 1.Task 6 application.purpose notation.jpg)
   
7. **Deduplicate Data**: Removed duplicate loan purposes to ensure data accuracy.
   ![Task 7. Deduplicate data](screenshots/Capstone Project part 1.Task 7. Deduplicate data.jpg)
   
8. **Generate Report on Loans Issued**: Created reports on total loans issued by day and year.
   ![Task 8 Create a table that counts loans grouped by year](screenshots/Capstone Project part 1.Task 8 Create a table that counts loans grouped by year.jpg)

9. ## Project Summary For a detailed project summary, please refer to (Project Summary for TheLook Fintech.Part 1.PDF.pdf).

## Achievements
- Successfully provided the Treasury department with valuable data insights.
- Enhanced understanding of the company’s cash flow.
- Demonstrated proficiency in data collection, processing, and storage using BigQuery.

## Value Delivered
- **Actionable Insights**: Enabled informed business decisions by the Treasury department.
- **Data Management Skills**: Showcased skills in handling and analyzing large datasets using SQL and BigQuery.
- **Professional Portfolio**: Created a project that can be added to a professional portfolio to showcase to potential employers.

## How to Use
Clone the repository: git clone <repository-url>
Review the screenshots and captions to understand the step-by-step process.
Set up your own BigQuery environment and replicate the steps outlined in the screenshots to reproduce the analysis and reports.

## Contributing
If you'd like to contribute, please fork the repository and create a pull request.
