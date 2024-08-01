# Bioinformatics Gene-Disease Research in the Post-Genomic Era

This folder contains the third assignment for the Bioinformatics course. The main file for this assignment is `Bioinformatics Gene-Disease Research in the Post-Genomic Era.ipynb`, which is a Jupyter notebook containing the analysis and code for various bioinformatics tasks.

## Contents

- `Bioinformatics Gene-Disease Research in the Post-Genomic Era.ipynb`: Jupyter notebook with the main analysis
- `Bioinformatics Gene-Disease Research in the Post-Genomic Era.pptx`: PowerPoint presentation summarizing key findings
- `Bioinformatics Gene-Disease Research in the Post-Genomic Era.pdf`: PDF version of the presentation

In the data.zip folder, you will find the following files:
- `disgenet.csv`: Dataset containing information about gene-disease associations
- `disgenet_small.csv`: A smaller version of the disgenet dataset
- `go_human.tsv`: Dataset containing information about gene ontology annotations for humans


## Setup

To run this notebook, you'll need Python with the following libraries:
- sqlalchemy
- pandas
- matplotlib
- numpy
- networkx

You can install these libraries using pip:

```
pip install sqlalchemy pandas matplotlib numpy networkx
```



## Running the Notebook

Open the `Bioinformatics Gene-Disease Research in the Post-Genomic Era.ipynb` file in Jupyter Notebook or JupyterLab to view and run the analysis.

## Analysis Overview

The notebook covers several research questions related to gene-disease associations and biological processes. The key analyses include:

1. Exploring the pace of progress in biomedical research since 1960
2. Identifying top genes and diseases by the number of associations
3. Analyzing degree distributions of genes and diseases
4. Investigating Alzheimer's Disease-related genes and their properties
5. Examining biological processes associated with Alzheimer's genes
6. Exploring diseases associated with Alzheimer's-related genes
7. Analyzing the relationship between the number of publications, disease specificity, and biological processes for top genes
   - Visualizes the top 10 genes with the highest number of publications
   - Compares the number of publications with the Disease Specificity Index (DSI) for each gene
   - Provides insights into the biological processes associated with these top genes
   - Key findings:
     - Genes with more publications aren't necessarily more disease-specific
     - TP53, while having the highest publication count, doesn't have the highest DSI
     - BRCA1 shows a higher DSI despite fewer publications, suggesting a more disease-specific role
     - The analysis highlights the importance of considering both publication count and DSI when studying a gene's role in disease processes

This analysis provides a comprehensive view of how research focus (measured by publication count) relates to a gene's specificity in disease associations, while also considering the biological processes these genes are involved in. A visual representation of these findings can be found in the accompanying PowerPoint and PDF files.

## Output

The notebook generates a `combined_sorted.csv` file, which contains sorted gene data including gene symbols, number of publications, disease specificity index (DSI), and associated GO terms.

The PowerPoint and PDF files provide a visual summary of the key findings, including charts and tables that illustrate the relationships between gene publication counts, disease specificity, and biological processes.