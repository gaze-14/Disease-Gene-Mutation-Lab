## From Gene Mutation to Disease: Li-Fraumeni Syndrome – TP53

## Student Information

**Name:** Gaze Everly M. Abrasaldo 
**Date of Analysis:** September 17, 2026

## Disease / Phenotype

**Li-Fraumeni syndrome (LFS)**

Li-Fraumeni syndrome is a hereditary cancer predisposition syndrome caused mainly by a germline pathogenic variant in the **TP53** tumor-suppressor gene.

## Gene

**Gene Symbol:** TP53
**Reference Transcript Accession:** NM_000546.6
**Reference Protein Accession:** NP_000537.3

## Documented Variant

**Nucleotide Variant:** c.1010G>A
**Protein Change:** p.Arg337His
**Mutation Type:** Missense mutation
**Variant:** NM_000546.6(TP53).1010G>A (p.Arg337His)

## ClinVar

**ClinVar Variation ID:** 12379
**ClinVar Accession:** VCV000012379.96

## Galaxy

**Galaxy History Name:** Abrasaldo_Li-Fraumeni_TP53_c.1010G>A_Lab.

## Project Description

This project investigates the relationship between the **TP53 c.1010G>A (p.Arg337His)** mutation and **Li-Fraumeni syndrome**. The analysis includes obtaining the TP53 reference coding sequence, translating the wild-type sequence into a predicted protein, manually introducing the documented mutation, translating the mutant sequence, and comparing the wild-type and mutant protein sequences.

## Reference Sequence Information

The TP53 reference transcript used in this analysis is **NM_000546.6**, with the coding sequence located at positions **143–1324**. The corresponding reference protein accession is **NP_000537.3**. The wild-type coding sequence is **1,182 bp** and translates into a predicted protein of **393 amino acids** in reading frame 1.

## Mutation Information

The documented mutation is **TP53 c.1010G>A**, which changes one nucleotide from **G to A** and results in the amino-acid substitution **p.Arg337His**. This is a single-nucleotide substitution and is classified as a **missense mutation**. The mutation does not change the reading frame or protein length.

## Results

The wild-type and documented mutant protein sequences first differ at **amino-acid position 337**. Only one amino acid is affected, and there are no downstream amino-acid changes. No amino acid was deleted or inserted, no premature stop codon was produced, and the protein length remains **393 amino acids**.

## Repository Contents

* `01_reference/` – WT CDS and WT protein sequences
* `02_documented_mutation/` – documented mutant CDS and mutant protein sequences
* `03_artificial_mutation/` – artificial mutant CDS and protein sequences
* `04_results/` – WT versus mutant alignment and results summary
* `05_report/` – final report
