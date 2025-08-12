# Shiny App Suite for Bioinformatics Analysis

## Overview
This repository contains the **complete, standalone version** of a suite of R Shiny applications for bioinformatics and experimental data analysis.  

Unlike the individual app repositories, this version **bundles all tools together** and can be run without installing **R** or any dependencies — simply download and run.  

---

## About the Suite

### Included Applications
Each of these apps can also be downloaded separately from their **individual GitHub repositories** (links in the table below).  
This repository provides the **all-in-one version** for convenience.

| App | Description | Individual Repo |
|-----|-------------|-----------------|
| **RNA-Seq Analysis Tool** | Differential expression (DESeq2, edgeR), volcano plots, heatmaps, pathway enrichment. Input: count matrix + sample metadata. | [RNA-Seq App](https://github.com/Andy-Ring/DESeq2-Shiny-App) |
| **Dose–Response Analyzer** | Fits dose–response curves, calculates IC50/EC50 with CIs, customizable plots. | [Dose–Response App](https://github.com/Andy-Ring/Dose-Response-Shiny-App) |
| **Growth Curve Analysis** | Calculates growth rates, doubling times, and statistical comparisons between groups. | [Growth Curve App](https://github.com/Andy-Ring/Cell-Growth-Curve-Analysis-Tool) |
| **Immunoblot Analysis Tool** | Quantifies immunoblot band intensity from images; designed as a user-friendly alternative to ImageJ. | [Immunoblot App](https://github.com/Andy-Ring/Immunoblot-Analysis-Tool) |

> More apps can be added in the future — this suite is modular.

---

## Installation

### Option 1 — Standalone Executable (No R Required)
- Download the latest full suite from the **[Releases](../../releases)** page. Choose the Windows/Mac installer to match your OS.
- Run the installer and install the app on your computer.
- In your apps, you should find 'Xi Group Analysis Tool Suite'. You can run it like you would normally run a Windows/Mac app.

### Option 2 — Run an Individual App from Its Repo
- Visit the app’s repository (see table above).
- Follow the installation instructions in that repo’s README.

---

## Usage
1. Launch `Xi Group Analysis Tool Suite`.
2. Select the desired app from the menu.
3. Upload your data in the format specified in each app's help section.
4. Adjust analysis parameters as needed.
5. Export your results.

---

## Example Screenshots
| RNA-Seq Volcano Plot | Dose–Response Curve | Growth Curve Plot | Immunoblot Analysis |
|----------------------|--------------------|-------------------|---------------------|
| ![Volcano](images/volcano_example.png) | ![Dose](images/dose_example.png) | ![Growth](images/growth_example.png) | ![Immunoblot](images/immunoblot_example.png) |

---

## Data Privacy
All computations run **locally** on your machine.  
No data is uploaded to external servers.

---

## Citation
If you use these tools in your research, please cite:
