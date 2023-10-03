# Statistical Modeling Using PyMC3

This repository contains code and resources for performing statistical modeling using PyMC3, a powerful Python library for Bayesian modeling and probabilistic programming. Whether you're new to Bayesian statistics or an experienced practitioner, this repository aims to provide you with a foundation for conducting Bayesian data analysis using PyMC3.


## Introduction

Bayesian statistics is a powerful approach to modeling and inference that allows us to quantify uncertainty and make data-driven decisions. PyMC3 is a popular library that simplifies the process of building and estimating Bayesian models. In this repository, we provide resources, tutorials, and examples to help you get started with Bayesian modeling using PyMC3.

This repository has a bunch of workshops that we did in class to play with. Their topics start from the basics of distribution and extend to the basics of deep learning.

## A special thanks to [Faraz Rashid](https://github.com/FarazRashid) who was my duo in this class.

## Installation

To get started with the code and examples in this repository, you'll need to install PyMC3 and other required dependencies. Here are the steps to set up your environment:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/AhmadHassan71/statistical-modeling-using-pymc3.git

2. Install the requirements
  -  Install latest version of [Python](https://www.python.org/downloads/)
  -  Install [Anaconda](https://www.anaconda.com) for the current user (not for all users) if not already installed
  -  Install [MSYS2](https://www.msys2.org/) strictly as instructed in the link
  -   In Environment Variables for the user, add the following to the path
      C:\msys64\ucrt64\bin
      C:\msys64\usr\bin
  -  Open Anaconda Powershell Prompt (anaconda3) as administrator and run the following in sequence. 


      ```
      conda update --all
      conda create -n pm3bap -c conda-forge pymc3 seaborn libpython mkl-service numba
      conda activate pm3bap
      conda install -c conda-forge notebook
      conda activate pm3bap
      jupyter lab
      ```
3. You are ready to play with the workshops!! Have Fun
