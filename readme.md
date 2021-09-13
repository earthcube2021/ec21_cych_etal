# Reanalysis of archived paleointensity data using a new statistical method.


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5496268.svg)](https://doi.org/10.5281/zenodo.5496268)


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/earthcube2021/ec21_cych_etal/HEAD)

When rocks cool from high temperature, they lock in a magnetization parallel to and proportional to the field in which they cool. By making the fundamental assumption that the magnetization is quasi-linearly related to this field, by replacing this ‘natural remanence’ with a laboratory remanence acquired in a known field, one can estimate the ancient magnetic field (the paleointensity).  This is done in a step-wise fashion with the additional assumption that a magnetization acquired by cooling from a particular temperature can be removed by re-heating to the same temperature and cooling in zero field, an assumption known as “reciprocity”.
Unfortunately, the reciprocity assumption is frequently violated, which can cause bias in paleointensity estimates. Paleomagnetists exclude these data using “selection criteria”, a set of statistics which describe how an experiment can fail. There is no universally accepted set of selection criteria, with each laboratory using their preferred set. This makes it difficult to compare results from different studies.
 We present a new method of analyzing paleointensity data called Bias Corrected Estimation of Paleointensity (BiCEP). Our method predicts a bias for each specimen, which allows us to estimate paleointensities that are unbiased without excluding data from the analysis. We can use this method to reinterpret previously published paleointensity data.  Along with this method, we present a notebook which provides tools for reading in data, applying the BiCEP method, and analyzing, visualizing and exporting the results. The notebook also contains a fully functional GUI, which can be used for all of these processes. We hope that paleomagnetists will be able to use these tools to (re)analyze their data in a more consistent manner and to improve the quality of paleointensity estimates.
