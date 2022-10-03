# Regulatory factors identification for nodal genes in zebrafish by causal inference

This repository contains the scripts to reproduce the result of the manuscript [*Regulatory factors identification for nodal genes in zebrafish by causal inference*]( )

## Abstract

 Nodal proteins play critical function for mesoderm and endoderm induction. Our previous study reported that the zebrafish *nodal* genes *ndr1*/*squint* and *ndr2*/*cyclops* are coordinately regulated by maternal Eomesa, Hwa/β-catenin signaling, and Nodal autoregulation. However, the exact contribution and molecular mechanism were not addressed. We applied the double fluorescence in situ hybridization (FISH) to assess the relative contribution of these three factors to the expression levels of *ndr1* and *ndr2*. Hwa-activated b-catenin signaling plays a major role in activation of *ndr1* expression in the dorsal blastodermal margin, while *eomesa* is mostly responsible for *ndr1* expression in the lateroventral margin and Nodal signaling contributes to ventral expansion of the *ndr1* expression domain. However, *ndr2* expression mainly depends on maternal *eomesa* with minor or negligible contribution of maternal *hwa* and Nodal autoregulation. Mechanistically, the different *cis*-regulatory regions of *ndr1* and *ndr2* were screened out via ChIP-qPCR and verified by the transgene constructs. Eomesa could interact with β-catenin and enhance their binding activity to *ndr1* promoter, and the marginal GFP expression driving by *ndr1 transgenesis* could be diminished without both maternal Eomesa and Hwa. While Eomesa, not β-catenin, could bind and activate *ndr2* demonstrated by *ndr2* transgenesis. Thus, the distinct regulation of *ndr1*/*ndr2* relies on different *cis*-regulatory regions.

## Casual inference

![image-20220713171240548](result/casual_model.jpg)

## Content

- `/data/`: the raw data to reproduce the figures
- `/result/`: the analysis result and figure of the manuscript
- `nodal_analysis.ipynb`: the raw code to reproduce the figures

## Contact

- Zehua Zeng (starlitnightly@163.com)