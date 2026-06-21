# SULEYMAN HAJIZADEH
📧 suleyman.hacizade1@gmail.com | 📍 Baku, Azerbaijan  
🔗 [LinkedIn](https://www.linkedin.com/in/suleyman-hajizadeh-609732213) | 🐙 [GitHub](https://github.com/SuleimanHajizadeh)

---

## PROFESSIONAL SUMMARY
Dedicated and detail-oriented Bioinformatician with a strong background in Genomics, high-throughput Gene Expression analysis, and Sequence Alignment. Proficient in Python and R for clinical and biological data analysis. Experienced in building reproducible pipeline architectures (Snakemake) and implementing statistical machine learning models to solve complex biomedical questions.

---

## EDUCATION
**Western Caspian University** — Baku, Azerbaijan  
*Bachelor of Science in Biology* | Expected Graduation: June 2026  
* **Relevant Coursework:** Molecular Biology, Genetics, Biochemistry, Computational Methods in Biology, Microbiology, Biostatistics.  
* **Academic Honors:** Independent researcher in computational genomics and transcriptomics conducted in parallel with degree coursework.

---

## CORE INTERESTS & EXPERTISE
* **Genomics & Transcriptomics:** Bulk/Single-Cell RNA-Seq, Differential Gene Expression.
* **Sequence Alignment:** Genomic sequence comparison, mutation profiling, and phylogenetic reconstruction.
* **Data Analysis & Visualization:** PCA, Heatmaps, statistical modeling, and workflow automation.
* **Structural Bioinformatics:** 3D protein structure prediction and macromolecular coordinate analysis.

---

## TECHNICAL & COMPUTATIONAL SKILLS
* **Programming Languages:** Python (Advanced), R (Intermediate), Shell scripting (Bash).
* **Genomics & Sequence Analysis:** HISAT2, Trimmomatic, FastQC, featureCounts, SRA Toolkit, BLAST, PDB Parser.
* **Bioconductor & R Stack (Gene Expression & Data Analysis):** DESeq2, WGCNA, pROC, ggplot2, edgeR, limma.
* **Scientific Python Libraries:** Biopython, NumPy, Pandas, Scikit-Learn, Matplotlib, SciPy.
* **Workflow Management & Reproducibility:** Snakemake, Conda, Git, GitHub.
* **Operating Systems:** Linux (Ubuntu/Debian POSIX environment), macOS, Windows.

---

## PROJECTS & RESEARCH EXPERIENCE

### 1. High-Throughput RNA-Seq & Gene Expression Pipeline (TNBC Cohort)
*Developed a portable, reproducible pipeline for differential gene expression analysis and transcriptomic classification in Triple-Negative Breast Cancer.*
* **Workflow Automation:** Built a modular [Snakemake](https://github.com/SuleimanHajizadeh/Bioinformatics-analysis/blob/master/workflows/bulk_rnaseq/Snakefile) pipeline integrating raw SRA read downloading (`fasterq-dump`), quality control (`FastQC`), adapter trimming (`Trimmomatic`), genomic alignment to the GRCh38 genome (`HISAT2`), and expression count generation (`featureCounts`).
* **Differential Gene Expression & Stats:** Integrated [DESeq2](https://github.com/SuleimanHajizadeh/Bioinformatics-analysis/blob/master/workflows/bulk_rnaseq/scripts/run_deseq2_analysis.R) to identify Differentially Expressed Genes (DEGs). Documented the statistical principles of the negative binomial model for handling overdispersion, VST transformations, and ComBat-seq batch adjustments in a dedicated [methods primer](https://github.com/SuleimanHajizadeh/Bioinformatics-analysis/blob/master/docs/STATISTICAL_METHODS.md).
* **Machine Learning Validation:** Designed a nested Leave-One-Out Cross-Validation (LOOCV) framework in Python with feature selection nested inside the training folds to prevent data leakage, yielding a robust classifier validated by randomized permutation tests (Empirical p-value < 0.05).

### 2. Custom Sequence Alignment & Computational Phylogenomics Pipeline (`phylo_pipeline.py`)
*Created a command-line phylogenetic pipeline to align and reconstruct the evolutionary history of the COL1A1 gene across vertebrate lineages.*
* **Data Mining:** Automated the fetching of canonical coding sequences from the NCBI GenBank database via the `Biopython.Entrez` API for 7 model species (*Homo sapiens*, *Pan troglodytes*, *Mus musculus*, *Rattus norvegicus*, *Bos taurus*, *Gallus gallus*, and *Danio rerio*).
* **Sequence Alignment & Distance Matrix:** Coded the mathematical models for nucleotide substitution—specifically the Jukes-Cantor (JC69) and Kimura 2-Parameter (K2P) distance matrices—directly from mathematical formulas in Python.
* **Clustering Algorithm:** Implemented the Neighbor-Joining (NJ) clustering algorithm from scratch in Python to compute branch lengths and topologies, outputting the reconstructed Newick tree and generating high-resolution cladogram visualizations using `matplotlib`.

### 3. Protein 3D Structural Biophysics & Coordinate Analyzer
*Developed a structural bioinformatics tool to compute residue-level properties and thermodynamic potentials from crystallographic coordinate files.*
* **Coordinate Parsing:** Utilized Biopython’s PDB module to parse atomic coordinate files, extracting Cartesian coordinates ($X, Y, Z$) for Chain A Carbon-Alpha (C$\alpha$) atoms of target PDB structures (e.g., Insulin `1COH`).
* **Spatial Modeling:** Coded a spatial packing density detector using a distance threshold of 8.0 Å, weighting packing values with Kyte-Doolittle hydrophobicity indexes to identify buried core residues.
* **Thermodynamic Scoring:** Coded a contact potential scoring loop utilizing a simplified Miyazawa-Jernigan (MJ) statistical potential matrix to estimate non-covalent folding free energies.
* **Validation:** Computed the Pearson correlation coefficient between C$\alpha$ packing densities and atom B-factors, revealing a strong negative correlation (e.g., $r = -0.3685$ for `1COH`) that mathematically validates core structural rigidity.

### 4. AlphaFold2 Structural Analysis — AKT1 Kinase (TNBC)
*Predicted and analyzed the 3D structure of the AKT1 hub kinase involved in breast cancer cell signaling.*
* **Structure Prediction:** Generated the 3D structure of the AKT1 hub kinase using ColabFold v1.6.1 (AlphaFold2 multimer); achieved a mean pLDDT of 65.61 across the full chain.
* **Structural Metrics:** Generated per-residue pLDDT confidence plots, Ramachandran backbone torsion analysis, C$\alpha$ contact maps, and PyMOL publication-quality renders.

---

## ONLINE SPECIALIZATIONS & CERTIFICATIONS
* **Data Analysis for Life Sciences** — Harvard University via edX (Expected Completion: July 2026)
* **Bioinformatics MicroMasters** — University of Maryland Global Campus via edX (Expected Completion: August 2026)
* **Python for Data Science and Machine Learning** — Udemy (Completed)

---

## AFFILIATIONS
* **Institute of Molecular Biology & Biotechnology (IMBB)** — Baku, Azerbaijan (2023 – Present)  
  *Bioinformatician (Independent Researcher)*

---

## LANGUAGES
* **Azerbaijani:** Native
* **English:** Professional Working Proficiency (Targeting IELTS 7.5+ in July 2026)
* **Russian:** Conversational
