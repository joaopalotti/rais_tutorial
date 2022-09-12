# rais_tutorial

ADD Commands to download dataset from Dropbox here


# tutorial
conda create --name tutorial python=3.8
conda install -c apple tensorflow-deps
conda install -c conda-forge -y pandas jupyter
conda install -c conda-forge tensorflow            # Probably without gpu acceleration
conda install matplotli
conda install -c conda-forge jupyter_contrib_nbextensions
conda install seaborn


# tutorial-tsfresh with tsfresh 
conda create --clone tutorial --name tutorial-tsfresh
conda activate tutorial-tsfresh
conda install tsfresh
conda install statsmodels==0.12.1



#tutorial-pycaret
conda create --clone tutorial --name tutorial-tsfresh
pip install --pre pycaret


#tutorial-keras
conda create --clone tutorial --name tutorial-keras
conda install -c apple tensorflow-deps
pip install tensorflow-macos



