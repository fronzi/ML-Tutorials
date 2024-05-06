# Tutorial: Predicting Structural Properties using Machine Learning Models

This tutorial provides a step-by-step guide on using machine learning to predict the structural properties of materials. We will use a dataset of crystal structures, enhance it with descriptors, and apply machine learning models to predict properties such as shear modulus, elastic anisotropy, and Poisson's ratio.

## Overview

The tutorial covers the following steps:

1. Loading and examining a dataset using pandas.
2. Adding descriptors to the dataset using the `matminer` library.
3. Training and comparing two machine learning methods with `scikit-learn`.
4. Visualizing the results.

## Requirements

- Python 3.x
- Libraries: `pandas`, `matminer`, `scikit-learn`, `pymatgen`, `matplotlib`, `seaborn`, `IPython`, `statsmodels`, `tensorflow`

## Dataset

The dataset is stored in a JSON file containing structural information and properties of the crystals. 

