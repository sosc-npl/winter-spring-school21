# winter-spring-school21


For installation of anaconda, you can follow the following command lines. 

First install ‘conda’. For this 
Installing conda-build 
(Installing and updating conda-build — conda-build 3.21.4+3.g3b99b222.dirty documentation)
 To install conda-build, in your terminal window or an Anaconda Prompt, run:
conda install conda-build
To update conda and conda-build, in your terminal window or an Anaconda Prompt, run:
conda update conda
conda update conda-build

Create a new environment:
$ conda create -n pwss21
 
Activate the new environment:
$ conda activate pwss21
To verify the installation of new environment please put the command in terminal:
$ conda env list
It should show the name of the new environment, pwss21, in the list.
 
Testing the conda environment
We highly recommend that please test the new environment via jupyter notebook in your browser. 
$ jupyter notebook
 
If there are any issues you would find during installation please contact at spring.winter.school@gmail.com or put your issues in the slack channel of #computation_problems. 
 

The practical hands-on sessions will be conducted on Jupyter notebooks. 

For additional software packages installation, please follow the command lines below.


conda update conda 
conda install -c anaconda scipy
conda config -env -add channels conda-forge
conda install -c conda-forge matplotlib
conda install -c anaconda pandas
conda install -c anaconda seaborn
conda install -c conda-forge notebook
conda install -c conda-forge jupyterlab

