# Performing multiple alignment of homologous sequences with DECIPHER

# Erik Wright

eswright@pitt.edu

# Workshop Description

Multiple sequence alignment is useful across many domains of biology, and is particularly difficult when sequences are very dissimilar.
In this lab, we will demonstrate how to align sequences in R using the DECIPHER package.
In particular, we will focus on how to choose the best input options to ensure a high quality alignment.
This workshop will cover:

* Importing sequences from a FASTA file
* Choosing the right function for aligning your sequences
* Inspecting the output multiple sequence alignment
* Understanding important input parameters
* Downstream analyses that are enabled by alignment

## Pre-requisites

* Familiarity with Biostrings and XStringSet classes
* Reading through the [Art of Alignment](http://DECIPHER.codes/Documentation/Documentation-ArtOfAlignment.html) vignette
* Quickly reading the publication about AlignSeqs (Ref. 1)

1. [Wright, E. DECIPHER: harnessing local sequence context to improve protein multiple sequence alignment. BMC Bioinformatics 16, 322 (2015).](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-015-0749-z)

## Workshop Participation

This will be a lab where participants follow along on their computers.

## _R_ / _Bioconductor_ packages used

* Biostrings
* DECIPHER

## Time outline

| Activity                              | Time |
|---------------------------------------|------|
| Packages/Introduction                 | 5m   |
| Different functions for alignment     | 10m  |
| Demonstration of multiple alignment   | 5m   |
| Practicing aligning your sequences    | 5m   |
| Important parameters and settings     | 5m   |
| Determining alignment quality         | 5m   |
| Visualizing an alignment              | 5m   |
| Downstream analyses with alignments   | 10m  |

# Workshop goals and objectives

## Learning goals

* Know which DECIPHER function is best for aligning your sequences
* Understand how to tell when an alignment is of good quality

## Learning objectives

* Be able to apply DECIPHER's alignment functions to your own sequences
* Perform downstream analyses starting from a multiple sequence alignment
