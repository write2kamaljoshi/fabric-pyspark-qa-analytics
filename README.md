# QA Test Analytics using Microsoft Fabric & PySpark

## Overview

This project demonstrates how Microsoft Fabric and PySpark can be used to analyze QA automation test execution results.

The solution loads test execution data into a Fabric Lakehouse, performs data analysis using PySpark, and generates visual insights to help identify quality trends.

---

## Technology Stack

- Microsoft Fabric
- Lakehouse
- PySpark
- SQL
- Data Visualization

---

## Project Assets

- PySpark Notebook: `qa_test_analysis.ipynb`
- Microsoft Fabric Lakehouse
- Synthetic QA Test Execution Dataset
- Lakehouse Tables
- Build-wise Quality Analysis
- Top Failing Tests Analysis
- Slowest Tests Analysis
- Visualizations and Charts

---

## Architecture

```text
Initial Test Results CSV
            ↓
Microsoft Fabric Lakehouse
            ↓
PySpark Notebook
            ↓
Data Exploration & Validation
            ↓
Synthetic QA Test Dataset Generation
            ↓
test_executions Lakehouse Table
            ↓
PySpark Transformations & Aggregations
            ├── Build-wise Pass Percentage
            ├── Top Failing Tests Analysis
            └── Slowest Tests Analysis
            ↓
Analytics Tables
            ↓
Charts & Visualizations
```

---

## Analytics Implemented

### 1. Build-wise Pass Percentage

Calculates the pass percentage for each build to assess build quality and identify stable builds.

### 2. Top Failing Tests

Identifies the test cases contributing the highest number of failures, helping teams prioritize investigation efforts.

### 3. Slowest Tests Analysis

Highlights test cases with the highest average execution duration to identify execution bottlenecks.

---

## Key Fabric Concepts Used

- Workspace
- Lakehouse
- Notebooks
- Files
- Tables
- Data Visualization
- Data Storage and Management

---

## Key PySpark Concepts Used

- DataFrames
- Data Ingestion
- Filtering
- Aggregations
- GroupBy Operations
- Calculated Metrics
- Data Persistence
- Table Creation

---

## Skills Demonstrated

- Microsoft Fabric
- PySpark
- Data Engineering Fundamentals
- Data Analysis
- Data Visualization
- SQL
- ETL Concepts
- Lakehouse Architecture
- KPI Calculation
- Analytical Reporting
- QA Metrics Analysis
- Troubleshooting and Data Validation

---

## Sample Insights

- Build quality trends
- Pass percentage by build
- Failure hotspots
- Execution bottlenecks
- Test stability monitoring
- Identification of high-risk test cases

---

## Learning Outcomes

Through this project I gained hands-on experience with:

- Microsoft Fabric Lakehouse
- PySpark Data Processing
- Data Visualization
- QA Analytics
- SQL-based Data Exploration
- Table Management
- Data Aggregation Techniques
- Analytical Dashboard Development

---
## Screenshots

### Lakehouse

![Lakehouse](screenshots/lakehouse.png)

The Microsoft Fabric Lakehouse used to store raw files and processed tables.

---

### Build-wise Pass Percentage Analysis

![Build-wise Pass Percentage Analysis](screenshots/build-summary.png)

Build quality analysis showing total tests, passed tests, and pass percentage for each build.

---

### Top Failing Tests

![Top Failing Tests](screenshots/top-failing-tests.png)

Analysis of test cases with the highest number of failures, helping identify failure hotspots.

---

### Slowest Tests Analysis

![Slowest Tests Analysis](screenshots/slowest-tests.png)

Average execution duration analysis used to identify test execution bottlenecks and optimization opportunities.

---
## Project Workflow

1. Created a Microsoft Fabric workspace and Lakehouse.
2. Uploaded sample QA test execution data as a CSV file.
3. Read and analyzed the CSV using PySpark DataFrames.
4. Generated a synthetic QA test execution dataset using PySpark.
5. Persisted the dataset as a Lakehouse table (`test_executions`).
6. Performed build-wise quality analysis.
7. Identified top failing test cases.
8. Calculated average execution duration for each test case.
9. Created visualizations for quality reporting and analysis.
10. Stored aggregated results in Lakehouse tables for reuse.

---

## Future Enhancements

- Flaky Test Detection
- Automated Data Pipelines
- Power BI Dashboard Integration
- Historical Trend Analysis
- Defect Analytics Integration
- Real-time Test Execution Monitoring
- CI/CD Analytics Integration

---

## Conclusion

This project demonstrates an end-to-end QA analytics workflow using Microsoft Fabric and PySpark. The solution showcases how test execution data can be transformed into actionable insights that help engineering teams monitor quality, identify failure hotspots, and optimize test execution performance.
