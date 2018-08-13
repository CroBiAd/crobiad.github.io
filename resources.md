---
layout: page
title: Resources
permalink: /resources/
---

# Software

The group develops a wide range of software, predominantly aimed at biology end-users in order to
democratize crop genomic resources.

Because of the nature of our funding and research, much of our code is developed
internally and maintained using git repositories on a [local GitLab](/internal/code) install.
As projects approach publication, these resources are moved to our publically accessible
[GitHub account](https://github.com/CroBiAd).

## Public Access

  * [POTAGE](/potage/) (pronounced "[pəʊˈtɑːʒ](http://img2.tfd.com/pron/mp3/en/UK/df/dfskskssdfd5drh7.mp3)"): A Visualisation
    Tool for Speeding up Gene Discovery in Wheat. Accepted in Scientific Reports
    (doi: [10.1038/s41598-017-14591-7](https://dx.doi.org/10.1038/s41598-017-14591-7)).
  * [**D**iversity **A**mong **W**heat ge**N**omes (DAWN)](/dawn/) submitted.

## Restricted to the School of Agriculture, Food & Wine

  * [agwine-blast](/afw/blast): A BLAST server containing the IWGSC RefSeq v1.0 assembly.

## Restricted to the Internal Network

  * [coching](/internal/coching)
  * [bwpf](/internal/bwpf): Bread Wheat Promoter Finder
  * [blast](/internal/blast): A BLAST server containing a mix of published and unpublished data sets
  * [POTAGE](/internal/potage): A POTAGE server containing published and unpublished data sets
  * [fetch](/internal/fetch): Simple sequence retrieval for selected genome assemblies
  * [dev-DAWN](/dev-dawn/): Diversity Among Wheat geNomes
  * blast-dev
  * [GitLab](/internal/code): Project/code/software development resources
  * [bareos](/internal/bareos): Backup server
  * [Genome Ribbon](/internal/ribbon): Web server for visualising structural variants generated from PacBio alignments.
    Modified to load decompressed CSI BAM index files.

# Scientific Computing Infrastructure

Research involving large, complex, plyploid genomes such as that of wheat often requires computers with large amounts
of RAM. However, such infrastructure is not normally available from typical high performance computing (HPC) providers.
As such, we operate our own scientific computing infrastructure, which includes several large memory nodes.

Our current infrastructure comprises of:

  * A Slurm based cluster consisting of 2 compute nodes with the following specs:
    * 72 CPUs (Intel Xeon E5-2699v3 @ 2.30GHz)
    * 755 GBytes RAM
    * 880 GBytes fast local storage (2 x SSD's in RAID0)
    * Access to 120 TBytes of clustered storage
  * A stand-alone compute node with the following specs:
    * 64 CPUs (Intel Xeon E7-4830 @ 2.13GHz)
    * 512 GBytes RAM
    * 1.7 TBytes fast local storage
    * Access to 120 TBytes of clustered storage

In addition to these local hardware resources, the group also has access to resources made available through:

  * [NeCTAR Research Cloud](https://nectar.org.au/research-cloud/) (2 allocations: one for training and one for the group)
    * 430 CPUs
    * 1.7 TBytes RAM
    * 5 TBytes of object storage
  * University of Adelaide's [phoenix](https://www.adelaide.edu.au/phoenix/) HPC
