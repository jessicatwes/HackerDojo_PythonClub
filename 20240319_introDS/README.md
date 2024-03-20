# 2024/03/19: Python Club Meetup
## Topic:
Introducing Data Science from a biologist perspective. 2 methods of Supervised learning will be discussed in this meeting; linear regression and logistic regression. 

Jupyter notebook for regression methods
- [Linear Regression](https://github.com/jessicatwes/HackerDojo_PythonClub/blob/main/20240319_introDS/20240319_LinearRegresssion.ipynb)
- [Logistic Regression](https://github.com/jessicatwes/HackerDojo_PythonClub/blob/main/20240319_introDS/20240319_LogisticRegresssion.ipynb)

## Libraries used this week
- [scikit-learn](https://scikit-learn.org/stable/) - Machine learning library that has tools to make predictive data analysis. We will be using it to do linear regression.
- [matplotlib](https://matplotlib.org/) - Visualization library to create static and interactive visualization in Python
- [seaborn](https://seaborn.pydata.org/) - Data visualization library based on matplotlib. The difference between matplotlib and seaborn is that we can pass a pandas DataFrame directly to the plot and refer to each column in DataFrame by name.

## Setting up your coding environment to run machine learning analysis
I will be using Jupyter notebook to run my analysis since it with be visually heavy. The notebook allows you to run different visualization analysis of your data in blocks.

### Virtual environment
To run the Jupyter notebook, we will create a virtual environment in Replit to install  libraries. In the shell terminal, create a  virtual environment and install the kernel.
```
$ pip3 install virtualenv

# This creates the virtual environment and names it "vmjn"
$ virtualenv vmjn

# Activate the virtual environment so that any package you install will be installed into your virtual  environment
$ source vmjn/bin/activate

# Install libraries we will  use
$ pip install numpy
$ pip install scikit-learn
$ pip install statsmodels

# Install jupyter kernel for the virtual environment
$ ipython kernel install --user --name=vmjn
```

** Note: I ended up not using Replit because I was fighting library installation and virtual machine. The Jupyter notebook was developed in Google Colab.

