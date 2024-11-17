grn-ms-code R Markdown file including code for: 

### Identification of DE genes for RNA-seq datasets/Tissue ###

1. Raw read count normlization: edgeR TMM method for calculating CPM and FPKM values.
2. Get an expressed gene list for all samples/tissue
3. Run DEseq2 on all mutant alleles x W22 control/ tissue, not each mutant allele x W22 separately to determine if any genes could be DE due to genetic differences between the control W22 r-g colorless and UniformMu color-converted W22. 
4. PCA plots: Expressed genes/Tissue that were not DEG between all mutant alleles and W22 control in the 3 tissues: imbibed embryo, tassel stem and seedling leaf tissues were used for PCA analysis
5. DEseq on all genes/tissue for each mutant allele (3 biological replicates) x W22 (3 biological replicates)

### Enrichment for shared DEGs between multiple independent mutant alleles (Figure S2) ###

### Enrichment for TF predicted targets ###
1. GO term enrichment of DEGs
2. Enrichment of TF DEGs as GCN predicted target genes 
3. GCN predicted targets fold change enrichment

### Identifying TF binding sites in Y1H promoter cloned regions of MYB40 and HSF24 ### 
No code, just further description and input file included.

### Morphological field measurements ###

### Phenolic profiling with targeted LC-MS- Meatbolite data analysis ###
