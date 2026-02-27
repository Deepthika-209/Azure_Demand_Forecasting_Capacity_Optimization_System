Azure Demand Forecasting & Capacity Optimization System
>	Project Overview
This project focuses on preparing historical cloud usage data for building a predictive system that forecasts demand for compute and storage resources. The objective is to support efficient capacity planning, reduce infrastructure waste, and improve resource allocation decisions.
_________________________________________
	Milestone 1 
Objective — Data Collection & Preparation
The goal of this milestone is to collect, clean, validate, and structure datasets so they are ready for machine learning modeling.
_________________________________________
> Tasks Completed
> 
•	Collected Azure usage dataset with regional and temporal attributes
•	Added external influencing variables relevant to demand trends
•	Cleaned dataset by handling missing values
•	Removed duplicate and inconsistent records
•	Standardized column formats
•	Validated numerical ranges and logical consistency
•	Generated new time-based features for analysis
________________________________________
📂 Project Files

•	dataset.csv → Raw dataset
•	milestone1.py → Data preprocessing script
•	LICENSE → MIT License file
________________________________________
🛠 Technologies Used

•	Python
•	Pandas
•	NumPy
•	Matplotlib
________________________________________
> Output of Milestone 1
A structured, clean, and validated dataset prepared for forecasting models and analytical processing.
________________________________________

 Milestone 2 — Feature Engineering & Data Wrangling
> Objective

The goal of this milestone is to enrich the cleaned dataset by engineering meaningful features and transforming it into a structured, model-ready format suitable for forecasting.

> Tasks Completed

• Identified key demand-driving features such as capacity planning, operational spend, reliability score, and economic indicators
• Engineered rolling statistical features (7-day rolling mean and standard deviation) to capture usage trends
• Created lag variables (1-day, 7-day, 14-day) to model temporal dependencies
• Added seasonality indicators including day of week, weekend flag, and quarter
• Detected and flagged demand spikes for anomaly awareness
• Applied categorical encoding for regional and service line variables
• Structured dataset with consistent time granularity and timestamp indexing
• Prepared final model-ready dataset for predictive modeling

> Output of Milestone 2

A fully feature-engineered and time-series structured dataset ready for forecasting model development.

