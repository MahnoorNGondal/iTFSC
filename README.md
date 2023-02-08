# iTFSC
integrated transcription factor analysis for single cell data (iTSC) is an R package designed to consolidate transcription factor (TF) information across multiple tools to arrive at a more robust list of TF. The package also allows users to do downstream visualization including differential expression analysis. The package will be validated using four different cancer types.  

### Requirements
In order to run this package you will need to install the following dependencies:
- library(SCENIC)
- library(BITFAM)
- library(Dorothea)

### Project detail:

Description: develop an integrated transcription factor analysis tool for single-cell and bulk data. The tool will include 4-5 existing transcription factors tools (eg SCENIC, DORTHEA, BITFAM etc) for single-cell data combined to give the users the transcription factor probability generated by a combined analysis. One way to select the best transcription factor is simply extracting the most common transcription factor generated from multiple tools. Other ways are to use the differential expression to decide on the best transcription factor across different cell types and find a common or high probability one. I am doing something similar for my research project, but I always thought it would be helpful if there was a package or tool to do this for me. The main idea would be to ensure that the transcription factors that we are getting are the ones that are actually involved, and this would be done by reproducibility across tools and through other downstream analyses.

### Features: the features tool will include the following features:

- integrated and fast TF analysis using 4-5 existing tools
- extract common TFs generated from all tools
- differential expression between cell types using limma on the output of the results from different tools
- GSEA on the results from differential expression analysis
- (if time) Apply the tools for bulk data (given there are at least 100 patients)
- (if time) use the transcription factors for the deconvolution of bulk data


![Workflow](https://user-images.githubusercontent.com/89783694/217571498-99290176-6ca2-445d-9ff9-4564ad563b12.png)
