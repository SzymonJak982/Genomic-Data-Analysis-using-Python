# Genomic-Data-Analysis-using-Python-
In these notebooks I conducted genomic data analysis using Python to investigate potential disease-associated gene variants in a sequenced DNA from the  male patient and his mother. The data was made available by the Institute of Mother and Child in Warsaw. DNA was sequenced using Illumina platform Next- Gen sequencer.
<br /> Docker Image used: spark-edugen-2.4.3-0.1.7-ga024cfc
 
## Introduction
NGS (Next-Generation Sequencing) is a powerful technology used in genomics to decode and understand the genetic information contained in DNA. It provides a comprehensive view of an individual's genetic makeup, achieved by generating millions of short DNA sequences, or "short reads." These short reads are then aligned, assembled, and analyzed to reveal genetic variations, mutations, and other genomic features. NGS technology is essential for various applications in research and clinical settings, enabling the study of complex genetic traits,

## Purpose of NGS Data Analysis
The primary goal of NGS data analysis is to extract meaningful information from raw sequencing data. This information can include the identification of genetic variations, mutations, and other genetic features in the sequenced patient DNA that are crucial for understanding diseases. 

## NGS Data Analysis Workflow
NGS data analysis involves a multi-step process:

1. **Data Acquisition**: Raw sequencing data in FASTQ format, containing nucleotide reads and quality scores, is obtained from sequencing machines.
2. **Exploratory Data Analysis**: Exploration of the quality and length of the reads to assess data quality.
3. **Data Preprocessing**: Preprocessing of the data in order to remove low-quality reads and adapters (sequences used to aid keeping track of separate sequences) used, improving the reliability of downstream analysis.
4. **Pipeline Operations**: Alignment tools like BWA map reads to a reference genome, and tools like GATK (Genome Analysis Toolkit) are used for variant calling.
5. **Data Visualization**: Tools like IGV (Integrative Genomics Viewer) are used to visualize data, aiding in exploring genomic features.
6. **Variant Analysis**: Variants are checked against publically available databases of variants to determine their clinical significance and association with diseases.

## Key insights:  
- The likely-pathogenic variant in SNAP25-AS1 was identified in both the son's and the mother's DNA, reinforcing its potential significance in the context of disease development
- SNAP25-AS1 variant present in patient might be associated with rare genetically conditioned diseases like Epileptic Encephalopathy.
  
