# Gates Cambridge Scholarship Personal Statement
### Candidate: Suleyman Hajizadeh | Western Caspian University, Baku, Azerbaijan
### Word limit: 500 words | Programme: PhD Computational Biology / Bioinformatics

---

Science, as I have practised it, begins not with a tool but with a question. When I first encountered the Jukes-Cantor model — a mathematical equation expressing the probability that a nucleotide changes identity over evolutionary time — I did not reach for MEGA or any graphical interface. I opened a Python interpreter, derived the inversion formula by hand, and wrote the function myself. The result, `d = -3/4 · ln(1 - 4p/3)`, is a single line of code; but the act of deriving it is what made the biology real for me.

This impulse — to implement rather than to operate — defines my research approach and my motivation for a Cambridge PhD.

My primary project is a computational analysis of triple-negative breast cancer (TNBC), the most aggressive and therapeutically resistant subtype. Starting from publicly available RNA-seq data (GEO: GSE116212), I built an end-to-end analysis pipeline: automated SRA download, HISAT2 alignment, featureCounts quantification, and DESeq2 differential expression analysis, orchestrated with Snakemake for full reproducibility. I did not stop at running the software. I derived the mathematics underlying the Negative Binomial model (`Var(X) = μ + αμ²`), documented the Benjamini-Hochberg FDR procedure step-by-step, and applied a nested cross-validated machine learning classifier to distinguish TNBC molecular subtypes. A manuscript reporting these findings is currently under review at PLOS ONE.

Parallel to this, I implemented the Kimura 2-Parameter (K2P) evolutionary distance model and a Neighbour-Joining tree algorithm entirely from mathematical definitions — with no phylogenetics library — to analyse COL1A1 divergence across seven vertebrate species. I also implemented the Miyazawa-Jernigan statistical contact potential to assess hydrophobic core stability in the AKT1 kinase, combining it with crystallographic B-factor analysis to probe the relationship between packing density and structural flexibility. Every component was coded from the relevant equation, not from a pre-packaged function.

The constraint that shaped this approach is real: Western Caspian University is a young institution with minimal computational infrastructure and no bioinformatics research tradition. I built this portfolio with a laptop, an NCBI account, and a commitment to mathematical rigour. I do not present this as a hardship narrative — I present it as evidence that I can work independently and that I understand what I implement.

Cambridge is where I need to be. The Wellcome Sanger Institute's work on single-cell tumour heterogeneity and the MRC Biostatistics Unit's Bayesian approaches to genomic modelling represent the precise frontier I wish to join. A Cambridge PhD would give me the supervisory depth, the collaborative environment, and the computational resources to move from individual analyses to questions of genuine clinical impact — understanding why TNBC resists therapy, and what the transcriptome can tell us that we have not yet known how to ask.

The question precedes the tool. I am ready to ask harder ones.

---
*Word count: ~490*
