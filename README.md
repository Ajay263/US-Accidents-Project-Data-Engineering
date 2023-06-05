# US ACCIDENTS -DATA ENGINEERING PROJECT ![alt text]([https://storage.googleapis.com/kaggle-datasets-images/199387/440241/412582fbce64eb8e7f25a8a029e4fee0/dataset-card.jpg?t=2019-05-21-00-08-38](https://github.com/Ajay263/Data-Engineering-Sources/blob/main/Terraform/img/accident.jpg))

# Problem statement

In many states across the country, car crashes are a major cause of fatalities and injuries. However, without proper knowledge of what might be causing these crashes, it can be difficult to develop effective strategies to reduce their occurrence. This is where analyzing the US car crash dataset can be incredibly valuable.

By analyzing this dataset, we can identify patterns and trends in car crashes, such as the most common types of crashes, the factors that contribute to crashes (e.g. weather conditions, road quality, driver behavior), and the geographic regions with the highest crash rates. Armed with this information, we can develop targeted interventions to reduce the number of crashes in high-risk areas and improve traffic safety overall.

For example, if we find that a particular intersection has a high rate of crashes, we can investigate potential causes (such as poor signage or confusing lane configurations) and implement changes to make the intersection safer. Similarly, if we find that a particular region has a high rate of crashes due to poor weather conditions, we can develop strategies to improve road maintenance and provide better weather-related information to drivers.


# Dataset

US car crash dataset (covers 49 states). Crash data is collected from February 2016 to December 2021 using various APIs that provide streaming traffic incident (or event) data. These APIs transmit traffic data captured by a variety of entities, such as US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors on road networks. There are currently around 2.8 million crash records in this dataset.


# Solution


A data engineering pipeline created using Prefect for orchestration to analyze the US car crash dataset, identify patterns and trends in car crashes, and develop strategies to reduce the number of crashes in high-risk areas and improve traffic safety overall. The pipeline can be designed to perform the following tasks:

1. Extract the US car crash dataset from Kaggle APIs that provide streaming traffic incident data and store it in Google Cloud Storage (GCS).

2. Transform the data using DBT to clean and prepare it for analysis. This will involve standardizing the data format, handling missing values, and combining data from different sources if necessary.

3. Load the cleaned data from GCS into BigQuery for analysis. This will involve configuring the pipeline to load the data into the appropriate storage solution and ensuring that the data is properly formatted for analysis.

4. Analyze the data using data visualization tools such as Looker Studio to identify patterns and trends in car crashes, such as the most common types of crashes, the factors that contribute to crashes (e.g. weather conditions, road quality, driver behavior), and the geographic regions with the highest crash rates.

5. Develop targeted interventions in high-risk areas and improve traffic safety overall based on the insights gained from the data analysis.

6. Create interactive dashboards using Looker Studio to allow stakeholders to explore the data and gain insights into the factors that contribute to crashes and the effectiveness of interventions.

