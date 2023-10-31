# Genomic-Data-Analysis-using-Python-
In this notebook, I conducted genomic data processing using Python to investigate potential disease-associated gene variants in a male patient. The dataset was obtained from publicly available data provided by sequencers at the Institute of Mother and Child in Warsaw. The data originates from Next-Generation Sequencing (NGS) analysis of an anonymous patient and his mother.
<br /> Docker Image used: spark-edugen-2.4.3-0.1.7-ga024cfc
 
## Introduction
NGS (Next-Generation Sequencing) is a powerful technology used in genomics to decode and understand the genetic information contained in DNA. It provides a comprehensive view of an individual's genetic makeup, achieved by generating millions of short DNA sequences, or "short reads." These short reads are then aligned, assembled, and analyzed to reveal genetic variations, mutations, and other genomic features. NGS technology is essential for various applications in research and clinical settings, enabling the study of complex genetic traits,

## Purpose of NGS Data Analysis
The primary goal of NGS data analysis is to extract meaningful information from raw sequencing data. This information can include the identification of genetic variations, mutations, and other genetic features in the sequenced patient DNA that are crucial for understanding diseases. 

## NGS Data Analysis Workflow
NGS data analysis involves a multi-step process:

1. **Data Acquisition**: Raw sequencing data in FASTQ format, containing nucleotide reads and quality scores, is obtained from sequencing machines.
2. **Exploratory Data Analysis**: We explore the quality and length of the reads to assess data quality.
3. **Data Preprocessing**: Data is preprocessed to remove low-quality reads and adapters (sequences used to aid keeping track of separate sequences) used, improving the reliability of downstream analysis.
4. **Pipeline Operations**: Alignment tools like BWA map reads to a reference genome, and tools like GATK (Genome Analysis Toolkit) are used for variant calling, which is finding areas of the DNA that, after alligning to reference genome seems to be unique for the patient. 
5. **Data Visualization**: Tools like IGV (Integrative Genomics Viewer) are used to visualize data, aiding in exploring genomic features.
6. **Variant Analysis**: Variants are checked against publically available databases of variants, such as ClinVar to determine their clinical significance and association with diseases.

## Key insights:  
[in progress]
