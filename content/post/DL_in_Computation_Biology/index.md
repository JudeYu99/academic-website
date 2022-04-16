---
title: Nature Communications | Current progress and open challenges for applying deep learning across the biosciences
subtitle: 

# Summary for listings and search engines
summary: A Review of Deep Learning Applications in Computational Biology

# Link this post with a project
projects: []

# Date published
date: 2022-04-12T00:00:00Z

# Date updated
lastmod: 2022-04-14T00:00:00Z

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
- Computational Biology
- Nature Publications
- Machine Learning

---

Protein structure prediction has been a major challenge in computational biology for half a century, and recently, deep learning has made unprecedented progress in this area. A recent paper  explores recent advances, limitations, and perspectives on the future of deep learning in five areas: protein structure prediction, protein function prediction, genetic engineering, systems biology and data integration, and phylogenetic inference. The article discusses each application area and discusses the major bottlenecks of deep learning methods, such as training data, problem scope, and the ability to leverage existing deep learning architectures in new environments, and concludes with a summary of discipline-related and general challenges facing deep learning in the biosciences.

The success of AlphaFold2 in predicting protein 3D structure has become a typical example of deep learning in computational biology. The review provides a systematic overview of current results and open problems in applying deep learning in biology.

The review first introduces the model architectures widely used in biology, noting that the models used include supervised, unsupervised, and reinforcement learning paradigms. Common models in graph neural networks, image recognition (CNN), and natural prediction processing (RNN, transformer) have been successfully applied in biology.

The paper classifies the achievements into four categories: paradigm revolution, significant, moderate, and lesser scale success. Current progress, size of public datasets, and common model architectures for the five types of problems are indicated according to application scenarios.

The overview notes that while deep learning has achieved paradigm-shifting-level success in, for example, protein structure prediction, changing the default options in the field. Strides have also been made in more areas such as protein function prediction, genetic engineering, and multi-omics data integration. However, for other domains, such as phylogenetic inference, classical computational methods still prevail in these areas relative to traditional methods. Not all applications of deep learning have been equally successful in computational biology. Successful domains are highly dependent on a large number of standard datasets, both annotated and unstandardized, that are diverse, unbiasedly sampled, and close to real-world application scenarios.

In addition to providing an overview of the progress in each field, the highlight of the review is the identification of general challenges and possible solutions to the application of deep learning in biology.

1. biased conclusions: i.e., the conclusions given by the model do not match the real situation. To face this problem, what is needed is to improve the experimental design to avoid differences in the distribution of training data and actual data, and also to identify the reasons for biased models and use fairer models in a targeted manner.

2. higher computational cost: the solution is to parallelize the computation and optimize the code, or to select some (core) data for training, and to improve the AI architecture and use more energy-efficient computational facilities.

3. lack of explanations for the model: for this, one can use statistical analysis such as SHAP [1] to evaluate the importance of features, or use tools like GNNExplainer [2] to give explanations for GNN-based models after they are trained.

4. limited training dataset: feasible solutions include labeling more data, and using the model for data augmentation to generate new similar training data based on the existing dataset.

5. overfitting: countermeasures include regularization, dropping neuron dropouts, stopping training early, using a smaller capacity model, and using more training data.

6. Poor performance of the model on new data: In this case, the data set should be extended or a larger model should be used, and the generalization ability of the model should be analyzed in the context of biological knowledge, e.g., Deep Variant trained on human data performs poorly in detecting mutations in plants and animals that contain multiple pairs of chromosomes instead of one pair (because of the different biological mechanisms and the need to use the corresponding training data).

The review highlights the interpretability of the models and the efficiency of the training process, which includes both the high cost of training and the fact that trained models are only applicable to specific domains. More detailed feasible suggestions are also targeted.



### Reference

1.	_Sapoval N, Aghazadeh A, Nute MG, et al. Current progress and open challenges for applying deep learning across the biosciences. Nat Commun. 2022;13(1):1728. Published 2022 Apr 1._

