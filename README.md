# Bank of Thailand Workshop
## Slides
See folder `slides`
## Setup Day 2
**Important** Please make sure to complete Setup Day 1 before proceeding.

From within the environment, install all dependencies.
```
pip install xgboost
pip install opencv-python
pip install shap
```

For Lab 3, please manually download and extract all zip files in `home` folder to `/home` relative to your local working directory 
## Setup Day 1

First, let's create an environment where we will install all dependencies needed for this workshop.

For Anaconda, use the following command to create an environment called `workshop` (you can change this) and install necessary libralies.

```
conda create --name workshop python=3.7 tensorflow pandas matplotlib scikit-learn jupyterlab
```
This will install Python 3.7 (Tensorflow 2 requires Python<3.8), Tensorflow 2 for deep learning implementation, pandas for data structure management, Matplotlib for visualization, Scikit-learn for mathematical tools, and Jupyter Lab for running Notebooks.

After the installation is completed, activate the environment

```
conda activate workshop
```

Next, start Python and verify if Tensorflow 2 is successfully installed. The output should be similar to the following.
```
>>> import tensorflow as tf
>>> tf.__version__
'2.1.0'
>>> exit()
```

#### Jupyter

Now, let's start Jupyter Lab using the following command
```
jupyter lab
```

Your browser should start up automatically and redirect you to Jupyter Lab Launcher window. 

If it doesn't, you can manually go to the following address: `http://localhost:8888/lab`. 

Note that for first-time users, Jupyter Lab may ask you to authorize the browser by asking you to input an access token. Please refer to the terminal for the instruction.
