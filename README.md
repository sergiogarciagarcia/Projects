# Projects
In this section, you can find the list of the relevant projects where I was key contributor as part of small teams or that I developped on my own

ENERGY PREDICTION (November 2020)

https://app.powerbi.com/view?r=eyJrIjoiMGY0M2QxYzYtNDg5ZC00MDMzLWE1MDAtMjIxMTc4MmI2NDNjIiwidCI6IjkzZjMzNTcxLTU1MGYtNDNjZi1iMDlmLWNkMzMxMzM4ZDA4NiIsImMiOjZ9

In a small squad of 4 poeple (PO, Data Science, Data Analyst, AI Engineer), for 2 weeks partial time, we worked on a MVP to build a Prediction Model for Energy consumption for Germany regions. 
The purpose was to predict the amount of energy to be generated in 40 energy stations to meet demand, and reduce as much as possible overconsumption (waste), as well as underconsumption (need to buy energy to third parties)

Solution consisted of 2 parts: 
1) Prediction Model:
The Model was built using Azure Machine Learning Studio to develop a prediction model using Azure Notebook. From the data from previous year, several prediction models were developped:
==> Holt-Winters Seasonal ad-hoc development 
==> AutoML solution from Azure

The solution contained 2 data feed options:
- Bulk data generation that could be consummed
- REST API endpoint that could be consume on demand (real-time)

The solution based on historical data achieved > 0.94 accuracy on test data, while the business objective was 0.90.

2) Data Visualization:
Data Visualization Dashboards was built on Power BI, connecting to Azure Blob Storage shared with Azure Machine Learning Studio (placeholder of the bulk data generated) 

The Dashboards were dynamically populated and represent the data in multiple ways that enable attention to diferent aspects for decision making. 


