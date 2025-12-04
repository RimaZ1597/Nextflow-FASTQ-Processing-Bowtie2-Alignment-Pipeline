# Nextflow FASTQ Processing & Bowtie2 Alignment Pipeline

This repository contains a simple, modular Nextflow pipeline that performs quality trimming of FASTQ files using Unix tools (e.g., `cutadapt`) and sequence alignment using `bowtie2`. The project demonstrates how to build reproducible, automated workflows for NGS data processing using Nextflow.

---

## Features

* Automatic detection of FASTQ input files  
* Trimming & filtering of sequencing reads using `cutadapt`
* Reference genome indexing using `bowtie2-build`
* Sequence alignment using `bowtie2.`
* Output generation in trimmed FASTQ and SAM formats
* Fully reproducible Nextflow workflow

---

## Purpose of This Project

This project was created to:

* Practice writing modular Nextflow pipelines. 
* Understand processes, channels, inputs, and outputs. 
* Learn how to integrate common NGS tools in a workflow 
* Demonstrate FASTQ trimming and basic read alignment
* It serves as a foundational template for beginners learning workflow automation in bioinformatics.

