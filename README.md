# Fundamentals of machine learning 2026 Fork
## The course is held at FEI, VSB-TU Ostrava 

Original course material by and [Jan Platoš](https://github.com/jplatos/VSB-FEI-Fundamentals-of-Machine-Learning) and [Radek Svoboda](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning).

# 📊 Exercises
## Exercise 1
The aim of the exercise is to get an overview of the basic capabilities of the Pandas, Matplotlib and Seaborn libraries and be able to setup a Python Virtual Enviroment (`venv`)

> [Jupyter Notebook](https://github.com/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/VSB-FEI-Fundamentals-of-Machine-Learning-2026-Fork/blob/main/fml_01.ipynb)


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
