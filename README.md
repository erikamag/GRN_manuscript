# GRN Manuscript Supplemental Tables and Data Files

**Table S1. 32 Maize TF mutant alleles isolated from the UniformMu population to test GRN predictions.** Mutant allele transcriptome data obtained, UniformMu Mu ID and Stock, Pos: Mu insertion position within the gene, Pedi: pedigree of the mutant stock sampled for RNA-seq (BC = backcross, S = self), and PDI: protein-DNA interaction prediction method. RNA-seq CPM and FPKM for TF mutant and wild-type W22, DE data averaged across biological replicates (N), log2fc: log2 fold change of mutant to control, lfcSE: log fold change standard error and FDR adjusted p-value. Data for TF genes that are that are DE in the mutant compared to the wild-type are highlighted. 

**File S1. Differentially expressed genes for each TF mutant allele.** Up- and down-regulated DE genes (log2fc ≥ 1 and FDR adjusted p-value < 0.05) for each mutant allele and those shared by multiple independent alleles per TF in this study.

**File S2. Morphological traits measured for a subset of TF mutant alleles.** Morphological traits were measured for 12 mutant alleles in two different fields during one field season. Measurements for two plant architecture traits (measured in cm): plant height (PHT) and ear height (EHT) and two flowering time dates: days to tassel shedding (DTT) and days to ears silking (DTE) are recorded for each mutant row and multiple W22 control rows per field (X-6 or X-7). Significance test (unpaired t-test, FDR adjusted p-value < 0.05) results for log transformed PHT and EHT values between each mutant row and the combined W22 control rows within a field are included. 

**File S3. Metabolite data for 24 phenolic compounds in 32 TF mutant alleles.** The first sheet contains the raw LC-MS data arbitrary units of area (AUA) and limits of detection (LOD) for each phenolic compound per genotype, biological replicate and LC-MS batch (1 or 2). The mean AUA and standard deviation for the three biological replicates are included. AUA was log2 normalized for statistical analyses. The second sheet, log2 AUA t-test, contains the unpaired t-test statistic, raw p-values, and FDR adjusted p-values for each mutant allele compared to both controls: W22 r-g or UniformMu W22 (ufmu). Significance (FDR adjusted p-value < 0.05) is denoted by an asterisk (*) and not significant (ns).

**File S4. Significant hypergeometric enrichment of GO terms associated with TF mutant allele differentially expressed genes.** The subset (n) of TF mutant allele up- or down-regulated DEGs (B73v4 and W22 gene IDs recorded) with a significant GO term enrichment (hypergeometric, p-value < 0.05).

**File S5. Predicted targets from GCN and Y1H methods for all transcription factors in this study.** TF-target predictions are listed by prediction method: y1h; Y1H screen, n1; 1/45 GCNs, and/or n3; 3/45 GCNs. For TFs with Y1H predictions, total targets (n) represent all B73v4 target genes. For TFs with GCN predictions, total targets (n) represent a subset of the predicted B73v4 targets that have an annotated W22 gene model and are expressed (CPM ≥ 1 in at least one sample/tissue). 

**GEO Series:GSE280139** includes meta data for raw RNA-seq data deposited to **NCBI BioProject: PRJNA936808** and processed gene expression data. 

**Code** directory contains an RMarkdown file with all the code used in the manuscript
