# Assembling and binning of metagenomes pipeline

nf-core/mag is a bioinformatics best-practice analysis pipeline for assembly, binning and annotation of metagenomes.

You can find a more exhaustive description and running instructions in here: https://nf-co.re/mag/2.5.4/

Here we provide with a small manual to how to prepare, for running the pipeline and running it in the Microsoft Azure environment.

## Create samplesheet.csv as:
```
sample,run,group,short_reads_1,short_reads_2,long_reads
M01,L3,0,az://masldmice/data/M01/M01_EKDN240001175-1A_222TJJLT4_L3_1.fq.gz,az://masldmice/data/M01/M01_EKDN240001175-1A_222TJJLT4_L3_2.fq.gz,
M01,L8,0,az://masldmice/data/M01/M01_EKDN240001175-1A_222VF7LT4_L8_1.fq.gz,az://masldmice/data/M01/M01_EKDN240001175-1A_222VF7LT4_L8_2.fq.gz,
M02,L8,0,az://masldmice/data/M02/M02_EKDN240001176-1A_222VF7LT4_L8_1.fq.gz,az://masldmice/data/M02/M02_EKDN240001176-1A_222VF7LT4_L8_2.fq.gz,
```