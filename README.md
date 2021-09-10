# Projects
In this section, you can find the list of the relevant projects where I was key contributor as part of small teams or that I developped on my own

ENERGY PREDICTION (November 2020)

https://app.powerbi.com/view?r=eyJrIjoiMGY0M2QxYzYtNDg5ZC00MDMzLWE1MDAtMjIxMTc4MmI2NDNjIiwidCI6IjkzZjMzNTcxLTU1MGYtNDNjZi1iMDlmLWNkMzMxMzM4ZDA4NiIsImMiOjZ9

In a small squad of 4 people (PO, Data Science, Data Analyst, AI Engineer), for 2 weeks partial time, we worked on a MVP to build a Prediction Model for Energy consumption for Germany regions. 
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




HR PROMOTION PREDICTOR (July 2021)

https://colab.research.google.com/drive/1a6pNxkgGBrbV4rKUhlMy-BLn-OwR0gAd

In a small squad of 3 people as part of AI BootCamp organized at DXC, we selected a business case from Kaggle to test the different steps in an AI project, to acquire some internal badges that validate the understanding of these aspects.
1) Industrialized AI Data Engineering => To build pipelines of data flows from/to data stores (MongoDB), as well as deploy Utility AI
2) Industrialized AI Data Scientist => To design and run experiments and perform AI Forensics
3) Industrialized AI Leader => To run an Agile Transformation and to Create Data Stories
Once all completed a Badge of Industrialized AI Master is achieved.

The exercise was focused on the use of Libraries that encapsulate diferent APIs from other Libraries (pytorch, ...)
https://github.com/dxc-technology/DXC-Industrialized-AI-Starter

The Business case was not a very good one because the data is not much reliable and there are cases where same data can represent as well a positive and a negative case. As missing data to enable a model to discriminate the result with quality was not achieved, this was used mainly for educational purposes. The imbalance dataset also represented an additional challenge that we had to overcome by selecting proper metrics (No Data Augmentation was used for this case)

Once the data cleansing, data store and experiments were run to get a conclusion, an Utility was built in Algorithmia (https://algorithmia.com/) for consumption.




