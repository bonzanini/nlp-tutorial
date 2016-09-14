title: 'Assessing performance of Support Vector Machine kernels to detect interactions in genotyped data'
subtitle:
speaker: tim-vivian-griffiths
---
Machine learning methods can present new possibilities for research topics looking at identifying genetic aetiologies of disease. However in complex disorders, such as those seen in psychiatric conditions, this can be especially hard given the loosely defined phenotype classifications of the diseases.

In this study, I examine how well the different kernel methods for Support Vector Machines do when trying to perform a binary classification on phenotypes that have been simulated from genotyped genetic data in schizophrenia cases and controls. These simulated phenotypes were made from different aspects of the data, either the main-effects or pairwise interactions between different mutations. The advantage of using simulated phenotypes over real case/control status is that now, the aetiology of the binary outcomes is known. The results show that when interactions between 20% of the inputs features are included, any small contribution of these are detectable when using a Radial Basis Function (RBF) kernel in a Support Vector Machine when compared with the performance of a linear kernel.

These results show that the different performances of the RBF and linear kernels can be used to detect the presence of pairwise interactions between features, even when the effect sizes of these are only marginally larger in size than the main-effects.
