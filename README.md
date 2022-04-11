In this project we have the role of  a growth analyst at MercadoLibre (Connexions vers un site externe.). With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, we want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.
In a bid to drive revenue, we’ll produce a Jupyter notebook that contains your data preparation, analysis, and visualizations for all the time series data that the company needs to understand. We’ll use text and comments to document your findings, and we’ll answer the question prompts in the instructions. Specifically, this file should contain the following:

Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

An evaluation of how the company’s stock price correlates to its Google Search traffic.

A Prophet forecast model that can predict hourly user search traffic.

Answers to questions in the instructions that you write in your Jupyter Notebook.


## Installation: This Project needs the installation of this required libraries : 
```
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews
`````



## Technologies : This project leverages Anaconda and Jupyterlab with Python 3.7:

We need also to import the following libraries and dependencies :
```
# Import the required libraries and dependencies
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
````



## Contributor: Amine Baite
