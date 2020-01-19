# Embeddings
A repository for some files related to embeddings

Files: 
* README.md - this file
* 2019-TIMC-Embeddings-shareable.pdf - a .pdf of my Jan 13, 2020 talk to the West Point Network Science Centre
* Viz-UMAP.ipynb - A simple example showing interactive visualizations of a UMAP projection of sklearn digits data with mouseover

## Getting started with UMAP with interactive plots

HDBSCAN is a fairly static implementation at the moment. UMAP is being more actively developed.  For some more modern things (interactive viz), try the experimental branch (which is quite near to becoming the master!)

* pip install hdbscan
* pip install datashader
* pip install holoviews
* pip install git+https://github.com/lmcinnes/umap@0.4dev

## Getting started with HDBSCAN and UMAP -- Basic version
For basic usage, you can simply 

* pip install hdbscan
* pip install umap-learn

There may be some issues with pip installing in Windows (I exclusively use linux for dev work). If you use Windows and run into any issues please let me know.
