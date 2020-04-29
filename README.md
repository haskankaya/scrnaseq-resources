# scrnaseq-resources
A list of resources on scRNA-seq analysis including tutorials and guides. They are split broadly into 'processing' and 'analysis' categories, where 'processing' describes the process from raw data to expression matrices, and 'analysis' describes the subsequent processes to understand and visualise the data.

## Processing Tutorials
 - CellRanger from 10X Genomics: https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/using/tutorial_ov
 
 - Kallisto/bustools:
   - introduction: https://www.kallistobus.tools/introduction
   - tutorial: https://www.kallistobus.tools/tutorials (python and R)

## Analysis Tutorials
### R
 - Seurat vignette/tutorial from the Satija Lab (who developed Seurat): https://satijalab.org/seurat/v3.1/pbmc3k_tutorial.html

### Python
 - "Bioinformatics for Benched Biologists" Youtube-recorded Zoom stream from Prof. Lior Pachter and colleagues: https://www.youtube.com/watch?v=vKsh_ovq8x8 - includes a Google Cloud link to an interactive notebook so you can code along with them and use Google's servers for computation
 
 ## Complete courses:
 - Sanger Institute scRNA-seq two day course: https://scrnaseq-course.cog.sanger.ac.uk/website/index.html
 - Broad Institute: https://broadinstitute.github.io/2019_scWorkshop/ - CellRanger, Seurat, and others


## Other
 - Dizzyingly-long list of every scRNA-seq software available: https://github.com/seandavi/awesome-single-cell (n.b includes a list of tutorials)
 
 
 
 
 
## Copy of list taken from https://github.com/seandavi/awesome-single-cell
I'll maybe merge this with my above sorted list at some point?

- [Orchestrating Single-Cell Analysis with Bioconductor](https://osca.bioconductor.org) - [R] - This blogdown book describes a comprehensive and reproducible workflow for the analysis of single-cell RNA-sequencing data.
- [Aaron Lun's Single Cell workflow on Bioconductor](http://bioconductor.org/help/workflows/simpleSingleCell/) - [R] - This article describes a computational workflow for basic analysis of scRNA-seq data using software packages from the open-source Bioconductor project.
- [Bioconductor2016 Single-cell-RNA-sequencing workshop by Sandrine Dudoit lab](https://github.com/drisso/bioc2016singlecell) - [R] - SCONE, clusterExperiment, and slingshot tutorial.
- [BiomedCentral Single Cell Omics collectin](http://www.biomedcentral.com/collections/singlecellomics) - collection of papers describing techniques for single-cell analysis and protocols.
- [Clustering 3K PBMCs with Scanpy in Galaxy](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/scrna-scanpy-pbmc3k/tutorial.html) - Galaxy Training Material.
- [CSHL Single Cell Analysis - Bioinformatics](https://github.com/YeoLab/single-cell-bioinformatics/) course materials - Uses Shalek 2013 and Macaulay 2016 datasets to teach machine learning to biologists
- [CyTOF Workflow](https://github.com/markrobinsonuzh/cytofWorkflow) - [R] - An R-based pipeline for differential analyses of high dimensional mass cytometry data, primarily based on Bioconductor packages. [Link](https://f1000research.com/articles/6-748) to the paper describing a high-level introduction to the core concepts and code.
- [Festival of Genomics California Single Cell Workshop](https://kdkorthauer.github.io/FestivalWorkshopVignettes/) - [R] - Explores basic workflow from exploratory data analysis to normalization and downstream analyses using a dataset of 1679 cells from the Allen Brain Atlas.
- [Gilad Lab Single Cell Data Exploration](http://jdblischak.github.io/singleCellSeq/analysis/) - R-based exploration of single cell sequence data. Lots of experimentation.
- [Harvard STEM Cell Institute Single Cell Workshop 2015](http://hms-dbmi.github.io/scw/) - workshop on common computational analysis techniques for scRNA-seq data from differential expression to subpopulation identification and network analysis. [See course description for more information](http://scholar.harvard.edu/jeanfan/classes/single-cell-workshop-2015)
- [Hemberg Lab scRNA-seq course materials](http://hemberg-lab.github.io/scRNA.seq.course/index.html)
- [Pre-processing of 10X Single-Cell RNA Datasets in Galaxy](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/scrna-preprocessing-tenx/tutorial.html) - Galaxy Training Material.
- [Theis Lab Single Cell Tutorial](https://github.com/theislab/single-cell-tutorial) - The main part of this repository is a case study where the best-practices established in the manuscript are applied to a mouse intestinal epithelium regions dataset from Haber et al., Nature 551 (2018) available from the GEO under GSE92332.
- [Using Seurat (v1.2) for unsupervised clustering and biomarker discovery](http://www.satijalab.org/seurat/get_started_v1_2.html) - 301 single cells across diverse tissues from (Pollen et al., Nature Biotechnology, 2014). Original tutorial using Seurat 1.2
- [Using Seurat (v1.2) for spatial inference in single-cell data](http://www.satijalab.org/seurat/get_started_v1_2.html) - 851 single cells from Zebrafish embryogenesis (Satija*, Farrell* et al., Nature Biotechnology, 2015). Original tutorial using Seurat 1.2
- [Seurat (v3.0) - Guided Clustering Tutorial](https://satijalab.org/seurat/v3.0/immune_alignment.html) - new tutorial using Seurat 3.0
 
 
