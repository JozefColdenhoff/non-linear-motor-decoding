Github repository of the thesis: A comparison of non-linear methods for the decoding of motor performance.

## Prerequisites
 - Install Anaconda
 - Fork the repository
 - Use `conda env create -f non-linear-motor-decoding.yml` to create a new environment with the required packages
 - Use `conda activate non-linear-motor-decoding` to activate the new environment
 - Finally use Jupyter Notebook to open the notebooks

## The iPython notebooks
The notebook `Binned data creation and analysis.ipynb` contains the code used to extract the features from the copy-draw data. It also contains the plots used in the data analysis, as well as the result of the bootstrap test for the difference in medians.

The notebook `Method evaluation.ipynb` contains the results of the methods on the three different datasets. 

The notebook `Method evaluation decorrelated.ipynb` contains the results of the methods on the dataset with the correlated features removed.
