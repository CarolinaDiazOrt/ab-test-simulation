# A/B Testing on Simulated Data

## Overview
This project demonstrates the design, simulation, and analysis of a basic A/B test using **synthetic data**.  
It replicates a common business scenario where an e-commerce company tests a new **Call-To-Action (CTA)** button against the current version to measure the impact on conversion rates and revenue.  

The workflow covers:
- Generating reproducible synthetic user-level data  
- Introducing heterogeneity (new vs. returning users, daily variability)  
- Analyzing conversion rates and ARPU (Average Revenue Per User)  
- Applying statistical tests to determine significance of observed differences  

The repository is intended as a clear, educational example suitable for a data science or analytics portfolio.

---

## Dataset Description
Each row in the simulated dataset represents one user visit. The key columns are:
- `user_id`: unique identifier for each user  
- `date`: simulated visit date  
- `group`: experiment assignment (A = control, B = treatment)  
- `is_new_user`: whether the user is new (1) or returning (0)  
- `converted`: binary outcome (1 = converted, 0 = not converted)  
- `revenue`: purchase amount (0 if not converted, >0 if converted)  

---