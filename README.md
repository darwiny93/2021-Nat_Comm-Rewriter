# 2021-Nat_Comm-Rewriter

Sample analysis for Rewriter genomic editing of HEK293T cells. The DADA2 R package is used to filter, denoise, and merge paired-end reads. Edited alleles are identified using exact matching to reference sequence containing the surrogate mutation encoded by Rewriter components. Inputs are Illumina NGS fastq files from targeted amplicon sequencing of editing genomic loci. Output file is a .csv table containing the total number of alleles, the count of edited alleles, and the editing efficiency value for each sequencing library.

To run, clone the repository and execute the R markdown script in RStudio. Estimated time to run on a standard desktop computer is 30 minutes.

Code was run using RStudio and R version 4.03.
