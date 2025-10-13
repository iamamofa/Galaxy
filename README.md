# 🧬 Cholera Sample Analysis with Galaxy
### A Step-by-Step Guide to Analyzing Illumina Sequencing Data

---

## 📖 Overview
This course provides a complete, hands-on guide to analyzing **Vibrio cholerae** Illumina sequencing data using the **Galaxy platform** and supporting bioinformatics tools.  
You’ll learn how to perform quality control, genome assembly, annotation, and comparative genomics — all through an accessible, reproducible workflow.

The modules in this course include:

- **Home**
- **Unix/Linux Introduction**
- **Package Management (Conda)**
- **Containers**
- **Nextflow**
- **R Programming**
- **Galaxy Introduction**
- **Galaxy Collections**
- **Workflows**
- **Cholera Case Study (Final Module)**

---

## 🧫 Final Module: Cholera Case Study

### 🔍 Introduction
In this final module, you’ll apply everything learned to analyze real *Vibrio cholerae* outbreak samples.  
Using **Illumina sequencing data**, you’ll conduct a **complete genomic analysis pipeline** — from raw reads to annotated genomes and phylogenetic trees.

---

## 🦠 About *Vibrio cholerae*

*Vibrio cholerae* is a **Gram-negative bacterium** and the causative agent of **cholera**, a severe diarrheal disease.  
Analyzing its genome helps us:

- Track outbreak sources and transmission routes  
- Identify **antibiotic resistance genes**  
- Understand **virulence factors**  
- Support development of **prevention and treatment strategies**

---

## 🧪 Analysis Workflow

### **Step 1: Quality Control**
- Tool: **FastQC**  
- Evaluate:
  - Per-base sequence quality  
  - Adapter contamination  
  - Over-represented sequences  

### **Step 2: Read Trimming**
- Tools: **Trimmomatic** or **fastp**  
- Remove low-quality bases and adapter sequences.

### **Step 3: Genome Assembly**
- Tools: **SPAdes** or **MEGAHIT**  
- Assemble trimmed reads into contigs to reconstruct genomes.

### **Step 4: Assembly Quality Assessment**
- Tool: **QUAST**  
- Metrics to assess:
  - Number of contigs  
  - **N50** value  
  - Total assembly length  

### **Step 5: Genome Annotation**
- Tool: **Prokka**  
- Identify:
  - Protein-coding genes  
  - RNA genes  
  - Functional annotations  

### **Step 6: Comparative Analysis**
- Identify:
  - SNPs and variants  
  - **Antibiotic resistance** and **virulence genes**  
  - Phylogenetic relationships among isolates  

---

## 🎯 Expected Outcomes
By the end of this module, you will have:

✅ High-quality assembled genomes  
✅ Annotated gene lists  
✅ Identification of key virulence and resistance genes  
✅ Phylogenetic tree showing sample relationships  
✅ A complete, reusable **Galaxy workflow**

---

## 📂 Dataset
All Cholera sample datasets are publicly available via **[Zenodo](https://zenodo.org/)**.  
Before beginning, ensure that you have created your **paired collection** in Galaxy, as described in the *Galaxy Collections* module.

---

## 🔗 Resources

- [Galaxy Training Materials](https://training.galaxyproject.org/)
- [Launch Galaxy](https://usegalaxy.org/)
- [Download Dataset (Zenodo)](https://zenodo.org/)
- [Course in a Box (P2PU)](https://course-in-a-box.p2pu.org/)

---

## 🧱 Built With
- **Galaxy Platform** for workflow execution  
- **FastQC**, **Trimmomatic**, **SPAdes**, **QUAST**, **Prokka** for bioinformatics steps  
- **R Programming** for data visualization and result interpretation  
- **Nextflow** for reproducible pipelines  
- **Conda** and **Containers** for environment management  

---

## ⚖️ License
Unless otherwise noted, all materials in this course are licensed under a  
**[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**.

---

## 🙌 Acknowledgments
This course was built using **Course in a Box**, a project of [P2PU](https://p2pu.org/).  
We thank the **Galaxy Project** and **open-source bioinformatics community** for providing the tools and data that make this training possible.

**Acknowledgments** to  ```Dr. Jolynne Mokaya for continual Support :smile```
---

> *“Empowering open, reproducible, and accessible bioinformatics education.”*
