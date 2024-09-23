In this project, I was given a dataset consisting of raw loan data, including various attributes like loan amounts, interest rates, employment length, loan grades, and payment details. The objective was to clean, analyze, and transform this raw data into actionable insights using predefined KPIs. I also had to create two dashboards—Summary Dashboard and Overview Dashboard—to visualize the data effectively. Below is an overview of how I completed each step of the process:


1. Understanding the Raw Data:
The first step was to dive into the raw dataset and comprehend its structure. The raw data contained columns such as:

Loan ID
Loan amount
Interest rate
Annual income
Loan grade
Employment length
Loan term (e.g., 36 months, 60 months)
Total payment made
Debt-to-income ratio (DTI)
I analyzed each column to understand its significance and how it would contribute to the overall analysis.


2. Data Cleaning:
Data cleaning was a critical part of the project. The raw dataset contained missing values, inconsistent formats, and redundant information. I performed the following steps:

Handled Missing Values: I identified missing values in key fields such as employment length and loan amounts. These were either filled using average values or, where necessary, removed to avoid skewing the analysis.
Standardized Formats: Dates, numeric values, and other fields were standardized to ensure consistency across the dataset.
Removed Duplicates: I checked for and removed any duplicate records to maintain data integrity.


3. Defining and Calculating KPIs:
Based on the predefined KPIs, I started generating key performance indicators (KPIs) that would drive the final insights. The major KPIs I worked on included:

Loan Application Count: The total number of loan applications, giving an overview of the data size.
Total Funded Amount: The sum of all loan amounts to represent the total funds provided.
Total Amount Paid: The sum of total payments made across all loans, showing repayment progress.
Average Interest Rate: Calculated to understand the average cost of borrowing.
Average Debt-to-Income Ratio (DTI): To analyze the borrower’s ability to manage loan payments relative to their income.
These calculations were done using pivot tables and formulas to summarize the data across various dimensions like loan grades, states, and terms.


4. Creating Pivot Tables for Deeper Analysis:
Pivot tables were used extensively to summarize the raw data. Some of the key pivot table operations included:

Grouping by Loan Grade and Term: This allowed me to evaluate the average loan amounts and interest rates by loan grade (A, B, C, etc.) and loan term (36 months, 60 months).
Summarizing Funded and Paid Amounts: I used pivot tables to calculate the total funded amounts and total payments made, which provided insights into overall lending and repayment trends.
Calculating Average Interest Rates and DTI: The pivot tables helped aggregate the data and calculate averages for interest rates and debt-to-income ratios, enabling a deeper understanding of borrower risk profiles.


5. Building the Dashboards:
With the calculated KPIs and pivot table summaries, I moved on to dashboard creation. My goal was to present the insights in a clear, easy-to-understand format that would enable stakeholders to grasp the key trends and metrics at a glance.

Summary Dashboard:

This dashboard was designed to give a high-level overview of the dataset. It included KPIs like total loan applications, total funded amounts, total amount paid, and average interest rates.
I used visual elements like charts and graphs to highlight these key metrics, making it easier to see trends and comparisons across different loan grades and terms.
Overview Dashboard:

The Overview Dashboard provided more granular insights, such as how loan performance varied across different borrower segments (e.g., employment length, loan term, and grade).
I incorporated interactive elements like slicers and filters, allowing users to drill down into specific categories and explore the data dynamically.
The dashboard included visuals like bar charts, pie charts, and trend lines to represent the relationship between loan amounts, interest rates, and repayment behavior.


6. Using Excel Features to Enhance Visualization:
The dashboards were built using various Excel features that enhanced the user experience:

Pivot Tables: Central to the dashboards, pivot tables allowed dynamic data manipulation and recalculation of KPIs based on filters.
Charts and Graphs: I created bar charts, line charts, and pie charts to visually represent key metrics, making the dashboards more engaging and easier to interpret.
Slicers: I implemented slicers to allow users to filter data by categories like loan grade, term, and state, enabling deeper data exploration.
Conditional Formatting: To highlight critical metrics (e.g., high DTI or high-interest rates), I used conditional formatting to draw attention to outliers and significant trends.


7. Final Presentation and Insights:
Once the dashboards were complete, I reviewed the results to extract actionable insights. Some key findings included:

Higher loan amounts were associated with lower interest rates in higher loan grades (A, B), indicating that more creditworthy borrowers receive better terms.
Loans with longer terms (60 months) tended to have higher interest rates and a higher likelihood of default, as indicated by higher DTI ratios.
Borrowers with longer employment lengths tended to have lower DTIs and better loan performance, suggesting stability in income is a strong indicator of repayment capacity.
