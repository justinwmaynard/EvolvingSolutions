## Nieves Response

------

### Nieves et a. use the random forest machine learning method to predict what value globally?

Nieves et al. uses a random forest method as outlined by Stevens et al. to examine which covariates are most important in determining population distribution by first predicting global population density. This paper seeks to find a better understanding of the relationships between different covariates, which would improve mapping of population and lead to more accurate modelling of future scenarios. 

### Describe in detail how random forest works. 

Random forest methods are machine learning methods classified as “ensemble methods.” Ensemble methods function by taking individual decision trees that are “weak learners,” and combining those trees into a “strong learner.” This is beneficiary as performance on large datasets is increased, and the ability of the random forest method to model difficult learning tasks is more effective. Using bagging, a random forest model generates a number of unpruned decision trees.  Once a decision tree is grown, the one third of the bagged data not grown upon is known as the “out of bag” (OOB). The OOB error can be calculated and then used for estimating covariate importance “by randomly permutating a given covariate’s OOB data with random noise and calculating the average per cent increase in the mean squared error.” 

### What is a dasymmetric population allocation?

A dasymetric population allocation is a method for allocation of population datasets from larger levels, such as country, to more specific levels like grid cells at the resolution of 100m by 100m. Dasymetric allocation is asymmetric when population densities are allocated to individual grid cells, as some areas will be overestimated, and other areas will be underestimated, resulting in the densities adding up to one. This results in a higher resolution data.

### Which geospatial covariates proved to be the most important when predicting global values of where humans reside?

The two geospatial covariates that were most important when predicting global population are urban and suburban extents, and built environment and urban suburban proxies. The authors also found that climate and environment covariate was one of the only covariates that was significantly more important.  The covariates on urban extenets and proxies were expected to be important, however the researchers were surprised about the importance of climate and environmental factors.