# Decisions Analytics

This repository gathers first decision datasets captured with ADS and ODM capabilities of IBM Cloud Pak for Business Automation.
It encompasses too python Jupyter notebooks that apply data science to these automated decisions to get business insights and understand what business rules and ML models have been used.

## Decision logics
We cover the following use cases:
   * Loan approval
   * Client loyalty program
   
## Datasets
For each business use case you find under [data](./data) the datasets of different sizes with the full decisions and the requests only.
Datasets are under ADS and ODM folder depending what tool has been used to automate the decisions.
Decisions and requests are serialized in JSON. For small sizes they are shared as regular files; And for larger ones they are shared in parquet. 

## Analysis of your decisions automated with Automation Decision Services
   * [Analyzing loan Approvals](https://nbviewer.org/github/DecisionsDev/decisions-analytics/blob/main/notebooks/ADS/ads-loanvalidation-analytics.ipynb)
   * [Analyzing loyalty program decisions](https://nbviewer.org/github/DecisionsDev/decisions-analytics/blob/main/notebooks/ADS/ads-loyaltyprogram-analytics.ipynb)
   * [Comparing loan approvals with tasks : V1 vs V2](https://nbviewer.org/github/DecisionsDev/decisions-analytics/blob/main/notebooks/ADS/ads-22.0.1-loanapprovalwithtasks-v1-vs-v2-5K.ipynb)

