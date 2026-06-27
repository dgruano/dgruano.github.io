---
layout: cv
title: CV
---

<div class="cv-header">
  <div class="cv-header-text">
    <h1>DANIEL GARCIA RUANO</h1>
    <p class="cv-subtitle">Geneticist and Bioinformatics Scientist</p>
    <p class="cv-contact">
      <a href="mailto:daniel.garciaruano@ibgc.cnrs.fr">daniel.garciaruano@ibgc.cnrs.fr</a> ·
      <a href="https://orcid.org/0000-0002-5033-8013">ORCID 0000-0002-5033-8013</a> ·
      <a href="https://github.com/dgruano">GitHub</a> ·
      <a href="https://www.linkedin.com/in/dgruano/">LinkedIn</a>
    </p>
  </div>
  <img class="cv-photo" src="/assets/cv-photo.png" alt="Daniel García-Ruano">
</div>

## PROFESSIONAL SUMMARY

**Bioinformatician and geneticist with 7+ years of research experience** spanning transcriptomics, machine learning for RNA biology, and experimental genetics. Current work focuses on **ML interpretability for lncRNA/mRNA classification** and **reproducible Snakemake pipelines for large-scale transcriptomic analyses**, with two manuscripts under review. Doctoral work applied whole-genome sequencing and variant-calling to experimental evolution, yielding three first-author peer-reviewed publications. I bring a rare combination of wet-lab and computational expertise, a consistent publication record across diverse biological questions, and a commitment to open-source and FAIR research practices.

## EDUCATION

**PhD in Cell Biology** *– "Revealing the link between cell volume and evolution"* · 2023
*University of Rennes 1 / IGDR CNRS UMR6290*

**Master's Degree in Clinical Cancer Research** · 2019
*University of Salamanca / Instituto de Biología Funcional y Genómica*

**Bachelor's Degree in Biotechnology** · 2018
*University of Salamanca / Instituto de Biología Funcional y Genómica*

## PROFESSIONAL EXPERIENCE

### Bioinformatics Scientist *(Temporary Associate Professor)* · 2024 – Present

*University of Bordeaux, Computational Biology & Bioinformatics Team (IBGC, UMR 5095)*

- **Developed an uncertainty-aware benchmarking framework** for mRNA/lncRNA classification tools, revealing systematic tool disagreement for ~45% of transcripts and demonstrating the discriminative value of transposable elements and non-B DNA features; first-author preprint on bioRxiv (2026).
- **Co-designed an interpretable deep-learning classifier** (multimodal: sequence + genomic context) for lncRNA identification, integrating transposable element content and non-B DNA motifs; manuscript under review at *Bioinformatics* (ECCB 2026).
- **Built end-to-end Snakemake pipelines** for (1) survival screening across 32 cancer types (in collaboration) and (2) benchmarking of computational transcript classification tools; all code versioned on GitHub.
- **Contributed to pydna and OpenCloning**, an open-source Python library and web app for molecular cloning design, focused on FAIR principles.
- **Supervised one Master's student** on transcript classification benchmarking.

### Postdoctoral Fellow *(Senior Genetics Scientist)* · 2023 – 2024

*University of Bordeaux, SyntheCell Team*

- **Applied RNA-seq and ChIP-qPCR** to dissect molecular basis of stress adaptation in fission yeast; manuscript in preparation.
- **Developed a CRISPR/Cas9 genome-editing strategy** to generate heterothallic strains from natural isolates for QTL mapping; published in *Yeast* (2024).

### PhD Candidate *(Junior Genetics Scientist)* · 2019 – 2023

*University of Rennes / IGDR CNRS UMR6290*

- **Implemented and extended the eVOLVER continuous culture platform** for long-term experimental evolution, delivering new software tools for experiment control and data analysis; published in *Open Biology* (2023).
- **Applied whole-genome sequencing and variant-calling** (GATK, FreeBayes) to track genomic adaptation across 16 evolving populations under 5 stress conditions.
- **Optimised fluorescence exclusion microscopy (FXm)** for high-throughput yeast cell volume measurement and developed an image analysis interface; published in *Journal of Cell Science* (2022).
- **Uncovered a stepwise adaptation mechanism**: SNV in *Toe2* transcription factor followed by a 10-copy CNV of target gene *SPBC36.01c*.

## LANGUAGES AND CORE COMPETENCES

**Programming:** Python (pandas, scikit-learn, seaborn), R (featureCounts, DESeq2, ggplot2), Bash

**Workflow / HPC:** Snakemake, Slurm/HPC, Git/GitHub, Conda

