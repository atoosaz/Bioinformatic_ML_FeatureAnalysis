# Bioinformatic_ML_FeatureAnalysis
finding features that are associated with the "type". Selecting the top 50 features that are highly associated with the "Tumor" or "Normal" label, performing clustering using these features, and create a heatmap.


· The file "TCGA-BRCA.htseq_fpkm-uq_gene_name.tsv" contains cancer gene expression data. Note that in bioinformatics datasets, features (genes) are represented in the row and samples are in the column. Therefore, in the file, each row represents a different feature, and each column is a sample.

· The file "TCGA-BRCA.pheno.tsv" contains information about the samples. Specifically, the column "type" tells you if a sample is "Tumor" or "Normal".

· Your task is to find features that are associated with the "type". Select the top 50 features that are highly associated with the "Tumor" or "Normal" label, perform clustering using these features, and create a heatmap.

· Note that not all samples are present in both files. You will need to first subset the samples that are present in both files.

· Write a report (maximum 2 pages), briefly describing your approach. Also, cite research papers that support your findings. Put figures and references in the report. The file should be named "feature_analysis_YourName.pdf".

· Also submit the output table (in csv format) of your top 100 features. The files should be named "feature_result_YourName.csv"
