# Design decisions when Deploying Azure Sentinel
There are several design decisions, which, when taken in advance would considerably speed up the deployment time.

Key Decisions:
1. Which data sources to onboard?
1. Which Threat Intellegence (TI) sources to add?
1. What are the different access levels the SOC should have(RBAC)?
1. What would be the average data ingestion per day and what would be the retention period(pricing)?
1. Which geographical location would the data be stored in (data residency)?
1. Which actions should generate alerts?
1. Which actions should generate incidents?
1. Which dashboards/ workbooks would make the SOC more effective?
1. What action should be taken after an alert/incident is generated(SOAR)?


## Which data sources to onboard?
Azure Sentinel has several in-bult connectors that can be accessed right from the console. 

:::image type="content" source="images/Dataconnectorslist.png" alt-text="Data Connectors in Azure Sentinel":::




