# DIGITAL EPIDEMIOLOGY Project
Project for digital epidemiology class 

   

STEPS that wewre be performed in the project:

1. Download Data from https://portal.gdc.cancer.gov/ gene expression data (data category: Transcriptome Profiling; data type: Gene Expression Quantification; workflow type: HTSeq – FPKM) for Uterine Corpus Endometrial Carcinoma (Project ID: TCGA-UCEC) and select only patients for whom cancer and normal tissue files are available.

2. Identify Differentially Expressed Genes (DEGs) specifying the **thresholds setting**. Select the thresholds to obtain a subset of hundreds of genes: p-value should be less than or equal to 0.05 (it is suggested to apply a correction for multiple comparisons) and Fold Change greater than or equal to 1.2. 

3. Using only DEGs, compute the gene co-expression networks related to the 2 conditions (cancer, normal) considering:
o Pearson’s correlation;
o Binary adjacency matrix where aij=0 if |R|<0.7 (where R is the Pearson correlation coefficient).
4. Compute the degree index and find the hubs (5% of the nodes with highest degree values)
5. Compare hubs sets related to the two condition (cancer, normal) and identify the hubs characterizing only cancer tissue.
Produce a short report (4 pages) describing:
o the performed analysis (specify the used programming language, the available functions and, if necessary, those implemented);
o the obtained results;
o (if possible) for one or two genes identified in task 5 (hubs characterizing only cancer tissue), some reference papers where that(those) gene(s) is(are) studied in the context of the same disease.

 


Team members:
Dusica Stepic, Omirbanu Nurassilova & Melis Kaymaz 
  

