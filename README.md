# Overcoming Doxorubicin Resistance in TNBC: A scRNA-Seq and CADD Pipeline

This repository contains the complete research workflow, code, and results from my Master's thesis titled **"Overcoming Doxorubicin Resistance in Triple-Negative Breast Cancer: A Single-Cell Transcriptomic and Structure-Based Drug Discovery Approach."**

## 🧪 Abstract
Triple-negative breast cancer (TNBC) lacks ER, PR, and HER2 receptors, limiting targeted treatment options. This study combines single-cell RNA sequencing (scRNA-seq) and computational drug discovery to dissect Doxorubicin-induced transcriptional reprogramming and chemoresistance. We identified consistently upregulated stress-response genes across high-dose treatments and computationally screened ~1,000 compounds. Ligand optimization and molecular dynamics simulations led to a novel drug-like compound with improved ADMET properties and superior efficacy over Doxorubicin.

## 🧬 Key Methods
- **scRNA-seq Analysis** (10x Genomics, Seurat)
- **Lineage-Resolved DEG Profiling**
- **GO/KEGG Enrichment (Enrichr)**
- **Virtual Screening (AutoDock Vina)**
- **Ligand Optimization (RDKit)**
- **ADMET Filtering (SwissADME, pkCSM, ProTox-II)**
- **Molecular Dynamics (GROMACS)**

## 🔍 Highlights
- Identification of stress-tolerant TNBC subclones
- CADD targeting of DDIT3, CNOT11, WDR5, and CENPT
- Generation of 60 novel ligand analogs via RDKit
- Final lead compound outperforms Doxorubicin in predicted toxicity and bioavailability

## 📂 Contents
- `/data/`: Raw and processed scRNA-seq data
- `/scripts/`: All R and Python scripts for analysis
- `/docking/`: Ligand libraries, docking outputs
- `/optimization/`: RDKit fragmentation + hybrid models
- `/md_simulation/`: GROMACS input/output files
- `/figures/`: Final plots, UMAPs, heatmaps, violin plots
- `README.md`: You are here
- `TNBC-Doxorubicin-Thesis.pdf`: Full manuscript

## 📜 Citation
If using this work, please cite:
> Balaji C. *Overcoming Doxorubicin Resistance in Triple-Negative Breast Cancer: A Single-Cell Transcriptomic and Structure-Based Drug Discovery Approach*. M.Sc. Thesis. 2025.

## 👨‍💻 Author
**Balaji C.**  
M.Sc. Bioinformatics  
Email: balaji150403@gmail.com  
[LinkedIn](https://www.linkedin.com/in/balajimadhvn/) | [GitHub](https://github.com/balajimadhvn)

---

### 🚀 Ideal for
- Cancer bioinformatics
- Drug repurposing and ligand design
- Single-cell transcriptomics
- Computational pharmacology

