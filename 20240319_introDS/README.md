# 2024/03/19: Python Club Meetup
## Topic:
Introducing Data Science from a biologist perspective. 2 topics will be covered in this meeting; Dimension reduction and regression analysis.

## Virtual environment
To run the Jupyter notebook, we will create a virtual environment in replit to install  libraries. In the shell terminal, create a  virtual environment and install the kernel.
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



