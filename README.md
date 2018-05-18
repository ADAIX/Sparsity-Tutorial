<a href="http://www.cosmostat.org/" target_="blank"><img src="http://www.cosmostat.org/wp-content/uploads/2017/07/CosmoStat-Logo_WhiteBK.jpg" width="400"></a>


# Sparsity Tutorial

> Author: <font color='#f78c40'>Samuel Farrens</font>    
> Year: 2018  
> Email: [samuel.farrens@cea.fr](mailto:samuel.farrens@cea.fr)  
> Website: <a href="https://sfarrens.github.io" target="_blank">https://sfarrens.github.io</a>

## Contents

1. [Objective](#Objective)
1. [Requirements](#Requirements)
1. [Notebooks](#Notebooks)
1. [Acknowledgements](#Acknowledgements)


## Objective

The objective of this tutorial is to provide a beginner level introduction to the concept of sparsity, in particular as a regularisation method for solving linear inverse problems. The tutorial does not provide an indepth mathematical background nor detailed explinations for every topic. Tutees should suppliment this tutorial with further reading of the various references provided in the notebooks for a more comprehensive understading of the subject. More information about how cutting edge sparsity techniques are being applied to astrophysical data is available on the <a href="http://www.cosmostat.org/" target_="blank">CosmoStat website</a>.

This tutorial is comprised of a series of <a href="https://jupyter-notebook.readthedocs.io/en/stable/" target_="blanck">Jupyter notebooks</a> that demonstrate how the tools implemented in sparsity work as well as showing the applicability of these tools to various simple problems. All code blocks are provided in Python (support for both 2.7 and 3.6+) and the number of external packages required to run the examples has be kept to a minimum. With the exception of plotting routines, all of the code has been clearly presented inside the the notebooks at least once to avoid the use of any "black boxes" for solving the problems presented.

## Requirements

In order to run the tutorial notebooks tutees will need to have the following installed:

* <a href="https://www.python.org/" target_="blank">Python</a> (2.7 or 3.6+, users are recommended to use Python 3.6)
* <a href="http://www.numpy.org/" target_="blank">NumPy</a> (recommend v1.14.1+)
* <a href="https://www.scipy.org/" target_="blank">SciPy</a> (recommend v1.0.0+)
* <a href="https://matplotlib.org/" target_="blank">Matplotlib</a> (recommend v2.1.0+)
* <a href="http://jupyter.org/" target_="blank">Jupyter</a> (recommend v1.0.0+)

Python 2.7 users should additonally install:

* <a href="https://pypi.org/project/future/" target_="blank">Future</a> (recommend v0.16.0+)

All of the packages listed above can easily be installed using either `pip` or <a href="https://www.anaconda.com/" target_="blank">Anaconda</a>.

*e.g.*

```bash
$ pip install numpy scipy matplotlib jupyter
```

or

```bash
$ conda install numpy scipy matplotlib jupyter
```


## Notebooks

1. [Introduction to Inverse Problems](./inverse_problems_1.ipynb)

1. [Introduction to Sparsity I](./sparsity_1.ipynb)

1. [Introduction to Sparsity II: Compressed Sensing](./sparsity_2_compressed_sensing.ipynb)

1. [Introduction to Sparsity III: Deconvolution](./sparsity_3_deconvolution.ipynb)

1. [Introduction to Wavelets](./wavelets_1.ipynb)

1. [Exercise Solutions](http://gifimage.net/wp-content/uploads/2017/10/dennis-nedry-gif-3.gif)

## Acknowledgements

S. Farrens would like to acknowledge the following people for helpful feedback and ideas for producing this tutorial: Fred Ngolè-Mboula and Jean-Luc Starck.
