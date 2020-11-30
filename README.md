# Resampling-Project-VCMF-Conference-
It is well known that in the forecasting of a target variable the linear models reduce to single index models, but
it is shown by Fan et al. that in nonlinear forecasting models, there is a possibility to extract multiple indices from
the factors. 

In this method, the sufcient factors are identifed as the eigenvectors of the conditional covariance
matrix of the factors given the target variable. The covariance matrix is estimated using slicing method. 
The sufcient factors are those eigenvectors which are signifcantly larger than zero. 

Several tests are proposed in order to determine the optimal number L of sufcient factors. We propose a robust method based on resampling for
determining L without imposing any assumption on the distribution of the noise
