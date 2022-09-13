# Rais Hands-on Tutorial on Sleep Staging


First of all, you will need Python in your machine and I higly recommend you to install an enviroment package like Conda.

- Please visit [this page to learn how to install conda in your machine](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

A good summary of the most important commands to learn with Codna are in its [cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).


## Installing the a few env:

- Basic Tutorial
```bash
conda create --name tutorial python=3.8
conda install -c apple tensorflow-deps
conda install -c conda-forge -y pandas jupyter
conda install -c conda-forge tensorflow            # Probably without gpu acceleration
conda install matplotli
conda install -c conda-forge jupyter_contrib_nbextensions
conda install seaborn
```

- Adding TSFresh to your basic tutorial env
```bash
conda create --clone tutorial --name tutorial-tsfresh
conda activate tutorial-tsfresh
conda install tsfresh
conda install statsmodels==0.12.1
```

- Adding Pycaret to your basic tutorial env
```bash
conda create --clone tutorial --name tutorial-tsfresh
pip install --pre pycaret
```

- Adding Keras to your basic tutorial env
```bash
conda create --clone tutorial --name tutorial-keras
conda install -c apple tensorflow-deps
pip install tensorflow-macos
```


### About the structure of this tutorial:

