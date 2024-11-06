---
layout: paper
title: "Clinically informed deep reinforcement learning for adaptive sequential multi-drug therapy"
image: /images/papers/2024-11-07-li-drl-adaptive-therapy.png
authors: Li Z, Chenxi A, Osman M, Fields J, Sun W, Yadav D, Huicochea Castellanos S, Faltas BM, Kim J
year: 2024
ref: Li et al. 2024. bioRxiv 
journal: "bioRxiv ."
---

### Abstract
Drug resistance remains a critical challenge in cancer treatment, driving tumor progression and relapse. Adaptive sequential multi-drug therapy offers a promising solution by dynamically tailoring treatment to tumor evolution. However, existing computational approaches for optimizing treatment strategies are often limited to single-drug regimens, rely on sparse tumor-monitoring data, and neglect critical clinical constraints, rendering them impractical for clinical use. We present, to our knowledge, the first clinically viable deep reinforcement learning (DRL) framework that optimizes adaptive sequential multi-drug therapy in a clinically feasible way. By integrating proximal policy optimization with action masking, our framework adheres to real-world clinical constraints. Further, the use of circulating tumor DNA (ctDNA) as a dynamic biomarker enables high-resolution temporal monitoring of tumor progression and genetic heterogeneity—surpassing the limitations of traditional imaging. Using an experimentally validated mechanistic model of virtual bladder cancer patients receiving FGFR3 inhibitor and antibody-drug conjugate therapies, the DRL agent learns optimal treatment policies through virtual trials with varying drug administration schedules and ctDNA sampling frequencies, aiming to maximize patient survival within the constraints of viable clinical practices. Our results show that the DRL-optimized treatment schedules significantly outperform standard clinical protocols, extending patient time-to-progression in both single and multi-drug scenarios. Incorporating ctDNA monitoring further enhances the agent’s ability to predict treatment response and dynamically adjust strategies, highlighting the potential of frequent biomarker measurements in adaptive therapy. By addressing key limitations of existing models, our framework provides a clinically viable, computationally robust solution for personalized adaptive cancer therapy, contributing to improved patient outcomes.
