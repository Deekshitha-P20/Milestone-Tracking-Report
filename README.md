# Milestone Tracking & Cost Comparison

**📌 Overview:**
This project is a solution to a real-world data analytics challenge focused on handling incomplete and ambiguous data in project tracking and estimated cost analysis.
The objective was to design robust logic and a data model capable of extracting meaningful insights from datasets where key fields (milestones and estimated amounts) contained inconsistencies such as blank or missing values.

**💡 Tools & Skills**
  - Data Modelling
  - DAX / Analytical Logic
  - Data Cleaning & Transformation
  - Business Problem Solving
  - Time-Based Analysis

---

**🚩 Problem Statement:**
The challenge involved two major analytical problems:

1. Milestone Tracking Challenge
Each project consists of multiple milestones. Blank values could indicate either:
  - A pending milestone. Or a non-applicable/skipped milestone.
  - This ambiguity led to incorrect progress calculations.
✅ Goal:
Accurately determine:
  - The actual number of relevant milestones, and the true project completion stage

2. Estimated Cost Analysis & Period Comparison
Cost data required classification into: Direct Costs and Indirect Costs
  Required dynamic calculation of:
  - Current Period values
  - Previous Period values
  - Cumulative (To-Date) values
  - All calculations needed to adapt based on user-selected filters (time and status).


**⚙️ Approach -**
  - Designed logic to differentiate between valid and irrelevant milestones based on milestone sequence and completion patterns
  - Built calculations to determine the last completed milestone and exclude non-applicable entries
  - Implemented business rules for cost categorisation
  - Created time-based dynamic measures for period comparisons
  - Structured the dataset to support accurate and scalable analysis


**📊 Key Learnings -**
  - Handling missing vs. non-applicable data scenarios
  - Translating business rules into analytical logic
  - Designing robust calculations for edge cases
  - Implementing time-intelligence logic for Cost Analysis & Period Comparison
  - Building reliable insights from imperfect datasets

---


**🔗 Dashboard**

<img width="1669" height="1125" alt="image" src="https://github.com/user-attachments/assets/af89f98b-1e59-4a6f-8b6c-1262dcc1606b" />

<img width="1669" height="1125" alt="image" src="https://github.com/user-attachments/assets/a9058b83-a0af-41f0-8b93-c15b197b307c" />
