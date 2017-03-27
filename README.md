# AACR 2017 - Abstract #558
## Computational analysis of clinically actionable genomic features: Precision Heuristics for Interpreting the Alteration Landscape (PHIAL)

This repository contains the figure generation code for the poster corresponding to AACR 2017 Abstract #558, "Computational analysis of clinically actionable genomic features: Precision Heuristics for Interpreting the Alteration Landscape (PHIAL)". For this project we compared PHIAL2 (Van Allen, 2013) and TARGET2 to their previously published versions using a cohort of 110 metatstatic melanoma (Van Allen, 2015) and 150 metastatic, castration resistant prostate samples (Robinson, 2015). 

The formal abstract for this presentation can be found here: http://www.abstractsonline.com/pp8/#!/4292/presentation/4249

## Presenters and Authors: 
Brendan Reardon, Nathanael Moore, Levi Garraway, Eliezer Van Allen.
### Affiliations
Dana-Farber Cancer Institute, Boston, MA; Broad Institute of MIT & Harvard, Cambridge, MA; Indiana University School of Medicine, Indianapolis, IN; Harvard Medical School, Boston, MA; Howard Hughes Medical Institute, Chevy Chase, MD.  

## Accompanying Abstract: 
### Background
PHIAL (Precision Heuristics for Interpreting the Alteration Landscape) was developed as a heuristic clinical interpretation algorithm for cancer genomic data to inform treatment decisions at the point of care and provide researchers with rapid assessment of tumor actionability. This approach used somatic whole exome sequencing data and a database of tumor alterations relevant for genomics driven therapy (TARGET). However, PHIAL was limited to first order genomic relationships, could not distinguish relative actionability given multiple actionable variants, did not maximize the richness of somatic-germline interactions, and could not leverage both exome and transcriptome data to move towards feature-based actionability. Towards that end, we developed a new interpretation methodology to address these areas and improve clinical actionability algorithms.
### Methods
We revised PHIAL to predict actionable alterations based on the presence of SNVs (in the context of allele specific expression from RNA-seq), indels, SCNAs, fusions, and global features (e.g., context-specific mutational burden) that imply actionability. Additionally, we refined and expanded the TARGET database to enable PHIAL to produce scores on multiple dimensions and reflect newly discovered relationships between genomics and clinical actions. Predictive implication values were assigned to reflect the validities of TARGET’s drug sensitivity, drug resistance, and prognostic claims.
### Results
We applied both the original (PHIAL1) and an updated version of PHIAL (PHIAL2) to a 255 patient cohort with whole exome/transcriptome sequencing data (146 castration-resistant prostate cancer and 109 metastatic melanoma samples). PHIAL1 identified 1,342 clinically actionable/biologically relevant events across the cohort with a median of 3 events per patient and 95% of patients having at least one event. PHIAL2 identified 2,508 events, with a median of 6 events per patient and 98.5% of patients harboring at least one event. Of these events, 8.12% were associated with an FDA-approved therapy and 2.09% with a clinical trial. PHIAL2 identified events in 9 patient samples that PHIAL1 associated with no events.
### Conclusion
PHIAL2 was able to identify and rank more putatively actionable alterations than PHIAL1, and effectively transitioned from a variant-based to a feature-based approach. This strategy may inform the utility of point-of-care whole-exome/transcriptome sequencing in larger contexts as these data emerge in clinical settings, and may bridge towards machine learning based approaches as patient outcomes are linked to genomic and transcriptomic features. Finally, PHIAL2 may ultimately provide a deeper understanding of, and suggest clinical actions for, cases in which there is no clear single genomic alteration associated with oncogenesis.
