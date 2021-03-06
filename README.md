# Research Interests

This directory is for summarizing the research interests in my area. It gives most updated papers, as well as the old ones. One may want to browse through different categories in case he/she is interested in using Machine Learning tools to help cure cancer.

## Table of Contents
- [Genomic Sequencing Technologies](#genomic_sequencing_technologies)
    * [10X](#10x)
    * [Single Cell](#single_cell)
    * [Illumina](#illumina)
    * [PacBio](#pacbio)
    * [Optical Maps](#optical_maps)
    * [Nanopore](#nanopore)
    * [HiC](#hic)
- [Computational Tools](#computational_tools)
    * [Structural Variation Detection](#structural_variation_detection)
    * [Reconstructing Heterogeneity](#reconstructing_ITH)
- [Cancer Specific](#cancer_specific)
    * [Molecular Timing of Mutations](#molecular_timing_of_mutations)

---

## <a name="genomic_sequencing_technologies"></a>Genomic Sequencing Technologies ##

**<a name="10x"></a>10X**

**<a name="single_cell"></a>Single Cell Sequencing**

- scDNA-seq

- scRNA-seq

- combined seq
 
   - **DNA(CNA) and RNA (SIDR):**   Han, Kyung Yeon, et al. "SIDR: simultaneous isolation and parallel sequencing of genomic DNA and total RNA from single cells." Genome research 28.1 (2018): 75-87.
   
   - **DNA(CNA) and RNA (DR-seq):**   Dey, Siddharth S., et al. "Integrated genome and transcriptome sequencing of the same cell." Nature biotechnology 33.3 (2015): 285.
   
   - **DNA(CNA) and RNA (GT-seq):**   Macaulay, Iain C., et al. "G&T-seq: parallel sequencing of single-cell genomes and transcriptomes." Nature methods 12.6 (2015): 519-522.
   
   - **DNA(SNV) and RNA (TARGET-seq):**   Rodriguez-Meira, Alba, et al. "Unravelling intratumoral heterogeneity through high-sensitivity single-cell mutational analysis and parallel RNA sequencing." Molecular cell 73.6 (2019): 1292-1305.

**<a name="illumina"></a>Illumina Paired-end**

**<a name="pacbio"></a>PacBio**

**<a name="optical_maps"></a>Optical Maps**

**<a name="nanopore"></a>Nanopore**

**<a name="hic"></a>HiC**

---

## <a name="computational_tools"></a>Computational Tools

**<a name="structural_variation_detection"></a>Structural Variation Detection**

- DNA

- RNA

   - CNA
   
      - **Using scRNA alone and control cells (sciCNV):**   Madipour-Shirayeh, Ali, et al. "Simultaneous Profiling of DNA Copy Number Variations and Transcriptional Programs in Single Cells using RNA-seq." bioRxiv (2020).
      
      - **Expression and SNV VAF (CaSpER):**    Harmanci, Akdes Serin, Arif O. Harmanci, and Xiaobo Zhou. "CaSpER identifies and visualizes CNV events by integrative analysis of single-cell or bulk RNA-sequencing data." Nature Communications 11.1 (2020): 1-16.
       
      - **Inferring CNA from scRNA (Analysis done in Supp pp.4-5 and Figure S23 shall be considered for our analysis and comparison, and pp.6 for defining normal cells):**   Patel, Anoop P., et al. "Single-cell RNA-seq highlights intratumoral heterogeneity in primary glioblastoma." Science 344.6190 (2014): 1396-1401.


**<a name="reconstructing_ITH"></a>Reconstructing Heterogeneity**

- DNA
   - **Weaver: allele-specific copy numbers of SVs**
   - **Meltos: SNVs + SVs for tree reconstruction on multi-sample bulk (Bioinformatics 2020)**
   - **bulk + SCS for tree reconstruction on CNA:**   Tumor Copy Number Deconvolution Integrating Bulk and Single-Cell Sequencing Data, Journal of Computational Biology (2020).
   - **TUSV: using SV to reconstruct tree (Bioinformatics 2018)**

- RNA

   - **Overcome Drop-outs (SClineger):**   Lu, Tianshi, et al. "Overcoming Genetic Drop-outs in Variants-based Lineage Tracing from Single-cell RNA Sequencing Data." bioRxiv (2020).

---

## <a name="cancer_specific"></a>Cancer Specific ##

**<a name="multiple_datasets"></a>Joint Analysis with Multiple Datasets**

   - **DNA, RNA, immune on multi-region bulk and single cell:**   Non-Genetic Intra-Tumor Heterogeneity Is a Major Predictor of Phenotypic Heterogeneity and Ongoing Evolutionary Dynamics in Lung Tumors

**<a name="molecular_timing_of_mutations"></a>Molecular Timing of Mutations**

   - **PCAWG reconstructing history:**   Gerstung, Moritz, et al. "The evolutionary history of 2,658 cancers." Nature 578.7793 (2020): 122-128. 
   
   - **PCAWG DNA and RNA:**    Calabrese, Claudia, et al. "Genomic basis for RNA alterations in cancer." Nature 578.7793 (2020): 129-136. (PCAWG paper in 2020, having both whole genome sequencing and trascript alteration data.)
