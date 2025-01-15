<!-- README file for YouTube tutorials -->
<!-- [YouTube](https://youtu.be/eMOA1pPVUc4) -->

# Python Data Analysis of Tech Gadget Sales with Pandas

## Metadata

- <ins>Project Owner</ins>: [@dark-teal-coder](github.com/dark-teal-coder)
- <ins>First Published Date</ins>: 2022-12-19

## Project

- **Title**: *Python Data Analysis of Tech Gadget Sales with Pandas*
- **Difficulty**:
  - [ ] Beginner
  - [x] Intermediate
  - [ ] Advanced
- **Scale**:
  - [x] Small
  - [ ] Medium
  - [ ] Large

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

## Installation 

### Python Development Tools

- Python 3
  - [Download and install Python 3 from python.org](https://www.python.org/downloads). 
- Python Package Installer/Manager `pip`
  - If you installed Python from [python.org](https://www.python.org), you should already have `pip`. If it is not installed, you can use the command `py -m ensurepip --default-pip` to bootstrap it from the standard library. If you are using Linux, you will have to [install the package manager separately](https://packaging.python.org/en/latest/guides/installing-using-linux-tools/). You can find out more about the `pip` tool [here](https://pip.pypa.io/en/stable/getting-started/). 
- Text Editor and Integrated Development Environment (IDE)
  - [Download and install the text editor Notepad++](https://notepad-plus-plus.org/downloads). 
  - [Download and install the IDE Visual Studio Code (VS Code)](https://code.visualstudio.com/download). 
  - [Install the web-based app Jupyter Notebook with pip](https://jupyter.org/install#jupyter-notebook)
  - [Install the web-based IDE JupyterLab with pip](https://jupyter.org/install#jupyterlab)
  - [Install Anaconda to get Jupyter Notebook](https://docs.jupyter.org/en/latest/install/notebook-classic.html#installing-jupyter-using-anaconda-and-conda)
- Command-line interface (CLI) 
  - You can [install the open-source PowerShell on Windows, Linux and macOS](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell) if you do not have or want to use a pre-installed CLI on your local machine. 

### Python Libraries

Check if you have Python installed using the command `python --version`, or simply, `python version`, in the CLI. [Git-clone the project repository from Github](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to the local machine. Use the command `py -m pip install package_name` to install the necessary Python libraries. Check out [pip documentation](https://pip.pypa.io/en/stable/cli/pip_install/) to learn more about `pip install`. Check the top part of the `.py` script file for the list of libraries required. For example, you may need `requests` and `beautifulsoup4` libraries if you see the following lines in the top part of the script file: 
```
import requests
from bs4 import BeautifulSoup
```
If `pip` fails to locate the relevant packages, you may find it at [Python Package Index (PyPI)](https://pypi.org/). Use `python file_name.py` to run the script in a CLI. Or, use an IDE, such as VS Code, to run the script. There will usually be a [Run] button in the top right corner of the opened script file. 

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

## Credits 

### Contributors 

- [@dark-teal-coder](github.com/dark-teal-coder)

### References 

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
