---
layout: paper
title: "Admixed populations in the neighbor-joining algorithm: a geometric analysis with five taxa"
image: /images/papers/2024-10-03-zhang-nj-admix-cone.png
authors: Zhang J, Lo WT, Stillman M*, <ins>Kim J</ins>*
year: 2024
ref: Zhang et al. 2024. bioRxiv 
journal: "bioRxiv 2024.10.18.619141."
pdf: /pdfs/papers/2024-zhang-nj-admix-cone.pdf
doi: 10.1101/2024.10.18.619141
---

### Abstract
The Neighbor-Joining (NJ) algorithm is a widely used method for constructing phylogenetic trees from genetic distances. While NJ is known to perform well with tree-like data, its behavior under admixture remains understudied. In this work, we present a geometric framework for analyzing the NJ algorithm under a linear admixture model. We focus on three key properties related to clustering order, distance, and topological path length in the resulting NJ trees involving five taxa. Our approach leverages polyhedral geometry to define NJ cones, which correspond to distinct cherry-picking orders and partition the space of dissimilarity vectors. We project dissimilarity vectors with admixture into a lower-dimensional space without admixture, defining polyhedral regions induced by NJ cones that satisfy specified properties. We compute the exact probabilities that these properties hold by directly calculating the volumes of the induced NJ cones and compare them with Monte Carlo integration and standard NJ simulation methods. Our results show that the property on clustering order is always satisfied, while the other properties are highly probable but depend on the admixture fraction. We also prove that certain induced NJ cones have zero volume, indicating that the corresponding NJ tree topologies are infeasible under admixture. We have implemented our methods as a publicly available module *NeighborJoining* within *Macaulay2*, providing an efficient tool for analyzing NJ cones and their properties. This work provides new insights into the geometric structure inherent to the NJ algorithm in the presence of admixture, identifying the conditions under which admixture influences the resulting phylogenetic trees.
