# SULEYMAN HAJIZADEH
📧 suleyman.hacizade1@gmail.com | 📱 [Phone Number] | 📍 Baku, Azerbaijan  
🔗 [LinkedIn Profile] | 🐙 [GitHub Portfolio]

---

## EDUCATION
**Western Caspian University** — Baku, Azerbaijan  
*Bachelor of Science in Biology* | Expected Graduation: June 2026  
* **Cumulative GPA:** [Your GPA, e.g., 3.85/4.00]  
* **Relevant Coursework:** Molecular Biology, Genetics, Biochemistry, Computational Methods in Biology, Microbiology, Biostatistics.  
* **Academic Honors:** [Any scholarships or awards, e.g., Academic Excellence Scholarship].

---

## RESEARCH INTERESTS
* Computational Biology & Genomics
* High-Throughput Transcriptomics (Bulk/Single-Cell RNA-Seq)
* Structural Bioinformatics & Computational Biophysics
* Evolutionary Genetics & Molecular Phylogenetics

---

## TECHNICAL & COMPUTATIONAL SKILLS
* **Programming Languages:** Python (Advanced), R (Intermediate), Shell scripting (Bash).
* **Scientific Python Libraries:** Biopython, NumPy, Pandas, Scikit-Learn, Matplotlib, SciPy.
* **Bioconductor & R Stack:** DESeq2, WGCNA, pROC, ggplot2, edgeR.
* **Workflow Management & Reproducibility:** Snakemake, Conda, Git, GitHub.
* **Bioinformatics Tools:** HISAT2, Trimmomatic, FastQC, featureCounts, SRA Toolkit, BLAST, PDB Parser.
* **Operating Systems:** Linux (Ubuntu/Debian POSIX environment), macOS, Windows.

---

## RESEARCH & TECHNICAL PROJECTS

### 1. High-Throughput Transcriptomics Pipeline (Bulk RNA-Seq & DESeq2)
*Developed a portable, reproducible pipeline for differential gene expression analysis in Triple-Negative Breast Cancer (TNBC).*
* **Workflow Automation:** Built a modular [Snakemake](file:///bioinformatics/Github/Bioinformatics-analysis/module_4_tnbc_paper/Snakefile) pipeline integrating raw SRA read downloading (`fasterq-dump`), quality control (`FastQC`), adapter trimming (`Trimmomatic`), genomic alignment to the GRCh38 genome (`HISAT2`), and expression count generation (`featureCounts`).
* **Differential Expression:** Integrated [DESeq2](file:///bioinformatics/Github/Bioinformatics-analysis/module_4_tnbc_paper/scripts/run_deseq2_analysis.R) to identify Differentially Expressed Genes (DEGs). Documented the statistical principles of the negative binomial model for handling overdispersion, VST transformations, and ComBat-seq batch adjustments in a dedicated [methods primer](file:///bioinformatics/Github/Bioinformatics-analysis/module_4_tnbc_paper/STATISTICAL_METHODS.md).
* **Machine Learning Validation:** Designed a nested Leave-One-Out Cross-Validation (LOOCV) framework in Python with feature selection nested inside the training folds to prevent data leakage, yielding a robust classifier validated by randomized permutation tests (Empirical p-value < 0.05).

### 2. Custom Computational Phylogenomics Pipeline (`phylo_pipeline.py`)
*Created a command-line phylogenetic pipeline to reconstruct the evolutionary history of the COL1A1 gene across vertebrate lineages.*
* **Data Mining:** Automated the fetching of canonical coding sequences from the NCBI GenBank database via the `Biopython.Entrez` API for 7 model species (*Homo sapiens*, *Pan troglodytes*, *Mus musculus*, *Rattus norvegicus*, *Bos taurus*, *Gallus gallus*, and *Danio rerio*).
* **Distance Matrix Calculation:** Coded the mathematical models for nucleotide substitution—specifically the Jukes-Cantor (JC69) and Kimura 2-Parameter (K2P) distance matrices—directly from mathematical formulas in Python.
* **Neighbor-Joining Tree Construction:** Implemented the Neighbor-Joining (NJ) clustering algorithm from scratch in Python to compute branch lengths and topologies, outputting the reconstructed Newick tree and generating high-resolution cladogram visualizations using `matplotlib`.

### 3. Protein Computational Biophysics & Folding Analyzer
*Developed a physical structural bioinformatics tool to compute residue-level properties and thermodynamic potentials from crystallographic coordinate files.*
* **Coordinate Parsing:** Utilized Biopython’s PDB module to parse atomic coordinate files, extracting Cartesian coordinates ($X, Y, Z$) for Chain A Carbon-Alpha (C$\alpha$) atoms of target PDB structures (e.g., Insulin `1COH`).
* **Hydrophobic Core Modeling:** Coded a spatial packing density detector using a distance threshold of 8.0 Å, weighting packing values with Kyte-Doolittle hydrophobicity indexes to identify buried core residues.
* **Statistical Potential Energy Scoring:** Coded a contact potential scoring loop utilizing a simplified Miyazawa-Jernigan (MJ) statistical potential matrix to estimate non-covalent folding free energies.
* **Rigidity & Thermal Displacement Analysis:** Computed the Pearson correlation coefficient between C$\alpha$ packing densities and atom B-factors, revealing a strong negative correlation (e.g., $r = -0.3685$ for `1COH`) that mathematically validates core structural rigidity.

---

## ONLINE SPECIALIZATIONS & CERTIFICATIONS
* **Data Analysis for Life Sciences** — Harvard University via edX (Expected Completion: July 2026)
* **Bioinformatics MicroMasters** — University of Maryland Global Campus via edX (Expected Completion: August 2026)
* **Python for Data Science and Machine Learning** — Udemy (Completed)

---

## LANGUAGES
* **Azerbaijani:** Native
* **English:** Professional Working Proficiency (Targeting IELTS 7.5+ in July 2026)
* **Russian:** Conversational
