# The Chimera and Gaggle Algorithms
The Chimera Algorithm is a CNN architecture optimizer using a mixture of Artificial Bee Colony and Genetic Algorithms. The models can be created from scratch or they can use a given input architecture to start from.

An example of the evolution of one of such models, created from scratch and meant for the characterization of misalignment artifacts in CT volumes, is shown below:

![alt text](https://github.com/AdriGoMar/ChimeraAlgorithm/blob/main/model_ev_visualization.gif?raw=true)

On the other hand, the Gaggle Algorithm combines the resulting populations of the Chimera Algorithm into ensembles to make use of the bias and variance reduction capabilities of Ensemble Learning.
