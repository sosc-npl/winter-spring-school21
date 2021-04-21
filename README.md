# winter-spring-school21
[Winter-Sprint School 21](http://soscnepal.info/)

This repository is meant to help participants to build up a virtual enviroment for working hands-on sessions of this school.

## Installation 
For installation of anaconda, you can follow the following command lines. 

First install ‘conda’. For this, Please visit this link; (https://docs.conda.io/projects/conda-build/en/latest/install-conda-build.html)

 To install conda-build, in your terminal window or an Anaconda Prompt, run:
 
 ```console
conda install conda-build
```
To update conda and conda-build, in your terminal window or an Anaconda Prompt, run:

```console
conda update conda
conda update conda-build
```

Create a new environment:

```console 
$ conda create -n wss21
```
 
Activate the new environment:

```console
$ conda activate wss21
```

To verify the installation of new environment please put the command in terminal:

```console 
$ conda env list
``` 

It should show the name of the new environment, wss21, in the list.
 
## Testing the conda environment

We highly recommend that please test the new environment via jupyter notebook in your browser. 

```console 
$ jupyter notebook
 ``` 
 
#### If there are any issues you would find during installation please contact at spring.winter.school@gmail.com or put your issues in the slack channel of #computation_problems. 
 

The practical hands-on sessions will be conducted on Jupyter notebooks. 

For additional software packages installation, please follow the command lines below.

```console 
conda update conda 
conda install -c anaconda scipy
conda config -env -add channels conda-forge
conda install -c conda-forge matplotlib
conda install -c anaconda pandas
conda install -c anaconda seaborn
conda install -c conda-forge notebook
conda install -c conda-forge jupyterlab
```

