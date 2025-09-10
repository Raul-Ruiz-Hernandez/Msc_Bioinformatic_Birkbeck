# Msc_Bioinformatic_Birkbeck
R code for data analysis
DATAsets (dgMatrices) FILES for HB6:
-	dn_filtered_feature_bc_matrix.h5:  https://www.ebi.ac.uk/biostudies/ArrayExpress/studies/E-MTAB-9544?query=E-MTAB-9544).
-	classical_filtered_feature_bc_matrix.h5:
 https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/544/E-MTAB-9544/Files/classical_filtered_feature_bc_matrix.h5
-	naive_filtered_feature_bc_matrix.h5:
https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/544/E-MTAB-9544/Files/naive_filtered_feature_bc_matrix.h5
- igmmem_filtered_feature_bc_matrix.h5:
https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/544/E-MTAB-9544/Files/igmmem_filtered_feature_bc_matrix.h5
-	trans_filtered_feature_bc_matrix.h5:
https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/544/E-MTAB-9544/Files/trans_filtered_feature_bc_matrix.h5

DATAset (Merger Seurat Object) FILES for HB6,HB34 & HB78 donors:
: https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/544/E-MTAB-9544/Files/scPure2_AllIntegrated.rds



ANALYSIS FILES:

(1) HB6.Thesis Analysis.Rmd:
To change the parameters of analysis, change on the section Experimental Parameters Been tested.
This File Contains at certain section (in brackets):
- Figure 1 (Section : Introduction subset paper/peripheral blood B cell scRNA-seq)
- Figure 2 (Section: CLUSTERING/Differential Gene Expression/By Sorted population).
- Figure 3 ( Section : QC. Filtering the raw (non-normalized data)/ Find variable Features: Selection of highly variable features/Before pruning Ig and TCR related genes)
- Figure 6.A&B ( section: Clustering representation)
- Figure 6.C ( section: Graph for purity each cluster (I) )

(2) HB6.Thesis Analysis.Supervised_Clustering.Rmd:
This File Contains at certain section (in brackets):
- Figure 5 (subsection: Comparison of Clustering Performance section).
- Supplementary_Fig_1.A (section: Graph for purity each cluster (I))
- Supplementary_Fig_1B&C ( section: Clustering representation)


(3) HB6.Thesis Analysis.Rmd:
This File Contains at certain section (in brackets):
- Figure 7 (Section4. AllHB_indep/Entropy scores/Overall entropy scores)
- Figure 8 (Section: 4.AllHB_indep/Create a Seurat Object with independant clustering all donor/ordered by subsets).
- Figure 9 (Section4. AllHB_indep/ DEI Clusters (AllHB_indep) / Fig5. poster)
- Supplementary_Table_2.A (Section4. AllHB_indep/ DEI Clusters (AllHB_indep) / Quantification Ig/TCR assocaited Gene Subgroups per Cluster)
- Supplementary_Table_2.B (Section4. AllHB_indep/ DEI Clusters (AllHB_indep) / Quantification Ig/TCR assocaited Gene Subgroups per Cluster)

(4) RCC_Samples_Thesis.Analysis.Rmd
This File Contains at certain section (in brackets):

- Figure 10 (section 1.Original paper file/represent UMAP object)
- Figure 11 (section 2.Full dataset Analysis./ CLUSTERING/Clustering representation).
- Figure 12 (section 2.Full dataset Analysis./Biological Identity of cluster found)
- Figure 13  (section 2.Full dataset Analysis./Biological Identity of cluster found/ Better defined clusters with the optimized pipeline)
- Figure 14 (section 2.Full dataset Analysis./Biological Identity of cluster found/ Better defined clusters with the optimized pipeline)
- Supplementary_Fig_3 (section 2.Full dataset Analysis./Biological Identity of cluster found/ Better defined clusters with the optimized pipeline)






