# water-risk-solution-accelerator

## TODO: Update Intro with Link to Blog

## Solutions Acelerator Notebooks
The goal of this repository is to serve as a solution accelerator for potential users of Divirod's data to become 
familiar with the data available. There are three notebooks in this accelerator repo. There are three notebooks in this 
repository, each with a slightly different purpose.
* Solution Accelerator Part 1 - The purpose of this notebook is to provide transparency for customers as to how Divirod uses the Databricks platform in combination with Spark streaming to couple low latency with high standards for data quality checks. Divirod continuously ingests, standardizes, and quality checks 30 million water measurements daily across 20,000 + locations from providers around the globe using Spark Streaming; this notebook is mean to give a glimpse as to how we do that, and give customers confidence in our data processing pipeline.

* Solution Accelerator Part 2 - The goal of this notebook is to demonstrate how the data in Divirod's data lake can be used to calculate thresholds for abnormal water level conditions. The workflow outlined in this notebook is currently implemented by Divirod, and is just one of many possible workflows that customers can build using Divirod's data platform. Customers can either access this dataset directly from Divirod or define customized workflows in a similar manner more tailored to their specifically defined risk thresholds.

* Solution Accelerator Part 3 - The goal of this notebook is to demonstrate how users can implement outlier detection workflows on top of water level data in order to notify decision makers of the occurrence of abnormal water levels in real time. The examples in this notebook pull from Divirod's Water Level Index (WLI) - an in-house water risk scoring system. The WLI score is calculated each day and indicates where the latest water level measurement falls in relation to historical measurements from that gauge. This index can be used as an indicator for when current water levels are either extremely high or extremely low when compared to historical trends. The WLI interactive map and methodology document can be found [here](https://wli.divirod.com/).

