Below is a brief overview of the provided code files for computing a novel morphological index of microstructures, written in both MATLAB and Python:

MATLAB Files:

1. spinodalTopologyCreator: This function is capable of generating spinodal microstructures.
2- imageExtractor: This function calculates the microstructural segments within a microstructure using computational homology. Subsequently, these segments are converted to grayscale images and saved in the designated directory.
3. myUnion: This function is designed to identify microstructural segments within a microstructure using the union-find algorithm.
4: imageOrganizer: This function loads all the microstructural images from the directory and subsequently applies the PCA algorithm to reduce their dimensions.
5: classificationTask: This function employs the k-means algorithm and classification techniques to generate the morphology-indicator index.
Python Files:
1: inverseAndForwardProblem: This function is designed to determine the optimal morphological property for a specific microstructure.
