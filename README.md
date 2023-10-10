Robust Validation: Confident Predictions Even When Distributions Shift

This repository contains the code for replication of the results in the paper "Robust Validation: Confident Predictions Even When Distributions Shift
" by XXXX-1, XXXX-4, XXXX-8 and XXXX-6. 

We note that all the R and python files are compatible to be run with the latest version of all the packages used. Simply doing install.packages(<package name> for R packages used and pip install <package name> for python packages will suffice.


To generate Figures 1 and 5, run the file code/Make Figs 1, 5 part 1.ipynb  and code/Make Figs 1, 5 part 2.ipynb 

To generate figures 2, 3, and 4, run the following files in the order:

Figure 2
Dataset preprocessing -> code/processing-cifar_10-and-mnist.ipynb
Experiment -> code/cifar10_mnist_experiment.py
Plot -> code/Make Figs 2, 3, 4.ipynb

Figure 3
Dataset preprocessing -> code/processing-cifar_10-and-mnist.ipynb
Experiment -> code/cifar10_mnist_experiment.py
Plot -> code/Make Figs 2, 3, 4.ipynb

Figure 4
Dataset preprocessing -> code/processing_imagenet.py / processing-imagenet.ipynb
Experiment -> code/cifar10_imagenet_experiment.py
Plot -> code/Make Figs 2, 3, 4.ipynb

To generate figures 6, 7, 8, and 9, run the file code/Make Figs 6, 7, 8, 9.ipynb

To generate figure 10, run the following files:

code/Make Fig 10-real estate.ipynb
code/Make Fig 10-weather history.ipynb
code/Make Fig 10-wine quality.ipynb