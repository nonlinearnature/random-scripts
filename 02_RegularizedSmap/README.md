# Manual implementation of the regularized S-map
The regularized S-map has been implemented according to Cenci et al. (2019) Methods in Ecology and Evolution (https://doi.org/10.1111/2041-210X.13150)

Currently, the regularization relies on "glmnet" package of R.

Regularized S-map functions are in "functions" folder, and they are tested in 01_RegularizedSmap.R. Accordign to a test using a subset of the data in Ushio et al. (2018) (see "data" folder), ridge (or lasso) S-map shows a better performance than the standard S-map, which is consistent with Cenci et al. (2019). Current implementations of the regularized and standard S-map are much slower than the standard S-map in rEDM package of R.
