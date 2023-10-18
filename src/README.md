# Workshop goals:

The following tutorial is designed to give an overview of single-cell sequencing data analyses. We will illustrate the pipeline using the Seurat software. 
Here, we address three main goals:
  - Perform QC analysis as well as dimensionality reduction
  - Identify cell types markers and clusters 
  - Compare the datasets to find cell-type and condition specific gene signatures


# Single cell data processing workflow

<img width="943" alt="Screen Shot 2023-10-12 at 10 59 05 PM" src="https://github.com/gamazonlab/IGESWorkshop2023/assets/59617853/5f93b165-6568-42da-b7ce-84304ed8fb4b">

# Post-clustering analysis
One post-clustering analysis is to perform differential expression analysis (DEG).
There are two different types of differential expression analysis:
      1) Between clusters
      2) Between experimental conditions

### Differential expression between clusters
This refers to finding the specific genes that are differentially expressed between clusters and allows identification of cell type markers that will be used for labeling.

### Differential expression between conditions
In this case, the goal is to identify those genes that are differentially expressed between two experimental conditions such as (stimulated vs unstimulated cells) or between disease cases (e.g., COVID-19) and healthy controls in a specific cell type. 

## Gene Set Analysis
To learn more about the function of the differentially expressed genes identified above, you can do gene set analysis (e.g., by using hypergeometric enrichment test). In this case, we obtain the combined function of the DEGs between disease and control patients. 


