---
title: "Exploring the predictive power of crossover hotspots in maize"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Developed a feature-based machine learning model to predict crossover hotspot occurrence in maize using chromatin and genomic features.'
date: 2022-12-16
venue: 'BTRY 6840 Final Project'
paperurl: 'http://16nikita.github.io/files/final_paper_btry_6840.pdf'
citation: 'Nikita Sajai and Ruth Epstein (2022). &quot;Exploring the predictive power of crossover hotspots in maize.&quot; <i>Final Project</i>.'
---

In maize and other plant species, mechanisms of crossover (CO) hotspots, locations across the maize genome where there is an enrichment of COs, remain elusive. Human and mouse studies have revealed CO hotspots are dictated by a zinc-finger protein, PRDM9, which is completely absent in plants. Nevertheless, CO hotspots in plant species exist and are maintained across evolutionary history. Meiotic recombination, the process by which genetic material is exchanged, is being explored as an avenue for generating new forms of genetic diversity, so understanding what factors control the formation of CO hotspots in maize and other important crop species will give breeders the power to unlock new and favorable combinations of alleles that lead to productive varieties. We constructed a labeled dataset incorporating several known features of COs in maize: site-specific DNA methylation, nucleosome occupancy, and distance to various chromosomal features as CO formation is biased towards the telomeric regions of many plant species’ chromosomes. We also tested unconfirmed features such as indel density and SNP density. We visualized this data using the program based on non-linear dimensionality reduction, and we then use this dataset to implement a feature-based supervised machine learning model to answer if CO hotspot occurrence in maize can be predicted.

**Tools:**
* Dimensionality reduction & visualization: UMAP for projecting high-dimensional chromatin and genomic features
* Machine learning framework: Python 3
* Algorithms & libraries: XGBoost (v1.7.2), scikit-learn (sklearn) for building and evaluating supervised binary classification models to distinguish single COs from CO hotspots
