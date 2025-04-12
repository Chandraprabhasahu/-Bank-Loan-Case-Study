# Bank Loan Analysis


## Project Overview

In this project, assume the role of a data analyst at a finance company that lends various types of loans to urban customers. A significant challenge for the company lies in identifying customers with insufficient credit history who may default on their loans. The goal is to use Exploratory Data Analysis (EDA) to identify risk patterns and ensure that capable applicants are not rejected while minimizing the financial loss from defaulters.

##  Project Files
-  [Download Loan Analysis Workbook](https://docs.google.com/spreadsheets/d/1JXkLL-Lp6vWnOs8PQaBRehvZE58gmacC/edit?usp=sharing&ouid=109009397325426290832&rtpof=true&sd=true)
-  [Download additional workbook_previous application data](https://docs.google.com/spreadsheets/d/1heXdUQ98DqtKWD3BzHqHyL36EY0BFlr3/edit?usp=sharing&ouid=109009397325426290832&rtpof=true&sd=true)


## Dataset
This project utilizes two key datasets:

1. Application Data
Contains information about each loan application including applicant demographics, financial data, and loan status.
File name: application.csv

2. Previous Application Data
Includes historical data of applicants’ past loan applications. Helps in understanding payment behavior and patterns of loan default.
File name: previous_application.csv

### Download the dataset files directly from the source below:
- [Dataset Source](https://drive.google.com/drive/folders/1VgA3fS_-WRu28jHyD0bU_aVsFg7Mj9nh?usp=sharing)
  

The dataset includes information about loan applications, categorized into the following outcomes:
- **Approved:** Loan application approved by the company.
- **Cancelled:** Application cancelled by the customer.
- **Refused:** Application rejected by the company.
- **Unused Offer:** Loan approved but not utilized by the customer.

### Key Scenarios:
- **Payment Difficulties:** Customers with late payment of over X days on at least one of the first Y installments.
- **All Others:** Customers with timely payment history.
  
##  Business Objectives
- Identify customers likely to face difficulty in paying loan installments.
- Prevent rejection of creditworthy applicants.
- Minimize approval of applicants who may default.
- Provide actionable insights to guide decisions on loan approval, loan amount adjustment, or interest rate modifications.


##  Data Analysis Tasks

### A. Identify and Handle Missing Data
- **Task:** Detect missing values using Excel functions such as `COUNT`, `ISBLANK`, `IF`.
- **Action:** Use imputation techniques like `AVERAGE`, `MEDIAN` or deletion based on severity.
- **Visualization:** Bar chart/column chart to show the percentage of missing values per variable.

### B. Detect Outliers in the Dataset
- **Task:** Use Excel statistical functions such as `QUARTILE`, `IQR` and conditional formatting to find outliers.
- **Action:** Assess business logic to determine whether to retain, transform, or remove outliers.
- **Visualization:** Box plots or scatter plots to highlight outlier distribution across variables.

### C. Analyze Data Imbalance
- **Task:** Determine distribution of classes using `COUNTIF`, `SUM`.
- **Action:** Calculate class ratio to assess imbalance in the target variable.
- **Visualization:** Pie chart or bar chart showing frequency of each class (e.g., defaulters vs non-defaulters).

### D. Univariate, Segmented Univariate & Bivariate Analysis
- **Univariate Analysis:** Examine the distribution of single variables using `COUNT`, `AVERAGE`, etc.
- **Segmented Univariate Analysis:** Compare variable distributions between defaulters and non-defaulters using filters/pivot tables.
- **Bivariate Analysis:** Explore relationships between variables using scatter plots, cross-tabs, and pivot tables.
- **Visualization:** Histograms, stacked/grouped bar charts, box plots, heatmaps.

### E. Identify Top Correlations for Each Scenario
- **Task:** Segment data by scenario (e.g., with/without payment difficulties) and calculate correlations.
- **Action:** Use Excel's `CORREL` function to identify variables with highest correlation to loan default.
- **Visualization:** Correlation matrices/heatmaps with highlights for top variables.

##  Tools & Technologies Used
- **Tool:** Microsoft Excel
- **Techniques:** EDA, Data Cleaning, Outlier Detection, Correlation Analysis, Visualization

##  Key Insights
- Identified variables with the highest impact on loan defaults.
- Determined periods with higher payment difficulties.
- Found significant data imbalance requiring mitigation.
- Proposed data-driven decision rules for loan approval strategies.

##  Outcomes
- Improved understanding of credit risk patterns.
- Recommendations to avoid financial losses due to defaults.
- Insights to enhance the loan evaluation framework.

##  Learnings
- Hands-on experience with Excel for handling real-world financial datasets.
- Developed a robust EDA pipeline for credit risk analysis.
- Strengthened skills in outlier detection, missing value treatment, and correlation analysis.

##  Project Structure
```
Bank-Loan-Analysis/
├── Dataset/
│   └── loan_applications.csv
├── Excel_Analysis/
│   ├── Missing_Data_Analysis.xlsx
│   ├── Outlier_Analysis.xlsx
│   ├── Univariate_Bivariate_Analysis.xlsx
│   └── Correlation_Analysis.xlsx
├── Visualizations/
│   ├── Missing_Values_Bar_Chart.png
│   ├── Outliers_Box_Plot.png
│   ├── Data_Imbalance_Pie_Chart.png
│   └── Correlation_Heatmap.png
└── README.md
```

##  Conclusion
This Bank Loan Analysis project offers critical insights into customer loan behavior using Excel-based exploratory analysis. By identifying risk patterns, data imbalance, outliers, and strong correlations, the analysis supports better, data-driven decisions in loan approvals and credit risk management.

---






