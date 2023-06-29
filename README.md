# Gene-Set-File-Generator

To help GWAS researchers, mainly for Geneset Analysis, this script generates a standard Geneset file based on the gene names.

The codes are fetched from the NCBI37.3.gene.loc file.

Currently, you must download the Gene-Set-File-Generator.ipynb file and run it according to the step by step on a Python platform such as Google Colab or Jupyter Notebook.

## **Important:** 
The file extension with the names of the genes must be `.txt` and there must be a `line break` between the names.

### Example:

Geneset file with names (GeneSetExample.txt)
````
SLC6A4
SLC6A3
DRD4
DRD5
HTR1B
SNAP25
BAIAP2
CHRNA7
````
Geneset file generated with codes (Set.txt)
````
SET	6532	6531	1815	1816	3351	6616	10458	1139
````

## TODO

[ ] Run in terminal easily (with step by step)
