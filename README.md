# Network-Based Data Analysis of Alzheimer’s Disease Pathology

This project applies a network-based approach to analyze the pathology of Alzheimer’s disease (AD) using gene expression data from autopsied temporal cortical samples. The study used the GSE106241 dataset, with samples categorized into control and affected groups based on Braak's staging to understand neural network alterations associated with AD.

## Dataset
The dataset, GSE106241, includes 71 autopsied samples categorized by Alzheimer's disease pathology. These are grouped into control and affected samples, providing insight into the severity of the disease.

## Technologies Used
- **Languages**: R
- **Libraries**: `igraph`, `rScudo`, `caret`, `gprofiler2`, `hgu133a.db`, `AnnotationDbi`

## Analysis
- **PCA**: Principal Component Analysis (PCA) was used to visualize relationships between samples based on gene expression data.
- **Random Forest**: A Random Forest model was implemented to identify genes significant for distinguishing between control and affected groups.
- **LDA**: Linear Discriminant Analysis (LDA) demonstrated strong classification performance, accurately grouping samples.
- **Lasso and Ridge**: These techniques were used to enhance model generalization, with Lasso achieving the best results for feature selection.
- **Network Visualization**: Generated a network visualization to highlight distinct clustering patterns between control and affected samples.
- **Enrichment Analysis**: Performed pathway enrichment analysis to identify Alzheimer's disease pathways, providing insights into molecular mechanisms of AD.

## Results
The project identified key genes and pathways involved in Alzheimer's disease pathology. Notably, enrichment analysis highlighted the relevance of these genes in AD, suggesting potential biomarkers for further study.

## How to Run the Code
1. Install R and the required libraries: `igraph`, `rScudo`, `caret`, `gprofiler2`, `hgu133a.db`, `AnnotationDbi`.
2. Download the dataset from [GEO GSE106241](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE106241).
3. Run each script in the order provided to reproduce the analysis.
