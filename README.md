# seismoDL101
Tutorial on seismic signal/noise classification; from linear to deep classifiers

This tutorial is meant to be an introduction to machine and deep learning. We use
seismic time series data from i) real earthquakes and ii) nuisance signals to 
train a suite of classifiers to discriminate between the two signal classes. We 
start from linear classifiers and keep increasing their complexity, to demonstrate 
to what extent the deep convnet classifiers outperform shallower and linear ones. 
We also explore how much data we need to train a deep classifier.

The repository contains training and testing data set files that together are 
~100Mb in size, so it may take a minute or two for downloading. In the meantime
you can set up your conda environment, e.g. if you are using unix like so:

$ conda create -c conda-forge -n seismoDL101 python=3.6 jupyter numpy scipy obspy keras tensorflow scikit-learn seaborn pandas h5py

I hope you enjoy the tutorial! For comments and questions please email 
mmeier@caltech.edu, March 13, 2019
