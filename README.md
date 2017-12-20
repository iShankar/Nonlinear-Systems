# Nonlinear-Systems
Understanding and application of tools for nonlinear dynamic systems

There is much controversy about the role of Chaos in heart rate variability. I will provide key references on that soon. Apparnetly methodologies are required to validate nonlinearity and determinstic nature first and then evaluate the system for chaotic parameters. I will provide more on that soon.

For now, I have installed TISEAN (https://www.pks.mpg.de/~tisean/) as an R package ('tseriesChaos'); it can be used for analyzing time seried data. I have also installed tseriesEntropy. I am assuming it supports shannon entropy calculations used by one author to discriminate three sets of patients identified in the Physionet challenge for Chaos (in 2009) - see the Athero folder for that. But it has non-zero exit status (that is, some dependency packages - rgl and ks. To install rgl, I had to install (with sudo)  xquartz – rawr). I have also installed a package for multiscale and multifactorial time series (TseriesMMA). I also saw mention of RDRToobox
