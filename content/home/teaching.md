---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: markdown

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Teaching
subtitle:

design:
  columns: '2'
---

## COMP9418: Advanced Topics in Statistical Machine Learning ([UNSW Sydney])  

The course has a primary focus on probabilistic machine learning methods, 
covering the topics of exact and approximate inference in directed and 
undirected probabilistic graphical models - continuous latent variable 
models, structured prediction models, and non-parametric models based on 
Gaussian processes. 

{{< figure src="cs9418-lab-screenshots/gp-regression-title.png" caption="Lab exercise on Gaussian Process Regression, running in JupyterLab." >}}

This course has a major emphasis on maintaining a good balance between theory 
and practice. As the teaching assistant (TA) for this course, my primary 
responsibility was to create lab exercises that aid students in gaining hands-on 
experience with these methods, specifically applying them to real-world data 
using the most current tools and libraries. 
The labs were Python-based, and relied heavily on the Python scientific 
computing and data analysis stack ([NumPy], [SciPy], [Matplotlib], [Seaborn], 
[Pandas], [IPython/Jupyter notebooks]), and the popular 
machine learning libraries [scikit-learn] and [TensorFlow].

Students were given the chance to experiment with a broad range of methods 
on various problems, such as Markov chain Monte Carlo (MCMC) for Bayesian 
logistic regression, probabilistic PCA (PPCA), factor analysis (FA) and 
independent component analysis (ICA) for dimensionality reduction, hidden 
Markov models (HMMs) for speech recognition, conditional random fields (CRFs) 
for named-entity recognition, and Gaussian processes (GPs) for regression and
classification.

[NumPy]: http://www.numpy.org/
[SciPy]: https://www.scipy.org/
[Matplotlib]: https://matplotlib.org/
[Seaborn]: https://seaborn.pydata.org/
[Pandas]: https://pandas.pydata.org/
[IPython/Jupyter notebooks]: http://jupyter.org/
[scikit-learn]: http://scikit-learn.org/
[TensorFlow]: https://www.tensorflow.org/
[JupyterLab]: https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906
[COMP9418]: http://www.handbook.unsw.edu.au/postgraduate/courses/2017/COMP9418.html
[UNSW Sydney]: https://www.unsw.edu.au/
