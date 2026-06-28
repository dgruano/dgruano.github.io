---
layout: default
title: Home
---
# Hi, I'm Dani 👋

**Bioinformatician & Cell Biologist** · Postdoc / ATER @ [IBGC](https://github.com/cbib), Université de Bordeaux

I work at the intersection of experimental and computational biology, using code to understand how cells grow, adapt, and evolve. Lately, I've grown particularly interested in gene regulation and its evolution, with a focus on long non-coding RNAs. As an entry point into this field, I'm exploring the computational challenges of distinguishing lncRNAs from mRNAs.

![Focus](https://img.shields.io/badge/Working_on-LNClassifier-29ABE2?style=flat)

![Daniel's GitHub stats](https://github-readme-stats.vercel.app/api?username=dgruano&show_icons=true&hide_border=true&rank_icon=github)


## 🛠️ Featured Projects

### LNClassifier · [@cbib](https://github.com/cbib)
A research project to benchmark and improve machine learning tools for classifying long non-coding RNAs (lncRNAs) vs. mRNAs. The key challenge: current tools disagree on ~45% of transcripts, pointing to genuine biological ambiguity rather than algorithmic failure. The project integrates underexplored genomic features — transposable elements and non-B DNA motifs — to build more robust, interpretable classifiers. All pipelines are built with Snakemake.
 
| Repository | Description |
|---|---|
| [uncertainty_aware_lnclassifier](https://github.com/cbib/uncertainty_aware_lnclassifier) | Benchmarks 8 classification tools with inter-tool agreement and per-transcript uncertainty quantification |
| [rep_extraction_pipeline](https://github.com/cbib/rep_extraction_pipeline) | Extracts repetitive element features from transcript sequences using RepeatMasker |
| [nbd_extraction_pipeline](https://github.com/cbib/nbd_extraction_pipeline) | Extracts non-B DNA motif features (G-quadruplexes, Z-DNA, triplex, etc.) using gfa and G4Discovery |
| [beta_vae_lnclassifier](https://github.com/cbib/beta_vae_lnclassifier) | Deep learning classifier integrating sequence, repeat, and non-B DNA features for lncRNA/mRNA discrimination, by my amazing colleage [@mikageorges](https://github.com/mikageorges) |


### [OpenCloning](https://opencloning.org) · [frontend](https://github.com/OpenCloning/OpenCloning_frontend) · [backend](https://github.com/OpenCloning/OpenCloning_backend)
An open-source web platform for designing and documenting molecular cloning experiments. Supports a wide range of cloning strategies with a visual, history-preserving interface. Built with React + Python/FastAPI. Created and led by [@manulera](https://github.com/manulera); I contribute as a collaborator to both the frontend and backend.

### [pydna](https://github.com/pydna-group/pydna) · [@pydna-group](https://github.com/pydna-group)
Python library for simulating DNA assembly — Gibson assembly, homologous recombination, restriction cloning, and more. A core tool in the synthetic biology Python ecosystem (226 ⭐). Created and led by [@BjornFJohansson](https://github.com/BjornFJohansson); I contribute as a collaborator to this project.

---

## 📄 Selected Publications

- **García-Ruano D. et al.** Uncertainty-aware benchmarking reveals ambiguous transcripts in mRNA–lncRNA classification. *bioRxiv* (2026) [[DOI]](https://doi.org/10.64898/2026.04.14.718168)
- **García-Ruano D. et al.** Engineering heterothallic strains in fission yeast. *Yeast* (2024) [[DOI]](https://doi.org/10.1002/yea.3914)
- **García-Ruano D.\*, Jain A.\*, et al.** Long-term evolution of proliferating cells using the eVOLVER platform. *Open Biology* (2023) [[DOI]](https://doi.org/10.1098/rsob.230118)
- **García-Ruano D. et al.** Fluorescence exclusion — a rapid, accurate and powerful method for measuring yeast cell volume. *J Cell Sci* (2022) [[DOI]](https://doi.org/10.1242/jcs.259392)

\* Equal contribution · Full list on [ORCID](https://orcid.org/0000-0002-5033-8013)

---

## 🧰 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Snakemake](https://img.shields.io/badge/Snakemake-039475?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAADfklEQVR42rWXS4icRRDHfzUzu7BkFzfRxBVEfBD14oJILoIHTz4OQhBRBC9eDB4lePIiJvFgFETxILnoTTQSQSUGBAO+QG8GFOIDQRN3o4kbEze78/h5sD7pfH47mX2koOjp6e6qf3XX6wuGkNoG2jndAtwBLAKtYtsAmACOASeBACzFAL2IkFFJnVIfU99Xf3Z99Iv6orpdbY2i/G71h5qQwRq5Ts+pk8OUP5wb+0OEjELVuQX1XM67+d976lST8gdzw7Lrp6VU+pC6Pw2yAPGK2imVT6tzam8dVtetX1JfUD+urVcgHigB7Kkdvpw0SEM/VduR7/ErMJkh9L/XqY2roV6GbKtB5jlgWwfYkcqbaFAcjjUAGB+y1gbsALMNCsx5pXweWACWVgGkvDlrN7gAvAn0OsDWBqHV/CvgCPARcBw4k6B6QH+I8rHc187fEymzD7Qi4kS1sQN0GwT0gQPA0xFxVp0FrgduSEHTwKYVrA7gj0zZfwGnSoXp9GMAEdHtACeKg9W7vxMRu9RZ9RngzvSTyieuuMT194GzwBxwXP0M+DIijlbrETGo0NxcC8E59Ub1VvXrFUKpqy428IUcm8L5pLpPnU69UV7Jj0WCOJz/Hcj5+cxkJQ9GiPV+xns3gVX0lrqpVN7Kymfm7V3qZvVYCuhvUALqF0Bey1J/kWN8kou3qTPqT8XBjaSq1tyntlrFezwJHEoP7gGnc9xo6qQz7ykdMXKcUcfVMXV38Sy9Bj+4FA9GKFi3R+kL/yH6d3418DZw1xotHWSOaafVTTljdwkgiv6v2nATsBO4NxPR5hQ8jCIVbynkdRNEPeMeiqL5JCL6K3RKV2XymRihKkam38kE/WgaYEPN+fyiJwCuTZ4psp6ZVnsjWF9Z+z0wHxH9TDyPA89m+i4BHO2k8nuAfWnhZM3SKA7FiG+/ACyp88DeiHhJ7QL7s0RXqX+5SkQfXsYO6PeM+bZ6pBYJe1uJ5JosIP1a/V4rD5J7wJXAy8AU8DpwobjNg610vIPpsa3iytfDVRvWAZaB7cA24APg7wT3HfBN1fG8CvzW0LlsFAl0ImIxu6oW8FREdFsZfn8CT+TCYIOVV7cyKLql54HDTfG+s/Yptl7q5fiFujV1XKeOD/s8u1/9dgO+E6qzp9Udq3swnVAfUd9N9KdWAajac0Z9Q71lmK5/APlCCp61UjJ6AAAAAElFTkSuQmCC&logoColor=white)
![Slurm](https://img.shields.io/badge/Slurm-HPC-555555?style=flat&labelColor=4CAEE3&logo=data:image/png;base64,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&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)


Machine learning · RNA-seq · Genome analysis · Experimental evolution · Microscopy image analysis

---

## 📬 Find me

[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-5033-8013)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dgruano-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/dgruano)
[![Bluesky](https://img.shields.io/badge/Bluesky-%40soybiotec.es-0285FF?style=flat&logo=bluesky&logoColor=white)](https://bsky.app/profile/soybiotec.es)
[![Institut IBGC](https://img.shields.io/badge/IBGC-UMR%205095-blue?style=flat)](https://www.ibgc.cnrs.fr/)

> *Bioinformatician at [@cbib](https://github.com/cbib) · Bordeaux, France*
