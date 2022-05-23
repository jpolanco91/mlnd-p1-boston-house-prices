# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

### Install

This project requires **Python 3.9**(included on the anaconda environment .yml file) and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter Notebook](http://ipython.org/notebook.html)


First you must download and install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. After downloading Anaconda we will proceed to install the `boston-house-prices` environment, which includes all the above libraries to run the code. To install the environment we run this command in this project's folder:

```bash
conda env create -f boston-house-prices.yml
```

This code will install all of the previously mentioned libraries needed to run this project. After the environment installation completes, we must then activate the environment in order to be able to run the code:

```bash
conda activate boston-house-prices
```

After running this code we're now ready to run the project's code. The instructions to run it are on the next section of these docs.

### Code

Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

### Deactivating environment.

If we want to deactivate the conda's environment for this project we run this command:

```bash
conda deactivate.
```