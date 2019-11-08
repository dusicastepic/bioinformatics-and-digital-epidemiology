# DIGITAL EPIDEMIOLOGY Project
Project for digital epidemiology class 

LINK FOR THE DRAFT version of the report so we can work on it together:
https://docs.google.com/document/d/1-RDHhVe4pr0A3Oghtv0e14O2oW_r2nI5u2TSMpR1cLo/edit?usp=sharing

TO DO:

Banuska and Melis ----> if you agree to complete other tasks?

Check what I did and change if something is wrong or change whatever you prefer :) 
3. see the images for drawing the networks for C and N and we should **check the threshold values**; Joanna said that prof said around 500 genes
4. Compute the degree index and find the hubs (5% of the nodes with highest degree values)
5. Compare hubs sets related to the two condition (cancer, normal) and identify the hubs characterizing only cancer tissue.

After these steps we should all start with the report ;)
and we should make some meaningful conclusions XD





STEPS that **(will)** be performed in the project:

Done:
1. Download Data from https://portal.gdc.cancer.gov/ gene expression data (data category: Transcriptome Profiling; data type: Gene Expression Quantification; workflow type: HTSeq – FPKM) for Uterine Corpus Endometrial Carcinoma (Project ID: TCGA-UCEC) and select only patients for whom cancer and normal tissue files are available.

2. Identify Differentially Expressed Genes (DEGs) specifying the **thresholds setting**. Select the thresholds to obtain a subset of hundreds of genes: p-value should be less than or equal to 0.05 (it is suggested to apply a correction for multiple comparisons) and Fold Change greater than or equal to 1.2. 

To do:

3. Using only DEGs, compute the gene co-expression networks related to the 2 conditions (cancer, normal) considering:
o Pearson’s correlation;
o Binary adjacency matrix where aij=0 if |R|<0.7 (where R is the Pearson correlation coefficient).
4. Compute the degree index and find the hubs (5% of the nodes with highest degree values)
5. Compare hubs sets related to the two condition (cancer, normal) and identify the hubs characterizing only cancer tissue.
Produce a short report (4 pages) describing:
o the performed analysis (specify the used programming language, the available functions and, if necessary, those implemented);
o the obtained results;
o (if possible) for one or two genes identified in task 5 (hubs characterizing only cancer tissue), some reference papers where that(those) gene(s) is(are) studied in the context of the same disease.


blabla write prettier for Cv XD
    This task is about ide
    - Which genes are differentially expressed? Find them and show which and how many of them are
      differentially expressed.
      Fold Change is used to express that characteristic. And it should be at least 2 (??).
    - Perform t-test and FDR (False Discovery Rate) correction method
    - Make a Volcano plot with FDR and Fold Change
    - Make two networks; One for control group and one for treated group; where value of 1 in adjacency 
      matrix is when there is correlation(Pearson correlation coefficient) >0.7 between two genes 
      and 0 otherwise.
    - Make significant conclusions and check if there is paper claiming that some of those 
      genes are found relevant in that type of cancer.



Team members:
Dusica Stepic, Omirbanu Nurassilova & Melis Kaymaz 
  

