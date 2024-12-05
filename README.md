# Tableau-Projects

## Introduction

This repository contains various projects I have completed in Tableau to showcase my data visualization and Tableau skills.

## Telco Customer Churn Analysis Dashboard

### Description

The project includes an analysis dashboard of customer churn in Telco, a fictional telecommunications company that provided home phone and Internet services to 7043 customers in California in Q3. The [Telco dataset](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113) is an IBM sample dataset that is widely used for practicing data analysis and machine learning. It consists of 6 .xslx files and contains:

* demographic info about customers – gender, age, martial status, dependents and location
* customer account info – tenure, contract, payment method, paperless billing, monthly charges, and total charges
* services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* customer churn metrics - churn label (which customers left and which stayed), churn score, and churn reason

This information allows analyzing differences between customers who left and stayed by demographic info, account info, and services signed up for. Furthermore, it allows analyzing other key churn metrics such as churn score and churn reason. All of this should help extract actionable insights for deisigning customer retention strategies.

The dataset is pre-processed, ensures data quality and consistency, and allows to start directly with data visualization.

### Dashboard

[Link to the dashboard on Tableau Public.](https://public.tableau.com/views/TelcoCustomerChurn_17282233160740/Dashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

I created a dashboard that breaks down customer churn by most of the dimensions available in the dataset:

![image](https://github.com/user-attachments/assets/64ab7c38-e89b-4c9e-bb4f-999641ba5be0)

* There are 3 parameters: Demographic Info, Account Info, and Services Signed Up For, which allow to choose different demographic, account, and services dimensions and explore churn among them.
* All graphs except Churn by Monthly and Total Charges work as filters activated by a click on the necessary dimension value.
* Total Customers mark card tooltip has 3 graphs of Customer Count broken down by the same 3 parameter dimensions chosen in the main view (therefore, the value change of the parameters in the main view also changes the values of the graphs in the total customer value tooltip).
* The Churn By Reason treemap has a drilldown from Churn Category to Churn Reason activated by a click on the necessary category.
