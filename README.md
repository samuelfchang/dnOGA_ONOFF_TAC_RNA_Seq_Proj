# dnOGA_ONOFF_TAC_RNA_Seq_Proj
 Bulk RNA Seq for dnOGAh ONOFF TAC Project in Wende Lab
 
Associated with manuscript: *will insert here

NCBI GEO Accession Number: *will insert here
 
Contact: sfchang@uab.edu or adamwende@uabmc.edu

## Decription of study/project 

Bulk RNA Sequencing of left ventricle mouse tissue from current project via Illumnia NovaSeq 6000 at UAB Helfin Genomics/Sequencing Core: output from core = .fastq files

Upstream analysis (following NF Core's Bulk RNA Seq Pipeline):
1) FastQC (version 0.11.7-Java-1.8.0_74) and MultiQC (version 0.8)
2) STAR alighnment (version 2.7.3a-GCC-6.4.0-2.28) and Salmon Quantification (version 1.8.0-gompi-2020b), using genome GRCm39 (GENCODE release M32)
3) MultiQC of all files

Downstream analysis: R version 4.3.1, R-studio version 2024.12.0+467

Last updated: 2025/05/27
