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
   ![Locate the dataset](Capstone%20Project%20part%201.Locate%20the%20dataset.jpg)

2. **Explore Fintech Data**: Identified key tables and columns containing loan amounts and issuance dates.
   ![Task 2 Explored the dataset](Capstone%20Project%20part%201.Task%202%20Explored%20the%20dataset.jpg)

3. **Import CSV and Create Table**: Imported a CSV file mapping US states to regions and created a standard table.
   ![Task 3 Import a CSV file and create a standard table](Capstone%20Project%20part%201.Task%203%20Import%20a%20CSV%20file%20and%20create%20a%20standard%20table.jpg)

4. **Join Data from Two Tables**: Combined loan data with region information using SQL JOIN to create a comprehensive report.
   ![Task 4 Join data from two tables](Capstone%20Project%20part%201.Task%204%20Join%20data%20from%20two%20tables.jpg)

5. **Create Table with CTAS**: Used CREATE TABLE AS SELECT to store data results and connected it to Google Sheets.
   ![Task 5 Create a table based on the results of a query using CTAS](Capstone%20Project%20part%201.Task%205.%20Create%20a%20table%20based%20on%20the%20results%20of%20a%20query%20using%20CTAS.jpg)

6. **Work with Nested Data**: Extracted loan purposes from nested columns to generate a detailed report.
   ![Task 6 Work with nested data](Capstone%20Project%20part%201.Task%206%20Work%20with%20nested%20data.jpg)
   ![Task 6 application.purpose notation](Capstone%20Project%20part%201.Task%206%20application.purpose%20notation.jpg)

7. **Deduplicate Data**: Removed duplicate loan purposes to ensure data accuracy.
   ![Task 7 Deduplicate data](Capstone%20Project%20part%201.Task%207.%20Deduplicate%20data.jpg)

8. **Generate Report on Loans Issued**: Created reports on total loans issued by day and year.
   ![Task 8 Create a table that counts loans grouped by year](Capstone%20Project%20part%201.Task%208%20Create%20a%20table%20that%20counts%20loans%20grouped%20by%20year.jpg)

9. **Project Summary For a detailed project summary, please refer to Capstone%20Project%20Summary%20for%20TheLook%20Fintech.Part%201.PDF.pdf.

## Achievements
- Successfully provided the Treasury department with valuable data insights.
- Enhanced understanding of the company’s cash flow.
- Demonstrated proficiency in data collection, processing, and storage using BigQuery.

## Value Delivered
- **Actionable Insights**: Enabled informed business decisions by the Treasury department.
- **Data Management Skills**: Showcased skills in handling and analyzing large datasets using SQL and BigQuery.
- **Professional Portfolio**: Created a project that can be added to a professional portfolio to showcase to potential employers.

## Contributing
If you'd like to contribute, please fork the repository and create a pull request.
