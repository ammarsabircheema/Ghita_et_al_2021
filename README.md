# NF-kB–dependent IRF1 activation programs cDC1 dendritic cells to drive antitumor immunity
**Authors:** Ghita Ghislat 1, Ammar S. Cheema 1, Elodie Baudoin 1, Christophe Verthuy 1, Pedro J. Ballester 2, Karine Crozat 1, Noudjoud Attaf 1, Chuang Dong 1, Pierre Milpied 1, Bernard Malissen 1, Nathalie Auphan-Anezin 1, Thien P. Vu Manh 1, Marc Dalod 1, Toby Lawrence 1,3,4,5 


1 CNRS, INSERM, Centre d'Immunologie de Marseille-Luminy (CIML), Turing Center for Living Systems, Aix-Marseille University, 13009 Marseille, France.

2 Cancer Research Center of Marseille CRCM, INSERM, Institut Paoli-Calmettes, Aix-Marseille University, CNRS, 13009 Marseille, France.

3 CNRS, INSERM, Centre d'Immunologie de Marseille-Luminy (CIML), Turing Center for Living Systems, Aix-Marseille University, 13009 Marseille, France. 

4 Centre for Inflammation Biology and Cancer Immunology, Cancer Research UK King's Health Partners Centre, School of Immunology and Microbial Sciences, King's College London, London SE1 1UL, UK.

5 Henan Key Laboratory of Immunology and Targeted Therapy, School of Laboratory Medicine, Xinxiang Medical University, Xinxiang, China.



**Abstract:**
Conventional type 1 dendritic cells (cDC1s) are critical for antitumor immunity. They acquire antigens from dying tumor cells and cross-present them to CD8+ T cells, promoting the expansion of tumor-specific cytotoxic T cells. However, the signaling pathways that govern the antitumor functions of cDC1s in immunogenic tumors are poorly understood. Using single-cell transcriptomics to examine the molecular pathways regulating intratumoral cDC1 maturation, we found nuclear factor kB (NF-kB) and interferon (IFN) pathways to be highly enriched in a subset of functionally mature cDC1s. We identified an NF-kB–dependent and IFN-y–regulated gene network in cDC1s, including cytokines and chemokines specialized in the recruitment and activation of cytotoxic T cells. By mapping the trajectory of intratumoral cDC1 maturation, we demonstrated the dynamic reprogramming of tumor-infiltrating cDC1s by NF-kB and IFN signaling pathways. This maturation process was perturbed by specific inactivation of either NF-kB or IFN regulatory factor 1 (IRF1) in cDC1s, resulting in impaired expression of IFN-y–responsive genes and consequently a failure to efficiently recruit and activate antitumoral CD8+ T cells. Last, we demonstrate the relevance of these findings to patients with melanoma, showing that activation of the NF-kB/IRF1 axis in association with cDC1s is linked with improved clinical outcome. The NF-kB/IRF1 axis in cDC1s may therefore represent an important focal point for the development of new diagnostic and therapeutic approaches to improve cancer immunotherapy.

## Goal of the Github:
This github repository contains the code that was used to analyze single cell RNA-seq data in article mentioned above.

## Datasets:

single cell RNA-seq datasets used in the study can be accessed online using the GEO accession number GSE171870.

## Code Description:

**Dockerfile:** contains the Dockerfile for generating the Docker image for performing the analysis

**seurat_analysis_only_cDC1_113_cells.Rmd:** used to generate Figures 2A, 2C, 2D and supplementary Figures S2A, S2B, S2C and S7F  

**analyzing_data_with_different_conds.Rmd:** used to generate results shown in Figures 6A, 6D and supplementary Figures S7B, S7C, S7E, S7F, S7G, S7N  

**re_analyzing_cDC1_data_from_Maier_et_al.Rmd:** used to generate suplementary Figures S8A, S8C, S8D, S8E 

**trajectory_inference_cDC1.Rmd:** used to generate Figure 6E, 6F and 6G

**jaccard_index_analysis_2.Rmd:** used to generate supplementary Figure S8B
