# HR-Fabric-Data-Analysis
This project is an end-to-end HR Analytics solution developed using Microsoft Fabric and Power BI.

The solution demonstrates the complete BI workflow starting from data ingestion to dashboard visualization using modern data engineering and reporting techniques.

The dashboard provides insights into:

1.Employee Headcount
2.Attrition Analysis
3.Average Salary
4.Average Age
5.Recruitment Source Analysis
6.Department-wise Employee Distribution
7.Gender & Marital Status Analysis

## Architechture
Data Source
    ↓
Dataflow Gen2
    ↓
Lakehouse
    ↓
Semantic Model
    ↓
Power BI Dashboard
    ↓
Scheduled Pipeline Refresh
