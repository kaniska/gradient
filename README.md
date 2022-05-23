

# Project Details




# Template for TigerGraph Graph for All Challenge Submissions
Use this template for your project submisison and edit the README following the text below. Add your project code and data (if public) to the repository. 

# Project Title
- GRADIENT (GRAphical Drugs and Disease Insight for Effective Treatment)

**Contributers and Contact Information:**
- Kaniska Mandal
  - kaniska.mandal@gmail.com
  - https://www.linkedin.com/in/kaniskamandal/

- Tyrone Hou
  - tyroneh@bu.edu
  - https://www.linkedin.com/in/tyronehou/

**Problem Statement**

It's extremely important to identify the drugs which are not suitable due to adverse effetcs and verify if the high cost justifies the quality.
This kind of Drug applicability monitoring solution is not available in healthcare. This is a time-sensitive issue. It's very important to use Drug Ratings data and User reviews data in order to find the problems. The prescribers and insurance companies also need such insights in order to understand if any Drugs with anomalous behaviour being recommended.


**Description**: 

This project aims at developing functionalities using TigerGraph which can help review the quality of drugs used for treatment of diseases and identify potential anomalies like if the prescribers are using low rated drugs. Our goal is to improve healthcare by extracting useful insights from the usage of drugs, discovering anomalies and help saving lifes. 

- Link to Video: https://www.youtube.com/watch?v=-ZwvVojbIfo&t=2s
- Link to Project Report: https://github.com/kaniska/gradient/blob/main/GRADIENT_Project_Report.pdf

- Impactful observation in solving a real world problem 
  - Find the doctors prescribing low rated drugs for different diseases

- Innovative use case of graph

We mainly focussed on joining multiple tabular datasets (drug-diease, drug-rating, drug-prescriber) and represeting the connected data in a cohesive graph.

  - Find the Drugs Most prescribed by Prescribers 
  - Find which drugs are used to treat most number of diseases
  - Find the diseases being treated with low rated drugs
- Applicable graph solution 

**Disclaimer**
- Following reports have been generated from research datasets (links specified in Reference
section) and are only for demonstrative purposes.

 - **Data**:
  ● Drug Bank Ids
  https://go.drugbank.com/releases/latest#open-data
  ● Stanford Biosnap databases
  Disease Synopsis
  http://snap.stanford.edu/biodata/datasets/10003/10003-D-MeshMiner.html
  ● Disease-Drug associations
  http://snap.stanford.edu/biodata/datasets/10004/10004-DCh-Miner.html
  ● Medicare Part D Prescribers - by Provider and Drug
  https://data.cms.gov/provider-summary-by-type-of-service/medicare-part-d-prescribers/m
  edicare-part-d-prescribers-by-provider-and-drug/data
 
 - **Technology Stack**:
 
  - TigerGraph Studio was used for executing GSQL queries to extract insights.
  - Jupyter Notebook was used to run pytigergraph library and connecting to 
 
 - **Visuals**:
 
 https://github.com/kaniska/gradient/blob/main/GRADIENT_Project_Report.pdf

## Dependencies

- pandas  
- pytigergraph

## Installation

This can include:
1. Clone repository
2. Login to Tigergraph Account and verify Graph Studio is accessible
  - https://gradient-test.i.tgcloud.io 
  - user: public_access 
  - pwd: public_access
4. Run the Notebooks
- https://github.com/kaniska/gradient/tree/main/notebooks


## Future Improvements

● Overall we have established a solid foundation for developing interesting features and
discovering many anomalies which can improve healthcare and save lives.

● Cluster the Prescriber and providers based on drugs prescribed.

● We have already identified prescribers recommending low rated drugs which are also
very costly for example related to HIV Treatments.

● We would like to create a cluster of such prescriber-drug-disease groups.

● There is a great opportunity to find if banned drugs and drugs with adverse effects are
being used.

● Check if any low rated drugs are being prescribed to age group > 65
Find similar prescribers based on the drugs prescription.

● Find social sentiment and usefulness of drugs by mining the review dataset (using NLP)
and then enrich the Graph.

● Find Adverse Drug Events and Key Terms from the Review Notes and link them to the
Drug Node in Graph.

● We want to capture time as a node in our graph in order to show how the price and
rating of drugs change over time.

● We want to leverage Data Science Algorithms like
https://docs.tigergraph.com/graph-ml/current/classification-algorithms/k-nearest-neighbor
s and
https://docs.tigergraph.com/graph-ml/current/similarity-algorithms/jaccard-similarity-of-ne
ighborhoods-batch


## References

- https://docs.tigergraph.com/home/
- http://snap.stanford.edu/biodata/datasets/10003/10003-D-MeshMiner.html
- http://snap.stanford.edu/biodata/datasets/10004/10004-DCh-Miner.html
- https://data.cms.gov/provider-summary-by-type-of-service/medicare-part-d-prescribers/m
edicare-part-d-prescribers-by-provider-and-drug/data