**Omics & Analysis:** RNA-seq (STAR, HISAT2, Salmon, htseq, Trinity), variant calling (GATK, FreeBayes)

**ML / AI:** Model interpretability, deep learning for sequence classification, benchmarking

**Wet Lab:** Fission yeast genetics, CRISPR/Cas9, ChIP-qPCR, fluorescence microscopy, microfluidics, flow cytometry

**Languages:** Spanish (native), English (C1, Cambridge-certified), French (professional proficiency)

## PUBLICATIONS

- **García-Ruano D**, Georges M, Mohanty S, Makova K, Chalopin D and Nikolski M. Uncertainty-aware benchmarking reveals ambiguous transcripts in mRNA–lncRNA classification. *bioRxiv* (2026). \[Preprint, first author\] [[DOI]](https://doi.org/10.64898/2026.04.14.718168)
- Georges M, **García-Ruano D**, Mohanty S, Makova K, Chalopin D and Nikolski M. Interpretable multimodal learning from sequence and genomic context for lncRNA classification. *Submitted to Bioinformatics (ECCB proceedings)* (2026). \[Under review\]
- Naji F\*, Oterino-Sogo S\*, Beltsung F, **García-Ruano D**, … Nikolski M, Rezvani HR. Spatial and Bulk Transcriptomics Defines the Molecular Evolution of Cutaneous Squamous Cell Carcinoma and Reveals Stage-Specific Biomarkers of Clinical Relevance. *bioRxiv, under revision at Cell Death and Disease* (2026). [[DOI]](https://doi.org/10.64898/2026.04.30.721943)
- Venkova L, **García-Ruano D**, Jain A, Charvin G, Coudreuse D. High-Throughput Measurement of Single-Fission Yeast Cell Volume Using Fluorescence Exclusion. *Methods in Molecular Biology* (2025). \[Book chapter\] [[DOI]](https://doi.org/10.1007/978-1-0716-4168-2_2)
- **García-Ruano D**, Hsu I, Leray B, Billard B, Liti G, Coudreuse D. Engineering heterothallic strains in fission yeast. *Yeast* (2024). [[DOI]](https://doi.org/10.1002/yea.3914)
- **García-Ruano D**\*, Jain A\*, Heins ZJ, Wong BG, Yimer Wolle E, Khalil AS, Coudreuse D. Long-term evolution of proliferating cells using the eVOLVER platform. *Open Biology* (2023). [[DOI]](https://doi.org/10.1098/rsob.230118)
- **García-Ruano D**, Venkova L, Jain A, Ryan JC, Radhakrishnan Balasubramaniam V, Piel M, Coudreuse D. Fluorescence exclusion – a rapid, accurate and powerful method for measuring yeast cell volume. *Journal of Cell Science* (2022). [[DOI]](https://doi.org/10.1242/jcs.259392)
- López-Goñi I, … **García-Ruano D**, … et al. #EUROMicroMOOC: using Twitter to share trends in Microbiology worldwide. *FEMS Microbiology Letters* (2019). [[DOI]](https://doi.org/10.1093/femsle/fnz141)

**Selected presentations:**

- Society for Molecular Biology and Evolution (SMBE) 2026, Copenhagen · Poster
- Oncosphere International Conference 2023, Bordeaux · Selected flash poster
- Journées Scientifiques ED-BS Bretagne-Loire 2022 · Talk
- EMBL Conference "Molecular Mechanisms in Evolution and Ecology" 2020 · Poster

## TEACHING EXPERIENCE

**Temporary Associate Professor (ATER)**, Université de Bordeaux · 2024 – Present
Full-time position (384 h) across 5 teaching units: **cell biology, developmental biology**, experimental imaging, and scientific communication; bilingual (FR/EN).

**Guest Lecturer**, University of Bordeaux · 2023
Invited lecture on cell division and the cell cycle.

**Teaching Assistant**, University of Rennes 1 · 2022
Eukaryotic Genetics, EDUC Alliance Initiative (24 h).

## SCIENCE COMMUNICATION & OUTREACH

- **Public engagement**: café talks, DNA extraction workshops for children, science fair activities on microscopy, molecular biology, and bioinformatics.
- **EUROMicroMOOC contributor**: co-authored publication in *FEMS Microbiology Letters* (2019).
- **SoyBiotec initiative**: YouTube channel and social media covering genetics, cancer research, and science news for general audiences.

## FUNDING & AWARDS

- 4th-year PhD extension grant · Fondation ARC pour la Recherche contre le Cancer (2022)
- Science communication prize · Fundación Antama (2019)
- Master's scholarship · Institute of Biomedicine of Salamanca, IBSAL (2019)
