# -p-falciparum-variant-calling-pipeline-
The purpose of this pipeline To identify genetic variants(snps, indels) across the whole genome from the P. falciparum parasites in two villages of Mali.

PartI:
We will first do a QC on the sequences using fasrqc
PartII 
Map the clean reads using BWA 
PartIII
PRE-PROCESSING ALIGNED READS using GATK and Picard
PartIV
Variant Discovery using GATK
