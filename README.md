# UnDIP: Hyperspectral Unmixing Using Deep Image Prior
Hyperspectral image processing through implicit regularization by a neural network

This is an implementation of the paper:   
B. Rasti, B. Koirala, P. Scheunders and P. Ghamisi, "UnDIP: Hyperspectral Unmixing Using Deep Image Prior," in *IEEE Transactions on Geoscience and Remote Sensing*, vol. 60, pp. 1-15, 2022, Art no. 5504615, doi: 10.1109/TGRS.2021.3067802.

# Project description
One of the key challenges in hyperspectral data analysis is unmixing, which involves separating the mixed spectral signatures of different materials present in a pixel. 
This paper is based on Deep Image Prior, which involve training a deep neural network to reconstruct an input image by
minimizing a suitable loss function that encourages image fidelity and adherence to the desired prior. By applying this concept to hyperspectral unmixing, 
we can estimate the abundances corresponding to each material through the optimization of a neural network which enforces the priors by its structure.   
Full details in the pdf report.
