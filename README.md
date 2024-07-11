# Freelancer Project: Assess sensitivity of different biological age accerlations in response to smoking status
## Design a comprehensive analysis pipeline for client involving multivariate linear regression

Main Language: R

- Project description: The purpose of this project is to evaluate the sensitivity of biological age acceleration estimates calculated via different aging clocks in response to smoking, considering a range of covariates covering lifestyle, diet and demographic background.

- Main Contents:
  - Cohort Characterisation: Key variables description (Table + Graph)
  - Linear Regression Model Fit
    - Basic Model: Age_acc ~ smoking + age + gender
    - Extended Model: Age_acc ~ smoking + age + gender + other_covariates
  - Interaction Analysis: to determine if the effect of smoking on biological age acc differs by cronological age and gender
  - Sensitivity Analysis using alternative smoking measures (for current smokers only)
