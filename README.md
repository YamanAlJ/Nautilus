Nautilus
Nautilus is a biologically informed pipeline for pathway elucidation and gene discovery from transcriptomic data.
It takes raw gene expression data and produces ranked gene candidates for missing or unknown steps in biosynthetic pathways.

Currently, Nautilus is being used to study and elucidate the full fucoxanthin biosynthesis pathway in diatoms, identifying and validating unknown genes involved.

Current Capabilities
 - Sample labeling using GSVA to assign activity scores based on custom gene set expression
 - Gene-level labeling via differential expression using pyDESeq2, based on GSVA-derived sample contrasts
 - Dimensionality reduction from tens of thousands of genes to a focused set of a few hundred high-confidence candidate genes (ML-ready)

In Development
 - Feature attribution using pmVAE to further narrow to a handful of top-ranked genes
 - Function prediction of top candidates to identify plausible enzymatic roles
 - Multimodal integration of genomic data alongside expression data
 - File manegemnt improvements
