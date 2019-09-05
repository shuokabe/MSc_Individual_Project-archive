# Presentation

This QuEst++ folder contains the files (mainly data, configuration files and Jupyter notebooks) used to carry out the document-level (M)QE with QuEst++.

- customize_scorer.py is a modified version of the original customize_scorer provided by QuEst++ in order to print the system's predictions for the test set.

- PCA_QUEST++ is a Jupyter notebook which carries out dimensionality reduction on the visual feature dataset with the help of PCA. This file generates the different datasets used to evaluate the impact of visual features on QuEst++.

- QUEST++ is a Jupyter notebook which implements all the tested settings (visual features and token information) for feature-based (M)QE in this project.

- Token_separation is a Jupyter notebook which generates the dataset for the token information on QuEst++.

- The QuEst++ config files folder contains all the config files that QuEst++ needs for all the tried settings (visual feature and token information).

- The QuEst++ data folder contains all the used datasets, generated by the PCA_QUEST++ and Token_separation notebooks.