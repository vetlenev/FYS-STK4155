# FYS-STK4155 - Project 1
This repository contains code for analyzing the fitting potential of regression methods on the FrakeFunction, using polynomial features.

The structure of the repository is as follows:
- A report as HTML-file containing the main implementation and results of the project.
- A Jupyter Notebook containing all code used to obtain the results.
- A folder ```figs``` containing all figures and plots from our results.
- Two ```.tif``` files for the topographic landscape used in Exercise 6. It runs the file ```n59_e006_1arc_v3.tif``` by default, which is a topographic landscape of the Lysefjord region in Rogaland, Norway.

The Jupyter notebook mainly uses functions and function calls to run the different sections and algorithms. Running the entire notebook as it is will only provide a subset of the results discussed in the report. It is easy though to reproduce all results, simply by changing the arguments passed to the functions. In exercise 6, the algorithm is implemented as a class, including some of the main concepts and functions from earlier tasks. This is to make it a more seemless experience when running the simulations for your desired landscape. Note that the gridsearch method only works for Ridge and Lasso.


