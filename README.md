# skin-photoaging-rna-seq-analysis
RNA-seq differential expression analysis of UV-induced skin photoaging using Python
![Volcano Plot](volcano_plot.png)

## Background
This project analyzes RNA-seq differential expression data from UV-treated human dermal fibroblasts to investigate molecular changes associated with skin photoaging.

## Dataset
Publicly available differential expression data from GEO dataset GSE119009 were used.

## Methods
- DEG filtering using p-value and log2 fold change thresholds
- Volcano plot visualization
- ECM- and inflammation-related gene grouping
- Heatmap and boxplot visualization

## Results
Several extracellular matrix (ECM)-related and inflammation-associated genes showed altered expression patterns following UV treatment.

## Biological Interpretation
The analysis suggests UV-associated transcriptional changes related to extracellular matrix remodeling and inflammatory signaling in skin aging.

## Tools
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook
