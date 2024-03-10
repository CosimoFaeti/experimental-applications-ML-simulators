<p align="center">
  <img src="https://github.com/CosimoFaeti/causal-impact-analysis/assets/99746565/e671ee3f-5956-4a1c-88f2-156f1c1000ab" alt="unipi" width="30%">
</p>

# Experimental Applications of ML/NN simulators 
This repository contains my project for the *Machine Learning course* of my Master's degree in Data Science and Business Informatics at Università di Pisa.
The aim of this project is to conduct an a comprehensive analysis and comparison of different
models, namely **Random Forest**, **Support Vector Machine (SVM)**, and **Multi-Layer Perceptron
(MLP)**. In the first part, we focus on a *classification* task using benchmark Monk datasets, which is
achieved through empirical trials. The second part shifts attention towards a *multivariate
regression* task using the ML-CUP dataset. This involves a process consisting of preliminary
experimental trials, parameter fine-tuning, and an in-depth comparison among the models.
The code was developed in *Python* (Jupyter Notebook). Specific libraries utilizied for building machine learning models, including *Keras* for MLP, *TensorFlow* for Random Forest, *Scikit-Learn* for SVM, and *KerasTuner* for GridSearch.

## Abstract
This report presents the development and performance comparison of multiple models. The
validation technique employed involved a systematic approach, including preliminary experimental
trials, grid search with different levels of granularity, and a 5-fold cross-validation,
followed by the final model assessment. Using this approach, we identified the optimal
model for the ML-CUP task, which turned out to be a Support Vector Machine (SVM)
with a rbf kernel function.

## Repository Overview
In this repository, in the root level, you can find the pdf version of the report, the data and the code for the implementation of Random Forest, SVM, and MLP for both monk datasets and ML-CUP. More specifically:

**Monk datasets**:
* Monk.ipynb : contains the implementation of Random Forest, SVM, and MLP for three monk datasets

**ML-CUP**:
* RandomForest.ipynb : contains the implementation of Random Forest for ML-CUP
* SVM.ipynb : contains the implementation of SVM for ML-CUP
* MLP.ipynb : contains the implementation of MLP for ML-CUP
* TestBlindSet.ipynb : contains the implementation of SVM with rbf kernel function for blind test set (ML-CUP)
