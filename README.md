# Pattern Recognition Assignments

## Description

There are 3 assignments for the pattern recognition course. The solutions for each assignment are in each of the 3 respective folders. The solutions were written in the Jupyter Notebook files (.ipynb). 

## Set Up
In order to be able to open the Jupyter Notebook files and execute the code you can follow the follwoing steps to get an environment setup with the necessary packages.
1. Install the following prerequistes:
    - Anaconda 5.3 with Python 3.7 - [Link Here](https://www.anaconda.com/download/)
2. Use Anaconda to install packages in a new or existing virtual environment:
    `conda create -n new-env --file requirements.txt`
    or
    `conda install --yes --file requirements.txt`
3. Setup nbdime for a better diff tool with jupyter notebooks:
    `nbdime config-git --enable --global`