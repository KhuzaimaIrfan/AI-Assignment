# AI-Assignment
Healthcare Data Analysis & ODE Simulation Assignment Summary
You are tasked with cleaning and analyzing anonymized patient data and simulating a basic health model:

# (Q1) Outlier Detection & Feature Reduction 

Remove constant features using VarianceThreshold

Detect and remove outliers in CholesterolLevel

Handle missing values

# (Q2) Data Visualization 

Box plot: BloodPressure vs. RiskCategory

Count plot: Patient count per RiskCategory by Region

# (Q3) Statistical Testing 

One-sample t-test on CholesterolLevel (is mean ≠ 200 mg/dL?)

Chi-square test: Is there a link between Region and RiskCategory?

Include hypotheses, test stats, p-values, and interpretations

# (Q4) ODE Health System Simulation 

Solve: dC/dt = k(D - C) with k=0.1, D=100, C(0)=0

Solve from t=0 to 50 using both odeint and solve_ivp

Plot and compare the results of both methods
