
## Meta-analysis of colorectal cancer metagenomic studies

Talk held at the __3rd Workshop on Statistical and Algorithmic
Challenges in Microbiome Data Analysis__ on 2019-04-01

__Abstract__  
Association studies have linked microbiome alterations with many human
diseases, but not always reported consistent results, necessitating
cross-study comparisons.
Here, we present a meta-analysis of eight fecal shotgun metagenomic studies
of CRC (including 386 cases and 392 controls) that are diverse in geographic
sampling range and metagenomic data generation. Whilst controlling for
technical and clinical confounders, we identified a core set of 29 species
significantly enriched in CRC metagenomes (FDR < 1E-5), including 8 species
without genomic reference.
We extended the SIAMCAT R package to be able to train metagenomic
classification models to detect CRC based on taxonomic and functional
profiles for each of the studies. In the holdout-setting, the models
generally retained high accuracy, but combining training data across studies
(leave-one-study-out, LOSO) further improved model accuracy (0.83, area
under the receiver operating characteristic curve, AUROC). Additionally,
LOSO classifiers were CRC-specific as they maintained the expected false
positive rate on samples from other microbiome-disease association studies.
Functional analysis of CRC metagenomes revealed protein and mucin catabolism
genes to be enriched while carbohydrate degradation genes were depleted.
Moreover, we inferred elevated levels of secondary bile acid conversion
pathways from CRC metagenomes suggesting a metabolic link between
cancer-associated gut microbes and a fat- and meat-rich diet.
Through extensive validations, this meta-analysis firmly establishes
globally generalizable, predictive taxonomic and functional microbiome
signatures that could become the basis for future diagnostic tests.
Furthermore, the SIAMCAT R package provides the methodology facilitating
future meta-analyses for other microbiome-disease associations.
