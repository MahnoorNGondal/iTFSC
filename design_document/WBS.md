TCGA matchmaker
- Activity 1: Set up GitHub repository
  - [X] Task 1.1: Set up GitHub repository
  - [X] Task 1.2: Create high-level description document
  - [X] Task 1.3: Design a workflow document
  - [X] Task 1.3: Create code structure
- Activity 2: Build prototype I
  - Activity 2.1 : Make the first function and add function description
    - [ ] Task 2.1.1: Import the RDS file 
    - [ ] Task 2.1.2: Downsample the seurat object to 1000 cells
    - [ ] Task 2.1.3: Check the quality of the seuratobject that user provides
    - [ ] Task 2.1.4: Convert the seurat object into expression data matrix format
  - Activity 2.2: Define high-level functions
    - [ ] Task 2.2.1: Run SCENIC (also incoporate ways to include its dependencies)
    - [ ] Task 2.2.2: Decide on SCENIC's output - try to use Rshiny to display output
    - [ ] Task 2.2.3: Run BITFAM (might cause memory issues)
    - [ ] Task 2.2.4: Decide on BITFAM's output - try to use Rshiny to display output
    - [ ] Task 2.2.5: Run Dorothea 
    - [ ] Task 2.2.6: Decide on Dorothea's output - try to use Rshiny to display output
    - [ ] Task 2.2.7: Run GSEA (establish a list of target to TF mapping)
    - [ ] Task 2.2.8: Decide on GSEA's output - try to use Rshiny to display output
  - Activity 2.3: Novel ways to analysis the output from the TF functions
    - [ ] Task 2.3.1: Perform a differential gene expression 
       - [ ]  Task 2.3.1.1: The deliverable would be a a DE list with p values
    - [ ] Task 2.3.2: Perform GSEA
       - [ ]  Task 2.3.2.1: The deliverable would be a a GSEA - preferably with C2 pathways list with p values
    - [ ] Task 2.3.2: Construct a robust rank list for the TFs
       - [ ] Task 2.3.2.1: The first implementation would be to gather the list of TF across all output
       - [ ] Task 2.3.2.2: The next step would be to score the TFs - with the TFs most common getting the highest score (we can also provide correlation methods). 
       - [ ] Task 2.3.2.3: For visualization purposes log2 would be employed to better visualize the data alongside venn diagram   
    - [ ] Task 2.3.3: The output would be available to the user as excel sheets and Rshiny output
