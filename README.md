# Telia andmeteaduse praktika kodutöö

Näidisülesande lahendus, mis ennustab telekommunikatsiooni ettevõttest lahkuvaid kliente.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The repository consists of the [dataset](WA_Fn-UseC_-Telco-Customer-Churn.csv) and the [Jupyter Notebook](Churn_Analysis.ipynb) file. 

The aim of this project is to predict clients in the dataset likely to leave, identify the possible causes in customer churn and suggest potential customer retention programs.

## Installation

To run the Jupyter Notebook, you will need to have Python installed on your system.

In order to install Jupyter Notebook, you can install it using pip, Python's package installer. Open a terminal or command prompt and run the following command:

```bash
pip install jupyterlab
```

Install the required packages.

```bash
pip install pandas scikit-learn matplotlib seaborn
```

Once all the prerequisites are installed, you can launch the Jupyter Notebook by navigating to the project directory in your terminal and running:

```bash
jupyter notebook Churn_Analysis.ipynb
```

## Usage

The Analysis consists of markdown cells, with text explaining the Python code and interpreting the outputs. 

In order to get the desired outputs, the Python cells can either be ran all at once, by selecting Run and then Run All Cells, or in sequence, by selecting Run this cell and advance.
