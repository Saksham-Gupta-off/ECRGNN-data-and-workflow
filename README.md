# ECRGNN-data-and-workflow
ECRGNN-data-and-workflow

## Overview
This is the data and code for the paper: `Graph Residual based Method for Molecular Property Prediction` which introduces the `ECRGNN` architecture for molecular property prediction

## Dataset Description
- **Data Source**: https://moleculenet.org/
- **Data Type**: SMILES Encoded Strings for molecules and corresponding Values/Labels
- **Data Format**: CSV

## Data Preprocessing
Classification data has been imputed with 2s and 0s for simulation of multilabel - multiclass & binary class classification.

## Data Preprocessing
Imbalance in data has been shown in `imbalances.ipynb`

## Code
Temporary Code has been provided for the ECRGNN and ECRGNN-VAE models in `ERCGNN_VAE.ipynb`. Code will be formalized as a part of future work