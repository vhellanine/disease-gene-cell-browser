# Junavhel Jane B. Olaguir
# UCSC Cell Browser Activity
From Genome to Cell: Exploring Disease Gene Using the UCSC Cell Browser

# 1. Assigned Gene and Disease
Gene: ATP7B

Disease: Wilson disease

# 2. Organ/Tissue Choice and Dataset Information

# Selected Dataset

**Dataset:** Human Liver  
**Dataset ID:** `human-liver`  
**Organ/Tissue:** Liver  
**Organism:** Human (*Homo sapiens*)  
**Disease Classification:** Healthy  

**Study:** *Single cell RNA sequencing of human liver reveals distinct intrahepatic macrophage populations*

**Publication:** MacParland et al. (2018), *Nature Communications*  
**NCBI GEO Series:** GSE115469  
**PubMed:** 30348985  

**Dataset URL:** https://cells.ucsc.edu/?ds=human-liver  
**Direct Plot:** https://human-liver.cells.ucsc.edu

# Reason for Dataset Selection

The Human Liver dataset was selected because ATP7B is associated with Wilson disease, a disorder involving abnormal copper accumulation that prominently affects the liver. Examining ATP7B expression in human liver cells allows its expression pattern to be investigated across hepatocytes and other liver cell populations.

The dataset is classified as healthy, so the results represent ATP7B expression in healthy human liver cells rather than cells from individuals with Wilson disease.

# Screenshot 1 — Selected Dataset

![Screenshot 1 - Human Liver Dataset](Screenshots/01_dataset.png)

# 3. Understanding the Cell Map

**a. What type of visualization is being shown?**

The Human Liver dataset displays a **t-SNE (t-distributed stochastic neighbor embedding) projection**. This visualization represents relationships among cells based on their transcriptomic profiles.

**b. What Does One Dot Represent?**

Each dot represents **one individual cell** profiled using single-cell RNA sequencing. Cells located near one another generally have more similar overall gene-expression profiles than cells positioned farther apart.

**c. What do the clusters represent in this particular dataset?**

The clusters represent groups of cells with similar transcriptomic profiles and correspond to different cell types or cellular populations in the human liver.

**d. List at least three cell-type or cluster labels visible in the dataset.**

- Hepatocyte
- Inflammatory Macs
- Non-inflammatory Macs
- LSEC 1
- Portal endothelial
- Cholangiocyte
- Stellate
- B cell
- Plasma
- NK-like

  # Screenshot — Cell Map

The screenshot below shows the t-SNE cell map of the Human Liver dataset with the annotated cell-type clusters.

![Human Liver Cell Map](screenshots/03_cell_map.png)
