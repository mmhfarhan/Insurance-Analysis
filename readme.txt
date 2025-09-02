Insurance Analysis Dashboard – Power BI

This project is an interactive Insurance Analysis Dashboard built in Power BI. It focuses on cleaning, transforming, and analyzing insurance-related data to deliver actionable insights for business decision-making.

🔧 Project Tasks Performed
1. Data Preparation & Cleaning

Imputation of Missing Values:

Replaced null/blank values with Mode (for categorical) and Median (for numerical) values using Power Query.

Value Replacement for Better Readability:

Marital Status → Yes → Married, No → Unmarried

Self Employed → Yes → Business, No → Job

Loan Status → Y → Approved, N → Not Approved

2. Feature Engineering with DAX

Created a calculated column to categorize Applicant Income into slabs:

0–5K, 5–10K, 10–15K, 15–20K, 20–25K, and Above 25K.

3. Visualizations

Developed multiple visuals to analyze data trends and insights:

Clustered Bar Chart – Credit History vs Applicant Income (with Loan Status as legend).

Line Chart – Maturity Term vs Premium Amount.

Line & Clustered Column Chart – Dependents vs Premium Amount & Applicant Income.

Area Chart – Income Slab vs Premium Amount & Count of IDs.

Pie/Donut Chart – Premium Amount by Branch & Self Employment status.

4. Dashboard Design

Created a single-page interactive dashboard with:

Slicers: Gender, Marital Status, Education.

Cards: Average Premium Amount, Average Applicant Income.

Navigation Buttons: Forward, Backward, and Home for smooth navigation.

🛠️ Tools & Technologies

Power BI (Data Cleaning, Transformation, Visualization, Dashboarding)

Power Query (ETL – Extract, Transform, Load)

DAX (Calculated Columns & Measures)