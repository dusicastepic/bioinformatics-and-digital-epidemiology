# DigitalEpidemiology
Project for digital epidemiology class



DRAFT STEPS (Until she sends the text of the assignment):

    - Download Data (Thyroid cancer data)  
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




https://portal.gdc.cancer.gov/repository?facetTab=cases&files_offset=180&filters=%7B%22op%22%3A%22and%22%2C%22content%22%3A%5B%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22cases.primary_site%22%2C%22value%22%3A%5B%22Thyroid%20gland%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22cases.project.program.name%22%2C%22value%22%3A%5B%22TCGA%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22cases.project.project_id%22%2C%22value%22%3A%5B%22TCGA-THCA%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.analysis.workflow_type%22%2C%22value%22%3A%5B%22HTSeq%20-%20FPKM%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.data_category%22%2C%22value%22%3A%5B%22Transcriptome%20Profiling%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.data_type%22%2C%22value%22%3A%5B%22Gene%20Expression%20Quantification%22%5D%7D%7D%5D%7D
