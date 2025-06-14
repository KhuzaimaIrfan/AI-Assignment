# AI-Assignment
Healthcare Data Analysis & ODE Simulation Assignment Summary
You are tasked with cleaning and analyzing anonymized patient data and simulating a basic health model:

# Outlier Detection & Feature Reduction (Q1)

Remove constant features using VarianceThreshold

Detect and remove outliers in CholesterolLevel

Handle missing values

# Data Visualization (Q2)

Box plot: BloodPressure vs. RiskCategory

Count plot: Patient count per RiskCategory by Region

# Statistical Testing (Q3)

One-sample t-test on CholesterolLevel (is mean ≠ 200 mg/dL?)

Chi-square test: Is there a link between Region and RiskCategory?

Include hypotheses, test stats, p-values, and interpretations

# ODE Health System Simulation (Q4)

Solve: dC/dt = k(D - C) with k=0.1, D=100, C(0)=0

Solve from t=0 to 50 using both odeint and solve_ivp

Plot and compare the results of both methods
