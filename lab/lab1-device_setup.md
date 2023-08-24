# Lab 1: Setting up Your Laptop

We will use Python for all our coding examples, lab demonstrations, and homeworks.
There are multiple ways to write and run a Python code. We will mainly use [JupyterLab](https://jupyter.org) (Jupyter Notebook) and [Google Colaboratory](https://colab.research.google.com).

Follow the below instructions to set them up.

## JupyterLab

We introduce both command-line interface (CLI) and graphical user interface (GUI) to install `jupyterlab`. Choose the one that you are comfortable with.

### Installing via CLI

#### On Mac or Linux

Follow https://wengroup.github.io/group_manual/computing/conda.html to install `conda`. Make sure you install Python version 3.10. Then install `jupyterlab` by running the below commands in your `terminal` app:

```shell
conda install -c conda-forge jupyter
```

To start `jupyterlab`, in your `terminal` app, do

```shell
jupyter lab
```

#### On Windows

We recommend to first install the [Window subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install) and then follow the above instructions for Mac and Linux.

### Installing via GUI

Follow https://docs.cems.umn.edu/intro/Prt_01_Lssn_00_Getting_Started.html# to set it up.
Instructions for Windows, Linux, and Mac are all included.
Make sure you install Python version 3.10.
This will install the [Anaconda Navigator](https://docs.anaconda.com/free/navigator/index.html), from which you can start `jupyterlab` and install other python packages.

## numpy, matplotlib, and other packages

Make sure you are comfortable install other packages, such as `numpy` and `matplotlib`.

CLI users can do it via your `terminal`.
GUI users who have installed the Anaconda Navigator can follow the instructions here: https://docs.anaconda.com/free/navigator/tutorials/manage-packages.html

## Running example notebook

Make sure you can successfully run the example jupyter notebook: `lab1-example.ipynb`.

## Google Colab

Google Colab is a cloud hosted notebook service. It is very similar to Jupyter notebook, but you do not need to install it and you can use it for free.
The flip side, however, is that the computational resource can be limited sometimes.

Follow instructions at https://colab.research.google.com/ to create new notebooks and play with it. Make sure you can upload `lab1-example.ipynb` and run it in Colab as well.
