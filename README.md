# Homework 1
Genetic Data Analysis

## Task Overview

The provided VCF file contains results from a population study on genetic mutations.  
Subjects affected by a disease are labeled as `case_x`, and healthy individuals as `control_x`.
The goal is to extract, visualize, and statistically analyze these mutations to identify those associated with the disease.

## Subtasks:
- Count and summarize participants and mutations
- Visualize mutation characteristics using histograms
- Apply chi-square tests to identify disease-associated mutations
- Create a Manhattan plot to visualize p-values across the genome
- Evaluate Hardy-Weinberg equilibrium for significant mutations
- Use UCSC Genome Browser and OMIM to identify genes related to top mutations

# Homework 2

## Task Overview
The provided FASTQ files result from sequencing a portion of the exome located on chromosome 11. 
The data originates from samples in the 1000 Genomes Project.
The whole is to analyze whole-exome sequencing data from the chromosome and detect the source of contamination.

## Subtasks:
- Perform quality control on raw FASTQ files using **FastQC**
- Align reads to the **hg38 reference genome** using **BWA-MEM**
- Analyze mapping statistics with **pysam**
- Process alignment data following **GATK best practices** (mark duplicates, BQSR)
- Call and hard-filter variants using **HaplotypeCaller**
- Compute variant statistics, such as SNP/INDEL counts and **Ti/Tv ratio**
- Annotate variants with **Funcotator**, focusing on **ClinVar clinical significance**
- Detect non-human contamination by assembling **unmapped reads** and identifying source organisms with **BLAST**
