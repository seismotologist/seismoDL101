# seismoDL101
Tutorial on seismic signal/noise classification; from linear to deep classifiers

This jupyter notebook tutorial is meant to be a general introduction to machine 
and deep learning. We use seismic time series data from i) real earthquakes and 
ii) nuisance signals to train a suite of supervised keras classifiers to 
discriminate between the two signal classes. We start from linear classifiers 
and gradually increase their complexity, to demonstrate to what extent deep 
convnet classifiers outperform shallower and linear ones. We also explore how 
to evaluate binary classifiers, and how much data we actually need to train 
deep classifiers. 

No prior knowldedge on seismology or machine learning is required; much of the 
tutorial builds on concepts from undergraduate-level applied mathematics 
(calculus, linear algebra, optimization). No GPUs or other special hardware is 
required, your laptop should work just fine. The repository contains training 
and testing data set files that together are ~100Mb in size, so it may take a 
minute or two for downloading. 

I recommend you use the conda package management system (https://conda.io/) to 
set up a working environment with tenserflow (I used version 1.5.0) and keras 
(2.2.4). If you are using unix and have installed conda you can set everything 
up by typing the following line in the terminal:

$ conda create -c conda-forge -n seismoDL101 python=3.6 jupyter numpy scipy obspy keras tensorflow scikit-learn seaborn pandas h5py

Then activate the environment (type 'source activate seismoDL101' in
terminal), and open the notebook (type 'jupyter notebook' in terminal), and you
should be ready to ... explore machine and deep learning!

I hope you enjoy the tutorial (\_/) For comments and questions please email 
mmeier@caltech.edu; last update: April 29, 2019; v1.0
