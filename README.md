# Uncertainty in Computer Vision

This repository consists of results from an internship project at the Integrated Vehicle Safety department of TNO.
Namely, [an internship report](Uncertainty_in_CV.pdf), overviewing the concept of uncertainty estimation in deep learning-based computer vision systems
and Jupyter notebook files, containing implementation examples for uncertainty estimation methods are included in this repository.

In these notebooks the following models are implemented:
* **[Basic Neural Network](CE_Softmax.ipynb)** - Estimating uncertainty based on the softmax-scaled value of the model output.
* **[Deep Ensemble](Deep_Ensemble.ipynb)** - Estimating uncertainty by averaging softmax-scaled outputs of multiple networks.
* **[Evidential Neural Network](ENN.ipynb)** - Estimating the α parameter of a Dirichlet distribution for uncertainty estimation.
* **[Equidistant Hypershperical Prototype Network](Equidistant_Hyperspherical_Prototype_Network.ipynb)** - Estimating the cosine similarity to pre-set class prototypes on a hypershpere,
after training a model to place inputs on the hypersphere appropriately.

The notebooks are meant for proof-of-concept / demonstration purposes and do not contain the most optimal parameters for
training each specific model.
