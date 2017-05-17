# Marker-genes
The provided files contain marker genes predicted using our marker tools
MGFM (Marker Gene Finder in Microarray data) or MGFR (Marker Gene Finder in RNA-seq data), which are available from the Bioconductor website.

predicted-marker-genes.xlsx - Detected marker genes for 16 normal tissues:
this file includes marker genes detected by MGFM only, marker genes detected by MGFR only, and the common marker genes (i.e. detected by both tools).

Novel-candidate-marker-genes.xlsx - Novel candidate marker genes:
this file includes the suggested novel candidate marker genes for each of the 16 examined tissues. These genes were predicted by both tools MGFM and MGFR. Searching for the gene symbols of these marker genes (and their synonyms) in association with the corresponding tissue in NCBI PubMed (http://www.ncbi.nlm.nih.gov/pubmed, all publications until March 29, 2017) yielded no publications. The marker genes are ranked according to their specificity using a combined score based on the specificity scores of MGFM and MGFR.

Glomeruli_robust_marker_genes.xlsx:
this file includes glomeruli robust marker genes for each of the examined kidney diseases ranked using a score ranging from 0 to 100, which is the number of times a gene was selected as a marker. 

Tubulointerstitium_robust_marker_genes.xlsx:
this file includes tubulointerstitium robust marker genes for each of the examined kidney diseases ranked using a score ranging from 0 to 100, which is the number of times a gene was selected as a marker. 

Marker_Genes_Diseased_Glomeruli.xlsx:
this file includes glomeruli marker genes for each of the examined kidney diseases obtained in the run with the best classification accuracy. 

Marker_Genes_Diseased_Tubulointerstitium.xlsx:
this file includes tubulointerstitium marker genes for each of the examined kidney diseases obtained in the run with the best classification accuracy. 
