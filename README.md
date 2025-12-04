# Human-Structural-Variation-Alaysis
A collection of analysis scripts and workflows for studying structural variation and adaptive evolution in the human genome.

### 1. GO_Enrichment_Analysis

This project performs a **Gene Ontology (GO) enrichment analysis** for the genes located in the largest inversion in the human genome, **chr8p23.1** (approx. 4.5 Mb).  

The workflow includes:  
- Retrieving all genes in the inversion region from **Ensembl**  
- Visualizing gene positions along the chromosome  
- Performing GO enrichment analysis for **all gene biotypes**  
- Generating bar plots, dot plots, and network plots for enriched GO terms  
- Splitting enrichment results by ontology: Biological Process (BP), Cellular Component (CC), and Molecular Function (MF)  

All analyses are performed in **R** using packages like `biomaRt`, `clusterProfiler`, `enrichplot`, `org.Hs.eg.db`, and `gggenes`.

For the **full interactive analysis**, visit the website:  
[GO Enrichment Analysis Website](https://rashikaranasinghe.github.io/Human-Structural-Variation-Alaysis/)
