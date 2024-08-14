## A scientific article about Bayesian Networks using continuos variables to calculate the probability of a person having chronic kidney disease (CKD).

# General information
This project focuses on the application of Gaussian Bayesian Networks (GBNs) to model [Chronic Kidney Disease (CKD)](https://www.kidney.org/kidney-topics/chronic-kidney-disease-ckd), exploring both linear and nonparametric modeling approaches. The aim is to identify risk factors and predict disease progression by comparing these models, with the goal of determining which best fits the data.

# Project Structure 
**Data Collection** Data from interviews with health experts were used to build the networks.

**Modeling**

-Linear Gaussian Bayesian Network: Models linear relationships between continuous variables using Gaussian distributions.

-Nonparametric Bayesian Network: Captures more complex and nonlinear relationships between continuous variables.
<p align="center">
  <img src="https://github.com/user-attachments/assets/5d3d07d7-bfc0-4e02-b271-cf53f7db8022" alt="imagen" width="400">
</p>

**Evaluation** The models were evaluated using BIC and AIC metrics, determining that nonparametric approaches performed better.

# Python
Used Python to clean the database for a sample of patients with and without CKD.

# R
Used R script to elaborate a DAG (Directed Acyclic Graph) which represents the dependence relationships of variables to determine whether a patient is prone to chronic kidney disease and to be able to detect it in time
