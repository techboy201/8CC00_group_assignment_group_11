# Finding inhibitors of PKM2 and ERK2 kinases.
This repository contains files and scripts used to identify inhibitors for ERK2 and PKM2 kinases using machine learning techniques.

## Project Overview
We aimed to discover potential inhibitors for the ERK2 and PKM2 kinases. We tested the following algorithms:
* k-NN algorithm
* CNN algorithm
* Random Forest algorithm

After all three were tested, the Random Forest algorithm was chosen to be executed on the untested molecules.
A grid search was executed to find the best parameters, after which the Random Forest algorithm was applied to the untested file.

## Repository Structure
* Random Forest Grid Search.ipynb
  - Performs a grid search to find the best values for the parameters.
* Final Random Forest.ipynb
  - Performs the random forest algorithm on the untested molecules.
  - Uses the parameters found from Random Forest Grid Search.
* K_nn.ipynb
  - Performs the k-NN algorithm.
* CNN.ipynb
  - Performs the CNN algorithm.
* EDA.ipynb
  - Performs an exploratory data analasys on the tested molecule file.
* tested_molecules.csv
  - All molecules to be used for the training of the ML model
* untested_molecules.csv
  - A list of all molecules that the final algorithm determines for if it inhibits ERK2 or PKM2.
* prediction_untested_molecules.csv
  - Untested_molecules.csv with the inhibition prediction of the final model added.


- - -
© 2024 Inhibitix. All Rights Reserved.
