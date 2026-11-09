# hcc1395-rnaseq-snv-pipeline
An educational pipeline for detecting and annotating SNV candidates from HCC1395 RNA-seq reads
variant (SNV) candidates from paired-end RNA-seq reads of the HCC1395
breast cancer cell line. This example focuses on chromosome 22 of GRCh38.

## Workflow

FastQC → fastp → HISAT2 → samtools → bcftools → RefSeq annotation
and transcript-specific coding effect prediction.

## Manual walkthrough results

- Overall alignment rate: 97.04%
- Variant records before filtering: 8,057
- SNV candidates after filtering: 546
- Unique SNVs with predicted coding effects: 154

## Scope

The results describe candidates observed in one tumor RNA-seq sample.
They do not establish tumor-specific DNA mutations.
