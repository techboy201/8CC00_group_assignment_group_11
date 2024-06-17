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
* Random Forest Grid Search
  - Performs a grid search to find the best values for the parameters.
* Final Random Forest
  - Performs the random forest algorithm on the untested molecules.
  - Uses the parameters found from Random Forest Grid Search.
* K_nn
  - Performs the k-NN algorithm.
* CNN
  - Performs the CNN algorithm.
* Group assignment Annemijn Gwen
  - Performs an exploratory data analasys on the tested molecule file.


- - -
© 2024 Inhibitix. All Rights Reserved.
