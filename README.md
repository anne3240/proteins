# proteins
This project is to construct machine learning (ML) models to predict the properties of proteins. The ML model was trained on data collected by running coarse-grained molecular dynamics simulations of proteins.

#gen_features.py:       generate the 30-dimensional features of a protein sequences, e.g. "AGEFDWKLFPARGDKEWFPKK"
#train_ML.py:           train Gaussian regression models to predict property 1 and property 2, respectively, and a classifier to predict property 3.
#geneticalgorithm_m.py: genetic algorithm for searching for new protein sequences with improved property 1 and property 2.
#ga_pareto_gpr.py:      integrate machine learning and GA to search for the new protein sequences
