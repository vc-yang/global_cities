# Repository for the paper "Inter-city firm connections and the scaling of urban economic indicators"

The code was written in Python 3, the files are Jupyter Notebooks last run in Python 3.11

`myFunctions.ipynb`: contains functions used in various notebooks in the repo. 
folder `Data`: contains cleaned and merged data used for analysis. The US, EU, and China population, GDP, and GNC data are saved as python pickles, and US crime data is saved in xslx format. 
`1_SAMI and descriptives 3 countries.ipynb`: Plots the scaling relationship in data and performs scaling residual analysis (SAMI)
`2 Regression EU.ipynb`, `3_Regression US.ipynb`, `4_Regression China.ipynb`, perform regression analysis for the three countries/regions, and compares the GNC model with null model. 
`5_Repeat analysis on crime.ipynb`: repeats SAMI and regression analysis on US murder rate data. 
