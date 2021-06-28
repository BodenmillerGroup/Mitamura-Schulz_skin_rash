# Mitamura_Schulz

This repo contains the code used for pre-processing and analysis in R of the Covid skin rash Imaging Mass Cytometry (IMC) data from Mitamura, Schulz et al. Allergy, 2021

## General info

Images from tissues of patients with Covid related skin rash (Covid-MDR), maculopapular drug rashes (MDR), drug rash with eosinophilia and systemic symptoms (DRESS) and control human skin (HC) have been acquired using IMC.

Single cell data was generated using the pipeline as described under: https://github.com/BodenmillerGroup/ImcSegmentationPipeline
The corresponding scripts and cell profiler pipelines can be found in the "preprocessing" folder of this GitHub repo.

All data analysis downstream of single cell generation was performed in R.

The raw data, the single cell data, the annotated files for cell type classification and the SingleCellObject (https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html) have been deposited on Zenodo at the following link: