---
title: "Statistical disclosure control for Census data with sdcMicro package: the computational challenges"
collection: publications
category: conferences
permalink: /publication/2024-11-29-Statistical-disclosure-control-for-Census-data-with-sdcMicro-package-the-computational-challenges
excerpt: ''
date: 2024-11-29
venue: 'Hellenic Statistical Authority, Greece'
slidesurl: 'https://r-project.ro/conference2024.html'
citation: 'Spiliopoulou V., Fragkopoulos D. (2024). &quot;Statistical disclosure control for Census data with sdcMicro package: the computational challenges&quot; <i>Use of R in Official Statistics 2024</i>.'
---

Abstract
===

Confidentiality must be respected for any dataset containing sensitive information about individuals. In this context, the implementation of methods ensuring adherence to ethical and legal commitments to protect statistical data confidentiality is necessary. The cell key perturbation method has been widely tested and used by National Statistical Offices (NSOs) for this purpose, particularly through the R package sdcTools. The Hellenic Statistical Authority has used this method on Census cubes submitted to Eurostat, as well as for the dissemination of national census tables. This paper presents the computational challenges encountered during this process, providing details on the hierarchies and the computational times required for complex cubes. An exponential impact on the time and system capacity needs is introduced for the production of protected cubes with more than six variables and the effect of the variable hierarchies. Additionally, the technical and statistical solutions employed
to efficiently automate and speed up the production of protected datasets, overcoming computational resource constraints, are discussed.