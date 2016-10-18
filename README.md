# README
Beginner's Guide to Machine Learning Competitions, EuroPython 2015, Tutorial

# Setup

```
git clone https://github.com/chdoig/ep2015-ml-tutorial.git
cd ep2015-ml-tutorial
```

- **Option A: Anaconda**

If you don't have Anaconda installed, you can install it from [here](https://store.continuum.io/cshop/anaconda/).
After following the instructions, you should be ready to go. 

If you already have Anaconda installed, make sure to update both conda and the dependencies 
to the latest versions, by running:

```
conda update conda
conda install pandas
conda install scikit-learn
conda install numpy
conda install ipython
conda install matplotlib
conda install seaborn
conda install ipython-notebook
```

- **Option B: Miniconda or Conda Environments**

If you want one the following:

- a lightweight alternative to Anaconda, you can install Miniconda from 
[here](http://conda.pydata.org/miniconda.html). 

or 
- isolate this scipy tutorial dependencies from your default Anaconda by using conda environments.

Follow this commands after cloning this repository:

```
cd ep2015-ml-tutorial
conda env create
```

If you are running Linux or OS X run:

```
source activate ep-ml
```

If you are running Windows, run:

```
activate ep-ml
```

Then run jupyter:

```
jupyter notebook
```

- **Option C: Alternative setup**

Install the following dependencies: pandas, numpy, scikit-learn, matplotlib, seaborn, ipython, ipython-notebook

# Data

Download the datasets from here:

- [labeledTrainData.tsv.zip](https://s3-eu-west-1.amazonaws.com/europython-tutorial/labeledTrainData.tsv.zip) ~13MB
- [testData.tsv.zip](https://s3-eu-west-1.amazonaws.com/europython-tutorial/testData.tsv.zip) ~13MB

# Slides

Slides are available at [http://bit.ly/ep2015-ml-tutorial](http://bit.ly/ep2015-ml-tutorial)
