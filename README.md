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

## Project Architecture

Test Results CSV
        ↓
Fabric Lakehouse
        ↓
PySpark Notebook
        ↓
Data Transformations
        ↓
Analytics & KPIs
        ↓
Charts & Visualizations

---

## Analytics Implemented

### 1. Build-wise Pass Percentage

Calculates the pass percentage for each build to assess build quality.

### 2. Top Failing Tests

Identifies the test cases contributing the highest number of failures.

### 3. Slowest Tests Analysis

Highlights test cases with the highest average execution duration.

---

## Key Fabric Concepts Used

- Workspace
- Lakehouse
- Notebooks
- Tables
- Data Visualization

---

## Key PySpark Concepts Used

- DataFrames
- Filtering
- Aggregations
- GroupBy
- Calculated Metrics
- Table Persistence

---

## Sample Insights

- Build quality trends
- Failure hotspots
- Execution bottlenecks
- Test stability monitoring

---

## Learning Outcomes

Through this project I gained hands-on experience with:

- Microsoft Fabric Lakehouse
- PySpark Data Processing
- Data Visualization
- QA Analytics
- Table Management
