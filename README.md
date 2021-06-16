# wormcells-notebooks
This repository collects all the notebooks and scripts used to wrangling C. elegans scRNAseq data and processing it with scvi-tools for the wormcells-viz and scdefg app. The deployments of these apps is described at https://wormbase.github.io/single-cell/

Notebooks are examples and can be run on Google colab most of the time

## Example notebook explaining data processing for wormcells-viz app
https://colab.research.google.com/github/WormBase/wormcells-notebooks/blob/main/wormcells_viz_pipeline_example.ipynb


## WormBase data wrangling convention is described here:
https://github.com/WormBase/single-cell/blob/main/data_wrangling_convention.md

### Datasets that have been wrangled and deposited at Caltech Data using the notebooks provided here


|Name| Description | Caltech Data Link | 
|-----------|-------------|-----|
| `packer2019.h5ad` | 89k cells profiled with 10xv2 across multiple timepoints of development| https://data.caltech.edu/records/1945|
| `taylor2020.h5ad` | 100k cells FACS sorte for neurons at L4 larval stage| https://data.caltech.edu/records/1977|
| `bendavid2021.h5ad` | 55k cells profiled with 10xv2 at L2 larval stage| https://data.caltech.edu/records/1972|
