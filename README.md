# KPMG_Virtual_Internship_Challenge
 Customers and transactions analysis

**Objective:** This challenge consists of a series of 4 modules provided and is provided by the KPMG Virtual Internship Program. The 3 modules are:
* 1. Data Quality Assessment: Perform EDA using Python and build visualization dashboards using Power BI.
* 2. Data Insights: Predict customer trends and behavior using supervised Machine Learning algorithm, recommend which of these 1000 new customers should be targeted to drive the most value for the organisation. (This is a Customer Segmentation with K-Means exercise)

**Data Type:** Structured data (Nemerical and Categorical), time-series. Since it's a structured dataset, the clean dataset can be stored in a SQL database such as SQL Elephant or PostgreSQL.

**Data Source:** Dataset was provided by KPMN's client, Sprocket Central Pty Ltd. (Provided in the Resources folder of this repo)

**3 Datasets:**
  * Customer Demographic
  * Customer Addresses
  * Transactions data in the past 3 months

- The datasets are related to each other by the customer_id column as shown in the diagram below:
  ![alt text](https://github.com/Navyhoang/KPMG_Virtual_Internship_Challenge/blob/main/Results/QuickDBD-Free%20Diagram.png "DBD")

**Data Quality Analysis includes:**
  * Check data accuracy: if values are close to true values.
  * Check data completeness: fill nan values with values that make sense. Drop rows if neccessary.
  * Check data consistency: check if values contradict to normally observed trends.
  * Check data currency: check if data are up to date.
  * Check data relevancy: drop columns or values that do not make any differences in the analysis or ML model development.
  * Validate data: check if data are within allowable ranges of values, and check for outliers. Ex: someone's age cannot be over 200.
  * Check for duplicates: remove duplicates to avoid double dipping in the ML model.

**Results Summary:* (In progress)

**1. MODULE 1:** (Complete)
- A list of recommendations for Data Treatment is provided in the Documentation folder as well as the Module 1 notebook in the Results folder. 
- 2 dashboards were created using Power BI. The file is also included in the Results folder and it can be published for sharing when a liecense is purchases. Snapshots of the dhasboard are shown below:

  ![alt text](https://github.com/Navyhoang/KPMG_Virtual_Internship_Challenge/blob/main/Results/CustomersDemographicsDashboard.PNG "Customer Demographics")
  ![alt text](https://github.com/Navyhoang/KPMG_Virtual_Internship_Challenge/blob/main/Results/PuchasesAnalysisDashboard.PNG "Purchases Analysis")
  
**1. MODULE 2:** (In-progress)


