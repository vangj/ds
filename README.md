# Intro

This repository is just some "no tears" tutorials on data science topics. You will need [Jupyter](http://jupyter.org/) to get the examples to run. The easiest way to get Jupyter is to install Anaconda as described below.

# Conda

To create a Conda environment, you need to install [Anaconda](https://anaconda.org/). Note, for Windows, do not type in `source activate ds` but instead `activate ds`. Assuming you are in the cloned `ds` repository directory, you may type in the following.

```bash
conda create -n ds python=2.7
source activate ds
pip install -r requirements.txt
python -m ipykernel install --user --name ds --display-name "ds"
```

To remove the environment.

```bash
conda env remove -n ds --yes
```

# Notebooks

* [Solve logistic regression problems with gradient descent through Autograd, no tears](autograd-logistic-regression-gradient-descent.ipynb)
* [Solve poisson regression problems with gradient descent through Autograd, no tears](autograd-poisson-regression-gradient-descent.ipynb)
* [Solve regression problems with gradient descent through Autograd, no tears](autograd-regression-gradient-descent.ipynb)
* [Dirichlet-Multinomial distribution, no tears](dirichlet-multinomial-distribution.ipynb)
* [Generating normally distributed values, no tears](generate-gaussian-distributed-values.ipynb)
* [Random Bayesian Network generation, no tears](generate-random-bbn.ipynb)
* [Gradient descent, no tears](gradient-descent.ipynb)
* [Kullback-Leibler divergence, no tears](kullback-leibler-divergence.ipynb)
* [Latent semantic analysis, no tears](latent-semantic-analysis.ipynb)
* [Neural network, no tears](neural-network-handcraft.ipynb)
* [Psuedo R^2 for logistic regression, no tears](psuedo-r-squared-logistic-regression.ipynb)
* [Regression with dummy variables, no tears](regression-dummy-variables.ipynb)
* [Using a Recurrent Neural Network (RNN) to classify sine wave signals, no tears](pytorch/classify-signals-rnn.ipynb)
* [Neural Networks, gradient descent, and regression, no tears](pytorch/neural-network-gradient-descent.ipynb)
* [Restricted Boltzmann Machine](restricted-boltzmann-machine.ipynb)

# Misc

To convert a `ipynb` to `html`, type in the following `jupyter nbconvert --to html --template basic [file.ipynb]`. To make the generated `html` file compatible with WordPress, type in `sed -e 's/\$\([^$]*\)\$/$latex \1$/g' [file.html] > [output.html]`.

# Copyright Stuff

```
Copyright 2018 Jee Vang

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```