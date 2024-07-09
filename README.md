# Algorithmic Trading Project

This repository documents my learning journey in machine learning and algorithmic trading. The goal of this project is to learn how to gather data and apply it to a machine learning model to predict which stocks will be the most profitable in the coming month. The data is extracted from the S&P 500 using Yahoo Finance. 

The features included in the model are: atr, bb_high, bb_low, bb_med, garman_klass_vol, macd, rsi, return_1m, return_2m, return_3m, return_6m, return_9m, return_12m, Mkt-RF, SMB, HML, RMW, and CMA.

## Packages & Technologies

- pandas
- numpy
- matplotlib
- statsmodels
- pandas_datareader
- datetime
- yfinance
- sklearn
- PyPortfolioOpt

## How to run the project

#### Prerequisites:
- Python 3.x
- pip (Python package installer)
- Git (optional, for cloning the repository)

#### Setup:
1. Clone the repository \
   ```git clone https://github.com/kylekmcleod/Algorithmic-Trading-Project.git```\
   ```cd Algorithmic-Trading-Project```
   
3. Setup the virtual enviroment \
   ```python -m venv my_virtual_env```\
   ```.\my_virtual_env\Scripts\activate```
   
4. Install dependencies:\
   ```pip install -r requirements.txt```
   
6. Open Jupyter Notebook:\
   ```jupyter notebook```
   
8. Explore notebooks:\
   Inside the notebooks directory, you'll find Jupyter notebooks (*.ipynb).
   Open a notebook by clicking on its filename in the Jupyter interface.
   Run cells in the notebook to execute code and see results.


