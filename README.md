# Fundamentals of machine learning 2026 Fork
## The course is held at FEI, VSB-TU Ostrava 

Original course material by and [Jan Platoš](https://github.com/jplatos/VSB-FEI-Fundamentals-of-Machine-Learning) and [Radek Svoboda](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning).

# 📊 Exercises
## Exercise 1
The aim of the exercise is to get an overview of the basic capabilities of the Pandas, Matplotlib and Seaborn libraries and be able to setup a Python Virtual Enviroment (`venv`)

> [Jupyter Notebook](https://github.com/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_01.ipynb)

## Exercise 2
The second exercise turns to inspecting and cleaning a raw dataset: distinguishing numerical, categorical and ordinal variables, converting data types, dropping redundant columns, and detecting and handling missing values with several strategies. It also covers choosing the right plot for a given question and using histograms, boxplots and the IQR to spot skewed distributions and outliers.

**Two variants of this exercise are available. The Guided overview walks through variable types, data cleaning and missing-value handling step by step on the Titanic dataset, using histograms and boxplots to flag outliers — the better starting point if you are new to exploratory analysis. The Active learning variant covers the same statistical ground — summary statistics, skewness, ordinal vs. continuous variables, missing-value interpretation, plot selection, correlation and outlier investigation — on a house-prices dataset, but asks you to predict, verify and interpret at each step rather than only run the cells, with guided pair-work activities. Pick one — they are alternatives, not a sequence.**

### Active learning

> [Jupyter Notebook](https://github.com/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_02.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_02.ipynb)

### Guided version

> [Jupyter Notebook](https://github.com/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_02_overview.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_02_overview.ipynb)

## How to create a Python Virtual Enviroment named `venv`
### Create `venv`
```
python -m venv venv
```

### Activate `venv`

* Activate `venv` in **Windows**
```
.\venv\Scripts\Activate.ps1
```

* Activate `venv` in **Linux**
```
source venv/bin/activate
```


### Intall python packages

```
pip install jupyter "jupyterlab>=3" "ipywidgets>=7.6"
pip install pandas matplotlib requests seaborn scipy scikit-learn
```

### 🚀 Run Jupyter lab

```
jupyter lab
```
