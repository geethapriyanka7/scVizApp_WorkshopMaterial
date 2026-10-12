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
> Application might crash during the workshop, please **Restart App** if you face any issues.

### Step 1: Load the data
 
**Goal:** Upload the .rds file.
 
1. Access the website link, stay on **Introduction** tab and select the **Load/Input Data** sub-tab.

 ![Step 1: Upload data](images/01.png)
 
2. Download `ifnb_demo_seurat.rds` using the **Input data** link in the Quick Links table.
3. Click **Browse** and select the downloaded file. The progress bar above the button shows the upload from your computer and reads **Upload complete** when it finishes.
   
![Step 1: Browse and upload](images/03.png) 

4. Click **Load Data**. A second progress bar tracks the loading. When it finishes, the message **✅ File uploaded: ifnb_demo_seurat.rds** appears.

![Step 1: Load data](images/04.png) 
   
5. The app then switches automatically to the **Cell Summary Profile** tab, where you can continue with the analysis.
 
> **Tip:** Files can take up to a minute to load.


### Step 2: Cell Summary Profile
 
**Goal:** Explore cell counts, clusters and conditions present in the cohort.
 
1. Contains 3 sub-tabs, **Samples Description** tab shows data columns and values present in each data column. At glance review of cohort data.

 ![Step 2.1: Sample Description](images/05.png)
 
2. **Cell Summary** tab allows users to explore cell counts and percentages from any two data columns. Visual and tabular options to explore cell summaries.

 ![Step 2.2: Cell Summary](images/06.png)

3. In **Dimesionality Reduction Plots**, users can access PCA and UMAP to understanding cell clustering in the data
   
 ![Step 2.3: UMAP](images/07.png)

4. Click **Browse** and select the downloaded file. The progress bar above the button shows the upload from your computer and reads **Upload complete** when it finishes.
   
![Step 1: Browse and upload](images/03.png) 

4. Click **Load Data**. A second progress bar tracks the loading. When it finishes, the message **✅ File uploaded: ifnb_demo_seurat.rds** appears.

![Step 1: Load data](images/04.png) 
   
5. The app then switches automatically to the **Cell Summary Profile** tab, where you can continue with the analysis.
 
> **Tip:** 'Additional Option' feature is explained after Dot Plot Module.
 
---
