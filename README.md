<!-- README file for YouTube tutorials -->
<!-- [YouTube](https://youtu.be/eMOA1pPVUc4) -->

# Python Data Analysis of Tech Gadget Sales with Pandas

## Project

- **Title**: *Python Data Analysis of Tech Gadget Sales with Pandas*
- **Difficulty**:
  - [ ] Beginner
  - [x] Intermediate
  - [ ] Advanced
- **Scale**:
  - [x] Small
  - [ ] Medium
  - [ ] Big

## Repository Description

This repository contains a Jupyter notebook which demonstrates how to analyze tech gadget sales in the US in 2019. We use the Python Pandas and Matplotlib libraries to analyze and answer business questions about 12 months worth of sales data here. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We walk through different Pandas & Matplotlib methods below.

- Concatenating multiple CSVs together to create a new DataFrame (`pd.concat()`)
- Adding columns
- Parsing cells as strings to make new columns (`.str`)
- Using the `apply()` method
- Using `groupby()` to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

## Instructions

### To Get All the Files in the Current Repository

- Click [Code]
- Click [Download ZIP]
- Extract the .zip file to the working directory

### To Fork a Repo and Clone it Locally

To access all of the files, fork this repo and then clone it locally.

For more information, please refer to [Fork a repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

### To Install Python Pandas Library

- Open a command-line interface
- Type `pip install pandas`
- Press [Enter]

For more information, please refer to [Installing Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html#installing-pandas).

### To Install Jupyter Notebook

*Prerequisite*: Python[^note]

- Run `pip3 install --upgrade pip` to upgrade to the latest version of `pip`
- Run `pip3 install jupyter` to install Jupyter Notebook

For more information, please refer to [Installing the Classic Jupyter Notebook Interface](https://docs.jupyter.org/en/latest/install/notebook-classic.html#installing-the-classic-jupyter-notebook-interface).

[^note]: Python is a requirement for installing the Jupyter Notebook.

## References

- [pandas.DataFrame.any documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.any.html)
- [pandas.DataFrame.dropna documentation](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dropna.html)
- [pandas.to_numeric documentation](https://pandas.pydata.org/docs/reference/api/pandas.to_numeric.html)
- [pandas.to_datetime documentation](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html)
- [pandas.Series.dt.month documentation](https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.month.html)
- [pandas.DataFrame.groupby documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html)
- [matplotlib.pyplot.plot documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)
- [matplotlib.pyplot.grid documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.grid.html)
- [pandas.DataFrame.duplicated documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.duplicated.html)
- [pandas.DataFrame.transform documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.transform.html)
- [itertools.combinations documentation](https://docs.python.org/3/library/itertools.html#itertools.combinations)
- [itertools.combinations() in Python](https://www.codespeedy.com/itertools-combinations-in-python/)
- [collections.Counter documentation](https://docs.python.org/3/library/collections.html#collections.Counter)
- [Python's Counter: The Pythonic Way to Count Objects](https://realpython.com/python-counter/)
- [Update Method Of Counter Class](https://pythontic.com/containers/counter/update)
- [matplotlib.pyplot.subplots documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html)
- [matplotlib.axes.Axes.twinx documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.twinx.html)

&nbsp;

*1st Completion Date: Dec 20, 2022*&emsp;
