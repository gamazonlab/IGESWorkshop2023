# Workshop goals:

The following tutorial is designed to give an overview of single cell sequencing data analyses using the Seurat software procedure. 
Here, we address three main goals:
  - Perform QC analysis as well as dimensionality reduction
  - Identify cell types markers and clusters 
  - Compare the datasets to find cell-type and condition specific gene signatures


# Single cell data processing workflow

<img width="943" alt="Screen Shot 2023-10-12 at 10 59 05 PM" src="https://github.com/gamazonlab/IGESWorkshop2023/assets/59617853/5f93b165-6568-42da-b7ce-84304ed8fb4b">

# Post-clustering analysis
One approach after clustering is to perform differential expression analysis(DEG).
There are two different differential expression analysis:
      - Between clusters
      - Between experimental conditions

## Differential expression between clusters
This refers to finding the specific genes that are differentially expressed between clusters and allows identification of cell type markers that will be used for labeling.

## Differential expression between conditions
In this case, the goal is to identify those genes that are differentially expression between two experimental conditions such as (stimulated vs unstimulated cells) or between disease cases (covid) and healthy controls in specific cell type. 

## Gene Set Analysis
To learn more about function of the differentially expressed genes identified above, you can do gene set analysis by using hypergeometric enrichment test.


