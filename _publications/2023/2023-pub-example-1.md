---
title:          "MatFEA: Efficient Finite Element Framework for Analyzing Pavement Structures With Nonlinear Unbound Materials"
date:           2023-06-05 00:01:00 +0800
selected:       true
pub:            "Transportation Research Record (TRR)"
pub_date:       "2023"
abstract: >-
  This paper reports the details of a computationally efficient finite element analysis code (called MatFEA), designed specifically for flexible pavements, where stress-dependent characteristics of unbound layers are considered. The stress-dependent nonlinearity of the unbound materials has been modeled in MatFEA through an iterative approach. MatFEA was mainly developed to improve the Mechanistic-Empirical Asphalt Pavement Analysis (MEAPA) web application with capability of analysis/design of nonlinear pavement structures. A specific-purpose mesh generation algorithm was developed for the MatFEA in which the mesh density was dynamically adjustable based on the expected stress magnitude. To verify the results of the MatFEA, 12,000 nonlinear pavement structures with different structural and loading properties were generated and analyzed with MatFEA. The same pavement structures were modeled in a general-purpose FE-based ABAQUS™ program. The results of this study showed that the critical pavement structural responses from the MatFEA were almost identical with those modeled by ABAQUS™ program. The average runtime of MatFEA for analyzing each pavement structure was about 1.13 s. Finally, it was concluded that application of the dynamically adjustable mesh generation algorithm in the MatFEA helped achieve a reasonably high accuracy as well as efficient runtime, which brings the advantage of implementing the MatFEA as a pavement structural response model in the mechanistic-empirical pavement analysis/design procedures.
cover:          /assets/images/covers/2023_MatFEA.png
authors:
- S. Farhad Abdollahi
- M. Emin Kutay
- Mahdi Ghazavi
links:
  Paper: https://journals.sagepub.com/doi/abs/10.1177/03611981221150246
---