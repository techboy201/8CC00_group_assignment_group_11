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
* Grid_search_random_forest
  - Executes a grid search to find the best values for the parameters
* Final Random Forest
  - Executes the random forest algorithm on the untested molecules.
* K_nn
  - executes the k-NN algorithm
* CNN
  - Executes the CNN algorithm


- - -
© 2024 Inhibitix. All Rights Reserved.
