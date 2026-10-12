# scVizApp_WorkshopMaterial
Welcome to scVizApp Hands-on workshop!!! Materials and Documentation required to follow through scVizApp hands-on workshop are here
## Overview
This platform provides an interactive workspace for exploring summaries of cell types and clusters, interactive plots of gene expression, and access to downstream analyses.
**Modules covered in this workshop**
 
| Module | What it does |
|---|---|
| Data upload | Load a Seurat object (.rds) |
| Clustering and UMAP | Explore clusters and conditions |
| Violin / Feature / Dot Plot | Visualize marker gene expression |
| Cluster Annotation | Annotate cell types present in the cohort |
| Module Scoring | Score gene sets (e.g. interferon signaling) |
| Differential Expression | Compare conditions and export results |
 
**Workshop scenario:** "I have a dataset with Control and interferon-beta-stimulated samples. I want to annotate the cell clusters using known marker genes, then score interferon-stimulated gene activity to see which cell types respond most strongly to stimulation compared to Control followed with Differential expression analysis between interferon-beta-stimulated samples vs Control."*
 
---
## Quick Links
 
| Resource | Link |
|---|---|
| Access the app | [scVizAppPublic](https://biocoreapps.bsd.uchicago.edu/public/app/scvizapppublic) |
| Input data | [ifnb_demo_seurat.rds](https://drive.google.com/file/d/1prKYu_bkvOS3dzhNu5levhpWLqbbqRlq/view?usp=sharing) |
| Demo data | [`demo_data/`](demo_data/) |
| Walkthrough tutorial | [`demo_data/README.md`](demo_data/README.md) |
| Slides | [ADD SLIDES LINK](ADD_SLIDES_LINK) |
 
---
## Demo Data
 
| File | Description | Size |
|---|---|---|
| `ifnb_demo_seurat.rds` | Seurat object, Control vs IFN-beta-stimulated | 83MB |
| `demo_data/cell_type_markers.xlsx` | gene list with gene and cellType columns (used in DotPlot module) | ADD |
| `demo_data/REACTOME_INTERFERON_SIGNALING.v2026.1.Hs.gmt` | gene set for Module Scoring (used in Scoring Module) | ADD |
 
**Download:** click the file, then choose **Download raw file** (or use the download icon).
 
---
## Walkthrough
 
> **Estimated time:** ~5 minutes for the full workflow.

### Step 1: Load the data
 
**Goal:** Upload the .rds file.
 
1. Go to the **Data** tab.
2. Click **Browse** and select `ADD_FILE_NAME.rds`.
3. Wait for the confirmation message.
<!-- ![Step 1: Upload data](images/01_load_data.png) -->
*Screenshot placeholder: `images/01_load_data.png`*
 
> **Tip:** ADD a helpful note, e.g. large files can take up to a minute to load.
 
---
