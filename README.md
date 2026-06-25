# skin-photoaging-rna-seq-analysis
RNA-seq differential expression analysis of UV-induced skin photoaging using Python
![Volcano Plot](volcano_plot.png)

## Background
This project analyzes RNA-seq differential expression data from UV-treated human dermal fibroblasts to investigate transcriptomic changes associated with skin photoaging. Because UV exposure can influence extracellular matrix regulation, inflammatory signaling, and cellular stress responses, the project focuses on how these biologically relevant processes are altered at the gene expression level.

## Central Question
Which coordinated biological processes are altered in UV-exposed dermal fibroblasts, and do these transcriptomic changes reflect a chronic photoaging program or an acute UV stress response?

## Dataset
Publicly available differential expression data from GEO dataset GSE119009 were used.

## Methods
- DEG filtering using p-value and log2 fold change thresholds
- Volcano plot visualization
- ECM- and inflammation-related gene grouping
- Heatmap and boxplot visualization

## Results
Several inflammation-related genes showed overall downregulation following UV treatment, while ECM/collagen-related genes exhibited comparatively smaller expression changes. Differentially expressed genes associated with UV-induced stress responses and extracellular matrix regulation were identified, and expression patterns were visualized using heatmaps and pathway-level comparison plots.

## Biological Interpretation and Limitations
This project initially expected to observe a typical chronic photoaging expression pattern — including strong inflammatory activation and collagen-related downregulation following UV exposure.
However, the selected inflammation-related gene groups showed overall downregulation, while ECM/collagen-related genes exhibited relatively limited expression changes. These findings suggest that the dataset may reflect an acute UV stress response or severe cellular damage state, rather than a fully established chronic photoaging phenotype.
This interpretation is partially consistent with the original study, which also reported broad transcriptional suppression and UV-induced necrotic stress responses in NHDF cells.
One limitation of this project is that gene grouping was performed manually based on a curated gene selection, rather than through formal pathway enrichment analysis.

## Tools
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook
