# 🧬 Tissue-Specific Transcriptomic Analysis: Liver vs. Skin

## Overview

This project investigates **differential gene expression** across human **liver** and **skin** tissues using a complete NGS-based RNA-Seq analysis pipeline. Leveraging publicly available transcriptomic datasets from the **Human Protein Atlas**, the study aims to uncover **tissue-specific gene signatures** and **biological pathways**, with an emphasis on understanding **liver-related skin manifestations**.

---

## 🔍 Objectives

- Identify **Differentially Expressed Genes (DEGs)** between liver and skin tissues.
- Compare **metabolic** and **structural** gene expression profiles across tissues.
- Discover key **gene interactions**, **biological functions**, and **pathway enrichments**.
- Explore **cutaneous indicators** of liver dysfunction to support **biomarker discovery** and **diagnostic development**.

---

## 📊 Data & Tools

### Data Source
- **RNA-Seq datasets** from Human Protein Atlas (Uppsala University Hospital).

### Technology Platform
- **Next-Generation Sequencing (NGS)**

---

## 🧪 Pipeline Workflow

### 1. 🧼 Data Preprocessing
- **Quality Control:** FastQC v0.11.9
- **Trimming:** Trim Galore (adapter removal & quality trimming)

### 2. 🧬 Alignment & Quantification
- **Read Mapping:** HISAT2 to human reference genome
- **Post-Processing:** SAMtools for SAM/BAM handling
- **Visualization:** IGV (Integrative Genomics Viewer)

### 3. 📈 Differential Expression Analysis (RStudio v4.3.1)
- **Tools:** DESeq2, edgeR, Genefilter, Pheatmap, RColorBrewer
- **Visuals & Outputs:**
  - PCA & MDS plots to cluster tissues
  - Smear plots & heatmaps for DEGs
  - Tables of statistically significant up/downregulated genes

### 4. 🧠 Functional Interpretation
- **Enrichment Analysis:** DAVID for GO and KEGG pathways
- **Gene Network Analysis:** STRING database for interaction mapping

---

## 🔬 Key Findings

- **Liver-Specific Genes:** Enriched expression in **CYP**, **UGT**, **ALDH** families
- **Skin-Specific Genes:** Upregulation of **keratin genes** (KRT1–KRT14)
- **Biological Link:** Molecular support for **skin symptoms in liver disease** (e.g., jaundice, keratin changes)

---

## 📌 Applications

- Insight into **cutaneous biomarkers** of liver dysfunction
- Contribution to **clinical diagnostics** and **transcriptomic-based screening**
- Foundation for **precision medicine** and **biomarker development**

---

## 📁 Repository Structure

