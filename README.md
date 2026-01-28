# E. coli NGS Analysis Pipeline

## Project Overview
This project demonstrates a complete bioinformatics pipeline for analyzing **Escherichia coli** (Strain K-12) genomic data. The goal is to perform quality control, alignment to a reference genome, and variant calling.

## Data Source
- **Organism:** E. coli
- **Reference Genome:** E_coli_ref_genome.fasta

## Pipeline Steps
1. **Quality Control:** Performed using `FastQC` to assess raw read quality.
2. **Trimming:** Used `Trimmomatic` to remove low-quality bases.
3. **Alignment:** Reads were mapped to the reference genome using `Bowtie2`.
4. **Variant Calling:** Identified SNPs and Indels, saved in `variants.vcf.gz`.

## Tools Used
- FastQC
- Bowtie2
- Samtools
- BCFtools

## Results
- High-quality alignment achieved with index files provided in `fastqc_practise/E_Coli_Index/`.
- Final variants are documented in the VCF files.

