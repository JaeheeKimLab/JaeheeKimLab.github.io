---
layout: paper
title: "Bayesian phylodynamic inference of population dynamics with dormancy"
image: /images/papers/2025-01-20-cappello-seedbank.png
authors: Cappello L*, Lo WTJ*, Zhang JZ*, Xu P, Barrow D, Chopra I, Clark AG, Wells MT, Kim J
year: 2025
ref: Cappello et al. 2025. PNAS (in press)
journal: "Proceedings of the National Academy of Sciences of the United States of America (in press)."
pdf: /pdfs/papers/2025-cappello-seedbank.pdf
supplement: /pdfs/papers/2025-cappello-seedbank-si.pdf
doi: 10.1101/2025.01.19.633741
---

### Abstract
Many organisms employ reversible dormancy, or *seedbank*, in response to environmental fluctuations. This life-history strategy alters fundamental eco-evolutionary forces, leading to distinct patterns of genetic diversity. Two models of dormancy have been proposed based on the average duration of dormancy relative to coalescent timescales: weak seedbank, induced by scheduled seasonality (e.g., plants, invertebrates), and strong seedbank, where individuals stochastically switch between active and dormant states (e.g., bacteria, fungi). The weak seedbank coalescent is statistically equivalent to Kingman's coalescent with a scaled mutation rate, allowing the use of existing inference methods. In contrast, the strong seedbank coalescent differs fundamentally, as only active lineages can coalesce, while dormant lineages cannot. Additionally, dormant individuals typically mutate at a slower rate than active ones. Consequently, despite the significant role of dormancy in the eco-evolutionary dynamics of many organisms, no methods currently exist for inferring population dynamics involving dormancy and associated parameters. We present a Bayesian framework for jointly inferring a latent genealogy, seedbank parameters, and evolutionary parameters from molecular sequence data under the strong seedbank coalescent. We derive the exact probability density of genealogies sampled under the strong seedbank coalescent, characterize the corresponding likelihood function, and present efficient computational algorithms for its evaluation based on our theoretical framework. We develop a tailored Markov chain Monte Carlo sampler and implement our inference framework as a package *SeedbankTree* within *BEAST2*. Our work provides both a theoretical foundation and practical inference framework for studying the population genetic and genealogical impacts of dormancy.
