# topo-data
Topological data analysis tool for energy utilities. 
The following is the Topological Model organized into two phases. 
Phase One was a Kohonen Self-Organized Map (SOM) in SAS Enterprise Miner. The SOM is an artificial neural network that uses PCA for eigenvalues and forms a simplified static 2D map of the data without evolution (Kohonen, 1982). 
The neural network ‘learns’ from the training data and each iteration is closer to the ideal shape. 
The training data is mapped as an input vector to the target space containing grid nodes analogous to neurons. 
Phase Two is the Python Kepler Mapper Algorithm. The algorithm forms multi-dimensional simplexes, which are shapes that have Persistent Homology or a shape lifecycle. 
Machine Learning-AI Gradient Boost and Decision Trees were used to determine feature importance. This is used to create a simplicial complex in reduced dimensions (Singh, Mémoli, & Carlsson 2007).
