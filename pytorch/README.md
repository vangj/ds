# Intro

This repository is just some "no tears" tutorials on data science topics. You will need [Jupyter](http://jupyter.org/) to get the examples to run. The easiest way to get Jupyter is to install Anaconda as described below. This folder is a one-off focused on code samples using [Pytorch](http://pytorch.org/).

# Conda

To create a Conda environment, you need to install [Anaconda](https://anaconda.org/). Note, for Windows, do not type in `source activate ds` but instead `activate ds`. Assuming you are in the cloned `ds` repository directory, you may type in the following. Look here on [installing Pytorch on Windows](http://pytorch.org/).

```bash
conda create -n ds-pytorch python=3.6
activate ds-pytorch
pip install -r requirements.txt
pip install http://download.pytorch.org/whl/cpu/torch-0.4.0-cp36-cp36m-win_amd64.whl 
pip install torchvision
python -m ipykernel install --user --name ds-pytorch --display-name "ds-pytorch"
```

To remove the environment.

```bash
conda env remove -n ds-pytorch --yes
```


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