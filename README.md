# Project Name
GRADIENT (GRAphical Disease Insight for Effective Treatment)

# Goal

This project aims at reviewing the quality drugss used for treatment of diseases and identifying if the prescribers are using low rated drugs by leveraging the TigerGraph.


# Repo Structure

# Dataset
- [Drug Bank Ids](https://go.drugbank.com/releases/latest#open-data)
- Stanford Biosnap dataset
    - [Disease Synopsis](http://snap.stanford.edu/biodata/datasets/10003/10003-D-MeshMiner.html)
    - [Disease-Drug associations](http://snap.stanford.edu/biodata/datasets/10004/10004-DCh-Miner.html)
- [Medicare Part D Prescribers - by Provider and Drug](https://data.cms.gov/provider-summary-by-type-of-service/medicare-part-d-prescribers/medicare-part-d-prescribers-by-provider-and-drug/data)

# Design 

- Analyzing the dataset and understanding the requirements

- [Input - Data Source] => [ETL Process] => [Graph Creattion Process] => [Graph Query & Analysis] => [Output - Insights]

# Development 

## Fetch dataset

## Create Graph

# Deployment

## load the graph in tg cloud

# Executon 

## run the query in tg cloud
```
Add your steps here
```

![](images/graph_environment1.png)

# Analysis

*Disclaimer*
- Following reports have been generated from research datasets (links specified in Reference section) and are only for demonstrative purpose. 

## Find the doctors prescribing low rated drugs for different diseases 
- Sample Query 
```
Add your query here
```
- Output Graph
![](images/analysis1a.png)

- Obsrvation

Prescriber Sub Graph for given disease

![](images/analysis1b.png)
    
## Find the diseases being treated with low rated drugs
- Sample Query 
```
Add your query here
```
- Output Graph
![](images/analysis2a.png)

- Obsrvation

Drill down into a specific disease

![](images/analysis2b.png)

## Find top prescribers treating diseases with top-rated drugs

- Sample Query 
```
Add your query here
```
- Output Graph
![](images/analysis3a.png)

- Obsrvation

Drill down into a specific prescriber

![](images/analysis3b.png)

## Find similar prescriber groups treating similar diseases
- Sample Query 
```
Add your query here
```
- Output Graph
![](images/analysis4a.png)

- Obsrvation

## Find which drugs are used to treat most number of dieases
- Sample Query 
```
Add your query here
```
- Output Graph
![](images/analysis4a.png)

- Obsrvation

## Find which diseases use most number of drugs
- Sample Query 
```
Add your query here
```
- Output Graph
![](images/analysis4a.png)

- Obsrvation

# Future Work


# Useful Tips

# References
