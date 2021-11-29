---
title: Breakthroughs in Recent Protein Structure Prediction
subtitle: 

# Summary for listings and search engines
summary: Personal interpretations of this phenomenon

# Link this post with a project
projects: []

# Date published
date: 2021-07-24T00:00:00Z

# Date updated
lastmod: 2021-07-25T00:00:00Z

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
- Protein
- Protein Structure

---

One of the key information needed to understand a biological process is the structure of its constituent proteins, but the experimental methods for structure determination are often time-consuming and laborious, and the results are uncertain, requiring a lot of time and resources. In contrast, protein sequences are easily obtained by translating genomic sequences, and a large amount of proteins can be obtained. Since the structure of a protein is determined by its sequence, an attempt to deduce the folding problem of the protein from another sequence has been going on for half a century, and its importance has risen with the exponential growth of the sequence database. Frustrated that it failed to bring decisive progress. In fact, since the first decade of this century, the protein science community has increasingly realized that this problem is one of the great challenges of computational biology.

In 1972, scientist Prof. Christian Anfinsen won the Nobel Prize in Chemistry for his "research on ribonuclease, especially the connection between amino acid sequence and biologically active conformation". At the award ceremony, he put forward a famous hypothesis: In theory, the amino acid sequence of a protein should completely determine its structure. This hypothesis led to a fifty-year exploration of calculating the three-dimensional structure of a protein based only on its one-dimensional amino acid sequence.

In recent years, benefiting from the rapid development of artificial intelligence and deep learning technology and the accumulation of large amounts of structural biology data, the methodology of protein structure prediction has made breakthrough progress. 

In the 14th protein structure prediction competition **CASP14** held in 2020, the artificial intelligence algorithm **AlphaFold2** (AF2 for short) developed by the Google DeepMind team shocked the world. The prediction accuracy of the target protein of the competition GDT_TS score exceeded 90%, which means that The predicted structure of many of these proteins is very close to the experimental structure, and the RMSD is within 1-2 angstroms. On July 15, 2021, the DeepMind team published a paper in _Nature_, describing the design ideas of AF2 in detail and providing runnable open source code. 

On the same day, David Baker's team published a paper in _Science_, and proposed the **RoseTTAFold** algorithm and its open source code using similar design ideas. Subsequently, the DeepMind team used AF2 to predict the structure model of a total of more than 300,000 proteins without experimental structures in multiple species, and jointly established the structure prediction database AFDB with EBI. The emergence of this series of results has attracted a lot of attention from the scientific community, and everyone has different opinions. On the one hand, top structural biologists such as Professor Yigong Shi even claimed that AF2 was the most important scientific breakthrough of this century; on the other hand, some scientists questioned the accuracy of AF2 predictions. 

The Google DeepMind team and the Baker's Laboratory have publicly released the AlphaFold and RoseTTAfold algorithm codes to explain the deep learning (DL) algorithm for protein folding prediction. The DeepMind team cooperated with the European Institute of Bioinformatics (EBI) and applied AlphaFold to the whole genome, including humans, mice, yeast and E. coli.

The artificial intelligence (AI) system nearly perfectly predicted the three-dimensional structure of proteins. However, this achievement does not mean that artificial intelligence will make experimental structural biology redundant. Structural biology is essential for understanding how proteins work and how they interact dynamically is still crucial.





### Reference

1.	_Andrei N. Lupas, Joana Pereira, Vikram Alva, Felipe Merino, Murray Coles, Marcus D. Hartmann; The breakthrough in protein structure prediction. Biochem J 28 May 2021; 478 (10): 1885–1890._
2.	_Tunyasuvunakool, K., Adler, J., Wu, Z. et al. Highly accurate protein structure prediction for the human proteome. Nature (2021)._
3.	_Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature (2021)._



