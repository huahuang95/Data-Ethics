# Data-Ethics
## US Income Tax Audit Algorithms
Team project for Data Ethics (BA840)

### Data Source
- [IRS Audit Rates by County from ProPublica](https://www.propublica.org/datastore/dataset/irs-audit-rates-by-county)
- [Tax Return Data by County from IRS](https://www.irs.gov/statistics/soi-tax-stats-county-data)
- [US Census Demographic Data from Kaggle](https://www.kaggle.com/muonneutrino/us-census-demographic-data)

### Project Objectives
- Inspect the fairness of the IRS (Internal Revenue Service) audit algorithm. We would like to know:
  - What factors lead to an increased chance of being audited?
  - What demographic factors are associated with higher audit rates?
  - Is the algorithm fair in how it assigns audits? 

### Methods
- Language: Python
- Exploratory data analysis for fairness analysis
  - Gender analysis
  - Race analysis
  - Income analysis
  - Unemployment analysis 
  - Professionals analysis
- Decision Tree

### Project Summary
- We examined the distribution and relationship between the audits and the demographic variables (race, gender, income level, etc) and applied **decision tree** for predicting audit rates. We found that race and socioeconomic status could be the proxy variables in the audit algorithm, even though the algorithm does not explicitly consider them. 
- In terms of consequentialism and deontology:
  - Consequentialism:
    The algorithm doesn't result in a good outcome on balance. Lower-income taxpayers face a higher chance of an audit. If the audit algorithm is unfair, it will result in certain groups of people will be treated unfairly in terms of time input in filing tax return documents.
  - Deontology:
    From the perspective of deontology, the algorithm seems not consistent with moral rules. People have the rights to be treated equally; an unfair audit algorithm will against that right, especially when a high audit rate could be an indicator of less trust towards the specific minority.

*By Agnes(Tzuhua) Huang, Roozbeh Jafari, Scott McCoy, Shuyi Zhu*
