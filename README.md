# Recovery of DESI BGS redshift measurements using Machine Learning

The object of this monograph was to apply machine learning (ML) methods to data coming from DESI end-to-end simulations to correct (or recover) true redshift of Bright Galaxies using observational variables as input. 

We found that the true redshift of the Bright Galaxy Sample (BGS) can be recovered using the variables FLUX\_G, FLUX\_R, FLUX\_Z, FLUX\_W1 and FLUX\_W2 as input to kernel methods. Using an ensemble model consisting of three KRRs (Kernel Ridge Regression) trained on subsamples of size 100.000, we were capable of approximate the DESI instrument redshift measurements to its true value up to a coefficient of determination $r^2 = 0.98$.  This model shows great potential to further enhancement, i.e. the fine-tuning of the model hyper-parameters, different classes of machine learning algorithms, as well as further use of ensemble methods with more than three "subtraining" sets in order to reduce bias.

The trained models did not work when tested in other classes of galaxies, probably because of the different distributions of fluxes. However, we infer that the same methodology could be used starting by training the models in the corresponding datasets. We expect that by doing so, the results of this work can be replicated and applied to all the classes in DESI. 
