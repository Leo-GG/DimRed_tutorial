# Demystifying Dimensionality Reduction Techniques in the 'Omics' Era: A Practical Approach for Biochemistry and Molecular Biology Students

This repository contains teacher & student materials accompanying the article "Demystifying Dimensionality Reduction Techniques in the 'Omics' Era: A Practical Approach for Biochemistry and Molecular Biology Students" (link pending publication).

The article describes a series of examples based on demographic data and single cell transcriptomics (on the sc/ folder) that we found useful for teaching concepts and applied methods of dimensionality reduction to students from non-mathematical backgrounds.

# Instruction sets
We provide instructions for [teachers](/Instructions/Teachers.md) and [students](/Instructions/Students.md) on how to use these materials in the classrom.

# COVID-19 demographics examples
We propose to use a very simple dataset with demographic data from the COVID-19 pandemic to illustrate PCA and non-linear dimensionality reduction.

## Materials
We provide [a Jupyter notebook for the PCA examples](demographicsMaterials/covid_PCA.ipynb) that contains annotations and examples for the students.
A [second notebook](demographicsMaterials/covid_NonLinear.ipynb) contains the code to reproduce the examples demonstrating non-linear methods presented in the paper.

## Data
The data is provided in [a small .csv file](demographicsMaterials/covid_processed.csv)

## Exercises
We provide an additional "blank" annotated [notebook](demographics/covid_PCA_exercises.ipynb) that can be used as a set of exercises in which students have to reproduce the PCA examples in Python.

# Single-cell transcriptomics examples
We suggested to use single-cell or single-nuclei data to illustrate the same concepts using a larger, more complex dataset.

## Materials
We provide Jupyter notebooks that reproduce the examples presented in the article [on PCA](scMaterials/sc_PCA.ipynb) and on [non-linear methods](scMaterials/sc_NonLinear.ipynb)

## Data 
The scRNA-seq data for these examples is provided in a loom file hosted on [Figshare](https://figshare.com/projects/Dimensionality_Reduction_Tutorial/151215)

## Running on Google Colab
- If you have a (free) google account, you can run all the Jupyter notebooks directly on your browser without having to download or install anything on your computer. To do so, simply click the links bellow:
  -[Notebook with PCA using COVID-19 data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/demographicsMaterials/covid_PCA.ipynb)
  -[Notebook with non-linear methods using COVID-19 data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/demographicsMaterials/covid_NonLinear.ipynb)
  -[Notebook with PCA using single-cell RNAseq data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/scMaterials/sc_PCA.ipynb)
  -[Notebook with non-linear methods using single-cell RNAseq data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/scMaterials/sc_NonLinear.ipynb)

# Additional examples
We provide a web-based resource with dimensionality reduction demos on 2D and 3D data: (https://reduce.streamlit.app/)
These are simple examples that might help students visualize some of the dimensionality reduction concepts.
