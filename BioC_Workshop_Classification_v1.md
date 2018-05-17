# Classifying marker gene sequences with the IDTAXA algorithm

# Travis De Wolfe, Erik Wright

tdewolfe@wisc.edu, eswright@pitt.edu

# Workshop Description

Marker gene sequences, such as the 16S rRNA, are commonly used to analyze microbiome samples.
An important part of this analysis is the assignment of sequences to taxonomic groups.
Here, we will demonstrate how to accurately classify sequences with the IDTAXA algorithm,
which is composed of the LearnTaxa and IdTaxa functions in the DECIPHER package.
This workshop will cover:

* Training a classifier based on a reference taxonomy
* Investigating putative problem taxonomic groups
* Classify new sequences to reference taxonomic groups
* Visualizing the classifications in a single sample
* Comparing classifications across multiple samples
* Extracting information from objects of class Taxa

## Pre-requisites

* Familiarity with Biostrings and XStringSet classes
* Reading through the [Classifying Sequences](http://DECIPHER.codes/Documentation/Documentation-ClassifySequences.html) vignette

## Workshop Participation

This will be a lab where participants follow along on their computers.

## _R_ / _Bioconductor_ packages used

* Biostrings
* DECIPHER

## Time outline

| Activity                               | Time |
|----------------------------------------|------|
| Packages/Introduction                  | 5m   |
| Description of the IDTAXA algorithm    | 5m   |
| The format of reference taxonomies     | 5m   |
| Creating a classifier object           | 5m   |
| Plotting Taxa objects of class Train   | 5m   |
| Investigating putative problem groups  | 10m  |
| Classifying new sequences              | 5m   |
| Visualizing Taxa objects of class Test | 5m   |
| Extracting taxonomic information       | 5m   |

# Workshop goals and objectives

## Learning goals

* Understand the basis of the IDTAXA algorithm
* Describe the difference between IdTaxa and LearnTaxa
* Know where to obtain reference taxonomies and how to use them
* Identify and investigate putative problem groups

## Learning objectives

* Interpret the output contained in objects of class Taxa
* Compare the classifications of reads belonging to different samples
* Formulate how to apply IDTAXA to your own microbiome sequences
