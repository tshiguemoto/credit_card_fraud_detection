# Credit Card Fraud Detection
#### Final Project for my Udacity Nanodegree in Machine Learning Engineer

### Instalação
This project requires **Python 3** and the following Python libraries installed:

- [iPython](https://ipython.org/)
- [Matplotlib](https://matplotlib.org/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Scikit-learn](http://scikit-learn.org/stable/)
- [Scipy](https://www.scipy.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [StatsModels](https://www.statsmodels.org/stable/index.html)
- [Time](https://docs.python.org/3/library/time.html)
- [XGBoost](http://xgboost.readthedocs.io/en/latest/get_started/index.html#python)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Execução
In a terminal or command window, navigate to the top-level project directory and run one of the following commands::

```ipython notebook CapstoneProject.ipynb```  

or

```jupyter notebook CapstoneProject.ipynb```

This will open the iPython Notebook software and project file in your browser.

## Data

The dataset refers to transactions of European card users in September 2013, obtained from Kaggle. Possessing 284807 lines and 31 features, of which 28 are dependent variables that due to confidentiality are the results of PCA transformations. The data used in this project is `creditcard.csv` and you can have access to this dataset in: https://www.kaggle.com/mlg-ulb/creditcardfraud/data.

**Features**
- `Time`: Seconds between each transaction
- `V1-V28`: Dependent anonymous variables due to confidentiality
- `Amount`: Transaction Amount
- `Class`: Variable response. If the transaction was fraudulent
