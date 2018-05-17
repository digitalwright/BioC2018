# Mapping synteny between genomes with DECIPHER's FindSynteny function

# Nicholas Cooley, Erik Wright

npc19@pitt.edu, ESWRIGHT@pitt.edu

# Workshop Description

Syntenic regions are collinear blocks of homologous sequence
that are shared between two or more genomes. Synteny is often
used in comparative genomics to identify orthologous regions.
This workshop will be a lab on how to create and work with
objects of the class Synteny within the Bioconductor package
DECIPHER. This workshop will cover:

* Genome import and database construction
* Use of FindSynteny to map syntenic regions between genomes
* Accessing the Synteny object created by FindSynteny
* Extracting data from the Synteny object
* Visualization of the syntenic blocks

## Pre-requisites

* Familiarity with Biostrings
* Familiarity with DECIPHER Databases (Ref. 1)

1. [Wright, E. S. The R Journal 2016, 8 (1), 352–359.](https://journal.r-project.org/archive/2016-1/wright.pdf)

## Workshop Participation

This will be a lab where participants follow along on their computers.

## _R_ / _Bioconductor_ packages used

* Biostrings
* DECIPHER

## Time outline

| Activity                          | Time |
|-----------------------------------|------|
| Packages/Introduction             | 5m   |
| Sequence databases                | 10m  |
| Demonstration of synteny mapping  | 5m   |
| Explanation of function arguments | 5m   |
| Dissecting Synteny objects        | 10m  |
| Visualization of syntenic blocks  | 5m   |
| Alignment of syntenic regions     | 5m   |

# Workshop goals and objectives

## Learning goals

* Describe the use of syntenic mapping for comparative genomics
* Understand the appropriate use of FindSynteny and it's outputs

## Learning objectives

* Use DECIPHER functions to:
* Select genomes from NCBI or local databases
* Map synteny between genomes
* Analyze a synteny map among multiple genomes
* Provide a full understanding of the data structures involved
