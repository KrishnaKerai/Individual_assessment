# Project Title

Using machine learning to identify Idiopathic pulmonary fibrosis (IPF) using gene expression data

## Description 

This projet analyses bulk RNA-seq gene expression data from patient derived lung tissue samples of IPF and healthy control patients. Differential gene expression analysis was carried out to identify significantly upregulated and downregulated genes between IPF and healthy controls. The genes are visualised using a volcano plot and used to train a supervised machine learning model. 

A k-nearest neighbours classifer was trained using a selected panel of differentially expressed genes to classify IPF compared to control. Model is tested using repeated train-test splits, and results are visualised using accuracy metrics and confusion matrices. This project allows the use of machine learning to analyse transcriptmoic data for disease classification. 

## Getting Start

### Dependencies 

This project was tested using a Windows 11 operation system and Python version 3.12 through Jupyter lab.

### Required Python Libraries 

The following imports are needed for this project and were installed using uv: pandas, mygene, seaborn, numpy, scipy.stats, statsmodels.stats.multitest, matplotlib.pyplot, sklearn. 

### Installing

Original dataset can be uploaded to the jupyter note book from the Gene Expression Omnibus (GEO) website using the accession number GSE213001. The project program can be found on the Differential_gene_expression_analysis_in_IPF notebook in jupyter lab. 

### Executing program 

The project program can be executed by running each cell from the Differential_gene_expression_in_IPF jupyter lab notebook. 

## Authors 

Krishna Kerai 
Email: KeraiK@cardiff.ac.uk 

##Licensing 

This project is licensed by the MIT lisense.

##Acknowledgemnts

This project was supported by the Jean Golding institution for the South West Biosciences doctoral training program.
The original data set is publically available through Jaffer. J et al 2022 PMID: 36299365. 
