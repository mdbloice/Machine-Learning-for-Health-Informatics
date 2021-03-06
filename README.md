# Machine Learning for Health Informatics

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/mdbloice/Machine-Learning-for-Health-Informatics)

Jupyter notebook assignments for the _Machine Learning for Health Informatics_ course (LV 185.A83) at Vienna University of Technology.

## Assignment 3 

The final assignment is available on another GitHub repository, see here: <https://github.com/cassinius/mlhi-ass2-anonymization>. 

## Assignment 2 

Assignment 2 is now available under [`Assignment2.ipynb`](https://github.com/mdbloice/Machine-Learning-for-Health-Informatics/blob/master/Assignment2.ipynb). 

The task in this assignment is to replicate a high-dimensional gene expression dataset analysis performed by Ramaswamy et al. in the following paper:

S. Ramaswamy, P.  Tamayo,  R. Rifkin, S. Mukherjee, C.H. Yeang, M. Angelo, C. Ladd, M. Reich, E. Latulippe, J.P. Mesirov, T. Poggio, W. Gerald, M. Loda, E.S. Lander and T.R. Golub. __Multiclass cancer diagnosis using tumor gene expression signatures__. _PNAS, Proceedings of the National Academy of Sciences_. 2001 Dec 18; 98(26): 15149–15154.

The group performed both clustering and classification techniques on a 14 cancer gene expression dataset. The dataset is _high dimensional_, as the number of features (_p_=16,603 genes) far outweighs the number of observations (_N_=144 human tumour samples in the training set), hence it falls in to the category of _p_ ≫ _N_ problems. The study is also described in _Elements of Statistical Learning_ (Hastie, Tibshirani, and Friedman, 2009) in chapters 13 and 18. See the [`Assignment2.ipynb`](https://github.com/mdbloice/Machine-Learning-for-Health-Informatics/blob/master/Assignment2.ipynb) notebook for full details.

## Assignment 1 (16th of March 2016)—Introduction Lecture

You can find the introductory notebook under [`Assignment1.ipynb`](https://github.com/mdbloice/Machine-Learning-for-Health-Informatics/blob/master/Assignment1.ipynb). 
There is nothing to hand in for this assignment. Look through the notebook and make sure you can run this on your local machine and that you have all the libraries installed that you require to run the notebook. 

## Useful links and miscellany

Anaconda: [https://www.continuum.io/downloads](https://www.continuum.io/downloads)

__Use the Python 2.7 version!__

NumPy documentation: [http://docs.scipy.org/doc/numpy/reference/](http://docs.scipy.org/doc/numpy/reference/)

SciKit-Learn documentation [http://scikit-learn.org/stable/documentation.html](http://scikit-learn.org/stable/documentation.html)

Pandas documentation: [http://pandas.pydata.org/](http://pandas.pydata.org/)

Matplotlib tutorials and documentation: [http://matplotlib.org/devdocs/resources/index.html](http://matplotlib.org/devdocs/resources/index.html) 

Gallery of interesting Jupyter notebooks: [https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks) 

Good selection of Jupyter Notebooks: [http://nb.bianp.net/sort/views/](http://nb.bianp.net/sort/views/)
