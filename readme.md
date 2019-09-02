# Moviewatchers data analysis

## Summary

We load and analyse the provided dataset in regards with it's potential for creating some data-backed services. Explanations and data analysis are given in the Jupyter notebook file. Adjust path to the data files in the first cell of Jupyter notebook, then run all cells.

## Usage

1. Create a virtualenv with all dependencies with
>>> conda env create --file environment.yml

This submission is prepared and tested with Anaconda package manager which is standard for Python develooment.
Alternatively install packages from `requirements.txt` file - however `zipcodes` package is available from pip and `basemap` needs Anaconda's installation.

2. Activate virtual environment
>>>  conda activate submission-akusok

3. Open Jupyter notebook file
>>> jupyter notebook report.ipynb

4. Adjust path to data files in the first cell, default paths are:
>>> movies_file = "../data/ml-1m/movies.dat"
>>> ratings_file = "../data/ml-1m/ratings.dat"
>>> users_file = "../data/ml-1m/users.dat"

5. Generate the analysis/report by clicking "Cell" -> "Run all"
