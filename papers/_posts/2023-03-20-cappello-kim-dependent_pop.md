---
layout: paper
title: "adaPop: Bayesian Inference of Dependent Population Dynamics in Coalescent Models"
image: /images/papers/2023-03-20-cappello-kim-dependent-pop.png
authors: Cappello L*, <ins>Kim J</ins>*, Palacios JA
year: 2023
ref: Cappello*, Kim*, and Palacios. 2023. PLOS Computational Biology
journal: "PLOS Computational Biology 19(3):e1010897."
pdf: /pdfs/papers/2023-cappello-kim-dep-pop.pdf
supplement: /pdfs/papers/2023-cappello-kim-dep-pop-si.pdf
doi: 10.1371/journal.pcbi.1010897
---

### Abstract
The coalescent is a powerful statistical framework that allows us to infer past population dynamics leveraging the ancestral relationships reconstructed from sampled molecular sequence data. In many biomedical applications, such as in the study of infectious diseases, cell development, and tumorgenesis, several distinct populations share evolutionary history and therefore become dependent. The inference of such dependence is a highly important, yet a challenging problem. With advances in sequencing technologies, we are well positioned to exploit the wealth of high-resolution biological data for tackling this problem. Here, we present a novel probabilistic model that relies on jointly distributed Markov random fields. We use this model to estimate past population dynamics of dependent populations and to quantify their degree of dependence. An essential feature of our approach is the ability to track the time-varying association between the populations while making minimal assumptions on their functional shapes via Markov random field priors. We provide nonparametric estimators, extensions of our base model that integrate multiple data sources, and fast scalable inference algorithms. We test our method using simulated data under various dependent population histories and demonstrate the utility of our model in shedding light on evolutionary histories of different variants of SARS-CoV-2.

