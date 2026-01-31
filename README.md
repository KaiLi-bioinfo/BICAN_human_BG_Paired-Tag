# BICAN_human_BG_Paired-Tag

Paired-Tag single-cell multi-omics profiling of histone modifications and RNA expression in the human basal ganglia.

## Overview
The basal ganglia are essential subcortical hubs that coordinate movement, cognition, and affect, and are deeply implicated in a wide range of neurological and psychiatric conditions. Despite their importance, the regulatory logic that establishes and maintains basal ganglia cell-type identity remains poorly characterized, limiting our ability to interpret non-coding genetic risk variants linked to brain disease.

This repository supports a comprehensive single-cell Paired-Tag study of the adult human basal ganglia, integrating histone modification profiles with transcriptomic measurements across multiple anatomically defined regions. By jointly analyzing chromatin states and gene expression, the study delineates cell-type-resolved regulatory programs, including the selective deployment of activating and repressive regulatory elements and transcription factor networks underlying neuronal identity. Spatial transcriptomic data from matched regions further reveal regional and cellular heterogeneity in epigenomic organization. Comparative analyses between human and mouse highlight a dichotomy in evolutionary constraint, with core neuronal regulatory circuits conserved while inducible regulatory programs show substantial divergence. Together, this atlas provides a foundation for linking basal ganglia cell types to neuropsychiatric disease risk and for developing predictive models of regulatory element function and variant impact.

## Data
Raw sequencing data are available through controlled-access repositories. Processed data objects are described in the analysis notebooks.

Key related resources and publications include:

- **Basal ganglia cell-type annotation reference:**  
  Hu et al., *bioRxiv* (2025). Preprint describing comprehensive single-cell cell type labels used in this work.  
  https://www.biorxiv.org/content/10.64898/2025.12.15.694496v1  
  **Corresponding atlas data:**  
  https://brain-map.org/consortia/hmba

- **Basal ganglia HiC loop & ABC link:**  
  A Multimodal Single-Cell Epigenomic and 3D Genome Atlas of the Human Basal Ganglia. [link]
  https://github.com/DingWB/BG_snm3C-seq

- **Basal ganglia Visualization of single-cell multi-omics data:**  
  An Integrated Single-Cell and Epigenomic Resource for Comparative Analysis of the Basal Ganglia [link]
  https://basalganglia.epigenomes.net/.

- **Paired-Tag method and analysis:**  
  *Nature Methods* (2021) — Introducing the Paired-Tag protocol for joint profiling of histone modifications and transcription.  
  https://www.nature.com/articles/s41592-021-01060-3  
  *Nature structural & molecular biology* (2023) — Droplet-based single-cell joint profiling of histone modifications and transcriptomes.
  https://www.nature.com/articles/s41594-023-01060-1
     https://github.com/Xieeeee/Droplet-Paired-Tag

- ## Quality Control, Peak Calling, and Chromatin State Annotation:**  

Quality control and pseudo-bulk peak calling were conducted separately for each cell type following the ENCODE histone ChIP-seq standards. Peaks were called using the ENCODE ChIP-seq processing pipeline, and replicate consistency was evaluated using the Irreproducible Discovery Rate (IDR) framework. Chromatin state modeling and segmentation were performed using ChromHMM according to ENCODE-recommended protocols.

References:
- ENCODE histone ChIP-seq pipeline  
  https://www.encodeproject.org/chip-seq/histone/

- IDR software  
  https://www.encodeproject.org/software/idr/

- ChromHMM strategy  
  https://www.encodeproject.org/publications/8468259b-3be2-4483-970c-9ce1d4d93f3a/
  
- **Homeobox gene family overview:**  
  Springer Biology Reports (2007) — Review of homeobox genes and developmental regulatory roles.  
  https://link.springer.com/article/10.1186/1741-7007-5-47  
  Supplementary table of gene annotations:  
  https://static-content.springer.com/esm/art%3A10.1186%2F1741-7007-5-47/MediaObjects/12915_2007_143_MOESM7_ESM.htm

Please see the respective publications and repositories for detailed data access instructions and usage agreements.
