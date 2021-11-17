---
title: Paralogs and Orthologs
subtitle: 

# Summary for listings and search engines
summary: Definitions of Paralogs and Orthologs

# Link this post with a project
projects: []

# Date published
date: 2020-01-26T00:00:00Z

# Date updated
lastmod: 2020-01-27T00:00:00Z

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

categories:
- Bioinformatics
- Evolution
- Protein

---
### [Wikipedia Definition](https://en.wikipedia.org/wiki/Sequence_homology#Orthology)

Homologous sequences are orthologous if they are inferred to be descended from the same ancestral sequence separated by a speciation event: when a species diverges into two separate species, the copies of a single gene in the two resulting species are said to be orthologous. Orthologs, or orthologous genes, are genes in different species that originated by vertical descent from a single gene of the last common ancestor. The term ortholog was coined in 1970 by the molecular evolutionist Walter Fitch.

For instance, the plant Flu regulatory protein is present both in Arabidopsis (multicellular higher plant) and Chlamydomonas (single cell green algae). The Chlamydomonas version is more complex: it crosses the membrane twice rather than once, contains additional domains and undergoes alternative splicing. However it can fully substitute the much simpler Arabidopsis protein, if transferred from algae to plant genome by means of genetic engineering. Significant sequence similarity and shared functional domains indicate that these two genes are orthologous genes, inherited from the shared ancestor.

Orthology is strictly defined in terms of ancestry. Given that the exact ancestry of genes in different organisms is difficult to ascertain due to gene duplication and genome rearrangement events, the strongest evidence that two similar genes are orthologous is usually found by carrying out phylogenetic analysis of the gene lineage. Orthologs often, but not always, have the same function.

Orthologous sequences provide useful information in taxonomic classification and phylogenetic studies of organisms. The pattern of genetic divergence can be used to trace the relatedness of organisms. Two organisms that are very closely related are likely to display very similar DNA sequences between two orthologs. Conversely, an organism that is further removed evolutionarily from another organism is likely to display a greater divergence in the sequence of the orthologs being studied.



### Sequence homology, homologous proteins and protein families

When two genes have obvious sequence similarity, they are said to have sequence homology, or the sequence is homologous; the proteins they encode become homologous proteins. Homologous proteins often have the same or similar functions and three-dimensional structures. The concept of homologous proteins can be further refined. If two homologous proteins come from two different species, they are called orthologs. The orthologous proteins have the same function and structure; it is speculated that orthologous genes encode proteins that perform uniform functions in different species. If two homologous proteins exist in the same species, they are called paralog homology; the homologous genes encoding them are considered to be caused by gene duplication and the subsequent gradual change of the two copies of the sequence. Generally, paralog proteins are not only similar in sequence but also in three-dimensional structure, although their biological functions have changed in the process of evolution, similarity but not the same.

According to the homology of amino acid sequence, protein families with certain functional and structural characteristics can be determined. The members of a protein family are homologous proteins, and they have a common ancestor. According to the degree of amino acid sequence homology, proteins can be assigned to their respective families. The members of a protein family generally have 25% or more sequences that are identical, and the longer similar sequences are called Domains. Generally, the members of the protein family have several common three-dimensional structure and functional characteristics, but in some families, the degree of sequence similarity is not high, and it is only determined based on the identification of a few amino acid residues that are critical to a certain function. These invariant amino acid residues are usually scattered in a peptide that is not too long, but their position is determined, and this family-marked sequence becomes a motif.



### Species Differences in Amino Acid Sequences of Homologous Proteins

The homology comparison of amino acid sequence is done by computer program which can directly align or compare two or more protein sequences. When necessary, the program will introduce appropriate gaps in the sequence to obtain the best homology for the alignment. In other words, the fewest gaps are introduced to maximize the number of aligned positions of the same residue in all sequences being compared.

During evolution, the amino acid residues in the amino acid sequence of proteins will change, especially when the external environment changes drastically. For a certain protein, the amino acid residues necessary for its biological function remain almost unchanged during the entire evolution process, and are called invariant residues; The amino acid residues that are not important for protein function may change during evolution, that is, one kind of residue can be replaced by another kind of residue, these amino acid residues are called variable residues, and they can provide people with tracking in evolutionary information.

In the course of evolution, the mutation frequency of amino acid residues in different proteins can vary greatly. For example, cytochrome c. in the past 20 million years, the mutation rate of amino acid residues is about 60 times per 100 residues while in the past 5.8 million years, the residue mutation rate of hemoglobin is about 140 times per 100 residues. Besides, histones and ubiquitin, their residue mutation rate is very small and very conservative. If we want to track the evolution process and understand the genetic relationship between species, we first need to select the appropriate homologous protein family, and then use them to reconstruct the path of evolution. After obtaining the evolutionary relationship, drawing a phylogenetic tree can not only study the evolution process from single-celled organisms to multi-celled organisms, but also roughly estimate the divergence time of existing species. For example, the divergence time between humans and horses is 70 to 75 million years ago, mammals and birds are 280 million years ago, and vertebrates and yeast are 1.1 billion years ago.



### Homologous proteins share a common evolutionary origin

The comparison of the amino acid sequence of homologous proteins reveals that the members of the protein family have a common evolutionary ancestor. For example, the common ancestor of the cytochrome c family existed before the formation of their species. The closer the relationship between two species (two homologous proteins), the shorter their evolutionary time from the common ancestor is and vice versa.


  
### Reference

1.	_Fitch WM (June 1970). "Distinguishing homologous from analogous proteins". Systematic Zoology. 19 (2): 99–113._
2.	_Falciatore A, Merendino L, Barneche F, Ceol M, Meskauskiene R, Apel K, Rochaix JD (January 2005). "The FLP proteins act as regulators of chlorophyll synthesis in response to light and plastid signals in Chlamydomonas". Genes & Development. 19 (1): 176–87._
3.	_Fang G, Bhardwaj N, Robilotto R, Gerstein MB (March 2010). "Getting started in gene orthology and functional analysis". PLOS Computational Biology. 6 (3): e1000703._


