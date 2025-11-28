---
layout: compress
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
markdown: kramdown
kramdown:
  parse_block_html: true
---


<!-- CV Download Button -->
<div style="text-align:left; margin-bottom: 1em;">
  <a href="http://16nikita.github.io/files/Nikita_Sajai_AccessibleCV.pdf" target="_blank" style="padding: 0.5em 1em; background:#2E6F3E; color:white; text-decoration:none; border-radius:5px;">Download CV</a>
</div>

<details class="cv-section" open>
  <summary>Education</summary>
  <div class="cv-content">

  **Cornell University**  
  *B.A. in Biological Sciences*  
  *Concentration in Computational Biology*  
  *Minor in Climate Change*    
  Graduated *summa cum laude*, December 2022 — GPA: 4.054 (4.3 Scale)

  **Honors Thesis🦋:** [*The Mutagenic Effect of Recombination*](https://16nikita.github.io/publication/2010-10-01-paper-title-number-2)

  **My Favorite Courses🌟:** Listening to Indigenous Voices, Ecology & Evolutionary Biology, Perspectives on Climate Change, Environmental Justice, Ethics & The Environment, Computational Biology


  </div>
</details>

<details class="cv-section" open>
<summary>Research Experience</summary>
<div class="cv-content">

**Junior Specialist**  
*Bruce Wang Lab, UCSF* — *May 2023–Present*  
- Lead data scientist on single-cell physiological studies and complementary spatial transcriptomics analyses of liver development and disease progression in human and mouse models.
- Developed and maintained custom pipelines using Linux, R, and Python for data preprocessing, integration, and visualization on the following projects:  
  - **Spatial Transcriptomics of Human Liver:** Developed a curated panel of marker genes to enhance identification and spatial mapping of liver cell types in healthy human tissue, enabling more expansive and precise characterization of liver architecture and cellular organization. 
  - **PCT Progression in UROD-Treated Mouse Hepatocytes:** Investigated liver pathology in porphyria mouse models through the characterization of transcriptional changes in UROD-treated mouse hepatocytes, revealing stress-response activation, polyploidization, and disrupted zonation. Reconstructed hepatocyte differentiation trajectories via pseudotime analysis to map disease progression. Work is being prepared into manuscript.
  - **Wildtype Liver Physiology Single-Cell Analysis:** Examined how physiological processes (e.g. circadian rhythm, fasting, and the estrous cycle) influence liver gene expression across time and sex to understand baseline norms and deviations.   
- Bioinformatics consultant for UCSF Liver Center labs, completing analyses across a diverse range of topics: single-nuclei RNA-sequencing, spatial transcriptomics,  single-cell RNA-sequencing, ATAC-sequencing, lipidomics, proteomics, and micro-RNA sequencing.
  - **snRNA-seq: Hepatic Stellate Cells & Fibrosis:** Performed snRNA-seq analysis of hepatic stellate cells to assess tamoxifen’s impact on fibrosis development. Identified treatment-specific gene expression changes, characterized HSC subpopulations, and evaluated ligand–receptor signaling between HSCs, hepatocytes, and myeloid cells. Focused on pathways involved in collagen remodeling, including matrix-associated genes (e.g., MMP1, MMP3).
  - **Spatial Transcriptomics (Visium HD):** Analyzed Visium HD liver sections and integrated spatial data with single-cell profiles to investigate metabolic reprogramming in Kupffer cells. Compared wild-type and knockout mouse livers to map region-specific changes in innate immune and metabolic function
  - **Proteomics and MLM: Normothermic Perfusion & Transplant Viability** Conducted longitudinal proteomic analysis of bile and perfusate from normothermic machine-perfused livers to identify signatures predicting early allograft dysfunction (EAD). Integrated metadata such as steatosis status and perfusion timepoints to characterize metabolic collapse, ER/mitochondrial stress, inflammation, and loss of hepatocellular function in EAD grafts. Using LASSO MLM to uncover panel of proteins to predict EAD liver status. Contributed major analysis leading to a manuscript (second author).
  - **ATAC-seq: Chromatin Accessibility in MASLD vs Healthy iPSC-Hepatocytes** Compared chromatin accessibility landscapes between MASLD-derived and healthy iPSC-hepatocyte lines to identify regulatory regions linked to disease-specific transcriptional programs and metabolic dysfunction.

**Research Assistant**  
*Pawlowski Lab, Cornell University* — *Sept 2021–April 2023*  
- Collaborated with Dr. Wojtek Pawlowski and PhD student Ruth Epstein on multiple projects using Linux, R and Python:  
  - **Mutagenic Effect of Recombination:** [*Honors thesis;*](https://16nikita.github.io/publication/2010-10-01-paper-title-number-2) Evaluated the overlap of indels with crossover sites to understand the mutation generation potential of recombination hotspots in the maize genome.
  - **Mutant Recombination Landscape Effect on Breeding Efficiency:** [*Published in PNAS;*](https://16nikita.github.io/publication/2009-10-01-paper-title-number-1) Simulated effects of mutant recombination landscapes in maize and rice breeding in efforts to increase global recombination rates and improve the efficiency of breeding programs   
  - **Using DNA Sonication as Proxy for Chromatin Openness:** Lead researcher; tested the effectiveness of DNA sonication methods to assess chromatin openness in maize.

**Summer Research Intern (REU)**  
*Boyce Thompson Institute (Pawlowski Lab)* — *Jun 2021–Aug 2021*  
- Collaborated with Dr. Wojtek Pawlowski and PhD student Ruth Epstein:
  - Evaluate crossover hotspot proximity to haplotype blocks in maize. Project development in R.
  - Conducted wet-lab work using immuno-FiSH and super-resolution microscopy to study crossover protein localization on inverted chromosome arms.  


</div>
</details>


<details class="cv-section" open>
<summary>Computational & Bioinformatics Skills</summary>
<div class="cv-content">


### **Programming & Scripting**
- Python, R, Bash, Java  
- Custom pipeline development for scRNA-seq, snRNA-seq, ATAC-seq, spatial transcriptomics, and proteomics  
- Reproducible workflows: Git/GitHub, conda environments, Makefiles, workflow documentation  

### **Bioinformatics Tools & Frameworks**
- **Alignment & QC:** Bowtie2, STAR, Samtools, Bedtools, Picard, MACS2/MACS3, deepTools  
- **Single-Cell & Spatial:** Seurat, Scanpy, CellChat, CellPhoneDB, Harmony, Squidpy, Space Ranger  
- **Epigenomics:** MACS3 peak calling, featureCounts, HOMER, ATAC-seq QC (FRiP, TSS enrichment)  
- **Proteomics & Multi-Omics:** MaxQuant, Perseus, limma, clusterProfiler, KEGG/GO enrichment, LASSO regression  

### **Data Formats & Reference Resources**
- FASTQ, SAM/BAM/CRAM, BED, GTF/GFF, H5AD, Loom  
- Integrated use of Ensembl/GENCODE, UCSC Genome Browser, MSigDB, KEGG  

### **Statistical Analysis & Visualization**
- R: tidyverse, ggplot2, Seurat, limma, pheatmap, AlphaSimR  
- Python: pandas, numpy, matplotlib, scikit-learn, scanpy  
- Experience with modeling (mixed-effects, LASSO/elastic net), batch correction, pseudotime inference, and trajectory analysis  

### **Systems & High-Performance Computing**
- Unix/Linux (shell/bash)  
- SLURM-based HPC environments, array jobs, pipeline parallelization  
- Large-scale data management, cloud computing workflows  


</div>
</details>


<details class="cv-section" open>
<summary>Publications</summary>
<div class="cv-content">


- *Epstein R, Sajai N*, M. Zelkowski, A. Zhou, K.R. Robbins, & W.P. Pawlowski. (2023). "Exploring impact of recombination landscapes on breeding outcomes." *Proceedings of the National Academy of Sciences* (PNAS). 120 (14) e2205785119, https://doi.org/10.1073/pnas.2205785119 (2023).


</div>
</details>

<details class="cv-section" open>
<summary>Presentations & Talks</summary>
<div class="cv-content"> 

- **Oral Presentation:** Overview of Liver Gene Analysis Core - UCSF Liver Center Research in Progress (RIPS), San Francisco, CA, September 2025

- **Oral Presentation (Lightning Talk):** Designing a Healthy Human Liver Gene Panel for 10X Xenium Spatial Transcriptomics - UCSF Liver Center Annual Symposium, San Francisco, CA, May 2024

- **Poster Presentation:** The Mutagenic Effect of Recombination — Maize Genetics Meeting, St. Louis, MO, May 2023  

-**Poster Presentation:**  The Mutagenic Effect of Recombination - Cornell Honors Thesis Research Symposium, Ithaca, NY, December 2022

</div>
</details>

<details class="cv-section" open>
<summary>Other Professional Experience</summary>
<div class="cv-content"> 

**Administrative Assistant**  
*arXiv* — *Feb 2022–Dec 2022*  
- Managed metadata and handled journal/manuscript pre-print submissions.

**Research Intern**  
*U.S. Green Chamber of Commerce* — *Jan 2021–May 2021*  
- Conducted research on fast fashion's impact on climate change  
- Co-designed sustainability certification course

**Advocacy Intern**  
*Common Energy* — *Jan 2021–May 2021*  
- Educated residents on community solar programs.  
- Managed data on power usage, billing, and savings; built customer service and outreach skills.

</div>
</details>

<details class="cv-section" open>
<summary>Teaching</summary>
<div class="cv-content"> 

**Teaching Assistant for Perspectives in Climate Change Seminar**  
*Cornell Dept. of Biological & Environmental Engineering* — *Jan 2021–May 2021*  
- Collaborated with Dr. Peter Hess to support course organization; graded ~50 assignments weekly; attended faculty meetings


</div>
</details>

<details class="cv-section" open>
<summary>Community Involvement</summary>
<div class="cv-content"> 

- **Member**, oSTEM: LGBTQ+ STEM Professional Association— *October 2025–Present*

- **Volunteer**, *Clinic by the Bay* — *Jan 2024–Present*  
  - Volunteer for the food pharmacy program (~100+ hours of service)  
  - Support uninsured patients through grocery delivery, nutrition education workshops, healthy cooking demos, and educational materials (brochures, handouts)

- **Volunteer**, *Garden for the Environment (San Francisco)* — *Jan 2025–Present*  
  - Contribute to growing and harvesting clean produce for delivery to the Haight-Ashbury Food Bank

- **Vice President**, Young Researchers Program — *Sept 2019–Dec 2022*   
  - Vice President (2022), Scientific Communications Team Lead (2020-2021)
  - Provided high school students the opportunity to practice mentored research
  - Organized career aspiration events and scientific development programs (classes, lectures, and symposium)
- **Member**, OASIS: Asian and Pacific Islander LGBTQ+ — *Sept 2021–Dec 2022*


</div>
</details>

<details class="cv-section" open>
<summary>Awards</summary>
<div class="cv-content"> 

**Howard Milstein Scholarship, Cornell University**  
*Awarded Mar 2020*  
- Awarded $5000 scholarship

**Tanner Dean Scholar, Cornell University**  
*Awarded Sept 2019*  
- Awarded $1000 scholarship and up to $5000 research grant

</div>
</details>

