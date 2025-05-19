# lncRNA-Preprocessing-and-Filtering
This pipeline for the preprocessing of RNA-Seq data and the identification of high-confidence long non-coding RNAs (lncRNAs). It is designed to facilitate lncRNA discovery, especially in disease-related studies such as viral infections (e.g., dengue).
The pipeline covers the following key steps:
Quality Control and Trimming, Alignment to Reference Genome, Transcript Assembly; lncRNA Filtering: Length, Exon count ≥ 2, Class codes, ORF Prediction, Coding Potential Evaluation: Tools such as (CPC2, PLEK, and CPAT), Homology Search: Final filtered lncRNA candidates are compared against UniProt using BLASTX to exclude conserved proteins. A BLASTN search against non-coding RNA databases.
This modular and customizable pipeline enables the accurate identification of both known and novel lncRNAs and is especially useful for downstream analyses like differential expression, network analysis, and biomarker discovery.
