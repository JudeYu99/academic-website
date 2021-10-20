---
title: Brief in Bioinformatics / Computational Biology
subtitle: 

# Summary for listings and search engines
summary: Definition of the term and brief thinkings in this field

# Link this post with a project
projects: []

# Date published
date: 2018-10-07T00:00:00Z

# Date updated
lastmod: 2021-01-26T00:00:00Z

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
---

## Definition

Bioinformatics is an interdisciplinary field that develops methods and software tools for understanding biological data, in particular when the data sets are large and complex. As an interdisciplinary field of science, bioinformatics combines **biology**, **computer science**, **information engineering**, **mathematics and statistics** to analyze and interpret the biological data. Bioinformatics has been used for in silico analyses of biological queries using mathematical and statistical techniques (From [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)).

New research ideas in the field of modern life sciences:
1.	Various technologies and methods at the omics level
2.	High-throughput data
3.	Use informatics to process data
4.	Look at the problem from the perspective of systems biology

Recommendation reading by Xiaole Shirley Liu: [Levels of Bioinformatics Research](http://www.longwoodgenomics.org/2014/10/11/levels-of-bioinformatics-research/).

{{< figure src="Bioinformatics.png" title="Bioinformatics / Computational & Systems Biology" >}}

  
## Difference between computational biology and bioinformatics
	(*) In most conditions, it's not necessary to distinguish this two terms.


#### Computational Biology
	* The study of biology using computational techniques.
	* The goal is to learn new biology, knowledge about living systems.
	* It is about science.


#### Bioinformatics
	* The creation of tools (algorithms, databases) that solve problems.
	* The goal is to build useful tools that work on biological data.
	* It is about engineering.



  
## Topics in Computational Biology/ Bioinformatics

- Sequence analysis
- Structural bioinformatics: Sequence -> Structure -> Function
- Gene and protein expression
- Network and systems biology
- Gene function annotation / prediction
- Computational evolutionary biology
- Computational genomics
- Structural systems biology
- Precision medicine
- Computational immunology
- Computational neuroscience
- Literature mining
- Databases
- Webserver
- ...


## The Human Genome Project: 1990-2003

{{< figure src="HGP.jpg" title="The Human Genome Project (HGP) was an international scientific research project with the goal of determining the base pairs that make up human DNA, and of identifying and mapping all of the genes of the human genome from both a physical and a functional standpoint." >}}

- Proposed in 1985, formally launched in 1990, the work draft was released in 2001, and the completed drawing was completed in 2003;

- In September 1999, China formally joined the HGP and responsible for the 30 million base pairs of the short arm region of human chromosome 3 (1 %) sequencing

- Celera independently completed the sequencing of the human genome;

- HGP -- an opportunity for the development and growth of bioinformatics
	Through computer technology and mathematical methods, genome annotation, new gene discovery, genome comparison, and corresponding biological functions are derived from sequence features.

"Mapping the human genome has been compared with putting a man on the moon, but I believe it is more than that. This is the outstanding achievement not only of our lifetime, but in terms of human history."  

"A few months ago, I compared the project to the invention of the wheel. On reflection, it is more than that. I can well imagine technology making the wheel obsolete. But this code is the essence of mankind, and as long as humans exists, this code is going to be important and will be used."  

_-- Dr Michael Dexter_  
Director of the Wellcome Trust


  
## Genome annotation
#### Purpose and definition
- Structural genome annotation is the process of identifying genes and their intron-exon structures.
- Functional genome annotation is the process of attaching meta-data such as gene ontology terms to structural annotations.

{{< figure src="covid19.jpg" title="Genome composition and phylogenetic tree for 2019-nCoV" >}}

  
## Gene annotation
#### The very basis: find the single most likely coding sequence (CDS, no UTR)
- Translate sequence into 6 reading frames
- Look for frame longer that 30 codons (normally 50-60 codons)
- Presence of start codon and Shine-Dalgarno sequence
- Translate putative ORF into protein, and search databases
- Non-randomness of 3rd base of codon, more frequently G/C
- ...


  
## Bioinformatics in Protein Folding

- Protein folding: physical process by which a polypeptide folds into its characteristic and functional three-dimensional structure.

- Hydrophobic core -> side chain packing stabilizes the folded state  
Charged or polar side chains occupies the solvent-exposed surface -> interact with surrounding water

- Force fields: Amber, CHARMM, GROMOS, OPLS, etc.

- Energy landscape and Levinthal paradox

- Fragment-assembly method: Rosetta  
Key idea: Rosetta searches structure space to find fragments in proper structures to assemble the whole structure.

- Homology modeling:  
	Template identification -> Alignment -> Model building -> Model refinement -> Model evaluation
 
- AlphaFold2 (Deep Learning)

- I-TASSER

- ...

  (\*) Structure prediction will be discussed soon.


  
## Most Bioinformatics problems interested in:

1. Genome sequencing, structure, function, epigenetic genomics, etc.;

2. The evolutionary origin of the cell host;

3. Construction and analysis of complex molecular networks;

4. Bioinformatics research on molecular mechanisms of complex diseases;

5. Computational analysis of non-coding RNA;

6. Prediction and functional analysis of protein structure and modification;

7. Construction of important biological information database;

8. New technologies and methods of bioinformatics;

9. Single cell sequencing problems;

10.	...


  
### Reference
1.	_Wu, A., Peng, Y., Huang, B., Ding, X., Wang, X., Niu, P., Meng, J., Zhu, Z., Zhang, Z., Wang, J., Sheng, J., Quan, L., Xia, Z., Tan, W., Cheng, G., & Jiang, T. (2020). Genome Composition and Divergence of the Novel Coronavirus (2019-nCoV) Originating in China. Cell host & microbe, 27(3), 325–328._
2.	_ Robert Krulwich (2003). Cracking the Code of Life (Television Show). PBS._
3.	_"Human Genome Project: Sequencing the Human Genome | Learn Science at Scitable". www.nature.com. Retrieved 2016-01-25._


